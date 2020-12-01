# Projeto Trabalho de Graduação em Banco de Dados I

## TEMA: APLICAÇÃO MOBILE PARA RESERVA, PEDIDO E PAGAMENTO DE RESTAURANTES

### 1. INTRODUÇÃO
Nos dias atuais as filas dos restaurantes tem se tornado cada vez maiores, principalmente nos finais de semana e feriados, onde muitas pessoas acabam desistindo ou deixando de comemorar alguma data especial em razão do tempo em que passam aguardando um lugar junto a mesa. Partindo do princípio de que tempo é dinheiro, esse problema acaba causando prejuízos diários para inúmeros restaurantes.
Outra agravante do problema é a necessidade de manter um distanciamento social em razão da pandemia do novo Corona Vírus. Em lugares menos amplos foi necessário a retirada de algumas mesas para fazer jus ao distanciamento, porém os consumidores não deixaram de frequentar seus lugares favoritos, por essa razão as filas aumentaram, e consequentemente, o tempo de espera também, com menos mesas, há também menos pessoas que podem ficar no ambiente ao mesmo tempo, isso faz com que muitas pessoas se aglomerem na entrada do restaurante, aguardando alguém sair para liberar um lugar. O distanciamento social é respeitado no interior do local, mas do lado de fora acaba sendo muitas pessoas em um espaço pequeno, todas aguardando um longo período apenas para um jantar.
Além da aglomeração na fila de entrada, há que se falar no contato com os atendentes, garçons, filas para efetuar o pagamento, e assim por diante. Isso é um problema tanto atual, quanto ao longo prazo, daqui alguns anos, as pessoas ainda não irão querer voltar a ter tanto contato com desconhecidos assim como era em tempos “normais”.

Em uma pesquisa feita pela Federação das Câmaras de Dirigentes Lojistas do Estado de São Paulo (FCDLESP), foram levantados que cerca de 90% dos comerciantes dizem que as filas impactam negativamente no resultado real das vendas. O presidente da FCDLESP, Mauricio Stainoff, explicou que as filas podem atrapalhar os negócios: “Ver muitas pessoas nas lojas no primeiro momento pode parecer positivo, que o estabelecimento é de qualidade ou que tem promoções interessantes, porém, a experiência lá dentro pode não ser a mesma. Sem contar que muitas vezes pode parecer falta de organização”. 

#### 1.1. Objetivos do Trabalho 
O objetivo do trabalho é criar um aplicativo mobile onde será possível fazer reserva de restaurantes e, ao chegar ao local, pedidos podem ser feitos e pagamento realizado, tudo apenas pelo celular. 

#### 1.2. Conteúdo do Trabalho
O presente trabalho está estruturado em seis Capítulos, cujo conteúdo é sucintamente apresentado a seguir:

No Capítulo 2 é feita a fundamentação das tecnologias...
O Capítulo 3 apresenta o desenvolvimento da solução...
No Capítulo 4 são apresentados os resultados ...
O Capítulo 5 apresenta as considerações finais deste trabalho a partir da análise dos resultados obtidos...

### 2.	FUNDAMENTAÇÃO TÉCNICA
Este capítulo apresenta temas necessários para compreensão deste trabalho em seu desenvolvimento: 

#### 2.1. Levantamento de Requisitos
A aplicação deverá permitir dois tipos de cadastros, o primeiro se refere a pessoas que estão à procura de restaurantes sem filas; o segundo a donos desses locais.
No caso de um cliente, precisamos criar uma conta e informar dados como nome, sobrenome, cpf, e-mail, telefone, senha, e aceitar que o dispositivo colete sua localização, para poder visualizar os restaurantes com todos os dados que acompanha. 

#### 2.2.	Tecnologias utilizadas
Para o desenvolvimento desta aplicação foram escolhidas x tecnologias e seus recursos como:

