# Análise de Tarefas - Relato dos Resultados

## 1. Introdução

A análise de tarefas é uma etapa importante no projeto de IHC, pois é uma representação que auxilia no entendimento do trabalho dos usuários do sistema, o que auxilia a equipe de desenvolvimento na avaliação e reprojeto do sistema atual.[3]

Este documento visa relatar os resultados da avaliação com usuários reais do site do [Detran GO](https://www.detran.go.gov.br/psw/#/pages/pagina-inicial) realizada acerca das análises de tarefas elaboradas para o projeto, a fim de obter validação acerca dos mesmos.

Uma outra avaliação havia sido realizada anteriormente, como marcada [neste artefato](./relato_resultados_tarefas_deprecated.md).

## 2. Objetivos da avaliação

O objetivo da avaliação realizada foi a validação dos fluxos desenvolvidos na análise de tarefas a partir das técnicas de HTA (Análise de tarefas hierárquica) e GOMS (Goals, Methods, Selection Rules, Operators), bem como a detecção e recolhimento de ideias e alternativas para o design das tarefas proposto, a fim de melhorar aquilo que já foi desenvolvido.

São listados abaixo os três objetivos principais desta avaliação, de acordo com o [planejamento](./planejamento_analise_tarefas.md) da mesma:

- 1 - Avaliar a conformidaed com um padrão;
- 2 - Identificar problemas na interação e na interface;
- 3 - Comparar ideias e alternativas de design.

## 3. Metodologia
 Para os propósitos desta avaliação foi utilizada a metodologia já descrita no artefato de [planejamento da avaliação](./planejamento_analise_tarefas.md), que delineia elementos como:

### 3.1. Aspectos éticos
Sendo uma pesquisa com a participação de pessoas, a avaliação utilizou um termo de consentimento elaborado anteriormente e presente no [artefato](../../../analise_requisitos/aspectos_eticos.md)[1] correspondente, abaixo se encontra o mesmo.

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

---

## 4. Cronograma executado e participantes
### 4.1. Participantes
Na tabela 1 se encontram os participantes do teste piloto.

<center>

| Atividade    | Participante       | Função                    | Papel    |
| ------------ | ------------------ | ------------------------- | -------- |
| Teste piloto | Felipe Mastromauro | Equipe de desenvolvimento | Testador |
| Teste piloto | Pedro Muniz        | Equipe de desenvolvimento | Testador |

Tabela 1: Participantes do teste piloto(Fonte: Autor, 2023)

</center>

Na tabela 2 se encontram os participantes da entrevista conduzida.


<center>

| Atividade    | Participante       | Função                    | Papel    |
| ------------ | ------------------ | ------------------------- | -------- |
| Entrevista | Felipe Mastromauro | Equipe de desenvolvimento | Entrevistador |
| Entrevista | Pedro Muniz        | Equipe de desenvolvimento | Relator |
| Entrevista | João Camilo de Moura        | Usuário | Entrevistado |

Tabela 2: Participantes da entrevista(Fonte: Autor, 2023)

</center>

### 4.2. Cronograma
Na tabela 3 se encontra o cronograma executado da entrevista realizada.

<center>

| Atividade | Local | Data | Horário |
|-|-|-|-|
| Teste Piloto | Remoto (Google Meet) | 03/07/2023 | 15:00 |
| Entrevista | Remoto (Google Meet) | 03/07/2023 | 17:00 |

Tabela 2: Cronograma da entrevista realizada (Fonte: Autor, 2023)

</center>

## 5. Respostas das perguntas
Visando sumarizar os dados obtidos através da avaliação, as tabelas a seguir detalham as respostas do entrevistados para as perguntas elaboradas anteriormente, discriminadas por objetivo de avaliação e por tipo de análise de tarefas.

### 5.1 Perguntas específicas para o HTA

#### 5.1.1 Avaliar a conformidade com um padrão

##### 5.1.1.1 Diagrama de Consulta de CNH

A tabela 3 lista as respostas às perguntas sobre o objetivo 1 da avaliação para o diagrama da seção 3.1 do artefato (**Consulta de CNH**)

<center>

|**Número**|**Pergunta**|**Resposta**|
|--|--|--|
| 1 | Os planos possuem como característica os subobjetivos pelos quais são compostos? | Sim |
| 2 | Os níveis mais baixos do HTA são marcados de maneira diferente dos outros? | Sim |

Tabela 3: Respostas para as perguntas elaboradas para o objetivo 1 do HTA da seção 3.1 (Fonte: Autor, 2023).

</center>

##### 5.1.1.2 Diagrama de Solicitação de CNH

A tabela 4 lista as respostas às perguntas sobre o objetivo 1 da avaliação para o diagrama da seção 3.2 do artefato (**Solicitação de CNH**)

<center>

|**Número**|**Pergunta**|**Resposta**|
|--|--|--|
| 1 | Os planos possuem como característica os subobjetivos pelos quais são compostos? | Sim |
| 2 | Os níveis mais baixos do HTA são marcados de maneira diferente dos outros? | Sim |

Tabela 4: Respostas para as perguntas elaboradas para o objetivo 1 do HTA da seção 3.2 (Fonte: Autor, 2023).

</center>

##### 5.1.1.3 Diagrama de Emissão de CRLV

A tabela 5 lista as respostas às perguntas sobre o objetivo 1 da avaliação para o diagrama da seção 3.3 do artefato (**Emissão de CRLV**)

<center>

|**Número**|**Pergunta**|**Resposta**|
|--|--|--|
| 1 | Os planos possuem como característica os subobjetivos pelos quais são compostos? | Sim |
| 2 | Os níveis mais baixos do HTA são marcados de maneira diferente dos outros? | Sim |

Tabela 5: Respostas para as perguntas elaboradas para o objetivo 1 do HTA da seção 3.3 (Fonte: Autor, 2023).

</center>

#### 5.1.2 Identificar problemas na interação e na interface

##### 5.1.2.1 Diagrama de Consulta de CNH

A tabela 6 lista as respostas às perguntas sobre o objetivo 2 da avaliação para o diagrama da seção 3.1 do artefato (**Consulta de CNH**)

<center>

| **Número** | **Pergunta** | **Resposta** |
|--|--|--|
| 1 | Os objetivos definidos são atingidos ao fim da tarefa? | Sim |
| 2 | Há operações que não auxiliam na obtenção do objetivo? Quantas? | Não |
| 3 | Todas as operações são de fácil compreensão? | Sim |
| 4 | Os planos definidos permitem um claro entendimento dos subobjetivos a serem atingidos? | Sim |

Tabela 6: Respostas para as perguntas elaboradas para o objetivo 2 do HTA da seção 3.1 (Fonte: Autor, 2023).

</center>

##### 5.1.2.2 Diagrama de Solicitação de CNH

A tabela 7 lista as respostas às perguntas sobre o objetivo 2 da avaliação para o diagrama da seção 3.2 do artefato (**Solicitação de CNH**)

<center>

| **Número** | **Pergunta** | **Resposta** |
|--|--|--|
| 1 | Os objetivos definidos são atingidos ao fim da tarefa? | Sim |
| 2 | Há operações que não auxiliam na obtenção do objetivo? Quantas? | Não |
| 3 | Todas as operações são de fácil compreensão? | Sim |
| 4 | Os planos definidos permitem um claro entendimento dos subobjetivos a serem atingidos? | Sim |

Tabela 7: Respostas para as perguntas elaboradas para o objetivo 2 do HTA da seção 3.2 (Fonte: Autor, 2023).

</center>

##### 5.1.2.3 Diagrama de Emissão de CRLV

A tabela 8 lista as respostas às perguntas sobre o objetivo 2 da avaliação para o diagrama da seção 3.3 do artefato (**Emissão de CRLV**)

<center>

| **Número** | **Pergunta** | **Resposta** |
|--|--|--|
| 1 | Os objetivos definidos são atingidos ao fim da tarefa? | Sim |
| 2 | Há operações que não auxiliam na obtenção do objetivo? Quantas? | Não |
| 3 | Todas as operações são de fácil compreensão? | Sim |
| 4 | Os planos definidos permitem um claro entendimento dos subobjetivos a serem atingidos? | Sim |

Tabela 8: Respostas para as perguntas elaboradas para o objetivo 2 do HTA da seção 3.3 (Fonte: Autor, 2023).

</center>

#### 5.1.3 Comparar ideias e alternativas de design

##### 5.1.3.1 Diagrama de Consulta de CNH

A tabela 9 lista as respostas às perguntas sobre o objetivo 3 da avaliação para o diagrama da seção 3.1 do artefato (**Consulta de CNH**)

<center>

| **Número** | **Pergunta** | **Resposta** |
|--|--|--|
| 1 | Considerando o mesmo input e mesmo feedback, é possível que a tarefa possa conter menos subobjetivos? | Não |
| 2 | Considerando o mesmo input e mesmo feedback, é possível que a tarefa possa conter menos operações? | Não |
| 3 | Considerando o mesmo input e mesmo feedback, há planos de execução sequencial que possam se tornar paralelos ou de seleção? | Não |
| 4 | Considerando o mesmo input e mesmo feedback, há planos de execução paralelos que possam se tornar sequenciais ou de seleção? | Não |
| 5 | Das alternativas apresentadas, há alguma de maior eficiência ou mais fácil aprendizado? Por quê? | - |

Tabela 9: Respostas para as perguntas elaboradas para o objetivo 3 do HTA da seção 3.1 (Fonte: Autor, 2023).

</center>

##### 5.1.3.2 Diagrama de Solicitação de CNH

A tabela 10 lista as respostas às perguntas sobre o objetivo 3 da avaliação para o diagrama da seção 3.2 do artefato (**Solicitação de CNH**)

<center>

| **Número** | **Pergunta** | **Resposta** |
|--|--|--|
| 1 | Considerando o mesmo input e mesmo feedback, é possível que a tarefa possa conter menos subobjetivos? | Não |
| 2 | Considerando o mesmo input e mesmo feedback, é possível que a tarefa possa conter menos operações? | Não |
| 3 | Considerando o mesmo input e mesmo feedback, há planos de execução sequencial que possam se tornar paralelos ou de seleção? | Sim, 1 e 3 poderiam ser paralelos |
| 4 | Considerando o mesmo input e mesmo feedback, há planos de execução paralelos que possam se tornar sequenciais ou de seleção? | Não |
| 5 | Das alternativas apresentadas, há alguma de maior eficiência ou mais fácil aprendizado? Por quê? | Transformar os planos 1 e 3 em planos paralelos a um outro plano deixaria a tarefa mais simples e rápida |

Tabela 10: Respostas para as perguntas elaboradas para o objetivo 3 do HTA da seção 3.2 (Fonte: Autor, 2023).

</center>

##### 5.1.3.3 Diagrama de Emissão de CRLV

A tabela 11 lista as respostas às perguntas sobre o objetivo 3 da avaliação para o diagrama da seção 3.3 do artefato (**Emissão de CRLV**)

<center>

| **Número** | **Pergunta** | **Resposta** |
|--|--|--|
| 1 | Considerando o mesmo input e mesmo feedback, é possível que a tarefa possa conter menos subobjetivos? | Não |
| 2 | Considerando o mesmo input e mesmo feedback, é possível que a tarefa possa conter menos operações? | Sim, as operações 2.1 e 2.2 poderiam ser a mesma operação |
| 3 | Considerando o mesmo input e mesmo feedback, há planos de execução sequencial que possam se tornar paralelos ou de seleção? | Não |
| 4 | Considerando o mesmo input e mesmo feedback, há planos de execução paralelos que possam se tornar sequenciais ou de seleção? | Não |
| 5 | Das alternativas apresentadas, há alguma de maior eficiência ou mais fácil aprendizado? Por quê? | Sim, a junção das operações faria mais sentido considerando o funcionamento dos browsers modernos e a visualização de PDF |

Tabela 11: Respostas para as perguntas elaboradas para o objetivo 2 do HTA da seção 3.3 (Fonte: Autor, 2023).

</center>

### 5.2 Perguntas específicas para o CMN-GOMS

#### 5.2.1 Avaliar a conformidade com um padrão

##### 5.2.1.1 Emissão de CRLV

A tabela 12 lista as respostas às perguntas sobre o objetivo 1 da avaliação para a análise GOMS da seção 4.1 do artefato (**Emissão de CRLV**)

<center>

| **Número** | **Pergunta** | **Resposta** |
|--|--|--|
| 1 | Os operadores são sempre executados de maneira sequencial? Onde não são? | Sim |
| 2 | As regras de seleção representam a tomada de decisão do usuário sobre qual método utilizar em determinada situação? Onde não representam? | - |
| 3 | Os operadores representam ações concretas permitidas pelo sistema? Onde não representam? | Sim |

Tabela 12: Respostas para as perguntas elaboradas para o objetivo 1 do GOMS da seção 4.1 (Fonte: Autor, 2023).

</center>

##### 5.2.1.2 Consulta de CNH

A tabela 13 lista as respostas às perguntas sobre o objetivo 1 da avaliação para a análise GOMS da seção 4.2 do artefato (**Consulta de CNH**)

<center>

| **Número** | **Pergunta** | **Resposta** |
|--|--|--|
| 1 | Os operadores são sempre executados de maneira sequencial? Onde não são? | Sim |
| 2 | As regras de seleção representam a tomada de decisão do usuário sobre qual método utilizar em determinada situação? Onde não representam? | Sim |
| 3 | Os operadores representam ações concretas permitidas pelo sistema? Onde não representam? | Sim |

Tabela 13: Respostas para as perguntas elaboradas para o objetivo 1 do GOMS da seção 4.2 (Fonte: Autor, 2023).

</center>

##### 5.2.1.3 Solicitação de CNH


A tabela 14 lista as respostas às perguntas sobre o objetivo 1 da avaliação para a análise GOMS da seção 4.3 do artefato (**Solicitação de CNH**)

<center>

| **Número** | **Pergunta** | **Resposta** |
|--|--|--|
| 1 | Os operadores são sempre executados de maneira sequencial? Onde não são? | Sim |
| 2 | As regras de seleção representam a tomada de decisão do usuário sobre qual método utilizar em determinada situação? Onde não representam? | Sim |
| 3 | Os operadores representam ações concretas permitidas pelo sistema? Onde não representam? | Sim |

Tabela 14: Respostas para as perguntas elaboradas para o objetivo 1 do GOMS da seção 4.3 (Fonte: Autor, 2023).

</center>

#### 5.2.2 Identificar problemas na interação e na interface

##### 5.2.2.1 Emissão de CRLV

A tabela 15 lista as respostas às perguntas sobre o objetivo 2 da avaliação para a análise GOMS da seção 4.1 do artefato (**Emissão de CRLV**)

<center>

| **Número** | **Pergunta** | **Resposta** |
|--|--|--|
| 1 | A tarefa representada é executável? Quais partes não são executáveis sequencialmente? | Sim |
| 2 | Cada objetivo definido dentro da tarefá é atingido? Se não, quantas vezes não são atingidos? Por quê? | Sim |
| 3 | O tamanho dos métodos para atingir um objetivo é satisfatório? Que métodos não tem o tamanho ideal? | Sim |
| 4 | Cada método e seus subelementos (regras de seleção e operadores) são compreensíveis? Quais não são? Por qual razão? | - |
| 5 | Dentro de cada objetivo, há elementos que não o suportam (isto é, não ajudam em sua obtenção)? Quantos? | Não |

Tabela 15: Respostas para as perguntas elaboradas para o objetivo 2 do GOMS da seção 4.1 (Fonte: Autor, 2023).

</center>

##### 5.2.2.2 Consulta de CNH

A tabela 16 lista as respostas às perguntas sobre o objetivo 2 da avaliação para a análise GOMS da seção 4.2 do artefato (**Consulta de CNH**)

<center>

| **Número** | **Pergunta** | **Resposta** |
|--|--|--|
| 1 | A tarefa representada é executável? Quais partes não são executáveis sequencialmente? | Sim |
| 2 | Cada objetivo definido dentro da tarefá é atingido? Se não, quantas vezes não são atingidos? Por quê? | Sim |
| 3 | O tamanho dos métodos para atingir um objetivo é satisfatório? Que métodos não tem o tamanho ideal? | Sim |
| 4 | Cada método e seus subelementos (regras de seleção e operadores) são compreensíveis? Quais não são? Por qual razão? | Sim |
| 5 | Dentro de cada objetivo, há elementos que não o suportam (isto é, não ajudam em sua obtenção)? Quantos? | Não |

Tabela 16: Respostas para as perguntas elaboradas para o objetivo 2 do GOMS da seção 4.2 (Fonte: Autor, 2023).

</center>

##### 5.2.2.3 Solicitação de CNH


A tabela 17 lista as respostas às perguntas sobre o objetivo 2 da avaliação para a análise GOMS da seção 4.3 do artefato (**Consulta de CNH**)

<center>

| **Número** | **Pergunta** | **Resposta** |
|--|--|--|
| 1 | A tarefa representada é executável? Quais partes não são executáveis sequencialmente? | Sim |
| 2 | Cada objetivo definido dentro da tarefá é atingido? Se não, quantas vezes não são atingidos? Por quê? | Sim |
| 3 | O tamanho dos métodos para atingir um objetivo é satisfatório? Que métodos não tem o tamanho ideal? | Sim |
| 4 | Cada método e seus subelementos (regras de seleção e operadores) são compreensíveis? Quais não são? Por qual razão? | Sim |
| 5 | Dentro de cada objetivo, há elementos que não o suportam (isto é, não ajudam em sua obtenção)? Quantos? | -  |

Tabela 17: Respostas para as perguntas elaboradas para o objetivo 2 do GOMS da seção 4.3 (Fonte: Autor, 2023).

</center>

#### 5.2.3 Comparar ideias e alternativas de design

##### 5.2.3.1 Emissão de CRLV

A tabela 18 lista as respostas às perguntas sobre o objetivo 3 da avaliação para a análise GOMS da seção 4.1 do artefato (**Emissão de CRLV**)

<center>

| **Número** | **Pergunta** | **Resposta** |
|--|--|--|
| 1 | Dentro dos objetivos, há métodos que podem ser alterados ou removidos? Quais? | Não |
| 2 | Há operações que podem ser alteradas ou removidas? Quais? | Não |
| 3 | Há objetivos descritos que possam ser alterados ou removidos sem dano ao objetivo principal da tarefa? Quais? | Não |
| 4 | Há regras de seleção para os métodos que podem ser alteradas ou removidas para a melhor execução dos operadores? Quais? | - |
| 5 | Das alternativas apresentadas, há alguma de maior eficiência ou mais fácil aprendizado? Por quê? | - |

Tabela 18: Respostas para as perguntas elaboradas para o objetivo 3 do GOMS da seção 4.1 (Fonte: Autor, 2023).

</center>

##### 5.2.3.2 Consulta de CNH

A tabela 19 lista as respostas às perguntas sobre o objetivo 3 da avaliação para a análise GOMS da seção 4.2 do artefato (**Consulta de CNH**)

<center>

| **Número** | **Pergunta** | **Resposta** |
|--|--|--|
| 1 | Dentro dos objetivos, há métodos que podem ser alterados ou removidos? Quais? | Não |
| 2 | Há operações que podem ser alteradas ou removidas? Quais? | Não |
| 3 | Há objetivos descritos que possam ser alterados ou removidos sem dano ao objetivo principal da tarefa? Quais? | Não |
| 4 | Há regras de seleção para os métodos que podem ser alteradas ou removidas para a melhor execução dos operadores? Quais? | Não |
| 5 | Das alternativas apresentadas, há alguma de maior eficiência ou mais fácil aprendizado? Por quê? | - |

Tabela 19: Respostas para as perguntas elaboradas para o objetivo 3 do GOMS da seção 4.2 (Fonte: Autor, 2023).

</center>

##### 5.2.3.3 Solicitação de CNH


A tabela 20 lista as respostas às perguntas sobre o objetivo 3 da avaliação para a análise GOMS da seção 4.3 do artefato (**Solicitação de CNH**)

<center>

| **Número** | **Pergunta** | **Resposta** |
|--|--|--|
| 1 | Dentro dos objetivos, há métodos que podem ser alterados ou removidos? Quais? | Não |
| 2 | Há operações que podem ser alteradas ou removidas? Quais? | Não |
| 3 | Há objetivos descritos que possam ser alterados ou removidos sem dano ao objetivo principal da tarefa? Quais? | Não |
| 4 | Há regras de seleção para os métodos que podem ser alteradas ou removidas para a melhor execução dos operadores? Quais? | Não |
| 5 | Das alternativas apresentadas, há alguma de maior eficiência ou mais fácil aprendizado? Por quê? | - |

Tabela 20: Respostas para as perguntas elaboradas para o objetivo 3 do GOMS da seção 4.2 (Fonte: Autor, 2023).

</center>


## 6. Gravações

Abaixo se encontram as gravações do teste piloto, assim como das entrevistas realizadas com usuários.

### 6.1 Teste piloto

O vídeo 1 contém a gravação do teste piloto da entrevista, publicada como vídeo não listado no YouTube.

<center>

Vídeo 1: Teste piloto da entrevista (Fonte: Autor, 2023)

</center>

### 6.2 Entrevista

O vídeo 2 contém a gravação da entrevista, publicada como vídeo não listado no YouTube.

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/CutTJJi8wjs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Vídeo 2: Teste piloto da entrevista (Fonte: Autor, 2023)

</center>

## 7 Análise dos dados coletados

### 7.1 Dados coletados

Os dados obtidos a partir da entrevista realizada mostram que não há problemas graves nas tarefas do sistema representadas. No entanto, é possível se considerar alternativas para a implementação de duas das três tarefas a fim de garantir maior rapidez e compatibilidade com os browsers modernos.

### 7.2 Problemas Encontrados

Não foram identificados problemas de grande nota nos fluxos de tarefa apresentados na entrevista com o usuário. No entanto, foram apontadas as possibilidades para o remanejamento de operações no diagrama de emissão de CRLV para garantir a compatibilidade com os browsers modernos e evitar a sobreposição de funcionalidades, bem como a paralelização de planos relacionados à entrada de dados pessoais e de CFC desejado no diagrama de solicitação de CNH a fim de acelerar a tarefa emquestão.

## 8. Correções possíveis
A partir dos dados coletados através da entrevista, não foram encontrados problemas na análise tarefas elaborada, portanto não há necessidade de correções quanto aos diagramas. Contudo, ha'de se considerar as alternativas apontadas, como:

- Mudaças nas operações de download e visualização de CRLV;
- Paralelização dos planos de dados pessoais e de CFC.

## 9. Conclusão


## 10. Histórico de versão
| Versão | Data     | Descrição                                 | Autor(es) | Revisor(es) |
| ------ | -------- | ----------------------------------------- | --------- | ----------- |
| `1.0`  | 28/05/23 | Criação do documento e adição do conteúdo | Amanda N. e João M. | Pedro H.   |
| `1.1`  | 29/05/23 | Adição da gravação da entrevista e das respostas | Amanda N. e João M. | Pedro H.   |
| `1.2`  | 18/06/23 | Alterações de padronização | Pedro M. | Amanda N. |
| [`1.3`](./relato_resultados_tarefas_deprecated.md)  | 19/06/23 | Correções com base na [verificação](../../../verificacao/relato_tarefas.md) | Carlos E. | Pedro H. |
| `2.0`  | 04/07/23 | Reescrita do artefato | Felipe M. | Pedro M. |

