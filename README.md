# DesafioCeleritech
API Rick and Morty para armazenamento de informações sobre personagens e locais

Endpoints:
GET /characters = Lista todas as personagens cadastradas 
GET /locations = Lista todos os lugares cadastrados
POST /characters = Cria uma personagem 
POST /locations = Cria um local
GET /characters/{id} = Retorna a personagem referente ao id da requisição
GET /locations/{id} = Retorna o local referente ao id da requisição
PUT /characters/{id} = Altera os dados da personagem referente ao id da requisição 
PUT /locations/{id} = Altera os dados do local referente ao id da requisição 
DELETE /characters/{id} = Apaga os dados da personagem referente ao id da requisição 
DELETE /locations/{id} = Apaga os dados do local 

JSON para Personagens:
{
    "name":"nome da personagem",
    "status":"alive/dead/unknown",
    "species":"espécie da personagem",
    "nameOrigin":"local de origem da personagem",
    "gender":"'Female', 'Male', 'Genderless' ou 'unknown'"
    "nameLocation":"Local onde o personagem foi visto"
}

JSON para Locais:
{
    "name":"nome do local",
    "dimension":"dimensão a qual o local pertence",
    "residents":"personagens vistos no local"
}


- Importar o projeto no Eclipse como Maven Project
- Rodar a classe DesafioApplication como um Java Project (Por padrão do Spring será na porta 8080)
- Utilizando o Postman, realizar as requisições de acordo com o verbo http de interesse

http://localhost:8080



