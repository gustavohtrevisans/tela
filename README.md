# Telinha

Compartilhe a tela com os amigos por um link. O vídeo vai direto entre vocês (WebRTC), sem gravar nada.

1. Abra o site no computador (Chrome ou Edge) e clique em **Compartilhar minha tela**.
2. Mande o link que aparece no grupo. Seus amigos assistem pelo navegador, inclusive no celular.
3. Quem abrir o link pede para entrar: você aceita ou recusa (quem você aceitar entra direto das próximas vezes).
   Dá para desligar isso em "Só entra quem eu aceitar".
4. **Ligar câmera** mostra sua câmera numa bolha no canto (ou sozinha, sem compartilhar a tela).

A conversa pode continuar na call de voz do Discord. Se algum amigo ficar em "Não consegui conectar",
a rede dele bloqueia conexão direta: dá pra resolver colocando um servidor TURN em `TURN_EXTRA` no `index.html`.
