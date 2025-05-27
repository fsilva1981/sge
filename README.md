Sistema de Gestão de Estoque (SGE)

Autor: Francisco de Assis Ferreira Silva
Projeto apresentado como requisito de aprovação na disciplina Frameworks com Persistencia de Dados – Unialfa 2025.

📦 Sobre o projeto

O SGE (Sistema de Gestão de Estoque) é uma aplicação desenvolvida com o framework Django, visando facilitar o controle de estoque de produtos, incluindo funcionalidades para gerenciamento de marcas, categorias, fornecedores, entradas e saídas de produtos.

🧩 Funcionalidades

Cadastro e listagem de marcas
Cadastro e listagem de categorias
Cadastro e listagem de fornecedores
Registro de entradas (inflows) e saídas (outflows) de produtos
Controle de estoque com atualização automática
🛠️ Tecnologias utilizadas

Python 3.11
Django 4.x
SQLite (banco de dados padrão do Django)
Biblioteca Bootstrap (Atende demandas de Javascrip, CSS e HTML)
CharJS para demandas de dashboard

🚀 Como executar o projeto

Pré-requisitos
Python 3.11 ou superior instalado
Git instalado
Passo a passo
Clone o repositório:
git clone https://github.com/fsilva1981/sge.git
cd sge
Crie e ative um ambiente virtual:
python -m venv venv
# No Windows
venv\Scripts\activate
# No Linux/Mac
source venv/bin/activate
Instale as dependências:
pip install django
Nota: Se houver um arquivo requirements.txt, utilize:
pip install -r requirements.txt
Aplique as migrações do banco de dados:
python manage.py migrate
Crie um superusuário para acessar o painel administrativo:
python manage.py createsuperuser
Siga as instruções para definir um nome de usuário, e-mail e senha.
Inicie o servidor de desenvolvimento:
python manage.py runserver
Acesse o sistema:
Interface administrativa: http://127.0.0.1:8000/admin/
Interface principal (caso implementada): http://127.0.0.1:8000/
📁 Estrutura do projeto

sge/
├── app/
│   ├── brands/
│   ├── categories/
│   ├── inflows/
│   ├── outflows/
│   ├── products/
│   └── suppliers/
├── manage.py
├── README.md
└── LICENSE
Cada diretório dentro de app/ representa um módulo da aplicação, responsável por uma funcionalidade específica do sistema.

📝 Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para obter mais informações.




## 🙏 Agradecimentos

Este projeto foi desenvolvido com base nos conhecimentos adquiridos através das aulas do professor **Felipe** na plataforma [Django Master].  
Agradeço pelo conteúdo didático e claro, que foi essencial para a realização deste trabalho.

