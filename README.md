DRAGSTER - PROJETO ROBÓTICA (FNR 2027").

Este repositório contém a "blueprint completa" (código, esquemáticos e outros) para o desenvolvimento de um robô autónomo da categoria "Dragster".
O protótipo está a ser desenhado para competir no Festival Nacional de Robótica de 2027, em representação do Colégio Efanor.

Estrutura do repositório: O projeto está organizado nas seguintes diretoriais para facilitar o trabalho em equipa:
1. `/code`: Código-fonte, firmware e sketches desenvolvidos no Arduino IDE.
2. `/pcb`: Ficheiros de layout da placa de circuito impresso (PCB) no KiCad.
3. `/hardware`: Desenhos técnicos, esquemáticos e listas de componentes.
4. `/chassi`: Modelos 3D, ficheiros de corte/impressão e esboços da estrutura física.
5. `/pista`: Dados sobre as especificações da pista, sensores de partida/chegada e tempos.
6. `/robo`: Fotografias do progresso de montagem, protótipos em bancada e testes.
7. `/documentacao`: PDFs complementares, datasheets de componentes e relatórios.

Software Utilizado: Design Eletrónico: `KiCad` (versão 8.0 ou superior). Programação: `Arduino IDE` 2.x (Linguagem C/C++). Controlo de Versão: `Git & GitHub`.

Avisos Importantes: Para evitar conflitos de ficheiros (especialmente no KiCad), sigam sempre esta rotina.
1.  Selecionar o projeto: `cd "pasta do projeto"` (Ex: `cd Documents/Dragster`).
2.  Sincronizar Primeiro: Antes de abrir o KiCad ou o Arduino IDE, façam sempre: `bash git pull origin main`.
3.  Avisar a Equipa: Nunca editem o layout da PCB (`.kicad_pcb`) ao mesmo tempo. Combinem quem mexe na placa em cada dia.
4.  Guardar as alterações: `git add .`.
5.  Documentar os Commits: Ao enviar alterações, usem mensagens claras `git commit -m "mensagem"`.
6.  Enviar as alterações para web: `git push origin main`.

