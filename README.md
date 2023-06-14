<!-- Título -->
# Composição e Agregação

***Conteúdo da Aula:***

Com relação ao relacionamento entre os vários objetos de nossa aplicação, nós podemos ter relações de composição e relações de agregação.

A composição, como o próprio nome diz, ocorre quando uma classe é composta por objetos de outra classe.

Isso quer dizer que uma das classes envolvidas depende de maneira direta da existência da outra classe para que ela também possa existir.

Neste caso, nós geralmente temos duas definições para as classes envolvidas na composição:

* A classe forte, que domina o relacionamento e que é importante para que a outra classe possa existir;
* E a classe fraca ou anêmica, que é a classe que depende da existência da outra classe para existir.

Um exemplo clássico de composição é a relação entre uma classe que representa uma nota fiscal e a classe que representa os itens da nota fiscal.

A nota fiscal, para existir, depende explicitamente da existência dos itens da nota fiscal.

Sendo assim, temos aqui uma relação de composição:

* A nota fiscal é composta por itens da nota fiscal.

![Exemplo](https://d2v0x26thbzlwf.cloudfront.net/prod/13/img/rId174wgh0vtq.jub.png "Composição entre notas fiscais e itens de notas fiscais")

Acima, nós temos a composição entre notas fiscais e itens de notas fiscais de acordo com a UML.

A relação de agregação é um pouco diferente.

Ela ocorre quando dois ou mais objetos se relacionam na intenção de um objeto **“complementar”** informações no outro objeto.

Os dois objetos não necessariamente dependem um do outro para existir; mas, quando unidos, apresentam um sentido mais completo e descritivo sobre uma determinada situação.

Um exemplo clássico é a relação entre uma classe `Pessoa` e uma outra classe `Endereco`.

Ambos os objetos podem existir de maneira independente um do outro (pois não são somente pessoas que possuem endereço).

Mas, quando unimos objetos da classe `Pessoa` com objetos da classe `Endereco`, nós acabamos tendo uma pessoa mais **“completa”**:

* Uma pessoa com um endereço.

O mesmo vale para o endereço:

* Quando ele é unido com uma pessoa, ele acaba também **“fazendo mais sentido”**.

Quando dois ou mais objetos têm uma relação nesse sentido, nós temos uma agregação.

![UML](https://d2v0x26thbzlwf.cloudfront.net/prod/13/img/rId18d5g7v1u9.rnh.png "Representação UML de uma relação de agregação")

Acima, nós temos a representação UML de uma relação de agregação.

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-com-agr-com-agr-car-log-ori-obj-com-bas&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-com-agr-com-agr-car-log-ori-obj-com-bas?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-com-agr-com-agr-car-log-ori-obj-com-bas?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-com-agr-com-agr-car-log-ori-obj-com-bas?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-com-agr-com-agr-car-log-ori-obj-com-bas?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-com-agr-com-agr-car-log-ori-obj-com-bas?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
