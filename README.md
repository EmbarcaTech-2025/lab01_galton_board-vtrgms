
# Projetos de Sistemas Embarcados - EmbarcaTech 2025

Autor: Vitor Gomes

Curso: Residência Tecnológica em Sistemas Embarcados

Instituição: EmbarcaTech - HBr

Campinas, 09 de maio de 2025

---

## Objetivo

Este projeto tem como objetivo principal validar os conhecimentos adquiridos durante a primeira unidade da segunda fase do curso **Embarcatech**. Para isto foi desenvolvido um programa capaz de representar a um tabuleiro de Galton usando a placa de desenvolvimento [BitDogLab](https://github.com/BitDogLab).


## Funcionamento

O projeto consiste em uma simulação digital de uma máquina de Galton desenvolvida para a Raspberry Pi Pico, utilizando um display OLED. O sistema permite visualizar em tempo real o movimento de "bolas" que caem do topo da tela e colidem com obstáculos dispostos em linhas alternadas. A cada colisão, as bolas mudam de direção de forma probabilística (com chance ajustável entre 30%, 50% ou 70% para direita), replicando o comportamento clássico da máquina física. Dois botões  controlam a interação: um adiciona bolas individualmente, outro altera a probabilidade de direção, enquanto pressionar ambos alterna a exibição de um histograma na tela. Esse histograma mostra a distribuição acumulada das bolas em seis compartimentos, com barras verticais fixas que representam quantidades.


## Componentes usados

- Raspberry Pi Pico W
- Display OLED SSD1306 → Pinos 14 (GP10 - I2C1 SDA) e 15 (GP11 - I2C1 SCL)
- Botões: A → Pino 7 (GP5) e B → Pino 9 (GP6)



## Como reutilizar

É necessário instalar a [extensão oficial da Raspberry Pi Pico](https://github.com/raspberrypi/pico-vscode) no seu VSCode e criar um novo projeto C/C++.
Clone os arquivos presentes neste diretório e execute com sua placa conectada no modo BOOTSEL para compilar e importar o projeto.

>*Atente-se para a versão do SDK, este programa foi feito usando a 2.1.1*   


## Resultados

Comparando a espectiva com o resultado final concluo que o projeto serviu o seu propósito, entrega um resultado conforme descrito na atividade. Acredito que evolui durante o processo de criação, interagindo com aspectos que ainda não tinha sido exposto, no geral, muito satisfeito com o resultado.

---

## 📜 Licença
MIT License - MIT GPL-3.0.

