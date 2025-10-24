📘 API REST - Gestão de Vendedores (Protheus TLPP)
🎯 Descrição do Projeto
API REST desenvolvida em TLPP (TOTVS Language++) para integração com o sistema Protheus ERP. Implementa operações CRUD para gestão de cadastro de vendedores (tabela SA3), permitindo consultas e atualizações via requisições HTTP.

🚀 Tecnologias Utilizadas

TLPP (TOTVS Language++) - Linguagem de programação
Protheus 12.1.2410 - ERP Base
SQL - Banco de dados
REST API - Arquitetura de comunicação
JSON - Formato de dados
Postaman


📋 Funcionalidades
✅ Endpoints Disponíveis
MétodoEndpointDescriçãoGET/johndeere/vendedoresLista todos os vendedores cadastradosGET/johndeere/vendedores/:codigoBusca vendedor específico por códigoPUT/johndeere/atualizar_vendedoresAtualiza dados de um vendedor

📝 Exemplos de Uso
1️⃣ Listar Todos os Vendedores
httpGET http://localhost:8081/rest/johndeere/vendedores
Resposta:
json{
  "success": true,
  "total": 3,
  "vendedores": [
    {
      "codigo": "00001",
      "nome": "CLAUDIO DA SILVA",
      "email": "claudio@empresa.com",
      "telefone": "4136565598"
    }
  ],
  "mensagem": "Consulta realizada com sucesso"
}

2️⃣ Buscar Vendedor por Código
httpGET http://localhost:8081/rest/johndeere/vendedores/00002
Resposta:
json{
  "success": true,
  "codigo": "00002",
  "nome": "Daniel Luiz",
  "email": "daniel@empresa.com",
  "telefone": "41999998888",
  "endereco": "RUA DAS AROBOIRA",
  "bairro": "CAUURU",
  "municipio": "CURITIBA",
  "estado": "PR"
}

3️⃣ Atualizar Vendedor
httpPUT http://localhost:8081/rest/johndeere/atualizar_vendedores

Headers:
codigo: 00002
Content-Type: application/json

Body:
{
  "telefone": "41999998888",
  "email": "novo.email@empresa.com"
}
Resposta:
json{
  "success": true,
  "mensagem": "Vendedor atualizado com sucesso",
  "codigo": "00002"
}

🔧 Configuração e Instalação
Pré-requisitos

Protheus 12.1.2410 ou superior
AppServer REST configurado
Acesso ao banco de dados Oracle
VSCode com extensão AdvPL/TLPP

<img width="1202" height="615" alt="image" src="https://github.com/user-attachments/assets/7a49cb54-83b2-4547-b82c-5262f8e97df6" />
<img width="1177" height="188" alt="image" src="https://github.com/user-attachments/assets/57867d09-46df-4c4b-adad-3bbb857e7125" />
<img width="1027" height="425" alt="image" src="https://github.com/user-attachments/assets/4c665836-1098-461d-ba84-5a1ad97746b7" />


<img width="819" height="565" alt="testeJohndeere" src="https://github.com/user-attachments/assets/739cd4c5-768e-4c04-bdf7-36138725f6aa" />
