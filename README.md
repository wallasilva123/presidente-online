# Presidente Online — protótipo inicial

Interface inicial responsiva para o jogo de cartas Presidente Online.

## O que existe nesta versão
- Página inicial em português.
- Interface temática com mesa verde oval, assentos e cartas ilustrativas.
- Campo de nome, criação de código demonstrativo e entrada de código.
- Layout adaptável para celular e computador.

## Limitações importantes
Esta versão é somente um protótipo visual/front-end. Criar ou digitar um código não cria uma sala real, não sincroniza jogadores e não permite partidas online. As cartas exibidas são ilustrativas.

## Próximas etapas para multiplayer real
1. Definir e implementar as regras completas da variante de Presidente desejada.
2. Criar backend com autenticação opcional, salas e estado autoritativo da partida.
3. Implementar comunicação em tempo real por WebSocket ou serviço equivalente.
4. Sincronizar mãos privadas, turno, descarte e resultado com validação no servidor.
5. Testar partidas entre navegadores e celulares diferentes.

## Executar localmente
Abra `index.html` em um navegador. Para hospedagem, publique os arquivos estáticos em um serviço como GitHub Pages; isso hospedará a interface, mas não adicionará multiplayer por si só.
