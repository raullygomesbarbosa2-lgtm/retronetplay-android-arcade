# RetroNetPlay Arcade — Android

Projeto derivado do ZIP/HTML fornecido pelo proprietário. O modo Arcade solo abre ROMs locais e BIOS escolhidas pelo usuário; não inclui jogos comerciais nem arquivos BIOS.

- APK planejado para Android 6.0+ (API 23), via Capacitor/Android WebView.
- Controles virtuais grandes, alavanca direcional, botões A/B/X/Y, detecção de gamepads pelo Android/Gamepad API e tela cheia com tentativa de rotação horizontal.
- KOF: o nome do arquivo sugere FBNeo ou MAME 2003-Plus; para iniciar é necessário romset que corresponda ao núcleo e, frequentemente, BIOS Neo Geo compatível.
- A tela e os recursos multiplayer originais foram mantidos no código. O multiplayer e a biblioteca remota exigem o servidor Express/WebSocket do projeto; ainda não estão publicados/configurados por este build.
- A compilação do APK não comprova instalação, gameplay ou suporte a cada controle em aparelhos reais. Android 6 pode precisar de WebView atualizado para WebAssembly.

Não há ROMs comerciais, BIOS ou dumps incluídos.
