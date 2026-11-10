# FRONTIER

Protótipo web mobile de um jogo de mundo aberto original. Looty Bay é apenas uma das cinco regiões planejadas.

## Regiões presentes no protótipo
- Looty Bay: cidade costeira, banco, delegacia, mercado, garagem, joalheria e hotel.
- World / Desert: exploração, ruínas, posto avançado e coleta de recursos.
- Lair / Base: depósito, oficina, garagem e mesa de construção.
- Prison: blocos, pátio, refeitório e portão.
- Settlement: centro comercial, lote, mercado e prefeitura.

## Sistemas demonstrativos
Movimentação por joystick touch e teclado, câmera em primeira/terceira pessoa, troca de região, pontos de interação, saldo fictício, inventário local em memória, atividades de recompensa, vida, energia e progressão demonstrativa.

## Abrir
O protótipo usa Three.js via CDN. Abra `index.html` em um navegador moderno com internet. Hospedagem estática HTTPS é recomendada para iPhone.

## Limites importantes
Este é um protótipo inicial, não um jogo completo pronto para produção. Não há multiplayer, servidor autoritativo, persistência de conta, salvamento, economia online, IA policial, combate, interiores completos, física/veículos dirigíveis, missões sistêmicas ou builds nativas iOS/Android. O estado atual é temporário e reinicia ao recarregar.

## Próximas etapas técnicas
1. Separar cenas, entidades, UI e dados por módulos.
2. Adicionar persistência local e sistema de salvamento.
3. Implementar interação, combate, inventário e veículos reais.
4. Criar backend autoritativo e autenticação antes de economia/multiplayer.
5. Otimizar assets, streaming de mapas e controles para iOS/Android.
6. Preparar pipeline de build nativa e testes em aparelhos.

## Stack de prototipagem
HTML, CSS, JavaScript ES modules e Three.js. A arquitetura de produção proposta permanece Unity 6 + C# / URP, com backend e multiplayer dedicados após validação do protótipo.
