# Namaguederaz — projeto definitivo

Aplicativo watch-party Android/web com servidor Node/Express/WebSocket.

## Render
Build: `npm install`
Start: `node server.js`
Environment: `YOUTUBE_API_KEY` (necessária para a busca do YouTube).

## APK
O workflow instala Capacitor 7, cria o Android e aplica um MainActivity nativo que respeita o histórico WebView no botão físico Voltar: volta por etapas e só encerra no estado raiz.

## YouTube
A pesquisa usa a API oficial do YouTube e a reprodução usa o player oficial incorporado. O projeto não contorna DRM, restrições de incorporação ou políticas de terceiros.
