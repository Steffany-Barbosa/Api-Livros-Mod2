👩🏽‍💻Você precisa criar uma API em Flask que permita:

-Cadastrar um livro no banco de dados (POST com a rota /doar)  
-Listar todos os livros cadastrados (GET com a rota /livros)  
-Exibir uma página inicial (GET com a rota /) com uma mensagem personalizada à sua escolha.


⚙️ Requisitos técnicos:
1️⃣ Utilize Flask para criar as rotas.
2️⃣ Utilize SQLite como banco de dados.  
3️⃣ A tabela do banco de dados deve ser chamada LIVROS e conter os seguintes campos:
                 - id (chave primária, autoincrementada)
                 - titulo (texto, obrigatório)
                 - categoria (texto, obrigatório)
                 - autor (texto, obrigatório)
                 - image_url (texto, obrigatório)
5️⃣ Ao cadastrar um novo livro, a API deve retornar uma resposta JSON com o código 201 confirmando o cadastro.  
6️⃣ A rota GET /livros deve retornar todos os livros cadastrados no banco de dados, organizados em um JSON contendo: 
                - id
                - título
                - categoria
                - autor
                - image_url  
7️⃣ A rota inicial (/) deve exibir uma mensagem personalizada que você irá criar!
📤O que você deve entregar?

- O código da API Flask funcionando com as rotas GET e POST para /doar e /livros, além da rota inicial /  
- Um arquivo database.db com a estrutura do banco de dados criada