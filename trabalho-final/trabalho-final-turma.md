# Trabalho Final - Turma

Esse arquivo compila **todas as colaborações** realizadas pela turma durante a realização do trabalho final.
O propósito deste arquivo é permitir uma visão global de tudo o que foi desenvolvido, de maneira simples e rápida.

As colaborações estão divididas por tipos, conforme estabelecido na [especificação do trabalho final](../trabalho-final.md), e devem seguir o seguinte padrão:

`- frase descrevendo o que foi feito ([link para a colaboração]() - [@usuario]())`

Por exemplo:

- Permite que o OpenDSSDirect busque o caminho para o GCC independente da distribuição ([OpenDSSDirect#24](https://github.com/Muxelmann/OpenDSSDirect.make/pull/24) - [@filipesaraiva](https://github.com/filipesaraiva))

Segue abaixo todas as colaborações realizadas pela turma durante a disciplina.

## Reportar bug

- Mesmo quando usado um token pessoal, a CLI pede usuário e senha ([mathdroid/crop-github-images-cli#5](https://github.com/mathdroid/crop-github-images-cli/issues/5) - [@lubien](https://github.com/lubien)).
- O desenvolvedor não seleciona os arquivos específicos a serem publicados com o pacote gerando uma build com peso desnecessário ([pandrRe/Fastable#2](https://github.com/pandrRe/Fastable/issues/2) - [@lubien](https://github.com/lubien)).

## Melhorar documentação

- Melhoramento de documentação do repositório,que ao investigar a documentação não ficava claro como instalar e rodar o ambiente local de desenvolvimento, após conversar com os mantenedores e abrir um issue, eles alteraram a wiki com instruções que eu criei ([issue #219](https://github.com/ryceg/Eigengrau-s-Essential-Establishment-Generator/issues/219#issuecomment-506033821), [Wiki deles após sugestão](https://github.com/ryceg/Eigengrau-s-Essential-Establishment-Generator/wiki/Compiling-the-Generator) - [@urielfcampos](https://github.com/urielfcampos))

* Adição de Guia de designer ao arquivo de contribuição do repositorio Feather ([feathericons/feather#646](https://github.com/feathericons/feather/pull/646) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).


* Correção de exemplos que retornavam erros, presentes no README ([edsu/pymarc#137](https://github.com/edsu/pymarc/pull/137) - [@souzaluuk](https://github.com/souzaluuk))

* Instructions for setting the config params to enable switching the default language at the nav bar ([beautifulhugo#285](https://github.com/halogenica/beautifulhugo/pull/285) - [@cassiobatista](https://github.com/cassiobatista/)) 

* Documentação melhorada do projeto calourada-bootstrap ([calourada-bootstrap#1](https://github.com/JonatasFAlves/calourada-bootstrap/pull/1) - [@juliocesark](https://github.com/juliocesark))

* Documentação melhorada do projeto peludinhos ([peludinhos#3](https://github.com/getacesupa/peludinhos/pull/3) - [@juliocesark](https://github.com/juliocesark))


## Realizar tradução

* Tradução do README do projeto scancode-toolkit ([PR](https://github.com/nexB/scancode-toolkit/pull/1640) - [@tavareslucas](https://github.com/tavareslucas))

* Adição de tradução PT-BR no Projeto de Player de Musica Nuclear ([nukeop/nuclear#365](https://github.com/nukeop/nuclear/pull/365) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).

* Adição de README em pt_Br para biblioteca python `pymarc` ([edsu/pymarc#137](https://github.com/edsu/pymarc/pull/137) - [@souzaluuk](https://github.com/souzaluuk))

* Translate most of the Brazilian Portuguese stuff that goes in HTML hyperlinks ([hugo-academic#1121](https://github.com/gcushen/hugo-academic/pull/1121) - [@cassiobatista](https://github.com/cassiobatista/)) 

* Foi realizado a tradução da documentação do projeto BlindChat ([BlindChat#33](https://github.com/mayukh18/BlindChat/pull/33) - [@juliocesark](https://github.com/juliocesark))

* Foi realizado a tradução da documentação do projeto python-blogs ([python-blogs#240](https://github.com/python-gsoc/python-blogs/pull/240) - [@juliocesark](https://github.com/juliocesark))

## Corrigir bug

- O gerador de site estático usava os repositórios do usuário no site mas não contava que quando o usuário não tivesse repositórios um erro era ocasionado ([saberland/create-portfolio#26](https://github.com/saberland/create-portfolio/pull/26) - [@lubien](https://github.com/lubien)).
- O gerador de site estático não tinha suporte para links com `#fragment-identifiers` pois na build ele considerava apenas o link ao arquivo original ([saberland/saber#270](https://github.com/saberland/saber/pull/270) - [@lubien](https://github.com/lubien)).
- O parser não conseguia identificar corretamente o início de um link em markdown ([saberland/saber#278](https://github.com/saberland/saber/pull/278) - [@lubien](https://github.com/lubien)).
* Correção de bugs no do repositorio Simple Icons, icone desformatado ([simple-icons/simple-icons#1501](https://github.com/simple-icons/simple-icons/pull/1501) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).

## Adicionar pequena funcionalidade

* Adição de 3 modulos de tradução para o projeto langplusplus. ([PR da funcionalidade](https://github.com/fibanneacci/langplusplus/pull/25) - [@tavareslucas](https://github.com/tavareslucas))

- Pacote de um componente vue.js para animação de escrita, foi sugerido implementar a possibilidade de simular um cursor "falso", eu implementei como pedido. O cursor foi adicionado com a possibilidade de configurar a velocidade em que ele pisca, cor, formato e além de também adicionar uma classe css para infinitas configurações ([PR #6](https://github.com/trickstival/vue-typing/pull/6) - [@urielfcampos](https://github.com/urielfcampos))
- Aponta qual o comentário com melhores reações (baseado em uma heurística simples) em uma issue do GitHub para facilitar encontrar possíveis respostas ou destaques importantes de se ler ([sindresorhus/refined-github#2108](https://github.com/sindresorhus/refined-github/pull/2108) - [@lubien](https://github.com/lubien)).
- Incrementa a funcionalidade do ponto anterior adicionando uma _label_ no comentário em destaque ([sindresorhus/refined-github#2177](https://github.com/sindresorhus/refined-github/pull/2177) - [@lubien](https://github.com/lubien)).
- Implementa a possibilidade da biblioteca NodeJs chamada `create-site` usar [templates do GitHub](https://help.github.com/en/articles/creating-issue-templates-for-your-repository) ([saberland/saber#271](https://github.com/saberland/saber/pull/271) - [@lubien](https://github.com/lubien)).

* Adição de novo icone ao repositorio Font Awesome ([FortAwesome/Font-Awesome#15198](https://github.com/FortAwesome/Font-Awesome/pull/15198) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).

* Adição de novo icone ao repositorio Feather ([feathericons/feather#636](https://github.com/feathericons/feather/pull/636) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).

* Adição do icone do Canva ao repositorio Simple Icons ([simple-icons/simple-icons#1487](https://github.com/simple-icons/simple-icons/pull/1487) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).

* Adição do icone do Google Cloud ao repositorio Simple Icons ([simple-icons/simple-icons#1491](https://github.com/simple-icons/simple-icons/pull/1491) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).

* Adição do icone da Epic Games ao repositorio Simple Icons ([simple-icons/simple-icons#1492](https://github.com/simple-icons/simple-icons/pull/1492) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).

* Adição do icone do Babel ao repositorio Simple Icons ([simple-icons/simple-icons#1493](https://github.com/simple-icons/simple-icons/pull/1493) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).

* Adição do icone do Kodi ao repositorio Simple Icons ([simple-icons/simple-icons#1494](https://github.com/simple-icons/simple-icons/pull/1494) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).

* Adição do icone do Linux Deepin ao repositorio Simple Icons ([simple-icons/simple-icons#1495](https://github.com/simple-icons/simple-icons/pull/1495) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).

* Adição do icone do Exercism ao repositorio Simple Icons ([simple-icons/simple-icons#1496](https://github.com/simple-icons/simple-icons/pull/1496) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).

* Adição do icone do Intellij Idea ao repositorio Simple Icons ([simple-icons/simple-icons#1497](https://github.com/simple-icons/simple-icons/pull/1497) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).

* Adição do icone do Dynatrace ao repositorio Simple Icons ([simple-icons/simple-icons#1498](https://github.com/simple-icons/simple-icons/pull/1498) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).

* Adição do icone do Composer ao repositorio Simple Icons ([simple-icons/simple-icons#1505](https://github.com/simple-icons/simple-icons/pull/1505) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).

* Adição do icone do Haxe ao repositorio Simple Icons ([simple-icons/simple-icons#1506](https://github.com/simple-icons/simple-icons/pull/1506) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).

* Adição do icone do Apache Flink ao repositorio Simple Icons ([simple-icons/simple-icons#1507](https://github.com/simple-icons/simple-icons/pull/1507) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).

* Adição do icone do Chef ao repositorio Simple Icons ([simple-icons/simple-icons#1509](https://github.com/simple-icons/simple-icons/pull/1509) - [@JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)).

* Criação de função para parsing de arquivos JSON para objetos de registro (pymarc.Record) da biblioteca pymarc ([edsu/pymarc#137](https://github.com/edsu/pymarc/pull/137) - [@souzaluuk](https://github.com/souzaluuk))

* Verifiquei que no projeto [pymarc](https://github.com/edsu/pymarc) havia uma [issue](https://github.com/edsu/pymarc/issues/130) solicitando a modificação de uma função existente na biblioteca. ([edsu/pymarc#138](https://github.com/edsu/pymarc/pull/138) - [@souzaluuk](https://github.com/souzaluuk))

* Allow pub-sharing buttons configuration to be performed inside the publication's own `index.md` file ([hugo-academic#1131](https://github.com/gcushen/hugo-academic/pull/1131) - [@cassiobatista](https://github.com/cassiobatista/)) 

* Foi retirado o modal que estava apenas com texto, e adicionado 2 botões para redes sociais ao lado de "contate-me" para que ficasse melhor visualizado na página. E para o desenvolvimento desses botões foi utilizado o repositório [bootstrap-social](https://github.com/lipis/bootstrap-social). Essa pequena funcionalidade foi implementada no projeto calourada-bootstrap ([calourada-bootstrap#2](https://github.com/JonatasFAlves/calourada-bootstrap/pull/2) - [@juliocesark](https://github.com/juliocesark))

* Adicionado um novo botão de compartilhar utilizando modal para apresentar os links de compartilhamento referente a redes socias no projeto photo-share (([photo-share#1](https://github.com/JonatasFAlves/photo-share/pull/1)) e ([photo-share#2](https://github.com/JonatasFAlves/photo-share/pull/2)) - [@juliocesark](https://github.com/juliocesark))

## Adicionar grande funcionalidade

- Um projeto de auxílio para Dungeon masters de rpg de mesa, ele gera cidades e regiões inteiras, uma [issue](https://github.com/ryceg/Eigengrau-s-Essential-Establishment-Generator/issues/205), pedia para implementar uma nova funcionalidade que alterava a maneira que cidades eram geradas, incluindo um material de construcao "principal" para aquela cidade, que influencia o material das construções daquela cidade que acabavam ficando complementamente incoerentes por serem escolhidos aleatoriamente sem nenhuma influência da cidade em que se encontravam. Esta geração agora é influenciada pelo tamanho da cidade, riqueza e localização da mesma, depois de gerado, gera-se o material individual de cada construção da cidade, que é influenciada pelo material "principal" da cidade e pela riqueza do dono da construção.([PR #220](https://github.com/ryceg/Eigengrau-s-Essential-Establishment-Generator/pull/220) - [@urielfcampos](https://github.com/urielfcampos))
- Cria uma nova regra do eslint que adiciona a possibilidade de se passar argumentos a comentários _TODO_ e definir condições em que eles se tornam inválidos (data de expiração, biblioteca adicionada/removida, versão de certa tecnologia entre outros) ([sindresorhus/eslint-plugin-unicorn#302](https://github.com/sindresorhus/eslint-plugin-unicorn/pull/302) - [@lubien](https://github.com/lubien)).

* New members section layout ([beautifulhugo#287](https://github.com/halogenica/beautifulhugo/pull/287) - [@cassiobatista](https://github.com/cassiobatista/)) 

* New publications section layout ([beautifulhugo#286](https://github.com/halogenica/beautifulhugo/pull/286) - [@cassiobatista](https://github.com/cassiobatista/))

* Inclusão de um novo algoritmo de embedding - redução da dimensionalidade de dados em alta dimensão - na biblioteca de machine learning Scikit-learn ([A new manifold learning algorithm #14239](https://github.com/scikit-learn/scikit-learn/pull/14239) - [@elgrably](https://github.com/Elgrably), [@caioMFRodrigues](https://github.com/CaioMFRodrigues))

## Desenvolver estudo original com artigo sobre software livre

* Artigo sobre análise quantitativa de testes usando o SonarQube em repositórios do GitHub [Link para o Artigo](https://drive.google.com/open?id=145ZQaQuj7-0eCAtoYpbKH7sgXB_VZCbg) - (Dupla com o @leochrisis)

* Mapeamento de Ferramentas e Frameworks de Testes utilizando Mineração de Repositórios no GitHub ([@elgrably](https://github.com/Elgrably), [@caioMFRodrigues](https://github.com/CaioMFRodrigues))

* Processo de Desenvolvimento em Projetos Open Source: Um Estudo Observacional ([download](https://github.com/gustavopinto/tesl/files/3368976/Artigo.TESL.-.Andre.e.Thayssa.pdf) - [@ThayssaRocha](https://github.com/ThayssaRocha) e [@andremp93](https://github.com/andremp93))