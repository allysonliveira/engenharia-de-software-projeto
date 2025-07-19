# Proejeto de Engenharia de Softwate - "Meu Posto de Saúde"
## Projeto da disciplina de Engenharia de Software (DCA3603/UFRN). O projeto apresnenta três etapas de desenvolvimento:
- Backend
- Frontend
- Padrões do projeto

## Estrutura das etapas do projeto
### Backend

meupostodesaude/

├── app/

│   ├── main.py              # Arquivo principal da API

│   ├── models/              # Modelos do banco de dados (ORM)

│   ├── schemas/              # Schemas Pydantic (validação de dados)

│   ├── routes/              # Endpoints da API

│   ├── services/            # Regras de negócio

│   └── core/                # Configurações e autenticação

├── script_demo.py           # Script com chamadas HTTP

├── Dockerfile               # Definição do container backend

├── docker-compose.yml       # Integração com banco

├── .env                     # Variáveis de ambiente (ex: DB_URL, SECRET)

├── requirements.txt         # Dependências do Python

└── .github/workflows/tests.yml # CI/CD (GitHub Actions)
