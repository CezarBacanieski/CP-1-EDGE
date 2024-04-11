# CP-1-EDGE
# Controle de Iluminação para Vinícola

## Descrição
Este projeto propõe um sistema de controle de iluminação destinado a uma vinícola. O sistema monitora a luminosidade do ambiente e utiliza LEDs indicadores, juntamente com um buzzer, para alertar sobre diferentes condições de iluminação.

## Funcionalidades
- **Monitoramento da luminosidade:** Utilização de um sensor de luminosidade para medir o nível de iluminação na vinícola.
- **Indicação visual e sonora:** LEDs de diferentes cores (verde, amarelo e vermelho) e um buzzer fornecem feedback visual e sonoro sobre o estado da iluminação.
- **Controle automatizado:** Com base na leitura da luminosidade, o sistema realiza ajustes automáticos nos LEDs e no buzzer para fornecer feedback em tempo real sobre a iluminação do ambiente.

## Funcionamento
O sistema opera da seguinte forma:
- **LED Verde:** Indica que a luminosidade está dentro do intervalo ideal para a vinícola.
- **LED Amarelo e Buzzer:** Alerta sobre um nível de luminosidade que requer atenção.
- **LED Vermelho:** Indica uma condição crítica de iluminação que pode prejudicar a produção da vinícola. O buzzer é ativado simultaneamente.
- **Buzzer:** Para de soar após 3 segundos do acionamento do LED verde e ajuste da luminosidade.

## Instalação e Configuração
Para utilizar o sistema:
1. **Montagem do Hardware:** Conecte o sensor de luminosidade ao pino analógico A0 e os LEDs aos pinos digitais 9, 10 e 11, conforme especificado no código fonte.
2. **Upload do Código:** Carregue o código fonte fornecido para a placa Arduino utilizando a IDE Arduino.
3. **Alimentação:** Utilize uma fonte de energia adequada para alimentar a placa Arduino.
4. **Ajustes:** Se necessário, ajuste os limiares de luminosidade no código fonte para adaptar o sistema às condições específicas da vinícola.
5. **Execução:** Após a inicialização, o sistema começará a monitorar a luminosidade do ambiente e fornecerá feedback visual e sonoro conforme descrito anteriormente.

## Sobre a função map()
A função `map()` é utilizada no código fonte para ajustar os valores lidos pelo sensor de luminosidade para uma faixa específica, tornando mais fácil determinar a luminosidade do ambiente. 
Essa função mapeia um valor de uma faixa de entrada para uma faixa de saída.

## Links
- [Tinkercad](https://www.tinkercad.com/) - Teste o projeto!!
- [YouTube](https://www.youtube.com/) - Assista explicação em vídeo!!
