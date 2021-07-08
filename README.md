# web-services-via-CEP
Criação de um WEB Services para cadastramento de um usuário

* O programa consiste num modulo de cadastramento de usuários com os campos: nome, email, telefone, CEP e endereço (o campo email é chave de busca).
* Esses dados precisam ser gravados em um banco de dados AWS RDS.
* O campo CEP será usado para buscar o endereço completo através do serviço https://viacep.com.br/
* O usuário vai digitar o CEP e o sistema vai preencher os campos do endereço, exceto o número e o complemento.
* No processo de cadastramento será necessário subir a foto do usuário. Essa foto será armazenada em um bucket do AWS S3 configurado por você.
* Será preciso implementar inclusão, consulta e alteração de dados.

