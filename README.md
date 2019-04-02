# Teste de Desenvolvimento
Teste de Desenvolvimento para candidatos a vaga de estágio em desenvolvimento

#### Objetivo
O objetivo da tarefa é desenvolver uma aplicação que consiga buscar dados de uma _API Rest_, válidar dados de login de um usuário, apresentar erros de entrada de dados e em uma segunda página, carregar os seguintes dados:

`Picture.thumbnail` - Imagem do usuário.

`Name.First + Name.Last` - Nome Inicial e Final do usuário

`Email` - Email do usuário

`DOB.date` - Data de Nascimento

Todos os dados devem ser distribuidos na tela, da forma que foi construido o modelo estrutural.

#### Modelo Estrutural 

[https://marvelapp.com/6d1h499](https://marvelapp.com/6d1h499)

Você poderá utilizar a biblioteca UI de sua preferência para desenvolver a estrutura da aplicação (bootstrap, materialize, UIKIT e afins), desde que siga o modelo estrutural.


#### Especificações Técnicas 

* Você deverá obrigatoriamente utilizar o framework [React](https://reactjs.org/) 
* A **API** a ser consumida se encontra no link [http://jobs-globocereais-com.umbler.net/api/v1/peoples_get](http://jobs-globocereais-com.umbler.net/api/v1/peoples_get)
* Validar erros de input



#### Modelo de Dado da API
```javascript 
{"results":[{"gender":"male","name":{"title":"mr","first":"diego","last":"lemaire"},"location":{"street":"8287 rue andré-gide","city":"brest","state":"mayotte","postcode":81128,"coordinates":{"latitude":"-1.6055","longitude":"-151.4252"},"timezone":{"offset":"-12:00","description":"Eniwetok, Kwajalein"}},"email":"diego.lemaire@example.com","login":{"uuid":"380d63ac-9601-4aac-881c-8936caeb7b7d","username":"bigrabbit578","password":"lorena","salt":"MydfMOWF","md5":"5cec6d6da40bf6976f98e9a5aa751ba0","sha1":"165c0883b29e3bf2701b3b6db5a5494ecd63e5bc","sha256":"a0039f448b5bfc08a4087427dfe8e7e6c4f560c054cf59046b4baadc2c4e51f9"},"dob":{"date":"1976-08-25T22:43:39Z","age":42},"registered":{"date":"2005-11-28T01:21:20Z","age":13},"phone":"04-68-74-74-85","cell":"06-38-42-68-49","id":{"name":"INSEE","value":"1NNaN33586714 75"},"picture":{"large":"https://randomuser.me/api/portraits/men/38.jpg","medium":"https://randomuser.me/api/portraits/med/men/38.jpg","thumbnail":"https://randomuser.me/api/portraits/thumb/men/38.jpg"},"nat":"FR"}],"info":{"seed":"2377537b5c521c9c","results":1,"page":1,"version":"1.2"}}
```

#### How to run?
Você deverá criar um arquivo .README no seu repositório do github, com os passos para executar o projeto.
