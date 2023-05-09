# Princípios e diretrizes do projeto

## Introdução

Por definição, princípios representam objetivos gerais e de alto nível, enquanto diretrizes são regras seguidas e observadas no desenvolvimento de um projeto. Segundo Simone (2021), por mais que existam diversos princípios e diretrizes consolidados na literatura de IHC, estas devem ser utilizadas como uma ferramenta auxiliar ao processo de design, não o substituindo[1].

## Metodologia

Para determinar quais princípios e diretrizes seriam utilizadas no projeto, foram analisadas quais destas são utilizadas comumente em IHC e apresentados por Simone Barbosa[1]. Sendo estas:

- Correspondência com as espectativas dos usuários.
- Simplicidade nas estruturas das tarefas.
- Equilíbrio entre controle e liberdade do usuário.
- Consistência e padronização.
- Promoção da eficiência do usuário.
- Antecipação das necessidades do usuário.
- Visibilidade e reconhecimento.
- Contéudo relevante e expressão adequada.
- Projeto para erros.

## Princípios e diretrizes gerais

Segundo Norman (1988) um sistema deve ser projetado a partir de um modelo conceitual que o usuário possa compreender e aprender seu uso sem dificuldades. Este modelo deve ser capaz de interpretar as relações entre o sistema e o mundo real[1]. A partir disso os 9 princípios e diretrizes apresentados acima são comumente utilizados nos projetos de IHC, abaixo estão descritos cada um deles. Cada descrição foi retirada e adaptada do livro de Simone Barbosa[1].

### Correspondência com as expectativas dos usuários

O sistema deve ser projetado de forma a remeter suas funcionalidades a ações anteriores do usuário, fazendo com que o sistema atenda uma expectativa do usuário acerca de como cada função será executada. Para alcançar esse objetivo Norman (1988) sugere que o sistema se espelhe no mundo real, se baseando em como seu usuário realiza suas funções no mundo real, criando assim uma relação entre as intenções do usuário e as ações do sistema.

Além disso, Shneiderman (1998) recomenda que o sistema siga uma linha de raciocíonio ao desempenhar suas funções, além de fornecer uma resposta eficaz acerca do estado atual do sistema. Sempre se baseando no mundo real para definir uma linha de raciocínio lógica a ser seguida pelo usuário.

Por fim, Tognazzini (2014) alerta acerca do uso de metáforas e jargões nos conteúdos do sistema, pois podem confundir o usuário. Contudo, uma metáfora bem colocada pode acabar por auxiliar no entendimento do sistema, para isso as mesmas devem remeter a conceitos familiares ao usuário.

### Simplicidade nas estruturas das tarefas

Segundo Norman (1988) as tarefas devem ser simplificadas, reduzindo o planejamento e resolução de problemas relativos à mesma. Seguindo isso, tarefas complexas devem ser reestruturadas, para isso podem-se utilizar 4 técnicas:

- Fornecer ajuda e apoio ao usuário na realização da tarefa.
- Utilizar tecnologia para melhorar o feedback e aumentar o controle do usuário.
- Automatizar a tarefa ou parte dela.
- Modificar a tarefa para torná-la mais simples.

Deve-se tomar cuidado ao se utilizar demais da automatização, pois esta prática acaba por reduzir o controle e autonomia do usuário em relação ao sistema e a tarefa.

### Equilíbrio entre controle e liberdade do usuário

O sistema deve sempre buscar se adaptar de forma a permitir o controle do usuário sobre o mesmo, ao mesmo tempo que impõe restrições de forma a evitar erros do utilizador. Para isto, Norman (1988) sugere se utilizar das restrições para induzir o usuário a realizar apenas as ações "corretas", Tognazzini (2014) sugere porém, que o usuário possua um caminho principal com menos restrições mas que possa explorar o sistema como bem entender.

O sistema também deve fornecer uma sáida clara dos caminhos de utilização, ao mesmo tempo que deve se tornar mais fácil continuar no caminho principal a sair do mesmo. Segundo Cooper (1999), o sistema deve ser maleável, ou seja, permitir que as ações possam ser realizadas fora de ordem e com total liberdade, porém sempre mantendo registros para que nada se perca.

