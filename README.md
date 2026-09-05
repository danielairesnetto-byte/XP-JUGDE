# ⚖️ XP-JUDGE 🎲

O **XP JUDGE** foi criado com uma única missão: resolver a injusta distribuição de Pontos de Experiência nas suas mesas de RPG! ⚔️

Ele é um dispositivo portátil projetado para calcular e distribuir **XP** de forma rápida, imparcial e precisa. O sistema automatiza fórmulas complexas considerando o dano infligido 💥, a cura realizada 🧪 e as ações táticas 🛡️ de cada jogador. 

Tudo isso garante uma divisão justa ao final de cada sessão, sem quebrar o ritmo nem desacelerar a narrativa do jogo na mesa! 🧙‍♂️✨

## 🛠️ Lista de Materiais (Bill of Materials - BOM)

| Componente | Especificação / Modelo | Qtd. | Descrição / Função |
| :--- | :--- | :---: | :--- |
| 🧠 **Microcontrolador** | ESP32 DevKit v1 | 1 | Processamento principal do sistema |
| 📺 **Display** | OLED 0.96" I2C (128x64) | 1 | Interface visual via comunicação SDA/SCL |
| 🎮 **Navegação** | Módulo Joystick Analógico | 1 | Controle de menu e navegação adicional |
| 🔘 **Teclado** | Tactile Switches 12x12mm com Capa | 16 cada | Botões com capas padronizadas |
| 🚨 **Sinalização Visual** | LEDs 5mm (Verde = ON / Azul = Mute) | 2 | Indicadores luminosos do estado do sistema |
| ⚡ **Resistores** | 220 Ω (2x) / 1k Ω (1x) (1/4W) | 3 | Limitadores para os LEDs e base do transistor |
| 🔌 **Transistor** | 2N2222 (NPN) | 1 | Driver para acionamento do buzzer em 5V |
| 🔔 **Áudio** | Buzzer Passivo 5V | 1 | Feedback sonoro para teclas e notificações |
| 🔋 **Bateria** | Li-Ion 18650 (3.7V / 1200mAh) | 1 | Fonte de alimentação recarregável |
| 🔌 **Carregador** | Módulo TP4056 com Proteção (Type-C) | 1 | Módulo de carga via conexão Type-C |
| ⚡ **Step-Up** | Módulo Elevador MT3608 | 1 | Regula a saída da bateria para 5V constantes |
| 🔘 **Chave Geral** | Chave Liga/Desliga Redonda (2 Pinos) | 1 | Interruptor principal de acionamento |
| 🗂️ **Placa Base** | Perfboard Ilhada / PCB (7x9 cm) | 1 | Placa de circuito impresso para montagem |
| 📦 **Gabinete** | Patola PB-108/2 (116x74x25mm) | 1 | Case plástico de proteção |
| 🔌 **Fiação & Diversos** | Fios flexíveis e jumpers variados | - | Conexões elétricas e organização interna |

*Projeto em desenvolvimento ( :*
