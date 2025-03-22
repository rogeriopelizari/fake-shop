# Fake Shop

## Informações do Desafio

## Desafio CI/CD - Fake Shop
O e-commerce Fake Shop está em produção! No entanto, a empresa enfrenta dificuldades no processo de entrega e manutenção, e cabe a você ajudar a resolver.

Atualmente, o deploy no Kubernetes está extremamente demorado: as equipes precisam de dois dias para realizá-lo e, mesmo assim, o processo não é confiável. É necessário otimizar essa entrega para que os times possam focar no desenvolvimento em vez de desperdiçar tempo com tarefas manuais.

Sua missão é automatizar o deploy da aplicação utilizando GitHub Actions, garantindo que toda atualização no código seja entregue no ambiente de forma eficiente e padronizada.

Se você ainda não tem uma conta na Digital Ocean, pode se cadastrar através do link abaixo para ganhar créditos bônus e utilizar os recursos gratuitamente por um tempo:

### 🔗 Cadastro na Digital Ocean

## 🛠 Tarefa Prática
🚀 Automação do Deploy com CI/CD
🚀 Crie uma pipeline CI/CD no GitHub Actions para automatizar o processo de build e deploy.

## A pipeline deve:
* 📦 Criar a imagem Docker e publicá-la no Docker Hub.
* ☸️ Fazer o deploy da aplicação no Kubernetes, utilizando kubectl para aplicar os manifestos já criados anteriormente.

## Variáveis de Ambiente
* DB_HOST	=> Host do banco de dados PostgreSQL.
* DB_USER => Nome do usuário do banco de dados PostgreSQL.
* DB_PASSWORD	=> Senha do usuário do banco de dados PostgreSQL.
* DB_NAME	=>	Nome do banco de dados PostgreSQL.
* DB_PORT	=>	Porta de conexão com o banco de dados PostgreSQL.
* FLASK_APP => Variável da aplicação Python.