#### 2.2.1.	Postgree
Devido a escalabilidade, flexibilidade, confiabilidade sólida e constante disponibilidade que o servidor de banco de dados MySQL fornece foi feita a utilização deste SGBD (Sistema de Gerenciamento de Banco de Dados) além de sua alta velocidade de carga, caches de memória distintos, índices de texto completo, e outros mecanismos que satisfaz as expectativas de desempenho exigidas nos requisitos.

#### 2.2.2.	Javascript
É uma linguagem especifica que é bastante resposiva, o que envolve bastante outras tecnlogias que poderão entrar futuramente no projeto.

Também, o SGBD possui o código-fonte open source e gratuito, possuindo uma grande comunidade envolvida na busca de soluções e melhorias

#### 2.2.3. React Native
Para o front-end a tecnologia escolhida foi o React Native baseado na biblioteca React, na qual consiste em uma série de ferramentas para o desenvolvimento de aplicações móvel multiplataforma utilizando apenas Javascript. Sua principal vantagem consiste em que todo código desenvolvido com a tecnologia é convertido para linguagem nativa do sistema operacional possibilitando o desenvolvimento da aplicação tanto para Android como iOS utilizando apenas um código fonte.

#### 2.2.1.	Tecnlogias Devops
Tecnlogias relacionadas aos seguintes assuntos:
Gerencimento de projetos;
Versionador de código;
Tecnologias para update em nuvem.

#### 2.3.	Soluções Existentes

#### 2.3.1.	App Ifood
Hoje em dia, esse aplicativo é o maior do mundo no ramo de delivery, possuindo um sistema bastante intuitivo no qual podemos realizar pedidos e pagamentos tudo através do celular, o que é algo bastante inovador e tem muito haver com nossa ideia.

#### 2.3.2.	App TheFork
É um dos Apps com mais restaurantes cadastrados em todos cantos do mundo, tendo como foco a reserva de restaurantes. O aplicativos disponibiliza diversas promoções para usuários ativos, que são recompensados conforme utilizam.

#### 2.3.3.	App Restorando
O Restorando é bastante similar ao TheFork, mas conta com o feedback dos usuários para fazer recomendações melhores. Ele lista os estabelecimentos próximos e permite a busca por endereço ou cozinha, exibe os preços dos pratos, lista promoções e permite que o cliente faça uma reserva nos restaurantes de forma simples e prática.

### 3. DESENVOLVIMENTO

O desenvolvimento da aplicação em Reactive Native será a partir de componentes de código com APIs nativas no modelo de Single Page Applications (SPA). Permitindo a alteração de conteúdo sem a necessidade do carregamento de uma visualização por completo, mas sim apenas o conteúdo diferente havendo uma comunicação entre componentes direcionados para iOS ou Android. Através de dependências é realizado de forma nativa a interpretação do JavaScript React da aplicação, assim permitindo que o smartphone consiga interpretar e executar JavaScript da mesma forma que Java/Kotlin ou Objective-C/Swift, dependendo da plataforma.

#### 3.1. Arquitetura do Sistema

A arquitetura do projeto, envolve a ligação do dispositivo mobile conectando ao nodejs, através de algumas APIs, fazendo contato assim com o banco de dados:

<h1 align="center">
<img alt="Gobarber" src="./img/Imagem Arquitetura.png" />
</h1>


### REFERÊNCIAS

Tecnoblog. <b>5 aplicativos para fazer reserva em restaurantes no Brasil.</b> Disponível em https://tecnoblog.net/272057/aplicativos-reserva-em-restaurantes/ Acesso em: 25/10/2020.

Troco Simples. <b>O tempo de espera na fila pode acabar com o seu negócio</b> Disponível em https://trocosimples.com.br/o-tempo-de-espera-na-fila-pode-acabar-com-o-seu-negocio/ Acesso em: 30/10/2020.

Mercado & Consumo. <b>Varejistas acreditam que filas prejudicam vendas</b> Disponível em https://mercadoeconsumo.com.br/2018/08/13/varejistas-acreditam-que-filas-prejudicam-vendas/ Acesso em: 8/11/2020.