Além disso, o sistema deve ser capaz de permitir que o usuário inicie e desfaça as ações, evitando que o mesmo apenas reaja aos avisos do sistema, além de reduzir sua ansiedade e aumentar seu aprendizado no uso do sistema. Permitir que o usuário desfaça suas ações também auxilia na quantidade de informação ao evitar a necessidade de diversas janelas de confirmação por exemplo.

Por fim, o sistema também deve permitir que o usuário personalizae sua experiência através de parâmetros configuráveis, o sistema deve porém, ser projetado de forma a ser totalmente utilizável com seus parâmetros padrão.

### Consistência e padronização

O sistema deve manter um padrão de conteúdo no decorrer de seu uso assim como com sua documentação, desta forma pode-se melhorar o aprendizado do usuário, assim como corresponder às suas expectativas. Segundo diversos autores, o sistema deve ter suas funções, resultados, layout e visualização de informação padronizados e consistentes.

Para alcançar esta padronização, as funções com resultados semelhantes devem ser semelhantes da mesma forma, os usuários devem ser capazes de identificar e reconhecer funções a partir de seu design, além disso, eles não devem ter que se perguntar se palavras ou ações diferentes possuem o mesmo resultado ou significado.

Tognazzini (2014) recomenda que ações inertes do usuário possuam maior importância de padronização, evitando assim erros inconscientes. Seguindo esta lógica, funções com resultados diferentes devem ter layouts obviamente diferentes, da mesma forma, ações que necessitam de maior atenção do usuário podem ser discrepantes do restante para que evitem ações inertes a partir do usuário.

### Promoção da eficiência do usuário

Segundo Tognazzini (2014), o sistema deve priorizar a eficiência do usuário acima de performance computacional, já que pessoas são mais custosas do que máquinas. Para isso, recomenda que o sistema mantenha o usuário ocupado a todo momento ao deslocar processos demorados para executar em segundo plano, permitindo que o usuário se ocupe com outra tarefa. Já segundo Cooper (1999), o sistema não deve interromper o usuário durante a realização de uma tarefa, evitando perda de tempo.

Além de manter o usuário ocupado, outra estratégia para aumentar a eficiência é a proteção do trabalho dos usuários, o sistema deve garantir que nada que o usuário realiza seja perdido por alguma falha. Além disso, o sistema deve se recordar das ações do usuário, para que assim seu trabalho possa ser recuperado.

Nielsen (1994c) e Shneiderman (1998) recomendam a implementação de atalhos e aceleradores ocultos, estas ferramentas auxiliam e melhoram a eficiência de usuários experientes ao mesmo passo que não interfere na utilização do sistema por usuários iniciantes.

### Antecipação das necessidades do usuário

Segundo Tognazzini (2014) o sistema deve ser capaz de prever as intenções e desejos do usuário, se prontificando a atendê-los antes que o mesmo solicite. Uma forma de realizar esta antecipação proposta por Cooper (1999) é fornecer informações adicionais úteis ao usuário, evitando buscas repetitivas por exemplo, além disso o sistemadeve ser capaz de se preparar para prováveis situações futuras.

Tognazzini (2014) também recomenda a atenção na criação de valores padrão bem definidos, além disso estes valores também podem ser pré-preenchidos em formulários, porém sempre permitindo a edição e alteração pelo usuário.

### Visibilidade e reconhecimento

Segundo diversos autores, o sistema deve ser visível, ou seja o usuário deve possuir as informações necessárias para a operação do sistema a todo momento e para isso o estado, objetos, funções e opções do sistema devem estar constantemente atualizados e perceptíveis pelo usuário. Além disso, o usuário nunca deve ser responsável por lembrar informações passadas para ou por ele anteriormente, sendo uma tarefa do sistema.

