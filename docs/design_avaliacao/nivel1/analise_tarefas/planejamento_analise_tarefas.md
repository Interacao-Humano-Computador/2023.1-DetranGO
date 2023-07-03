# Análise de Tarefas - Planejamento da avaliação

## 1. Introdução

Na etapa de análise de requisitos foi realizada uma [análise de tarefas](./../../../analise_requisitos/analise_de_tarefas.md) a fim de compreender como certas tarefas são realizadas e por quê. Essa análise primeiramente definiu os objetivos das pessoas para depois listar os passos para a realização de uma determinada tarefa. 

Para o escopo da disciplina, foram utilizadas duas técnicas de análilse de tarefas: o HTA (Hierarchical Task Analysis - Análise hierárquica de tarefas) e o CMN-GOMS, isto é, a proposta original do GOMS (Goals, Operators, Methods and Selection Rules). Para solidificar as conclusões e informações obtidas a partir dessa análise, bem como corrigi-las, há de se realizar uma avaliação com usuários acerca desta análise. Para tanto, faz-se necessário o planejamento desta avaliação a fim de roteirizá-la, registrar datas e demarcar métodos. Descrito neste artefato está o planejamento da avaliação da análise de tarefas. 

## 2. Metodologia

Para o planejamento da avaliação do protótipo de papel elaborado, será utilizado o framework DECIDE, descrito por Simone Barbosa em seu livro Interação Humano Computador[4], seguindo o framework, o artefato terá os seguintes tópicos:

- **D** - Determinar os objetivos gerais da avaliação e identificar por que e para quem tais objetivos são importantes.
- **E** - Explorar perguntas a serem respondidas com a avaliação.
- **C** - Escolher (Choose) os métodos de avaliação a serem utilizados.
- **I** - Identificar e administrar as questões práticas da avaliação.
- **D** - Decidir como lidar com as questões éticas.
- **E** - Avaliar (Evaluate), interpretar e apresentar os dados.

## 3. DECIDE

### 3.1 D: Determinar os objetivos da avaliação de IHC

Para a avaliação das análises de tarefas desenvolvidas em [artefato anterior](./../../../analise_requisitos/analise_de_tarefas.md), julgam-se cruciais para o desenvolvimento do projeto e para a verificação de qualidade das análises desenvolvidas, bem como para a garantia do desenvolvimento de fluxos de uso eficientes para o sítio dois objetivos específicos como definidos por Barbosa et al. (2021) [4]:

- 1: **Avaliar a conformidade com um padrão**: Deve-se avaliar se as análises desenvolvidas estão de acordo com os padrões defindos para sua confecção. Ou seja, deve-se assegurar que as análises respeitem seus modelos à risca.
- 2: **Identificar problemas na interação e na interface**: Deve-se avaliar se a interação representada nas análises são eficientes e claras ao usuário, não impondo obstáculos e permitindo um uso adequado e que atinja os objetivos propostos em cada tarefa.
- 3: **Comparar ideias e alternativas de design**: As análises devem também ser avaliadas a fim de se considerá-las por outros ângulos e obter novas possibilidades para a execução de tarefas.

Para esta avaliação, serão avaliados os diagramas e análises referentes às tarefas a seguir:

- Solicitar CNH;
- Consultar CNH;
- Emitir CRLV.

### 3.2 E: Explorar perguntas a serem respondidas com a avaliação

A avaliação da análise de tarefas será balizada pelas perguntas a serem respondidas a partir da execução da avaliação. A seguir estão descritas as perguntas elaboradas discriminadas por seu objetivo.

#### 3.2.1 Identificação do usuário

As perguntas elaboradas para obter a identificação do usuário estão presentes na tabela 1 abaixo.

|**Número**|**Pergunta**|**Resposta**|**Observações**|
|:-:|:-:|:-:|:-:|
|1|Qual o nome completo do entrevistado? |Resposta aberta | - |
|2|Qual a idade do entrevistado?| Resposta aberta | - |
|3|Qual a ocupação do entrevistado?| Resposta aberta | - |
|4|Qual o grau de escolaridade do entrevistado?| Resposta aberta | - |
|5|Qual o grau de experiência tecnológica do entrevistado? (tecnófilo/tecnófobo)| Resposta aberta | - |

<center>

Tabela 1: Roteiro de perguntas para obtenção da identidade do usuário (Fonte: Autor, 2023).

</center>

#### 3.2.2 Perguntas específicas para o HTA

