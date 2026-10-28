# Atualização v13 — salas públicas e privadas

Esta atualização preserva o jogo existente e adiciona criação de salas públicas e privadas, lista de salas públicas com vagas, entrada por código e metadados de jogadores no servidor Colyseus. O limite continua sendo oito jogadores por sala.

## Importante

O servidor multiplayer precisa ser publicado separadamente de `RetardadosRoyale_Web_v6/` em uma hospedagem Node.js compatível com WebSockets. Após publicar o servidor, configure sua URL HTTPS em `src/multiplayer-config.js` e publique novamente o frontend na Netlify.

O modo online atual sincroniza jogadores e movimento; armas, tiros, dano, inventário, veículos e condição de vitória continuam fora da sincronização nesta versão. As partidas iniciam assim que o jogador cria ou entra numa sala; esta atualização não adiciona uma sala de espera pré-partida.
