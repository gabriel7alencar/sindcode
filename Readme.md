## 🚀 MÓDULO: Desenvolvimento de Sistemas (200h)

Este repositório documenta o progresso e o material desenvolvido para a Unidade Curricular (UC) de **Desenvolvimento de Sistemas** do **Curso Técnico em Desenvolvimento de Sistemas** do SENAI-DF.

A UC visa aplicar metodologias ágeis e tecnologias modernas para a criação de um sistema web completo.

### 🛠️ Tecnologias e Ferramentas

| Categoria | Tecnologia | Ícone |
| :--- | :--- | :--- |
| **Linguagem** | Python | <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" height="20"/> |
| **Framework** | Django | <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django" height="20"/> |
| **Banco de Dados** | MySQL (ou equivalente) | <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" height="20"/> |
| **Versionamento** | Git & GitHub | <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" height="20"/> <img src="https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white" alt="GitHub" height="20"/> |
| **Gestão Ágil** | Scrum & Jira | <img src="https://img.shields.io/badge/Scrum-004A7F?style=flat-square&logo=scrumalliance&logoColor=white" alt="Scrum" height="20"/> <img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white" alt="Jira" height="20"/> |

---

### 📚 Diário de Bordo da UC

#### **Aula 1: Introdução à Metodologia e Ambientação**

| Tópico | Detalhes |
| :--- | :--- |
| **Foco da UC** | Subfunção 2.1 e Padrão de Desempenho 2.1.1 (Conhecimento 1.0) |
| **Metodologia** | Estudo e aplicação do **SCRUM** como Metodologia de Desenvolvimento de Sistemas. |
| **Projeto-Alvo** | Criação de um site completo para a **SindCode**, incluindo módulos de: <br> - Benefícios <br> - Notícias <br> - Galeria |
| **Fundamentos** | Revisão e discussão sobre Paradigmas de Programação (Estruturado, Orientado a Objetos e Funcional). |
| **Ambientação Django/Python** | Preparação inicial do ambiente de desenvolvimento. |
| **Configurações** | Definição de Idioma (`LANGUAGE_CODE`) e Fuso Horário (`TIME_ZONE`). |
| **Comandos Essenciais** | `django-admin help` <br> `django-admin startproject setup .` |

---

#### **Aula 2: Ferramentas de Gestão e Segurança do Ambiente**

| Tópico | Detalhes |
| :--- | :--- |
| **Ferramentas Ágeis** | Análise e configuração de ferramentas para suporte ao SCRUM: **Jira** (abordando SCRUM completo e Kanban reduzido), **Trello**, **Notion**, **GitHub Project**, **Azure Boards/DevOps**. |
| **Segurança** | Implementação de boas práticas para gerenciamento de credenciais. |
| **Variáveis de Ambiente** | Configuração de variáveis sensíveis utilizando o arquivo `.env`. |
| **SECRET KEY** | Geração e isolamento da `SECRET_KEY` do Django. |
| **Dependências** | Instalação da biblioteca `python-dotenv`. |
| **Código-Chave** | Importação e carregamento da variável de ambiente: <br>```python\nfrom dotenv import load_dotenv\n# pip install python-dotenv\nload_dotenv()\nSECRET_KEY = str(os.getenv("SECRET_KEY"))\n``` |



#### **Aula 3: Boas práticas**

- 3.1: boas prática da subfunção 2.1
- 4.4: controle de versãp da subfução 2.1
- Entre no site: https://www.toptal.com/developers/gitignore/api/django
- Entre no github crie novo repositorio: https://github.com/gabriel7alencar/sindcode
- Usar o commit especificando a tarefa do SCRUM :git commit -m "<<codigo-task>> <<mensagem>> <<#status>>"
- O aplicativo do Django é como se fosse um modulo