Doodle Jump - Java Swing 🎮

Um jogo de plataforma vertical inspirado no clássico Doodle Jump 2, desenvolvido em Java utilizando Swing e conceitos de Programação Orientada a Objetos (POO).

A ideia do projeto foi recriar a experiência do jogo original, com gráficos desenhados à mão, diferentes tipos de plataformas, inimigos e um sistema de pontuação.

🎮 Funcionalidades
Visual desenhado à mão: gráficos feitos com Graphics2D, usando um estilo de papel quadriculado e desenhos rabiscados.
Menu principal: tela inicial com botões e transição entre os estados do jogo (Menu, Jogando e Game Over).
Sistema de pontuação: a pontuação aumenta conforme o personagem consegue subir.
Diferentes tipos de plataformas:
Verdes: plataformas normais que impulsionam o personagem.
Marrons: plataformas que racham e quebram quando o jogador pisa nelas.
Com mola: permitem dar saltos mais altos.
Inimigos: monstros que se movimentam pela tela. É possível derrotá-los pulando em cima deles, mas colidir lateralmente pode acabar com a partida.
Câmera dinâmica: a tela acompanha o personagem conforme ele sobe, dando a sensação de um cenário infinito.
🛠️ Tecnologias utilizadas
Java (JDK 8 ou superior)
Java Swing e AWT
Graphics2D para os desenhos
Timer para atualização do jogo
KeyListener e ActionListener para os controles e eventos
📁 Estrutura do projeto

O projeto foi dividido em classes para deixar o código mais organizado:

Arquivo	Responsabilidade
Main.java	Inicia o jogo.
GameFrame.java	Cria a janela principal.
GamePanel.java	Controla a lógica, a física e a renderização.
Player.java	Gerencia o personagem, seus movimentos e pulos.
Platform.java	Controla as plataformas e seus diferentes tipos.
Monster.java	Controla os inimigos, seus movimentos e colisões.
▶️ Como executar
Pré-requisitos

Antes de começar, é necessário ter o JDK 8 ou superior instalado.

Pelo terminal
Abra o terminal na pasta do projeto.
Compile os
