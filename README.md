Explorando AWS Step Functions

🎯 O que aprendi

Durante o laboratório, alguns pontos chamaram bastante minha atenção:

* **Visualização do workflow**: o Step Functions oferece uma representação visual de todo o fluxo da aplicação, facilitando o entendimento da execução e a identificação de possíveis falhas.
* **Definição dos fluxos utilizando ASL (Amazon States Language)**: os workflows são descritos em JSON, tornando a definição dos estados simples, padronizada e fácil de versionar.
* **Centralização da orquestração**: em vez de distribuir a lógica de execução entre diversos serviços, o Step Functions permite centralizar o fluxo em um único lugar, deixando claro qual serviço será executado em cada etapa.
* **Integração com serviços da AWS**: o serviço facilita a comunicação entre componentes como Lambda, SQS, SNS, DynamoDB e diversos outros serviços, sem a necessidade de criar uma lógica de orquestração manual.



🚀 Benefícios observados
* Melhor visualização do processo de negócio.
* Fluxos mais organizados e fáceis de manter.
* Menor complexidade na orquestração entre serviços.
* Facilidade para acompanhar a execução de cada etapa do workflow.
* Definição declarativa dos estados utilizando JSON.
💡 Conclusão

O principal aprendizado foi entender que o AWS Step Functions não executa apenas funções, mas atua como um orquestrador de workflows. Ele permite centralizar toda a lógica de execução, oferecendo uma visão clara do processo e facilitando tanto o desenvolvimento quanto a manutenção de aplicações distribuídas.
