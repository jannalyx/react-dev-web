# Challenge 4 of 4: Remova State Desnecessário

## Objetivo

Corrigir o comportamento inesperado ao exibir uma saudação, removendo o uso incorreto de state que está causando atraso na atualização da mensagem.

## Tarefas

1. **Identificar o uso desnecessário de state**  
   O botão deve solicitar o nome do usuário via `prompt` e exibir imediatamente uma saudação usando `alert`.  
   Atualmente, o nome é armazenado em uma variável de **state**, o que faz com que a saudação use um valor **defasado na primeira execução**.

2. **Remover o uso de `useState`**  
   Como o nome do usuário não precisa ser exibido em tela nem causar re-renderizações, não há necessidade de armazená-lo em um state.  
   Use uma variável local diretamente no evento `onClick`.