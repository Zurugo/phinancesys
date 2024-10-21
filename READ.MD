RFs (Requisitos funcionais)
[] Dever ser possivel cadastrar usuarios
[] Deve ser possivel retornar usuarios
[] Dever ser possivel cadastrar clientes 
[] Deve ser possivel listar todos os clientes 
[] Deve ser possivel realizar o cadastro de fornecedores 
[] Deve ser possivel listar todos os fornecedores 
[] Deve ser possivel realizar o cadastro de contas a pagar 
[] Deve ser possivel listar todos os titulos de contas a pagar 
[] Deve ser possivel realizar o cadastro de contas a receber
[] Deve ser possivel listar todos os titulos de contas a receber

RNs (Regras de negocio)
[] Para listar os fornecedores, obrigatoriamente precisamos informar o CNPJ
[] Para listar os clientes, obrigatoriamente precisamos informar o CPF ou CNPJ e Endereco
[] Para cadastrar um titulo de contas a pagar, obrigatoriamente precisamos informar um fornecedor
[] Para cadastrar um titulo de contas a receber, obrigatoriamente precisamos informar um cliente
[] Para listar os titulos de contas a pagar, obrigatoriamente precisamos informar um fornecedor
[] Para listar os titulos de contas a receber, obrigatoriamente precisamos informar um cliente

RNFs
[] A senha do usuario precisa estar criptografada
[] Os dados da aplicacao deve estar persistidos em um banco de dados PostgreSQL
[] Toda lista de dados precisam estar paginadas com 20 itens por pagina
[] O usuario deve ser identificador por um JWT (JSON Web Token)
