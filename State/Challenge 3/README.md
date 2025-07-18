# Challenge 3 of 4: Conserte uma Falha

## Objetivo

Corrigir um erro relacionado ao uso incorreto de Hooks no React, garantindo que o formulário funcione corretamente após o envio da opinião do usuário.

## Tarefas

1. **Identificar o erro de Hooks**  
   O erro “Renderizados menos Hooks do que o esperado” ocorre quando os Hooks (como `useState`) são usados de forma condicional.  
   No React, Hooks devem ser chamados sempre na mesma ordem e **fora de blocos condicionais**.

2. **Corrigir a lógica de renderização**  
   Reestruture o código para que os Hooks estejam fora de qualquer `if`, `switch` ou função condicional.  
   Mantenha o Hook de estado (`useState`) sempre no topo do componente, antes de qualquer lógica de retorno.
