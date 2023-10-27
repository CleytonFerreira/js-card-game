# JS Card Game
![JS Card Game](/src/assets/share.png)

## Sobre o projeto
Projeto de game baseado em jogos de cartas colecionáveis feito para o bootcamp [Potência Tech iFood - Desenvolvimento de Jogos](https://web.dio.me/track/potencia-tech-ifood-desenvolvimento-de-jogos?ref=CG&utm_source=ativos-90D&utm_medium=plataforma&utm_campaign=ifood-potencia-tech-2023&utm_term=banner-modal&utm_content=trilha-jogos-inscricoes-abertas), parceria da plataforma [iFood](https://www.ifood.com.br/) com a comunidade de aprendizado [DIO](https://web.dio.me).

## Aprendizados
- Gerenciamento de estados por meio de um objeto que guarda o estado inicial do game;
- Manipulação dos estados através de funções assíncronas;
- Adição e remoção de elementos na DOM de forma dinâmica com JavaScript;
- Uso da técnica **extract to method**, visando a manutenibilidade do código.

**Diferenças em relação ao projeto original disponibilizado na plataforma:**

- A maioria dos navegadores Web modernos tem restrições à reprodução automática de mídia, como áudio e vídeo. Estas restrições existem para melhorar a experiência do utilizador e evitar a reprodução automática indesejada ou intrusiva de conteúdos de midia. Para solucionar o problema foi adicionada uma lógica para para reproduzir/pausar a música de fundo, pois o usuário precisa interagir com o DOM primeiro para que o som possa ser reproduzido;
- Adicionados ícones do [Font Awesome](https://fontawesome.com/search?o=r&m=free) para o controle da música de fundo.
- Adicionado efeito sonoro para um caso de empate no duelo.

## Como jogar
O game tem a mecânica da brincadeira popular "pedra, papel e tesoura" onde temos três cartas diferentes, uma com cada atributo. O jogador e o computador recebem cinco cartas aleatórias. Clique na carta para colocá-la em duelo com a carta do oponente. Dependendo do atributo pode haver uma vitória, derrota ou empate. Lembre-se que:

- Pedra: A pedra vence a tesoura (a pedra quebra a tesoura);
- Tesoura: A tesoura vence o papel (a tesoura corta o papel);
- Papel: O papel vence a pedra (o papel cobre a pedra).

[Clique aqui](https://cleytonferreira.github.io/js-card-game/) para jogar.

## Considerações sobre o projeto
O projeto pode ser estendido de várias maneiras, tais como:
- Adicionar uma mecânica de card game complexa, definindo as várias fases de um turno durante a partida;
- Criar várias cartas com atributos e efeitos diferentes. As imagens podem ser geradas com modelos de inteligência artificial e editadas em programas de manipulação de imagens;
- Quando o game tiver várias cartas, o ideal é que ele tenha um banco de dados com as cartas registradas.
