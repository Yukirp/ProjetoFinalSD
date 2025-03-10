1. Proposta Geral
O projeto consiste no desenvolvimento de um jogo multiplayer distribuído inspirado na mecânica clássica do *Pong, com uma variação na disposição das plataformas, permitindo que elas fiquem tanto na vertical (esquerda e direita) quanto na horizontal (superior e inferior). Dois jogadores controlam as plataformas e devem rebater a bola para evitar que ela ultrapasse suas respectivas áreas. O objetivo é criar uma aplicação de jogo em rede, explorando conceitos de comunicação entre processos, sincronização e concorrência.

2. Tecnologias adotadas
Linguagens: JavaScript (frontend e backend)
Frameworks e Bibliotecas:
Phaser (renderização do jogo)
React (interface do usuário)
Socket.io (comunicação em tempo real entre cliente e servidor)
Node.js (backend da aplicação)
Express (servidor web e API REST)
Protocolo de comunicação: WebSockets (via Socket.io)
Modelo de Arquitetura: Cliente-Servidor, onde um servidor gerencia a lógica central do jogo e os clientes enviam comandos de entrada.
Plataforma de desenvolvimento: Linux
3. Justificativa
O projeto está diretamente relacionado à disciplina de Sistemas Distribuídos, pois aborda os seguintes conceitos fundamentais:
Comunicação entre processos: uso de WebSockets para troca de mensagens entre cliente e servidor.
Concorrência e sincronização: tratamento de eventos simultâneos dos jogadores sem conflitos.
Distribuição de estados: garantir que os dois jogadores tenham uma visão consistente do jogo em tempo real.
Tolerância a falhas: permitir a reconexão de clientes caso a conexão seja perdida.
4. Equipe e Responsabilidades
Gabriel Castro: desenvolvimento da lógica do jogo, gestão do servidor e implementação da comunicação em rede com Socket.io.
Ian Victor: desenvolvimento da interface gráfica utilizando Phaser e React, tratamento de eventos e interação do jogador com o jogo.
David Gabriel: testes, otimização do desempenho, documentação do projeto e suporte à implementação da comunicação entre cliente e servidor.
5. Repositório do Trabalho Final
https://github.com/Yukirp/ProjetoFinalSD.git
