# 🚀 Digital Hub - Busca de Usuários GitHub

## Objetivo
O objetivo deste projeto é desenvolver duas páginas web usando React: uma para buscar usuários do GitHub e exibir suas informações básicas, como número de repositórios, seguidores e pessoas que está seguindo; e outra para visualizar uma lista de todos os repositórios de um usuário, juntamente com informações relevantes sobre cada repositório.

## Funcionalidades

### Página de Busca de Usuários
- Criar uma página com um campo de entrada onde os usuários podem inserir o nome de usuário do GitHub que desejam buscar.
- Ao enviar o formulário de busca, a página deve consumir a API pública do GitHub (https://api.github.com/) para obter informações sobre o usuário especificado.
- As informações recuperadas devem ser exibidas de forma clara e organizada na página, incluindo o nome de usuário, avatar, biografia, número de repositórios, número de seguidores e número de pessoas que o usuário está seguindo.

### Página de Visualização de Repositórios
- Criar uma nova página onde os usuários possam inserir o nome de usuário do GitHub.
- Ao enviar o formulário de busca, a página deve consumir a API pública do GitHub para obter informações sobre todos os repositórios do usuário especificado.
- Os repositórios recuperados devem ser exibidos em uma lista na página, mostrando o nome do repositório, descrição, número de estrelas, linguagem de programação e data de criação.

## Requisitos Principais
- Utilizar React para criar as páginas de busca de usuários e visualização de repositórios.
- Organizar o projeto de forma adequada, utilizando componentes do React de forma eficiente.
- Utilizar React Hooks para gerenciar o estado da aplicação, como os dados dos usuários e repositórios recuperados da API do GitHub.
- Consumir a API do GitHub através do endpoint https://api.github.com/.
