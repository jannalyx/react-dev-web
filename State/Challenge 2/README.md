# Challenge 2 of 4: Corrigir Entradas de Formulário Travadas

## Objetivo

Permitir que os campos de entrada do formulário sejam editáveis utilizando o gerenciamento de estado do React.

## Tarefas

1. **Corrigir os campos de entrada**  
   Atualmente, os campos não exibem o que o usuário digita, pois estão “travados” com strings vazias.  
   Use **variáveis de state** (`useState`) para armazenar os valores dos campos e permitir que eles sejam atualizados com `onChange`.

2. **Garantir atualização entre renderizações**  
   As variáveis precisam manter seu valor mesmo após re-renderizações.  
   Para isso, certifique-se de que os `value` dos inputs estejam vinculados corretamente ao estado (state) correspondente.
