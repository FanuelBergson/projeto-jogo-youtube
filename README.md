# Jogo de Plataforma 2D - CEFET-MG

Repositório oficial do projeto integrador desenvolvido para o curso de extensão de Git e GitHub do CEFET-MG, utilizando a **Godot Engine**.

## Sobre o Jogo
Trata-se de um jogo de plataforma 2D desenvolvido com foco em mecânicas fluidas de movimentação (pulo, física de gravidade), transição de fases (cenários de floresta e tropicais) e camadas de fundo em parallax.

## Tecnologias Utilizadas
* **Godot Engine 4.x** (Motor de jogo)
* **GDScript** (Linguagem de script)
* **Git & GitHub** (Controle de versão e colaboração)

## Estrutura do Projeto
* `scenes/`: Cenas principais do jogo (fases). Menu ainda será implementado.
* `entities/`: Cenas e scripts do jogador (inimigos serão adicionados posteriormente).
* `sprites/` e `Tiles/`: Recursos gráficos, tilesets e fundos.
* `scripts/`: Controladores globais e lógicas de movimentação.

## Como Executar
1. Baixe e instale a Godot Engine 4.x (https://godotengine.org/).
2. Clone este repositório em sua máquina com o comando:
   git clone https://github.com/FanuelBergson/projeto-jogo-youtube.git
3. Abra a Godot Engine, clique no botão Import e selecione o arquivo project.godot na pasta raiz do projeto clonado.
4. Clique em Import & Edit, e com o projeto aberto, pressione F5 no teclado para rodar o jogo.
