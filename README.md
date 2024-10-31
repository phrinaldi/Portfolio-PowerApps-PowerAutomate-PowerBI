# Portfolio-PowerApps-PowerAutomate-PowerBI

# Sistema de Gerenciamento de Férias

## Contextualização:
Uma grande empresa do setor de tecnologia, chamada HashTech, enfrenta desafios significativos na gestão das férias dos seus colaboradores. Com uma força de trabalho de mais de 200 funcionários, a empresa atualmente utiliza um processo manual e descentralizado para solicitar, aprovar e monitorar as férias. Esse método resulta em várias dificuldades, tais como:

- **Demora na Aprovação**: Os pedidos de férias frequentemente demoram a ser processados, uma vez que dependem de várias camadas de aprovação manual.
- **Erros Humanos**: A inserção manual de dados em planilhas aumenta o risco de erros, como datas incorretas ou dados duplicados.
- **Falta de Transparência**: Os funcionários não têm visibilidade sobre o status das suas solicitações de férias, o que gera frustração e incerteza.
- **Relatórios Ineficientes**: A equipe de RH tem dificuldades em gerar relatórios precisos e em tempo hábil sobre o saldo de férias, as férias programadas e as ausências em diferentes departamentos.

## Situação:
A HashTech decidiu implementar um sistema automatizado de gerenciamento de férias utilizando as ferramentas Power Platform da Microsoft, especificamente Power Apps, Power Automate e Power BI. O objetivo é criar uma solução que permita:

1. **Solicitação de Férias**: Um aplicativo intuitivo em Power Apps onde os funcionários possam solicitar férias, visualizar seu saldo de dias disponíveis e acompanhar o status das suas solicitações.
2. **Aprovação de Férias**: Um fluxo automatizado em Power Automate que notifique os gestores sobre novas solicitações de férias, permitindo uma aprovação ou rejeição rápida e registrada.
3. **Centralização e Monitoramento**: Dashboards interativos em Power BI que forneçam aos gestores uma visão completa e atualizada sobre as férias dos colaboradores, incluindo relatórios detalhados sobre saldos de férias e aprovações pendentes.

## Objetivos do Case:
1. **Desenvolver o Aplicativo em Power Apps**: Criar uma interface amigável e funcional para que os funcionários possam gerenciar suas férias.
2. **Configurar o Fluxo em Power Automate**: Implementar um fluxo que automatize a comunicação e a aprovação das solicitações de férias, garantindo eficiência e redução de erros.
3. **Criar um Dashboard simples no Power BI**: Configurar relatórios dinâmicos que permitam o acompanhamento em tempo real das férias, facilitando a tomada de decisões pela gestão.

## Tarefas a Realizar:

1. **Desenho do Aplicativo**:
   - Definir os requisitos funcionais e não funcionais do aplicativo.
   - Criar as telas de solicitação, aprovação e visualização de status.
   - Integrar o aplicativo com uma base de dados.

2. **Implementação do Fluxo de Trabalho**:
   - Mapear o processo de solicitação e aprovação de férias.
   - Criar o fluxo de trabalho no Power Automate, incluindo notificações e aprovações.
   - Testar o fluxo para garantir a correta execução.

3. **Configuração dos Dashboards**:
   - Construir os dashboards em Power BI com os dados.
   - Implementar filtros e visualizações interativas para facilitar a análise

---------------------------------------------------------------------------------------------------------------------------

## Processo:

1- O usuário entra no aplicativo e solicita as férias

2- A solicitação cria um item (linha) em uma lista do Microsoft Lists

3- Ao criar uma linha no Lists, é disparado o fluxo do Power Automate

4- O fluxo envia um email de aprovação ou recusa das férias ao gerente

5- Depois da aprovação/recusa, um email é enviado ao colaborador

6- A linha é atualizada no Lists

7- A tela de Acompanhamento no Power Apps é atualizada

8- O gráfico de Gantt é atualizado no Power BI, que contém a representação gráfica dos requerimentos e períodos de férias




