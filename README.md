# Prototipo-Carregador

Fonte Regulada 12V - Projeto Proteus
Descrição

Este projeto consiste no desenvolvimento de uma fonte de alimentação regulada de 12 V utilizando o software Proteus. O objetivo do circuito é converter uma tensão alternada (AC) proveniente de um transformador em uma tensão contínua (DC) estável de 12 V, que pode ser utilizada para alimentar diferentes circuitos eletrônicos.

Funcionamento do Circuito

A tensão alternada entra no circuito através do conector J1 e é enviada para a ponte retificadora (BR1), responsável por converter a tensão AC em tensão contínua pulsante. Em seguida, os capacitores C1 e C2 realizam a filtragem da tensão, reduzindo as oscilações presentes após a retificação.

Depois do processo de filtragem, a tensão é aplicada ao regulador de tensão U1 (7812), que mantém a saída estabilizada em aproximadamente 12 V DC. O capacitor C3 auxilia na estabilidade da saída, reduzindo possíveis ruídos.

O circuito também possui um LED indicador (D1) com resistor R1, que sinaliza quando a fonte está energizada. Por fim, a tensão regulada é disponibilizada no conector J2, que funciona como saída da fonte.

Componentes Utilizados

J1 – Conector de entrada do transformador

BR1 – Ponte retificadora

C1 e C2 – Capacitores de filtragem

U1 – Regulador de tensão 7812

C3 – Capacitor de estabilização da saída

R1 – Resistor limitador de corrente

D1 – LED indicador

J2 – Conector de saída 12 V

Software Utilizado

Proteus 8 (ISIS e ARES)

Arquivos do Projeto

O repositório contém:

Esquemático do circuito

Layout da PCB

Visualização 3D da placa

Arquivos do projeto Proteus
