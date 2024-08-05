# 🚀 Dashboard de Jogos Olímpicos

## Descrição

Este projeto é uma aplicação web que exibe um painel de controle interativo para os Jogos Olímpicos. A aplicação consome a API do Codante, que fornece dados em tempo real sobre os eventos olímpicos, incluindo medalhas por país, locais dos eventos e outras informações relevantes.

Utilizando a biblioteca Leaflet para visualização de mapas e gráficos, o painel permite visualizar informações detalhadas sobre os locais dos eventos olímpicos em um mapa interativo e aplicar filtros para exibir dados relevantes. 

## Tecnologias Utilizadas

- **HTML/CSS**: Estrutura e estilo da interface.
- **JavaScript**: Lógica de funcionamento e interação com APIs.
- **Leaflet**: Biblioteca para mapas interativos.
- **Selenium WebDriver**: Automação de testes de interface.
- **Mocha**: Framework de testes.
- **Chai**: Biblioteca de asserções para testes.
- **Node.js**: Ambiente de execução do JavaScript no servidor.

## Funcionalidades

- **Visualização de Mapas**: O mapa é carregado e exibido utilizando a biblioteca Leaflet. Mostra marcadores para os locais dos eventos olímpicos.
- **Dados em Tempo Real**: Consome a API do Codante para exibir dados atualizados sobre medalhas por país e outras informações importantes.
- **Testes Automatizados**: Utiliza Selenium WebDriver com Mocha e Chai para realizar testes automatizados da interface do usuário e garantir que as funcionalidades estejam operacionais.

## Instalação

1. Clone o repositório:

    ```bash
    git clone https://github.com/SEU_USUARIO/olympics-dashboard.git
    ```

2. Navegue para o diretório do projeto:

    ```bash
    cd olympics-dashboard
    ```

3. Instale as dependências:

    ```bash
    npm install
    ```

## Uso

Para iniciar o servidor e visualizar a aplicação:

1. Inicie um servidor local (você pode usar ferramentas como `Live Server` no VS Code ou configurar um servidor local de sua preferência).

2. Acesse `http://localhost:PORT` no seu navegador para visualizar o painel.

## Executando Testes

Para rodar os testes automatizados, utilize o comando:

```bash
npm test
```