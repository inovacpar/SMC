SMC — Sistema de Monitoramento Climático

1. Sobre o projeto

O SMC (Sistema de Monitoramento Climático) é um dispositivo eletrônico desenvolvido para monitorar variáveis ambientais, inicialmente focado na temperatura e na umidade relativa do ar.

2. Objetivos

- Monitorar a temperatura ambiente.
- Monitorar a umidade relativa do ar.
- Realizar coletas periódicas de dados ambientais.
- Processar e disponibilizar as informações coletadas.

3. Componentes utilizados

Componente| Função
ESP32| Processamento dos dados
DHT22| Medição de temperatura e umidade
Fonte 5 V| Alimentação elétrica

4. Tecnologias

- C++
- Arduino IDE
- ESP32

5. Funcionamento

O sensor DHT22 realiza as medições de temperatura e umidade relativa do ar. Os dados são enviados ao ESP32, responsável pelo processamento das informações.Os dados são enviados para a plataforma ThingSpeak(MathWorks)

6. Desenvolvimento

Projeto em desenvolvimento. Esta documentação será atualizada conforme a evolução do dispositivo.

7. Melhorias futuras

Novas funcionalidades e sensores poderão ser incorporados em versões posteriores como um sensores de pressão, velocidade do vento e qualidade do ar.
