# Backend — Projeto Lojinha 🔧

**Visão geral**

Este diretório (`Back`) contém o backend do projeto **Lojinha**, iniciado no primeiro período do curso. Nesta fase, vamos acrescentar a parte de servidor e persistência de dados utilizando os conhecimentos do segundo período: **Python**, **banco de dados MySQL** e boas práticas de **gerenciamento de projetos**.

---

## Objetivos 🎯

- Implementar a API e a lógica de negócio do sistema da lojinha em **Python**.
- Persistir dados em **MySQL** seguindo o padrão **DAO (Data Access Object)** para separar lógica de acesso a dados da lógica de negócio.
- Aplicar técnicas de versionamento, testes e organização de projeto aprendidas no segundo período.

---

## Tecnologias previstas 🔧

- Linguagem: **Python 3.10+**
- Banco de dados: **MySQL**
- Padrão de projeto: **DAO** para acesso a dados
- Gestão do projeto: Git, issues, branch model (feature/bugfix)
- Opcional: frameworks leves (ex.: **Flask**, **FastAPI**) e bibliotecas de ORM ou abstração (mantendo o padrão DAO)

---

## Estrutura sugerida de pastas 📁

- `app/` — código da aplicação (controllers, serviços)
- `dao/` — implementações do padrão DAO (acesso ao MySQL)
- `models/` — definições de entidades
- `tests/` — testes unitários e de integração
- `migrations/` — scripts ou ferramentas de migração do banco
- `requirements.txt` — dependências do projeto
- `.env.example` — variáveis de ambiente necessárias

---

## Variáveis de ambiente (exemplo) ⚙️

```
MYSQL_HOST=localhost
MYSQL_PORT=3306
MYSQL_USER=seu_usuario
MYSQL_PASSWORD=sua_senha
MYSQL_DATABASE=lojinha_db
```

---

## Como começar (exemplo) ▶️

1. Criar e ativar um ambiente virtual:

```
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

2. Configurar o MySQL e atualizar as variáveis de ambiente.
3. Executar migrações e iniciar a aplicação (comando a ser definido conforme o framework escolhido).

---

> Nota: Adapte comandos e instruções conforme o framework ou ferramentas escolhidas. Mantenha o padrão DAO para garantir separação clara entre lógica de negócio e acesso a dados.

---

## Contribuição 🤝

- Abra issues para bugs e propostas de features.
- Use branches `feature/` e `fix/` e faça PRs com descrição clara.
- Escreva testes para novas funcionalidades.

---

**Licença**

Defina a licença do projeto conforme a política do curso ou do time.
