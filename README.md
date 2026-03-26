<div align="center">

```
███████╗ ██████╗  ██████╗ ██╗   ██╗███████╗██╗ █████╗
██╔════╝██╔════╝ ██╔═══██╗██║   ██║██╔════╝██║██╔══██╗
█████╗  ██║  ███╗██║   ██║██║   ██║█████╗  ██║███████║
██╔══╝  ██║   ██║██║   ██║██║   ██║██╔══╝  ██║██╔══██║
██║     ╚██████╔╝╚██████╔╝╚██████╔╝███████╗██║██║  ██║
╚═╝      ╚═════╝  ╚═════╝  ╚═════╝ ╚══════╝╚═╝╚═╝  ╚═╝
```

### Francisco Gouveia · Computer Engineering @ UMa · 19

*Building things from bare silicon to machine intelligence.*

[![GitHub](https://img.shields.io/badge/GitHub-FGouveia7-0d1117?style=for-the-badge&logo=github&logoColor=white&labelColor=161b22)](https://github.com/FGouveia7)
[![Location](https://img.shields.io/badge/Madeira,_Portugal-🌊-0d1117?style=for-the-badge&labelColor=161b22)](https://github.com/FGouveia7)
[![Focus](https://img.shields.io/badge/Data_Science_&_ML-→-0d1117?style=for-the-badge&labelColor=161b22)](https://github.com/FGouveia7)

</div>

---

## `whoami`

Estudante de Engenharia Informática na **Universidade da Madeira**, a construir uma base sólida que vai do hardware ao software — de processadores descritos em VHDL a algoritmos de machine learning. Não me interessa apenas fazer as coisas funcionar. Interessa-me perceber *porquê* funcionam.

A minha direção é clara: **Data Science e Machine Learning**. Transformar dados brutos em sistemas inteligentes que tomam decisões — é aí que quero estar.

---

## ⚙️ Stack

```
Languages   →   Python · C++ · VHDL · Java · JavaScript · HTML/CSS
Tools       →   Vivado ML · NetBeans · CLion · Git · GitHub
Boards      →   Artix-7 FPGA (Nexys A7-100T)
Learning    →   NumPy · Pandas · Matplotlib · Scikit-learn
```

---

## 📁 Projetos

---

### 🔬 Implementação de Processador de 8 bits em VHDL
> `VHDL` · `Computer Architecture` · `FPGA` · `Vivado ML`

**O projeto mais tecnicamente exigente do repositório.**

Implementação completa de um processador de **arquitetura Harvard, single-cycle, 8 bits**, descrito inteiramente em VHDL e sintetizado num FPGA **Artix-7 (Nexys A7-100T)**. Não é uma simulação abstrata — é um processador real, que corre num chip real.

O que foi implementado de raiz:

- **ALU** — suporta ADD, SUB, AND, OR, XOR, NOT
- **ROM** — memória de instruções com o programa gravado
- **RAM** — memória de dados com leitura e escrita em runtime
- **Program Counter** — controla o fluxo sequencial e os saltos
- **Flags Register** — Zero, Carry, Negative, Overflow para branching condicional
- **Unidade de Controlo** — descodifica instruções e gera todos os sinais de controlo
- **Gestor de Periféricos** — interface com switches, botões e LEDs da placa
- **Instruction Set completo**: `LDP`, `ADD`, `SUB`, `AND`, `OR`, `XOR`, `NOT`, `JMP`, `JGE`, `JZ`, `STORE`, `LOAD`

Pipeline completo de simulação e síntese validado no Vivado.

🔗 [Ver repositório](https://github.com/FGouveia7/Implementacao-Processador-de-8-bits-em-VHDL)

---

### 🏧 Máquina de Multibanco
> `VHDL` · `Digital Systems` · `FSM Design`

Simulação completa de uma **Máquina de Multibanco (ATM)** desenvolvida para a cadeira de Sistemas Digitais. O foco não foi apenas fazer funcionar a interface — foi desenhar a **Máquina de Estados Finitos (FSM)** que governa todo o comportamento do sistema.

Estados implementados: idle → validação de PIN → consulta de saldo → levantamento → depósito. Cada transição é explícita, determinística, e descrita ao nível do hardware digital.

🔗 [Ver repositório](https://github.com/FGouveia7/M-quina-De-Multibanco)

---

### 🍽️ Projeto EDA — Sistema de Gestão de Restaurante
> `C++` · `Data Structures & Algorithms` · `CMake`

Sistema de gestão de restaurante construído em **C++** para a cadeira de Estruturas de Dados e Algoritmos. A ideia era simples; a implementação, não.

Estruturas de dados utilizadas na prática:

- **Fila (Queue)** — clientes atendidos por ordem FIFO
- **Listas Ligadas** — gestão dinâmica de mesas, clientes e itens do menu
- **Persistência em ficheiro** — guardar e carregar o estado completo do restaurante

Arquitetura modular com headers `.h` e ficheiros `.cpp` separados. Compilado com CMake.

🔗 [Ver repositório](https://github.com/FGouveia7/ProjetoEDARestaurante)

---

### 🕵️ Jogo Sherlock Holmes
> `Java` · `NetBeans` · `Terminal Game` · `OOP`

Jogo de detetive interativo que corre **diretamente no terminal**, desenvolvido em **Java no NetBeans**. O jogador assume o papel de Sherlock Holmes e navega por uma narrativa de investigação através de escolhas feitas na linha de comandos.

Sem browser. Sem interface gráfica. Só lógica pura, texto, e decisões — como os jogos de texto clássicos. O projeto demonstra domínio de **Programação Orientada a Objetos** em Java: classes, herança, encapsulamento, e gestão de estado do jogo ao longo da sessão.

🔗 [Ver repositório](https://github.com/FGouveia7/JogoSherlockHolmes)

---

### 🎯 Jogo do Número Misterioso
> `Python` · `Game Logic` · `Terminal`

Jogo de terminal em Python onde o jogador tem **3 tentativas** para adivinhar um número gerado aleatoriamente. Simples na superfície — mas foi um dos primeiros projetos onde a lógica de jogo, o feedback ao utilizador, e o fluxo de controlo foram pensados de forma estruturada.

🔗 [Ver repositório](https://github.com/FGouveia7/Jogo-do-Numero-misterioso)

---

### 🌐 Teórico Prática DBW
> `JavaScript` · `Web Development` · `DBW`

Exercícios teórico-práticos para a cadeira de **Database and Web**. Cobre fundamentos de JavaScript, interação cliente-servidor, renderização dinâmica de conteúdo e programação orientada a eventos.

🔗 [Ver repositório](https://github.com/FGouveia7/TeoricoPraticaDBW)

---

## 🎯 Agora mesmo

```python
focus = [
    "Machine Learning — fundamentos matemáticos e algoritmos",
    "Python para Data Science — NumPy, Pandas, Scikit-learn",
    "Primeiro projeto pessoal de ML",
    "Defesa oral do processador de 8 bits em VHDL",
]
```

---

## 📊 Stats

<div align="center">

<a href="https://github.com/FGouveia7">
  <img height="180em" src="https://github-readme-stats-sigma-five.vercel.app/api?username=FGouveia7&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true" />
  <img height="180em" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=FGouveia7&layout=compact&theme=github_dark&hide_border=true&langs_count=8" />
</a>

<br/>

<a href="https://git.io/streak-stats">
  <img src="https://streak-stats.demolab.com?user=FGouveia7&theme=github-dark-blue&hide_border=true" />
</a>

</div>

---

<div align="center">

*Do hardware ao modelo — cada camada importa.*

[![GitHub](https://img.shields.io/badge/→_FGouveia7-0d1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/FGouveia7)

</div>
