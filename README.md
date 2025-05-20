# irrigacao-farmtech
Projeto de Irrigação Inteligente
Este projeto simula um sistema de irrigação inteligente utilizando ESP32, sensores e Python para armazenamento de dados.

Componentes Utilizados:
ESP32

Botões (Fósforo e Potássio)

LDR (pH)

DHT22 (Umidade)

Relé e LED (Bomba de Irrigação)

Lógica de Funcionamento:
A bomba de irrigação é acionada quando a umidade do solo está abaixo de 30%, o pH está entre 6 e 7, e há presença de fósforo e potássio no solo.

Armazenamento de Dados:
Os dados coletados pelos sensores são armazenados em um banco de dados SQLite, permitindo operações de inserção, leitura, atualização e exclusão.
