# Simulação de Temporizadores com Raspberry Pi Pico

## Descrição
Este projeto implementa dois sistemas de temporização utilizando o **Raspberry Pi Pico W** e o **Pico SDK**, simulados no **Wokwi**:

1. **Atividade 1 - Temporizador Periódico:** Um semáforo com LEDs que alternam a cada 3 segundos.
2. **Atividade 2 - Temporizador de Um Disparo (One Shot):** Um sistema onde um botão aciona LEDs sequenciais com atraso de 3 segundos entre cada mudança.

## Requisitos
- **Raspberry Pi Pico W**
- **SDK do Pico** instalado
- **Simulador Wokwi**
- **Editor VS Code**
- **Bibliotecas necessárias do CMake para o Pico SDK**

## Configuração do Hardware
### Atividade 1 - Semáforo
- LED **Vermelho**: GPIO 2
- LED **Amarelo**: GPIO 3
- LED **Verde**: GPIO 4

### Atividade 2 - Temporizador One Shot
- LED **Azul**: GPIO 6
- Botão (Pushbutton): GPIO 5
- 
- ## Simulação no Wokwi
Para simular no **Wokwi**, utilize o arquivo JSON fornecido (`codigo.json`).

## Observações
- O botão só pode ser pressionado após a sequência de LEDs finalizar na Atividade 2.
- A saída serial imprime mensagens indicando o funcionamento do sistema.