Segundo Tognazzini (2014), o sistema deve possuir mecanismos de status eficientes, pois o usuário não deve ter que buscar informações acerca do estado atual do sistema. Contudo, Cooper (1999) recomenda que as mensagens de status não devem ser exageradas, já que podem confundir o usuário, portanto devem ser sutis em sua grande maioria, destacando apenas os feedbacks de grande importância. O sistema também deve deixar claro ao usuário sua posição atual e caminho percorrido, permitindo o retorno facilitado e a navegação eficiente pelo sistema.

Quanto aos feedbacks do sistema, diversos autores recomendam que ações frequentes e com resultado esperado possuam feedbacks sutis, enquanto ações disruptivas ou voláteis possuam um feedback destacado. Segundo Tognazzini (2014), o sistema deve fornecer avisos ao usuário indicando o funcionamento do sistema durante carregamentos, os feedbacks podem ser classificados e implementados de acordo com a tarefa realizada e seu tempo de execução:

- Feedback visual/sonoro até 50ms após o clique em um botão.
- Sinalizar com uma ampulheta quando uma operação de 0,5 a 2s for realizada.
- Apresentar informações sobre o tempo de execução assim como uma barra de progresso para ações que demorem mais do que 2 segundos.
- Quando uma operação necessitar mais de 10 segundos, o sistema deve alertar de forma sonora e visual seu término, para recuperar a atenção do usuário.

### Contéudo relevante e expressão adequada

Segundo Reeves e Nass (1996) e se baseando no princípio de conversa cooperativa de Grice (1975), uma interação polida entre usuário e sistema deve seguir quatro máximas:

- **Máxima da qualidade:** Define que não se deve repassar informações imprecisas ou falsas ao usuário, ou seja, não mentir ou especular.
- **Máxima da quantidade:** Define que as informações devem ser simples, evitando dados desnecessários para o contexto de uso atual.
- **Máxima da relação:** Define que tudo que é apresentado deve ser relacionado ao tópico atual e ser relevante para o usuário futuramente.
- **Máxima de modo:** Define que se evite ambiguidade na apresentação das informações.

Além das quatro máximas, é recomendavel seguir algumas orientações para criar uma boa relação entre usuário e sistema, segundo Nielsen (1994c) o sistema deve possuir uma estética minimalista, evitando informação desnecessária e focando o usuário nas informações que necessita. Tognazzini (2014) recomenda o uso de textos e elementos concisos e informativos, além disso deve-se priorizar o entendimento do usuário à precisão dos termos utilizados.

Além das informações, as cores são de grande importância na expressão do sistema, guiando o uso do sistema e criando uma interface agradável, contudo deve-se tomar cuidado para a questão da acessibilidade, permitindo que o sistema seja operado por usuários com dificuldades.

### Projeto para erros

Segundo Norman (1988), o sistema deve ser projetado ao erro, ou seja, deve se prepara para que qualquer erro potencial será cometido pelo usuário, se prontificando para ajudá-lo a se recuperar do erro, além de permitir a reversão de qualquer ação do usuário e dificultar a realização de ações irreversíveis.

Cooper (1999) recomenda que controles perigosos, ou seja, que realizem ações importantes e irreversíveis não sejam posicionados próximos a controles frequentemente utilizados pelo usuário, evitando assim acidentes.

Nielsen (1994c) e Shneiderman(1998) recomendam que o sistema evite que o usuário cometa erros durante sua operação, contudo caso um erro ocorra, o sistema deve ser capaz de fornecer um feedback preciso e inteligível para o usuário, de forma que o mesmo possa reconhecer e se recuperar do erro cometido. Além disso, recomendam que o sistema possua uma documentação eficiente para auxiliar o usuário durante a operação do sistema.

## Referências Bibliográficas

> [1] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1. Acesso em; 09 mai. 2023.

## Histórico de Versão

| Versão | Data     | Descrição                                                        | Autor(es) | Revisor(es) |
| ------ | -------- | ---------------------------------------------------------------- | --------- | ----------- |
| `1.0`  | 09/05/23 | Criação do documento e adição dos principios e diretrizes gerais | Pedro M.  | João M.     |