Esta seção explora perguntas específicas para a análise hierárquica de tabelas, a fim de avaliá-las com mais especificidade. Cada diagrama deverá ser avaliado com base nestas perguntas.

##### 3.2.2.1 Avaliar a conformidade com um padrão

A tabela 2 compila perguntas relacionadas ao primeiro objetivo da avaliação para o HTA. As perguntas são baseadas na tabela 11.1 do livro de Interação Humano-Computador por Barbosa et al. (2021) [4], e foram adaptadas a fim de representar melhor o conteúdo de uma análise hierárquica de tarefas, também com base no mesmo livro. Esta tabela deve ser preenchida pelo entrevistador.


| **Número** | **Pergunta** | **Possível resposta** | **Observações** |
|--|--|--|--|
| 1 | Cada tarefa tem definido um input e um feedback esperado condizente? Quantas não possuem?| Sim/Não + Resposta aberta| - |
| 2 | Os planos possuem como característica os subobjetivos pelos quais são compostos? Quantos não possuem? | Sim/Não + Resposta aberta | - |
| 3 | Os níveis mais baixos do HTA são marcados de maneira diferente dos outros? Quais não são?| Sim/Não + Resposta aberta | - |

<center>

Tabela 2: Perguntas para o HTA elaboradas para o objetivo 1 (Fonte: adaptado de Simone Barbosa et al. (2021)[4]).

</center>

##### 3.2.2.2 Identificar problemas na interação e na interface

A tabela 3 compila perguntas relacionadas ao segundo objetivo da avaliação para o HTA. As perguntas são baseadas na tabela 11.1 do livro de Interação Humano-Computador por Barbosa et al. (2021) [4], e foram adaptadas a fim de representar melhor o conteúdo de uma análise hierárquica de tarefas, também com base no mesmo livro. Esta tabela deve ser preenchida pelo entrevistador.

| **Número** | **Pergunta** | **Possível resposta** | **Observações** |
|--|--|--|--|
| 1 | Os objetivos definidos são atingidos ao fim da tarefa? Quais objetivos não são atingidos? | Sim/Não + Resposta aberta | - |
| 2 | Há operações que não auxiliam na obtenção do objetivo? Quantas? | Sim/Não + Resposta aberta | A existência de operações sem objetivo claro é um erro grave |
| 3 | Todas as operações são de fácil compreensão? Quais não são? | Sim/Não + Resposta aberta | - |
| 4 | Os planos definidos permitem um claro entendimento dos subobjetivos a serem atingidos? Quais não permitem? | Sim/Não + Resposta aberta | - |

<center>

Tabela 3: Perguntas para o HTA elaboradas para o objetivo 3 (Fonte: adaptado de Simone Barbosa et al. (2021)[4]).

</center>

##### 3.2.2.3 Comparar ideias e alternativas de design

A tabela 4 compila perguntas relacionadas ao terceiro objetivo da avaliação para o HTA. As perguntas são baseadas na tabela 11.1 do livro de Interação Humano-Computador por Barbosa et al. (2021) [4], e foram adaptadas a fim de representar melhor o conteúdo de uma análise hierárquica de tarefas, também com base no mesmo livro. Esta tabela deve ser preenchida pelo entrevistador.

| **Número** | **Pergunta** | **Possível resposta** | **Observações** |
|--|--|--|--|
| 1 | Considerando o mesmo input e mesmo feedback, é possível que a tarefa possa conter menos subobjetivos? | Resposta aberta | - |
| 2 | Considerando o mesmo input e mesmo feedback, é possível que a tarefa possa conter menos operações? | Resposta aberta | - |
| 3 | Considerando o mesmo input e mesmo feedback, há planos de execução sequencial que possam se tornar paralelos ou de seleção? | Resposta aberta | - |
| 4 | Considerando o mesmo input e mesmo feedback, há planos de execução paralelos que possam se tornar sequenciais ou de seleção? | Resposta aberta | - |
| 5 | Das alternativas apresentadas, há alguma de maior eficiência ou mais fácil aprendizado? Por quê? | Resposta aberta | - |


<center>

Tabela 4: Perguntas para o HTA elaboradas para o objetivo 3 (Fonte: adaptado de Simone Barbosa et al. (2021)[4]).

</center>


#### 3.2.3 Perguntas específicas para o CMN-GOMS

Esta seção explora perguntas específicas para o CMN-GOMS, a fim de avaliá-los com mais especificidade. Cada instância deverá ser avaliada com base nestas perguntas.

