## State no React

É uma estrutura interna do React usada para armazenar dados que podem mudar ao longo do tempo dentro de um componente.  

Quando o state de um componente muda, o React automaticamente atualiza a interface para refletir essas mudanças.

### Por que usar state?

- Para guardar informações que podem ser alteradas pelo usuário ou por eventos.
- Para manter a interface sincronizada com os dados atuais do componente.
- Para permitir que o componente lembre informações entre renderizações.

### Como funciona?

- O state é inicializado com um valor padrão.
- Você usa uma função específica (como setState ou o hook useState) para atualizar esse valor.
- Cada vez que o state é atualizado, o React refaz a renderização daquele componente com os novos dados.

### Diferença entre state e props

- *Props* são dados que um componente recebe de seu "pai" e são imutáveis dentro do componente.
- *State* é um dado privado e mutável que o próprio componente gerencia.