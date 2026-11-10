# FRONTIER

Protótipo web mobile de um jogo de mundo aberto original, usando jogos de extração em mundo aberto como referência de sistemas. Não utiliza código, mapas ou assets proprietários de ROB RUN.

## Regiões jogáveis no protótipo
- **Looty Bay:** cidade costeira procedural, quadras, vias, fachadas, vitrines, iluminação, vegetação e serviços urbanos.
- **World / Desert:** terreno aberto, ruínas, posto avançado, recursos, centro de vendas e ponto de interesse territorial.
- **Lair / Base:** área privada com depósito, oficina, garagem, construção e lavagem de dinheiro demonstrativa.
- **Prison:** complexo cercado com pátio, blocos, refeitório e tentativa de fuga demonstrativa.
- **Settlement:** lotes, comércio local e prefeitura.

## Sistemas que já podem ser testados
- Controles por joystick touch e teclado.
- Câmera em primeira e terceira pessoa.
- Personagem articulado com animação básica de caminhada.
- Veículos dirigíveis com aceleração, direção e entrada/saída.
- Papéis de civil, criminoso e policial.
- Máscara, assaltos cronometrados, saque, nível de procurado, perseguição policial simplificada e fuga pela borda da cidade.
- Banco, ATM, motel, lojas, joalheria, receptador e serviços.
- Mochila, itens, dinheiro em mãos, saldo bancário, venda e armazenamento de saque.
- Compra de lote, melhorias e atividades nas regiões.
- Salvamento local no aparelho com localStorage.

## Abrir
O protótipo usa Three.js via CDN. Abra `index.html` em um navegador moderno com internet. Hospedagem estática HTTPS é recomendada para iPhone.

## Limites importantes
Esta versão é um **vertical slice de prototipagem**, não um jogo completo nem um clone idêntico. A cidade e os personagens são montados proceduralmente com geometria simples; ainda não há modelos 3D de alta fidelidade, texturas de produção, interiores completos, animações profissionais, física realista, combate com armas, multiplayer, contas online, servidores autoritativos, economia compartilhada ou builds nativas iOS/Android. A polícia e os veículos usam lógica simplificada de demonstração. Os dados são salvos apenas no navegador/aparelho.

## Próximas etapas técnicas
1. Substituir geometria procedural por assets 3D originais de produção e melhorar a direção de arte.
2. Implementar colisões, interiores funcionais, combate, animações e física de veículos.
3. Expandir cada mapa para áreas contínuas com streaming e pontos de extração.
4. Criar backend autoritativo, autenticação, inventário e economia online.
5. Adicionar multiplayer cooperativo e sistemas de clãs/território.
6. Preparar pipeline de build nativa e testes em aparelhos iOS/Android.

## Stack atual
HTML, CSS, JavaScript ES modules e Three.js. Unity 6 + C# / URP continua como opção de arquitetura de produção, caso o protótipo valide o loop principal.