##### 3.2.3.1 Avaliar a conformidade com um padrão

A tabela 5 compila perguntas relacionadas ao primeiro objetivo da avaliação para o CMN-GOMS. As perguntas são baseadas na tabela 11.1 do livro de Interação Humano-Computador por Barbosa et al. (2021) [4], e foram adaptadas a fim de representar melhor o conteúdo de uma análise de tarefas GOMS, também com base no mesmo livro. Esta tabela deve ser preenchida pelo entrevistador.

| **Número** | **Pergunta** | **Possível resposta** | **Observações** |
|--|--|--|--|
| 1 | Os operadores são sempre executados de maneira sequencial? Onde não são? | Sim/Não + Resposta aberta | - |
| 2 | Os métodos, em sua representação, possuem submétodos e/ou condicionais? | Sim/Não | - |
| 3 | As regras de seleção representam a tomada de decisão do usuário sobre qual método utilizar em determinada situação? Onde não representam? | Sim/Não + Resposta aberta | - |
| 4 | Os operadores representam ações concretas permitidas pelo sistema? Onde não representam? | Sim/Não + Resposta aberta | - |


<center>

Tabela 5: Perguntas para o CMN-GOMS elaboradas para o objetivo 1 (Fonte: adaptado de Simone Barbosa et al. (2021)[4]).

</center>

##### 3.2.3.2 Identificar problemas na interação e na interface

A tabela 6 compila perguntas relacionadas ao segundo objetivo da avaliação para o CMN-GOMS. As perguntas são baseadas na tabela 11.1 do livro de Interação Humano-Computador por Barbosa et al. (2021) [4], e foram adaptadas a fim de representar melhor o conteúdo de uma análise de tarefas GOMS, também com base no mesmo livro. Esta tabela deve ser preenchida pelo entrevistador.


| **Número** | **Pergunta** | **Possível resposta** | **Observações** |
|--|--|--|--|
| 1 | A tarefa representada é executável? Quais partes não são executáveis sequencialmente? | Sim/Não + Resposta aberta | - |
| 2 | Cada objetivo definido dentro da tarefa é atingido? Se não, quantas vezes não são atingidos? Por quê? | Sim/Não + Resposta aberta | - |
| 3 | O tamanho dos métodos para atingir um objetivo é satisfatório? Que métodos não tem o tamanho ideal? | Sim/Não + Resposta aberta | - |
| 4 | Cada método e seus subelementos (regras de seleção e operadores) são compreensíveis? Quais não são? Por qual razão? | Sim/Não + Resposta aberta | - |
| 5 | Dentro de cada objetivo, há elementos que não o suportam (isto é, não ajudam em sua obtenção)? Quantos? | Sim/Não + Resposta aberta | - |

<center>

Tabela 6: Perguntas para o CMN-GOMS elaboradas para o objetivo 2 (Fonte: adaptado de Simone Barbosa et al. (2021)[4]).

</center>

##### 3.2.3.3 Comparar ideias e alternativas de design

A tabela 7 compila perguntas relacionadas ao terceiro objetivo da avaliação para o CMN-GOMS. As perguntas são baseadas na tabela 11.1 do livro de Interação Humano-Computador por Barbosa et al. (2021) [4], e foram adaptadas a fim de representar melhor o conteúdo de uma análise de tarefas GOMS, também com base no mesmo livro. Esta tabela deve ser preenchida pelo entrevistador.


| **Número** | **Pergunta** | **Possível resposta** | **Observações** |
|--|--|--|--|
| 1 | Dentro dos objetivos, há métodos que podem ser alterados ou removidos? Quais? | Sim/Não + Resposta aberta | - |
| 2 | Há operações que podem ser alteradas ou removidas? Quais? | Sim/Não + Resposta aberta | - |
| 3 | Há objetivos descritos que possam ser alterados ou removidos sem dano ao objetivo principal da tarefa? Quais? | Sim/Não + Resposta aberta | - |
| 4 | Há regras de seleção para os métodos que podem ser alteradas ou removidas para a melhor execução dos operadores? Quais? | Sim/Não + Resposta aberta | - |
| 5 | Das alternativas apresentadas, há alguma de maior eficiência ou mais fácil aprendizado? Por quê? | Resposta aberta | - |

<center>

Tabela 7: Perguntas para o CMN-GOMS elaboradas para o objetivo 3 (Fonte: adaptado de Simone Barbosa et al. (2021)[4]).

