## 🚀 Sobre o desafio

Nesse desafio, será criada uma aplicação para treinar ReactJS!

Agora devemos continuar desenvolvendo a aplicação que irá armazenar
repositórios do nosso portfólio, já foi desenvolvido o backend no último desafio utilizando o Node.js.

### Funcionalidades da aplicação

Agora que você já está com o template clonado, e pronto para continuar, você deve abrir o arquivo **src/App.js**, e completar onde não possui código com o código para atingir os objetivos de cada funcionalidade.

Listar os repositórios da sua API: Deve ser capaz de criar uma lista com o campo title de todos os repositórios que estão cadastrados na sua API. Para carregar sua lista de repositorios a gente usa o useEffect dentro do react para ele disparar alguma função em algum momento do nosso componente. fazemos a conexao com o services do axios e vamos dentro do useEffect vamos chamar api.get. Precisamos de um estado do react para salvar esses repositorios, preciso salvar em algum lugar que o meu componente tem acesso e o melhor lugar sempre é o estado.

Adicionar um repositório a sua API: Deve ser capaz de adicionar um novo item na sua API através de um botão com o texto Adicionar e, após a criação, deve ser capaz de exibir o nome dele após o cadastro. 

Remover um repositório da sua API: Para cada item da sua lista, deve possuir um botão com o texto Remover que, ao clicar, irá chamar uma função para remover esse item da lista do seu frontend e da sua API.
