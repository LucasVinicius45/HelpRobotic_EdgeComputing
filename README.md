## Nome: Irana Pereira RM: 98593
## Nome: Lucas Vinicius Candido da Silva RM: 98480
## Nome: Mariana A Melo RM: 98121


### Este README fornece informações detalhadas sobre o projeto de IoT, incluindo uma descrição geral, a arquitetura proposta, recursos necessários, instruções de uso e outras informações relevantes.

## Descrição do Projeto
### O projeto de IoT proposto visa criar uma solução que permita monitorar e controlar dispositivos IoT usando uma combinação de Simulide, Node-RED, Tago Cloud e formato JSON para comunicação de dados. A solução é flexível e pode ser adaptada para várias aplicações, como monitoramento ambiental, automação residencial ou industrial, entre outros.

## Arquitetura Proposta
### A arquitetura da solução IoT é composta por três principais componentes: IoT devices, back-end e front-end.

## IoT Devices
### Os dispositivos IoT são sensores, atuadores ou dispositivos inteligentes que coletam informações do ambiente ou executam ações com base em comandos recebidos. Eles se comunicam com o back-end por meio de protocolos como MQTT ou HTTP, enviando e recebendo dados em formato JSON.

## Back-end
### O back-end é responsável por receber os dados dos dispositivos IoT, processá-los, armazená-los e disponibilizá-los para o front-end. O Node-RED é utilizado como a plataforma de automação e integração para facilitar a comunicação entre os dispositivos IoT e a Tago Cloud. O Node-RED também pode ser configurado para executar lógica personalizada, como alertas ou automações específicas do projeto.

## Front-end
### O front-end é a interface de usuário que permite aos utilizadores interagir com os dispositivos IoT e visualizar os dados coletados. Pode ser uma aplicação web ou móvel que acessa a Tago Cloud para exibir gráficos, tabelas e controles para monitorar e controlar os dispositivos.

## Recursos Necessários
### Para implementar esta solução IoT, são necessários os seguintes recursos:

## Dispositivos IoT
### Sensores, atuadores ou dispositivos inteligentes compatíveis com a comunicação via MQTT ou HTTP.
## Acesso à internet para enviar dados para o back-end.
### Back-end
### Servidor ou máquina onde o Node-RED será instalado.
### Instalação do Node-RED (https://nodered.org/docs/getting-started/installation).
### Conta na Tago Cloud (https://tago.io/).
### Configuração de dispositivos na Tago Cloud e obtenção de chaves de API para autenticação.
## Front-end
### Navegador da web moderno para acessar a interface do usuário.
## Instruções de Uso
### Aqui estão as etapas gerais para configurar e usar o projeto:

### Configure os dispositivos IoT para se comunicarem com o back-end usando os protocolos MQTT ou HTTP. Use as chaves de API da Tago Cloud para autenticação.

### Instale o Node-RED no servidor ou máquina escolhida.

### Crie um fluxo no Node-RED para receber dados dos dispositivos IoT, processá-los e enviar para a Tago Cloud. Use os nodes MQTT ou HTTP para comunicação com os dispositivos e o node Tago para enviar dados para a plataforma Tago Cloud.

### Na Tago Cloud, configure dispositivos, variáveis e dashboards para visualizar os dados coletados.

### Implemente a interface de usuário do front-end para acessar os dados na Tago Cloud, usando as APIs disponíveis.

### Teste a solução, monitorando os dispositivos IoT, enviando comandos e visualizando os dados em tempo real.

### Documente seu projeto, incluindo informações de configuração, scripts e lógica do Node-RED, e a estrutura do banco de dados na Tago Cloud.

### Requisitos e Dependências
### Node-RED
### Tago Cloud
### Dispositivos IoT compatíveis com MQTT ou HTT
