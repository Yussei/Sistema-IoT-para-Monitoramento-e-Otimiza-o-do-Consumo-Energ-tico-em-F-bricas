# Sistema-IoT-para-Monitoramento-e-Otimizacao-do-Consumo-Energetico-em-Fabricas
Repositório do Trabalho Semestral de Objetos Inteligentes Conectados 2.2024


Descrição do Trabalho
Neste trabalho, propus um sistema IoT para monitorar o consumo de energia em fábricas, com o objetivo de otimizar o uso de recursos energéticos e reduzir desperdícios. Para isso, será utilizado sensores inteligentes que serão instalados em máquinas e equipamentos industriais, fornecendo dados em tempo real para uma plataforma de gestão na nuvem, que analisará os padrões de consumo e sugerirá intervenções.

Código e Documentação
A documentação e códigos foram salvos nos tópicos ESP32_code aplicado no simulador Wokwi, indicado pelo professor e o arquivo Json para fazer a comunicação na mesma plataforma citada anteriormente.

Comunicação via Protocolo MQTT
A comunicação foi feita pela rede Wi-fi (TCP/IP), utilizando o protocolo MQTT para transferência de dados para o AdaFruit IO. Para isso, foi configurado o wifi_ssid e wifi_senha para conexão Wi-fi, configuração do Username + key  para a autenticação MQTT do AdaFruit e criação dos feeds de Relay, Corrente e Relé.
