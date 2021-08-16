# desafio-complementar-01-ignite-reactjs

## Dividindo uma aplicação em componentes afim de isolar as responsabilidades e facilitar a manutenção do código.

### O principal objetivo desta aplicação é refatorar uma página para listagem de filmes de acordo com gênero. 

A aplicação já se encontrava totalmente funcional, mas grande parte do seu código está diretamente no arquivo `App.tsx`. Para resolver isso da melhor forma, foi necessário dividir a aplicação em **pelo menos** duas partes principais: sidebar e o conteúdo principal que possui o header e a listagem de filmes.

- A aplicação possui apenas uma funcionalidade principal que é a listagem de filmes;
- Na sidebar é possível selecionar qual categoria de filmes deve ser listada;
- A primeira categoria da lista (que é "Ação") já deve começar como marcada;
- O header da aplicação possui apenas o nome da categoria selecionada que deve mudar dinamicamente.
