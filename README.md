

https://tdn.totvs.com/display/tec/TLPP

https://tdn.totvs.com/display/public/framework/REST

https://tdn.totvs.com/display/public/PROT/MATA040
## 📊 Estrutura do Código
```
JDAPIVEN.tlpp
├── ListaVendedores()        # GET - Lista todos
├── VendedorEspecifico()     # GET - Busca por código
└── AtualizaVendedor()       # PUT - Atualiza dados

- ✅ **Busca Flexível de Código**: Aceita códigos com 5 ou 6 dígitos
- ✅ **Validação de JSON**: Suporte a `JsonObject` e `FWJsonDeserialize`
- ✅ **Tratamento de Erros**: Logs detalhados e mensagens claras
- ✅ **ExecAuto MATA040**: Integração com rotina padrão do Protheus
- ✅ **SQL Direto**: Queries otimizadas para alta performance
- ✅ **HTTP Status Codes**: Implementação correta (200, 400, 404, 500)


📘 API REST - Desenvolver uma API RESTFULL em advpl Tlpp - que permita a recuperação e atualização (GET e PUT) de registro de vendedores na tabela (SA3 )
Get e Put (Protheus TLPP)

🎯 Descrição do Projeto
API RESTFULL em advpl Tlpp - que permita a recuperação e atualização (GET e PUT) de registro de vendedores na tabela (SA3 )
API REST desenvolvida em TLPP (TOTVS Language++) para integração com o sistema Protheus ERP.
Implementa operações cadastro de vendedores (tabela SA3), permitindo consultas e atualizações via requisições HTTP.

🚀 Tecnologias Utilizadas

TLPP (TOTVS Language++) - Linguagem de programação
Protheus 12.1.2410 - ERP Base
SQL - Banco de dados
REST API - Arquitetura de comunicação
JSON - Formato de dados
Postman


📋 Funcionalidades
✅ Endpoints Disponíveis
MétodoEndpointDescrição
GET/johndeere/vendedoresLista todos os vendedores
cadastradosGET/johndeere/vendedores/:codigo
Busca vendedor específico por código
PUT/johndeere/atualizar_vendedoresAtualiza dados de um vendedor



🔧 Configuração e Instalação
Pré-requisitos

Protheus 12.1.2410 ou superior
AppServer REST configurado
Acesso ao banco de dados SQL
VSCode com extensão AdvPL/TLPP
## 📊 Estrutura do Código
```

<img width="1202" height="615" alt="image" src="https://github.com/user-attachments/assets/7a49cb54-83b2-4547-b82c-5262f8e97df6" />
<img width="1177" height="188" alt="image" src="https://github.com/user-attachments/assets/57867d09-46df-4c4b-adad-3bbb857e7125" />
<img width="1027" height="425" alt="image" src="https://github.com/user-attachments/assets/4c665836-1098-461d-ba84-5a1ad97746b7" />
<img width="901" height="546" alt="retornoatulizacao" src="https://github.com/user-attachments/assets/21d47a8c-dd19-4c89-84ec-d09a79b1599a" />
<img width="819" height="565" alt="testeJohndeere" src="https://github.com/user-attachments/assets/739cd4c5-768e-4c04-bdf7-36138725f6aa" />
