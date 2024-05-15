# Aplicação de autômatos finitos no jogo Super Mario World

## _Resumo do projeto_

Este projeto foi criado com o objetivo de aplicar os conceitos que estão sendo estudados na
disciplina de __*Linguagens Formais e Autômatos*__ de forma prática. Para isso, foi selecionado um típico
problema real que é a modelagem dos estados de um jogo por meio de um autômato finito. Com base
nesse problema escolhido, foi construída uma aplicação em Python no Google Colab para simular os
possíveis estados do personagem Mario em uma fase do tradicional jogo de plataforma __*Super Mario
World*__, assim como as transições que ocorrem entre esses estados de acordo com os comandos de um
jogador.

## _Descrição dos arquivos deste repositório_

* O arquivo [Artigo.pdf](https://github.com/LeonardoMaioli/finite_automaton_super_mario_world/blob/main/Artigo.pdf) traz o artigo final elaborado, que descreve todas as etapas realizadas durante o projeto. Esse artigo possui uma introdução sobre autômatos finitos e o contexto da realização deste projeto. Além disso, é feita uma descrição detalhada de como o problema de modelagem dos estados do personagem Mario foi abordado e quais simplificações foram utilizadas no projeto. O artigo também traz a descrição da aplicação criada no Google Colab para a criação do autômato com base nas definições de modelagem.

* O arquivo [finite_automaton_smw_implementation.ipynb](https://github.com/LeonardoMaioli/finite_automaton_super_mario_world/blob/main/finite_automaton_smw_implementation.ipynb) é a aplicação criada no Google Colab que utiliza a biblioteca automathon para a criação do autômato finito que simula as ações do personagem Mario. Nessa aplicação também é possível testar se uma sequência de comandos de um jogador seria suficiente para fazer o Mario passar de fase.

* O arquivo [flowchart.png](https://github.com/LeonardoMaioli/finite_automaton_super_mario_world/blob/main/flowchart.png) é um fluxograma criado no início do projeto para ser utilizado como esboço do autômato finito com a legenda para as possíveis transições (setas) entre os estados (Marios). Esse mesmo fluxograma com a identificação dos estados considerados está presente no arquivo [flowchart_states.png](https://github.com/LeonardoMaioli/finite_automaton_super_mario_world/blob/main/flowchat_states.png).

* Além da criação do autômato no Google Colab, foi feita a criação do mesmo autômato para simulação dos estados do personagem Mario no JFLAP. O arquivo [first_level.jff](https://github.com/LeonardoMaioli/finite_automaton_super_mario_world/blob/main/first_level.jff) apresenta o código gerado para essa criação. Além disso, a imagem do autômato no JFLAP está disponível no arquivo [first_level_automaton.jpg](https://github.com/LeonardoMaioli/finite_automaton_super_mario_world/blob/main/first_level_automaton.jpg).

* O arquivo [simulation_video_phase_1_1.mp4](https://github.com/LeonardoMaioli/finite_automaton_super_mario_world/blob/main/simulation_video_phase_1_1.mp4) traz um vídeo disponível para download com uma simulação realizada para acompanhar o autômato enquanto um jogador joga a primeira fase.