</center>

### 3.3 C: Escolher (Choose) os métodos de avaliação a serem utilizados

O método escolhido para avaliar é a investigação através de entrevistas. A partir das respostas obtidas para as perguntas, uma análise das mesmas será conduzida a fim de determinar resultados da avaliação. Este método é ótimo para entender o que e como o usuário se sente ao falar sobre determinada atividade e proverá informações importantes para que o designer possa tomar decisões conscientes quanto ao público que deve atender.

### 3.4 I: Identificar e administrar as questões práticas da avaliação

#### 3.4.1 Recrutamento
Para a escolha dos participantes das entrevistas, deve ser levado em conta o [perfil de usuário](../../../analise_requisitos/perfilUsuario.md)[3] elaborado anteriormente, para que se possa afirmar que os entrevistados na avaliação representam de forma correta o público alvo do sistema trabalhado.

#### 3.4.2 Tarefas propostas
Para a avaliação, é necessário que todos os fluxos de tarefas representados pelo HTA e pelo GOMS sejam avaliados.

#### 3.4.3 Ferramentas utilizadas
As entrevistas poderão ser realizadas de forma presencial ou remota. Para que se possa realizar a avaliação de forma remota, os storyboards desenvolvidos devem ser convertidos em arquivos PDF utilizando a ferramenta [CamScanner](https://www.camscanner.com/)[5]. Para a realização e gravação da entrevista serão utilizadas as ferramentas [Google Meet](https://meet.google.com/)[7] para a realização da reunião e o [OBS](https://obsproject.com/pt-br/download/)[8] para a gravação da mesma.

#### 3.4.4 Teste piloto
Antes de realizar as entrevistas de fato, deverá ser realizado um teste inicial pela equipe de desenvolvimento, visando afirmar o funcionamento de todas as ferramentas utilizadas, além da identificação de problemas não encontrados anteriormente.

#### 3.4.5 Participantes das atividades

Na tabela 8 abaixo são definidos os participantes do teste piloto.

<center>

| Atividade | Participante | Função | Papel |
| -- | -- | -- | -- |
| Teste piloto | Amanda Noda | Equipe de desenvolvimento | Testador |
| Teste piloto | João Pedro Morbeck | Equipe de desenvolvimento | Testador |

Tabela 8: Participantes do teste piloto (Fonte: Autor, 2023)

</center>

Nas tabelas 9 e 10 abaixo são definidos os participantes da entrevista.

<center>

| Atividade | Participante | Função | Papel |
| -- | -- | -- | -- |
| Entrevista 1 | Felipe Mastromauro Corrêa | Equipe de desenvolvimento | Entrevistador |
| Entrevista 1 | Pedro Ferreira Muniz | Equipe de desenvolvimento | Relator |
| Entrevista 1 | Douglas Langkammer Gomes | Usuário do sistema | Entrevistado |

Tabela 9: Participantes da entrevista 1 (Fonte: Autor, 2023)

</center>

<center>

| Atividade | Participante | Função | Papel |
| -- | -- | -- | -- |
| Entrevista 2 | Pedro Ferreira Muniz | Equipe de desenvolvimento | Entrevistador |
| Entrevista 2 | Felipe Mastromauro Corrêa | Equipe de desenvolvimento | Relator |
| Entrevista 2 | João Camilo de Moura | Usuário do sistema | Entrevistado |

Tabela 9: Participantes da entrevista 1 (Fonte: Autor, 2023)

</center>

#### 3.4.6 Cronograma das atividades 
Na tabela 11 abaixo, estão descritos local, data e horário para o teste piloto.

<center>

| Atividade | Local | Data | Horário |
| -- | -- | -- | -- |
| Teste piloto | Remoto (Google Meet) | 03/07/2023 | 15:00 |

Tabela 11: Cronograma para o teste piloto (Fonte: Autor, 2023)

</center>

Nas tabelas 12 e 13 abaixo, estão descritos local, data e horário para a entrevista.

<center>

| Atividade | Local | Data | Horário |
| -- | -- | -- | -- |
| Entrevista 1 | Remoto (Google Meet) | 03/07/2023 | 17:00 |

Tabela 12: Cronograma para a entrevista 1 (Fonte: Autor, 2023)

</center>


| Atividade | Local | Data | Horário |
| -- | -- | -- | -- |
| Entrevista 2 | Remoto (Google Meet) | 03/07/2023 | 17:30 |

Tabela 13: Cronograma para a entrevista 2 (Fonte: Autor, 2023)

</center>

### 3.5 D: Decidir como lidar com as questões éticas

As questões éticas a respeito da avaliação devem ser tratadas de acordo com o que foi definido no documento de [Aspectos éticos](../../../analise_requisitos/aspectos_eticos.md) sobre pesquisa com pessoas.

Segue abaixo o termo de consentimento que será utilizado

#### <center>Termo de Consentimento Livre e Esclarecido</center>

---

Somos estudantes de Engenharia de software da Universidade de Brasília e estamos conduzindo uma pesquisa sobre o DetranGO, sitio da internet que busca oferecer serviços para a população do Goiás mas possui as mesmas funcionalidades do Detran de outros estados, como parte de nosso projeto na disciplina de Interação Humano Computador. Sua participação neste formulário é de caráter voluntário e todas as perguntas serão mantidas para fins acadêmicos e não serão compartilhados para terceiros.

Para decidir sobre o seu consentimento, é importante que você conheça as seguintes informações sobre a pesquisa:

-   Nossa equipe tem o compromisso de divulgar os resultados de nossas pesquisas para o cliente.
-   O consentimento para a participação na atividade é uma escolha livre, feita mediante a prestação de todos os esclarecimentos necessários sobre a pesquisa.
-   A atividade pode ser interrompida a qualquer momento, segundo a sua disponibilidade e vontade.
-   Será necessário gravar a atividade, e as gravações efetuadas serão divulgadas nos resultados do projeto.
-   Os dados coletados durante a atividade destinam-se estritamente a atividades de análise e elaboração de melhorias para o sistema do DetranGO.

Diante das explicações, é necessário que você esteja de acordo com a pesquisa que será realizada e concorda de livre e espontânea vontade em participar, como colaborador? Caso o participante seja menor de idade é necessária a permissão do responsável legal.

( ) Sim, estou de acordo. </br>
( ) Não estou de acordo.

### 3.6 E: Avaliar (Evaluate), interpretar e apresentar os dados

Após a execução da avaliação, os dados recolhidos deverão ser tratados e representados em um relatório final, visando afirmar e melhorar os storyboards desenvolvidos. Tal relatório deverá seguir a entrutura proposta no artefato de [planejamento do relato dos resultados da análise de tarefas](./planejamento_relato_resultados.md)[2].

## 4. Bibliografia

> [1] Artefato Aspectos éticos, acesso em 27 de maio de 2023. Para mais informações acesse: [link](../../../analise_requisitos/aspectos_eticos.md).

> [2] Artefato Planejamento do relato dos resultados da avaliação da análise de tarefas, acesso em 27 de maio de 2023. Para mais informações acesse: [link](./planejamento_relato_resultados.md).

> [3] Artefato Perfil de usuário, acesso em 27 de maio de 2023. Para mais informações acesse: [link](../../../analise_requisitos/perfilUsuario.md).

> [4] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1. Acesso em: 27 mai. 2023.

> [5] CamScanner, acesso em: 27 de maio de 2023. Para mais informações acesse: [link](https://www.camscanner.com/).

> [6] Google Meet, acesso em: 27 de maio de 2023. Para mais informações acesse: [link](https://meet.google.com/).

> [7] Lichess. Planejamento da avaliação da Análise de tarefas. Disponível em https://interacao-humano-computador.github.io/2022.2-Lichess. Acesso em 19 mai. 2023.

> [8] OBS, acesso em: 27 de maio de 2023. Para mais informações acesse: [link](https://obsproject.com/pt-br/download/).

## 5. Histórico de versão

| Versão | Data     | Descrição                                 | Autor(es) | Revisor(es) |
| ------ | -------- | ----------------------------------------- | --------- | ----------- |
| `1.0`  | 20/05/23 | Criação do documento e adição do conteúdo | Felipe M. | Carlos E.   |
| `1.1`  | 21/05/23 | Mudanças no planejamento e organização    | Felipe M. | Carlos E.   |
| `1.2`  | 16/06/23 | Alterações de padronização                | Pedro M.  | Amanda N. |
| [`1.3`](./plan_deprecated_1_3.md)  | 17/06/23 | Correções com base na [verificação](../../../verificacao/planejamentoA_tarefas.md) | Carlos E. | Pedro H. |
|  `2.0` | 02/06/23 | Alterações nas perguntas e adição de tabelas | Felipe M. | Amanda N. | 