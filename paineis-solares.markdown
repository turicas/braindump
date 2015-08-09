# Painéis solares

Esse arquivo fala sobre painéis solares para geração de energia elétrica
(painéis fotovoltaicos). Caso esteja interessados em painéis solares que
aquecem água, veja
[aquecedor-solar-de-baixo-custo.markdown](aquecedor-solar-de-baixo-custo.markdown).

## Introdução

O Sol é responsável por toda forma de vida na Terra. É energia gratuita que
está disponível para todos, em toda a superfície do planeta -- vamos usá-la!
\o/

Os painéis solares convertem energia luminosa do Sol em energia elétrica. Em
muitos casos, essa energia é armazenada em baterias para uso posterior
(inclusive à noite, quando não temos Sol).

O esquema mais simples de ligação é:

    Painel solar -> Controlador de carga -> Bateria -> Carga DC

Onde "carga" é o equipamento elétrico/eletrônico que você deseja utilizar. No
esquema acima, vale destacar:

- O controlador de carga é necessário para que o painel carregue de maneira
  correta a bateria (caso o painel seja ligado diretamente, a bateria pode ser
  danificada);
- A "carga" está ligada diretamente à bateria, isso quer dizer que é uma carga
  de corrente contínua (CC, ou em Inglês, DC) e não de corrente alternada (CA
  ou AC). Cargas de corrente contínua são largamente utilizadas, porém como o
  que temos em casa nas tomadas é corrente alternada, todos os equipamentos que
  trabalham internamente com corrente contínua (exemplo: computadores,
  celulares, roteadores Wi-Fi, lâmpadas fluorescentes e virtualmente todos os
  eletrônicos) possuem um transformador AC/DC (usualmente chamado de "fonte").

Caso queira ligar corrente alternada, precisaremos de um inversor, que
transforma energia de corrente contínua para corrente alternada -- seria o
contrário do conversor AC/DC, ou seja, é um conversor DC/AC:

    Painel solar -> Controlador de carga -> Bateria -> Inversor -> Carga AC

> Nota: caso seja possível, *evite o uso do inversor*, já que qualquer processo
> de transformação de energia adiciona perdas. Dessa forma, por exemplo, será
> mais eficiente ligar uma fita de LEDs diretamente à bateria do que ligá-la em
> uma "fonte AC/DC" e ligá-la no inversor (no segundo caso, duas conversões
> serão feitas: de DC para AC no inversor e de AC para DC na fonte).

Existem vários outros usos também, como:

- Kits de iluminação de jardim: painel, controlador de carga, bateria e lâmpada
  são integrados (e nem sempre é possível usar a energia em outros
  equipamentos),
- Kits de iluminação pública (em postes),
- Kits para bombeamento de água ("bombas solares"), dentre outros.


## Tipo de Bateria

Muitos projetos utilizam baterias automotivas, que podem servir em alguns
casos, mas não são ideais para projetos com painéis solares. As baterias
automotivas resistem a grandes descargas (é feita uma grande descarga ao ligar
o automóvel, por exemplo), porém não resistem a grandes descargas de forma
contínua. Para resolver esse problema, existem as **baterias estacionárias**,
que devem ser preferidas para projetos com painéis solares.


## O Que Não Usar

Em geral, não recomenda-se ligar em um sistema alimentado por bateria (como é o
caso dos painéis solares):

- Chuveiro elétrico
- Ferro de passar roupas
- Motores em geral

Acredito que por conta da grande quantidade de energia que exigem em pouco
tempo.


## Tipos de painel

- Monocristalino: menor,
- Policristalino: maior.

Parece que existe algum tipo de painel que resiste melhor a sombra/dias
nublados que outros. Procurar sobre.


## Onde Comprar

Alguns sites vendem kits, que já vem com painel solar, controlador de carga e
inversor, faltando apenas escolher a bateria, que deve ser dimensionada
conforme:

- Quantidade de energia que o(s) painel(éis) solar(es) conseguirá(ão) gerar
  para carregá-la;
- Autonomia de energia que você vai precisar para seu sistema (exemplo:
  conseguir resistir, mesmo com uso de energia, a uma semana de dias
  completamente nublados).

Existem também empresas que fazem todo o projeto, venda de equipamentos e
instalação (*on* e *off-grid*), mas essas em geral não dão os preços de cara --
é necessária solicitar um orçamento e/ou visita ao local. Pode ser útil para
quem não tem o espírito "do-it-yourself".

Lojas:

- [Minha Casa Solar](http://minhacasasolar.lojavirtualfc.com.br/): painéis,
  controladores de carga, baterias, inversores etc.
- [Brasil LED](https://www.brasiled.com.br/)
- [NeoSolar](http://www.neosolar.com.br/loja/)
- [Energia Pura](https://www.energiapura.com/)


## Projetos

- [Árvore solar para carregar
  celulares](http://www.slideshare.net/hronoya/instituto-nikola-tesla-projeto-arvore-solar-capaz-de-carregar-celulares)
