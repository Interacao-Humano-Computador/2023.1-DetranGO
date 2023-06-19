# Protótipo de papel - Relato dos resultados

## 1. Introdução
A prototipação é uma técnica amplamente difundida e importante no desenvolvimento de um software, pois auxilia na transmissão de ideias de design e conceitos entre os _stakeholders_ e a equipe de desenvolvimento. Neste quesito, o protótipo de papel se mantém afastado de um design específico, buscando a passagem de conceitos e ideias criadas pela equipe de desenvolvimento, procurando uma validação das mesmas pelos usuários do sistema[3].

Este documento possui a função de relatar os resultados obtidos a partir da avaliação do protótipo de papel elaborado realizada em conjunto com usuários reais do sistema do [Detran de Goiás](https://www.detran.go.gov.br/psw/#/pages/pagina-inicial)[4], buscando uma validação dos mesmos para o protótipo.

## 2. Objetivo
O objetivo da avaliação realizada foi a validação dos fluxos desenvolvidos no protótipo de papel elaborado, além de encontrar problemas e recolher ideias e alternativas propostas pelos entrevistados, visando a melhoria no que foi desenvolvido até então. Buscando encontrar problemas relacionados à usabilidade do sistema, como:

- Problemas de interação e design
- Conformidade com um padrão
- Ideias e alternativas de design

## 3. Metodologia
Para a avaliação, forma utilizadas a metodologia proposta no artefato de [planejamento](./planejamentoAvaliacao.md)[2] da mesma, contendo os elementos:

### 3.1 Aspectos éticos
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
Na tabela 1 abaixo se encontram descritos os participantes do teste piloto.

<center>

| Atividade    | Participante       | Função                    | Papel    |
| ------------ | ------------------ | ------------------------- | -------- |
| Teste piloto | Felipe Mastromauro | Equipe de desenvolvimento | Testador |
| Teste piloto | Pedro Muniz        | Equipe de desenvolvimento | Testador |

Tabela 1: Participantes do teste piloto(Fonte: Autor, 2023)

</center>

Na tabela 2 abaixo se encontram descritos os participantes da entrevista 1.

<center>

| Atividade    | Participante       | Função                    | Papel         |
| ------------ | ------------------ | ------------------------- | ------------- |
| Entrevista 1 | Felipe Mastromauro | Equipe de desenvolvimento | Entrevistador |
| Entrevista 1 | Pedro Muniz        | Equipe de desenvolvimento | Relator       |
| Entrevista 1 | Douglas Langkammer | Usuário do sistema        | Entrevistado  |

Tabela 2: Participantes da entrevista 1(Fonte: Autor, 2023)

</center>

Na tabela 3 abaixo se encontram descritos os participantes da entrevista 2.

<center>

| Atividade    | Participante       | Função                    | Papel         |
| ------------ | ------------------ | ------------------------- | ------------- |
| Entrevista 2 | Felipe Mastromauro | Equipe de desenvolvimento | Entrevistador |
| Entrevista 2 | Pedro Muniz        | Equipe de desenvolvimento | Relator       |
| Entrevista 2 | João Camillo       | Usuário do sistema        | Entrevistado  |

Tabela 3: Participantes da entrevista 2(Fonte: Autor, 2023)

</center>

Na tabela 4 abaixo se encontram descritos os participantes da entrevista 3.

<center>

| Atividade    | Participante       | Função                    | Papel         |
| ------------ | ------------------ | ------------------------- | ------------- |
| Entrevista 3 | Pedro Muniz | Equipe de desenvolvimento | Entrevistador |
| Entrevista 3 | Felipe Mastromauro | Equipe de desenvolvimento | Relator       |
| Entrevista 3 | Welder Fernandes     | Usuário do sistema        | Entrevistado  |

Tabela 4: Participantes da entrevista 3(Fonte: Autor, 2023)

</center>

### 4.2 Cronograma

Na tabela 5 estão detalhados os cronogramas das atividades realizadas.

| Atividade    | Local                | Data       | Horário |
| ------------ | -------------------- | ---------- | ------- |
| Teste piloto | Remoto (Google Meet) | 16/06/2023 | 20:00   |
| Entrevista 1 | Remoto (Google Meet) | 18/06/2023 | 16:30   |
| Entrevista 2 | Remoto (Google Meet) | 18/06/2023 | 17:30   |
| Entrevista 3 | Remoto (Google Meet) | 19/06/2023 | 14:00   |

Tabela 9: Cronograma para as entrevistas(Fonte: Autor, 2023)

## 5. Protótipos desenvolvidos
Para o protótipo de papel, foram elaborados três fluxos de atividade presentes no site do Detran do Goiás, tais fluxos foram excolhidos com base na importância e frequência que são utilizadas pelos usuários, os fluxos são:

- A consulta de CNH pelo site do [DetranGO](https://www.detran.go.gov.br/psw/#/pages/pagina-inicial)[4]
- A solicitação de CNH pelo site do [DetranGO](https://www.detran.go.gov.br/psw/#/pages/pagina-inicial)[4]
- A emissão de CRLV pelo site do [DetranGO](https://www.detran.go.gov.br/psw/#/pages/pagina-inicial)[4]

Nas imagens abaixo se encontram os protótipos elaborados para cada fluxo representado.

### 5.1 Consulta de CNH
![consultacnh1](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/c2e3e70b-bb64-4c47-bf41-370a17d17df8)

Figura 1: Consulta CNH 1 - passo 1 (Fonte: Autor, 2023)

![consultacnh2](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/05172323-36db-4836-b4c9-6b5ba05ba8ee)

Figura 2: Consulta CNH 2 - passo 2 (Fonte: Autor, 2023)

![consultacnh3](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/ab72eaef-647c-444c-93db-79e0160cd694)

Figura 3: Consulta CNH 3 - passo 3 (Fonte: Autor, 2023)

![consultacnh4](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/a8ad0d4d-fa53-4c64-87a7-2687acffaae4)

Figura 4: Consulta CNH 4 - passo 4 (Fonte: Autor, 2023)

![consultacnh5](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/5d9e62b9-b01e-407e-933a-2d3daadddfc5)

Figura 5: Consulta CNH 5 - passo 5 (Fonte: Autor, 2023)

![Consultacnh6](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/e6ed37bf-5db7-4e7f-8a29-3adca91d80cb)

Figura 6: Consulta CNH 6 - passo 6 (Fonte: Autor, 2023)

### 5.2 Solicitação de CNH
![solicitaçãocnh1](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/4bd0f04c-d6f8-4d93-a574-1bee3236ddb7)

Figura 7: Solicitação de CNH 1 - passo 1 (Fonte: Autor, 2023)

![solicitaçãocnh2](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/171cd408-a8ab-4462-a68a-cfbc1ad2f105)

Figura 8: Solicitação de CNH 2 - passo 2 (Fonte: Autor, 2023)

![solicitaçãocnh3](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/9a2c7ae6-9306-436d-a6e8-aa990abf2b6a)

Figura 9: Solicitação de CNH 3 - passo 3 (Fonte: Autor, 2023)

![solicitaçãocnh4](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/209f8d5c-5777-403e-95e6-e0ee6c1c9cac)

Figura 10: Solicitação de CNH - passo 4 (Fonte: Autor, 2023)

![solicitaçãocnh5](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/bb99a42f-230e-4286-bf8b-10265b91b9d6)

Figura 11: Solicitação de CNH - passo 5 (Fonte: Autor, 2023)

### 5.3 Emissão de CRLV
![solicitarcrlv1](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/252c3f96-4e51-42bf-9e17-79c896beac11)

Figura 12: Solicitação de CRLV - passo 1 (Fonte: Autor, 2023)

![solicitarcrlv2](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/2ff23c0b-7be4-4361-845a-216b47d422a4)

Figura 13: Solicitação de CRLV - passo 2 (Fonte: Autor, 2023)

![solicitarcrlv3](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/c3c4bd83-133c-41df-97b7-7c5eda40995a)

Figura 14: Solicitação de CRLV - passo 3 (Fonte: Autor, 2023)

![solicitarcrlv4](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/acb76602-5114-4dc8-ae97-0a64761dcfe7)

Figura 15: Solicitação de CRLV - passo 4 (Fonte: Autor, 2023)

![solicitarcrlv5](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/53289c39-1a9a-4b06-aea2-4e0ca43a67f7)

Figura 16: Solicitação de CRLV - passo 5 (Fonte: Autor, 2023)

![solicitarcrlv6](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/0fa860f1-6c1f-4972-8e5c-210c87f6afa4)

Figura 17: Solicitação de CRLV - passo 6 (Fonte: Autor, 2023)

![solicitarcrlv7](https://github.com/Interacao-Humano-Computador/2023.1-DetranGO/assets/58089751/de384935-6f98-491f-ac93-2952afdb547c)

Figura 18: Solicitação de CRLV - passo 2 (Fonte: Autor, 2023)

## 6. Respostas das perguntas
Visando sumarizar os dados obtidos através da avaliação, as tabelas a seguir detalham as respostas do entrevistado para as perguntas elaboradas anteriormente, discriminadas por objetivo de avaliação. Para cada protótipo desenvolvido, foram feitas todas as perguntas elaboradas anteriormente.

### 6.1 Entrevista 1

Abaixo estão descritos os dados coletados através da entrevista 1.

#### 6.1.1 Consulta de CNH

Abaixo se encontram as respostas do entrevistado para as perguntas acerca do protótipo de consulta de CNH.

##### 6.1.1.1 Problemas de interação e design

<center>

| Número | Pergunta                                             | Resposta                             |
|--------|------------------------------------------------------|--------------------------------------|
| 1      | Você conseguiu operar o sistema?                     | Sim                                  |
| 2      | Você conseguiu atingir o objetivo proposto?          | Sim                                  |
| 3      | Por que você não conseguiu atingir o objetivo?       | -                                    |
| 4      | Alguma parte da interface te deixou insatisfeito?    | Sim                                  |
| 5      | Qual parte da interface te deixou insatisfeito?      | Botão de download de consulta em PDF |
| 6      | Você entende a função de cada elemento da interface? | Sim                                  |
| 7      | Quais elementos você teve dificuldade de entender?   | -                                    |

Tabela 10: Respostas para as perguntas elaboradas para o objetivo 1 do protótipo de consulta de CNH na entrevista 1(Fonte: Autor, 2023).

</center>

##### 6.1.1.2 Conformidade com um padrão

<center>

| Número | Pergunta                                                                 | Resposta |
|--------|--------------------------------------------------------------------------|----------|
| 1      | As interfaces apresentadas seguem um padrão único?                       | Não      |
| 2      | O padrão apresentado remete a padrões utilizados em outros sites da Web? | Sim      |

Tabela 11: Respostas para as perguntas elaboradas para o objetivo 2 do protótipo de consulta de CNH na entrevista 1(Fonte: Autor, 2023).

</center>

##### 6.1.1.3 Ideias e alternativas de design

<center>

| Número | Pergunta                                                                                        | Resposta                                                                      |
|--------|-------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------|
| 1      | Você considera o fluxo realizado eficiente?                                                     | Não                                                                           |
| 2      | Você possui alguma anternativa para a implementação deste fluxo ou das interfaces apresentadas? | Sim                                                                           |
| 3      | Quais alternativas você propõe?                                                                 | Manter o padrão consistente; botão para visualizar o PDF e outro para baixar. |


Tabela 12: Respostas para as perguntas elaboradas para o objetivo 3 do protótipo de consulta de CNH na entrevista 1(Fonte: Autor, 2023).

</center>

#### 6.1.2 Solicitação de CNH

Abaixo se encontram as respostas do entrevistado para as perguntas acerca do protótipo de solicitação de CNH.

##### 6.1.2.1 Problemas de interação e design

<center>

| Número | Pergunta                                             | Resposta |
|--------|------------------------------------------------------|----------|
| 1      | Você conseguiu operar o sistema?                     | Sim      |
| 2      | Você conseguiu atingir o objetivo proposto?          | Sim      |
| 3      | Por que você não conseguiu atingir o objetivo?       | -        |
| 4      | Alguma parte da interface te deixou insatisfeito?    | Não      |
| 5      | Qual parte da interface te deixou insatisfeito?      | -        |
| 6      | Você entende a função de cada elemento da interface? | Não      |
| 7      | Quais elementos você teve dificuldade de entender?   | -        |

Tabela 13: Respostas para as perguntas elaboradas para o objetivo 1 do protótipo de solicitação de CNH na entrevista 1(Fonte: Autor, 2023).

</center>

##### 6.1.2.2 Conformidade com um padrão

<center>

| Número | Pergunta                                                                 | Resposta |
|--------|--------------------------------------------------------------------------|----------|
| 1      | As interfaces apresentadas seguem um padrão único?                       | Sim      |
| 2      | O padrão apresentado remete a padrões utilizados em outros sites da Web? | Sim      |

Tabela 14: Respostas para as perguntas elaboradas para o objetivo 2 do protótipo de solicitação de CNH na entrevista 1(Fonte: Autor, 2023).

</center>

##### 6.1.2.3 Ideias e alternativas de design

<center>

| Número | Pergunta                                                                                        | Resposta                    |
|--------|-------------------------------------------------------------------------------------------------|-----------------------------|
| 1      | Você considera o fluxo realizado eficiente?                                                     | Sim                         |
| 2      | Você possui alguma anternativa para a implementação deste fluxo ou das interfaces apresentadas? | Sim                         |
| 3      | Quais alternativas você propõe?                                                                 | Mostrar localidade dos CFCs |

Tabela 15: Respostas para as perguntas elaboradas para o objetivo 3 do protótipo de solicitação de CNH na entrevista 1(Fonte: Autor, 2023).

</center>

#### 6.1.3 Emissão de CRLV

Abaixo se encontram as respostas do entrevistado para as perguntas acerca do protótipo de emissão de CRLV.

##### 6.1.3.1 Problemas de interação e design

<center>

| Número | Pergunta                                             | Resposta           |
|--------|------------------------------------------------------|--------------------|
| 1      | Você conseguiu operar o sistema?                     | Sim                |
| 2      | Você conseguiu atingir o objetivo proposto?          | Sim                |
| 3      | Por que você não conseguiu atingir o objetivo?       | -                  |
| 4      | Alguma parte da interface te deixou insatisfeito?    | Sim                |
| 5      | Qual parte da interface te deixou insatisfeito?      | Página de download |
| 6      | Você entende a função de cada elemento da interface? | Sim                |
| 7      | Quais elementos você teve dificuldade de entender?   | -                  |


Tabela 16: Respostas para as perguntas elaboradas para o objetivo 1 do protótipo de emissão de CRLV na entrevista 1(Fonte: Autor, 2023).

</center>

##### 6.1.3.2 Conformidade com um padrão

<center>

| Número | Pergunta                                                                 | Resposta |
|--------|--------------------------------------------------------------------------|----------|
| 1      | As interfaces apresentadas seguem um padrão único?                       | Sim      |
| 2      | O padrão apresentado remete a padrões utilizados em outros sites da Web? | Não      |


Tabela 17: Respostas para as perguntas elaboradas para o objetivo 2 do protótipo de emissão de CRLV na entrevista 1(Fonte: Autor, 2023).

</center>

##### 6.1.3.3 Ideias e alternativas de design

<center>

| Número | Pergunta                                                                                        | Resposta                                                  |
|--------|-------------------------------------------------------------------------------------------------|-----------------------------------------------------------|
| 1      | Você considera o fluxo realizado eficiente?                                                     | Sim                                                       |
| 2      | Você possui alguma anternativa para a implementação deste fluxo ou das interfaces apresentadas? | Sim                                                       |
| 3      | Quais alternativas você propõe?                                                                 | Adicionar indicador visual de que o download foi iniciado |


Tabela 18: Respostas para as perguntas elaboradas para o objetivo 3 do protótipo de emissão de CRLV na entrevista 1(Fonte: Autor, 2023).

</center>


### 6.2 Entrevista 2

Abaixo estão descritos os dados coletados através da entrevista 2.

#### 6.2.1 Consulta de CNH

Abaixo se encontram as respostas do entrevistado para as perguntas acerca do protótipo de consulta de CNH.

##### 6.2.1.1 Problemas de interação e design

<center>

| Número | Pergunta                                             | Resposta                |
|--------|------------------------------------------------------|-------------------------|
| 1      | Você conseguiu operar o sistema?                     | Sim                     |
| 2      | Você conseguiu atingir o objetivo proposto?          | Sim                     |
| 3      | Por que você não conseguiu atingir o objetivo?       | -                       |
| 4      | Alguma parte da interface te deixou insatisfeito?    | Sim                     |
| 5      | Qual parte da interface te deixou insatisfeito?      | Botão de página inicial |
| 6      | Você entende a função de cada elemento da interface? | Sim                     |
| 7      | Quais elementos você teve dificuldade de entender?   | -                       |


Tabela 19: Respostas para as perguntas elaboradas para o objetivo 1 do protótipo de consulta de CNH na entrevista 2(Fonte: Autor, 2023).

</center>

##### 6.2.1.2 Conformidade com um padrão

<center>

| Número | Pergunta                                                                 | Resposta |
|--------|--------------------------------------------------------------------------|----------|
| 1      | As interfaces apresentadas seguem um padrão único?                       | Sim      |
| 2      | O padrão apresentado remete a padrões utilizados em outros sites da Web? | Sim      |


Tabela 20: Respostas para as perguntas elaboradas para o objetivo 2 do protótipo de consulta de CNH na entrevista 2(Fonte: Autor, 2023).

</center>

##### 6.2.1.3 Ideias e alternativas de design

<center>

| Número | Pergunta                                                                                        | Resposta                                     |
|--------|-------------------------------------------------------------------------------------------------|----------------------------------------------|
| 1      | Você considera o fluxo realizado eficiente?                                                     | Sim                                          |
| 2      | Você possui alguma anternativa para a implementação deste fluxo ou das interfaces apresentadas? | Sim                                          |
| 3      | Quais alternativas você propõe?                                                                 | Mudaria a posição do botão de página inicial |


Tabela 21: Respostas para as perguntas elaboradas para o objetivo 3 do protótipo de consulta de CNH na entrevista 2(Fonte: Autor, 2023).

</center>

#### 6.2.2 Solicitação de CNH

Abaixo se encontram as respostas do entrevistado para as perguntas acerca do protótipo de solicitação de CNH.

##### 6.2.2.1 Problemas de interação e design

<center>

| Número | Pergunta                                             | Resposta |
|--------|------------------------------------------------------|----------|
| 1      | Você conseguiu operar o sistema?                     | Sim      |
| 2      | Você conseguiu atingir o objetivo proposto?          | Sim      |
| 3      | Por que você não conseguiu atingir o objetivo?       | -        |
| 4      | Alguma parte da interface te deixou insatisfeito?    | Não      |
| 5      | Qual parte da interface te deixou insatisfeito?      | -        |
| 6      | Você entende a função de cada elemento da interface? | Sim      |
| 7      | Quais elementos você teve dificuldade de entender?   | -        |


Tabela 22: Respostas para as perguntas elaboradas para o objetivo 1 do protótipo de solicitação de CNH na entrevista 2(Fonte: Autor, 2023).

</center>

##### 6.2.2.2 Conformidade com um padrão

<center>

| Número | Pergunta                                                                 | Resposta |
|--------|--------------------------------------------------------------------------|----------|
| 1      | As interfaces apresentadas seguem um padrão único?                       | Sim      |
| 2      | O padrão apresentado remete a padrões utilizados em outros sites da Web? | Sim      |


Tabela 23: Respostas para as perguntas elaboradas para o objetivo 2 do protótipo de solicitação de CNH na entrevista 2(Fonte: Autor, 2023).

</center>

##### 6.2.2.3 Ideias e alternativas de design

<center>

| Número | Pergunta                                                                                        | Resposta |
|--------|-------------------------------------------------------------------------------------------------|----------|
| 1      | Você considera o fluxo realizado eficiente?                                                     | Sim      |
| 2      | Você possui alguma anternativa para a implementação deste fluxo ou das interfaces apresentadas? | Não      |
| 3      | Quais alternativas você propõe?                                                                 | -        |


Tabela 24: Respostas para as perguntas elaboradas para o objetivo 3 do protótipo de solicitação de CNH na entrevista 2(Fonte: Autor, 2023).

</center>

#### 6.2.3 Emissão de CRLV

Abaixo se encontram as respostas do entrevistado para as perguntas acerca do protótipo de emissão de CRLV.

##### 6.2.3.1 Problemas de interação e design

<center>

| Número | Pergunta                                             | Resposta |
|--------|------------------------------------------------------|----------|
| 1      | Você conseguiu operar o sistema?                     | Sim      |
| 2      | Você conseguiu atingir o objetivo proposto?          | Sim      |
| 3      | Por que você não conseguiu atingir o objetivo?       | -        |
| 4      | Alguma parte da interface te deixou insatisfeito?    | Não      |
| 5      | Qual parte da interface te deixou insatisfeito?      | -        |
| 6      | Você entende a função de cada elemento da interface? | Sim      |
| 7      | Quais elementos você teve dificuldade de entender?   | -        |


Tabela 25: Respostas para as perguntas elaboradas para o objetivo 1 do protótipo de emissão de CRLV na entrevista 2(Fonte: Autor, 2023).

</center>

##### 6.2.3.2 Conformidade com um padrão

<center>

| Número | Pergunta                                                                 | Resposta |
|--------|--------------------------------------------------------------------------|----------|
| 1      | As interfaces apresentadas seguem um padrão único?                       | Sim      |
| 2      | O padrão apresentado remete a padrões utilizados em outros sites da Web? | Sim      |


Tabela 26: Respostas para as perguntas elaboradas para o objetivo 2 do protótipo de emissão de CRLV na entrevista 2(Fonte: Autor, 2023).

</center>

##### 6.2.3.3 Ideias e alternativas de design

<center>

| Número | Pergunta                                                                                        | Resposta |
|--------|-------------------------------------------------------------------------------------------------|----------|
| 1      | Você considera o fluxo realizado eficiente?                                                     | Sim      |
| 2      | Você possui alguma anternativa para a implementação deste fluxo ou das interfaces apresentadas? | Não      |
| 3      | Quais alternativas você propõe?                                                                 | -        |


Tabela 27: Respostas para as perguntas elaboradas para o objetivo 3 do protótipo de emissão de CRLV na entrevista 2(Fonte: Autor, 2023).

</center>

### 6.3 Entrevista 3

Abaixo estão descritos os dados coletados através da entrevista 3.

#### 6.3.1 Consulta de CNH

Abaixo se encontram as respostas do entrevistado para as perguntas acerca do protótipo de consulta de CNH.

##### 6.3.1.1 Problemas de interação e design

<center>

| Número | Pergunta                                             | Resposta |
|--------|------------------------------------------------------|----------|
| 1      | Você conseguiu operar o sistema?                     | Sim      |
| 2      | Você conseguiu atingir o objetivo proposto?          | Sim      |
| 3      | Por que você não conseguiu atingir o objetivo?       |          |
| 4      | Alguma parte da interface te deixou insatisfeito?    | Não      |
| 5      | Qual parte da interface te deixou insatisfeito?      |          |
| 6      | Você entende a função de cada elemento da interface? | Sim      |
| 7      | Quais elementos você teve dificuldade de entender?   |


Tabela 19: Respostas para as perguntas elaboradas para o objetivo 1 do protótipo de consulta de CNH na entrevista 3(Fonte: Autor, 2023).

</center>

##### 6.3.1.2 Conformidade com um padrão

<center>

| Número | Pergunta                                                                 | Resposta |
|--------|--------------------------------------------------------------------------|----------|
| 1      | As interfaces apresentadas seguem um padrão único?                       | Sim      |
| 2      | O padrão apresentado remete a padrões utilizados em outros sites da Web? | Sim      |


Tabela 20: Respostas para as perguntas elaboradas para o objetivo 2 do protótipo de consulta de CNH na entrevista 3(Fonte: Autor, 2023).

</center>

##### 6.3.1.3 Ideias e alternativas de design

<center>

| Número | Pergunta                                                                                        | Resposta                                                                                                      |
|--------|-------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| 1      | Você considera o fluxo realizado eficiente?                                                     | Sim                                                                                                           |
| 2      | Você possui alguma anternativa para a implementação deste fluxo ou das interfaces apresentadas? |  Sim                                                                                                          |
| 3      | Quais alternativas você propõe?                                                                 | Informações da CNH de um lado, baixar consulta do outro, Deixar o botão para baixar a consulta mais acessível |


Tabela 21: Respostas para as perguntas elaboradas para o objetivo 3 do protótipo de consulta de CNH na entrevista 3(Fonte: Autor, 2023).

</center>

#### 6.3.2 Solicitação de CNH

Abaixo se encontram as respostas do entrevistado para as perguntas acerca do protótipo de solicitação de CNH.

##### 6.3.2.1 Problemas de interação e design

<center>

| Número | Pergunta                                             | Resposta |
|--------|------------------------------------------------------|----------|
| 1      | Você conseguiu operar o sistema?                     | Sim      |
| 2      | Você conseguiu atingir o objetivo proposto?          | Sim      |
| 3      | Por que você não conseguiu atingir o objetivo?       |          |
| 4      | Alguma parte da interface te deixou insatisfeito?    | Não      |
| 5      | Qual parte da interface te deixou insatisfeito?      |          |
| 6      | Você entende a função de cada elemento da interface? | Sim      |
| 7      | Quais elementos você teve dificuldade de entender?   |


Tabela 22: Respostas para as perguntas elaboradas para o objetivo 1 do protótipo de solicitação de CNH na entrevista 3(Fonte: Autor, 2023).

</center>

##### 6.3.2.2 Conformidade com um padrão

<center>

| Número | Pergunta                                                                 | Resposta |
|--------|--------------------------------------------------------------------------|----------|
| 1      | As interfaces apresentadas seguem um padrão único?                       | Sim      |
| 2      | O padrão apresentado remete a padrões utilizados em outros sites da Web? | Sim      |


Tabela 23: Respostas para as perguntas elaboradas para o objetivo 2 do protótipo de solicitação de CNH na entrevista 3(Fonte: Autor, 2023).

</center>

##### 6.3.2.3 Ideias e alternativas de design

<center>

| Número | Pergunta                                                                                        | Resposta |
|--------|-------------------------------------------------------------------------------------------------|----------|
| 1      | Você considera o fluxo realizado eficiente?                                                     | Sim      |
| 2      | Você possui alguma anternativa para a implementação deste fluxo ou das interfaces apresentadas? | Não      |
| 3      | Quais alternativas você propõe?                                                                 |


Tabela 24: Respostas para as perguntas elaboradas para o objetivo 3 do protótipo de solicitação de CNH na entrevista 3(Fonte: Autor, 2023).

</center>

#### 6.3.3 Emissão de CRLV

Abaixo se encontram as respostas do entrevistado para as perguntas acerca do protótipo de emissão de CRLV.

##### 6.3.3.1 Problemas de interação e design

<center>

| Número | Pergunta                                             | Resposta                          |
|--------|------------------------------------------------------|-----------------------------------|
| 1      | Você conseguiu operar o sistema?                     | sim                               |
| 2      | Você conseguiu atingir o objetivo proposto?          | sim                               |
| 3      | Por que você não conseguiu atingir o objetivo?       |                                   |
| 4      | Alguma parte da interface te deixou insatisfeito?    | sim                               |
| 5      | Qual parte da interface te deixou insatisfeito?      | duplicidade de inserção confundiu |
| 6      | Você entende a função de cada elemento da interface? | sim                               |
| 7      | Quais elementos você teve dificuldade de entender?   |


Tabela 25: Respostas para as perguntas elaboradas para o objetivo 1 do protótipo de emissão de CRLV na entrevista 3(Fonte: Autor, 2023).

</center>

##### 6.3.3.2 Conformidade com um padrão

<center>

| Número | Pergunta                                                                 | Resposta |
|--------|--------------------------------------------------------------------------|----------|
| 1      | As interfaces apresentadas seguem um padrão único?                       | sim      |
| 2      | O padrão apresentado remete a padrões utilizados em outros sites da Web? | sim      |


Tabela 26: Respostas para as perguntas elaboradas para o objetivo 2 do protótipo de emissão de CRLV na entrevista 3(Fonte: Autor, 2023).

</center>

##### 6.3.3.3 Ideias e alternativas de design

<center>

| Número | Pergunta                                                                                        | Resposta                                                           |
|--------|-------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|
| 1      | Você considera o fluxo realizado eficiente?                                                     | sim                                                                |
| 2      | Você possui alguma anternativa para a implementação deste fluxo ou das interfaces apresentadas? | não                                                                |
| 3      | Quais alternativas você propõe?                                                                 | Mudar a inserção dupla de dados e a localização do download de PDF |


Tabela 27: Respostas para as perguntas elaboradas para o objetivo 3 do protótipo de emissão de CRLV na entrevista 3(Fonte: Autor, 2023).

</center>

## 7. Gravações
Abaixo se encontram as gravações do teste piloto, assim como das entrevistas realizadas com usuários.

### 7.1 Teste Piloto
A reunião ocorreu presencialmente, onde foi gravada e disponibilizada no YouTube como vídeo não listado.
A gravação está disponível abaixo.

<iframe width="560" height="315" src="https://www.youtube.com/embed/KE6pVFEqk0g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### 7.2 Entrevista 1
A reunião ocorreu remotamente, onde foi gravada e disponibilizada no YouTube como vídeo não listado.
A gravação está disponível abaixo.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/P3izOCZlpfo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### 7.3 Entrevista 2
A reunião ocorreu remotamente, onde foi gravada e disponibilizada no YouTube como vídeo não listado.
A gravação está disponível abaixo.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/_RfjARvVgQM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


### 7.4 Entrevista 3
A reunião ocorreu remotamente, onde foi gravada e disponibilizada no YouTube como vídeo não listado.
A gravação está disponível abaixo.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/tU17VitLDdg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


## 8. Análise dos dados coletados
Foram encontrados alguns pontos de melhoria no protótipo desenvolvido, como a clareza de algumas informações, além de alternativas mais interativas de design.

## 9. Correções possíveis
São necessárias as correções:

- Maior clareza na escolha de CFC, foi observado certa confusão sobre o que seria um CFC.
- Adição de um indicador de localidade dos CFCs na tela de escolha.
- Maior clareza na exibição das informações da CNH.
- Alteração do posicionamento do botão de download de PDF da consulta de CNH.
- Criação de um botão para visualização das informações da CNH via PDF.
- Maior clareza nas informações de download do CRLV emitido.

## 10. Conclusão
Após a análise dos dados, pode-se concluir que os objetivos da avaliação foram totalmente concluídos, quanto aos objetivos do protótipo, pode-se afirmar que o mesmo cumpriu quase que totalmente suas metas, pecando apenas em alguns pontos de padronização e representação de dados.


## 11. Referências Biliográficas

> [1] Artefato Aspectos éticos, acesso em 11 de junho de 2023. Para mais informações acesse: [link](../../../analise_requisitos/aspectos_eticos.md).

> [2] Artefato Planejamento do relato dos resultados da avaliação do protótipo de papel, acesso em 11 de junho de 2023. Para mais informações acesse: [link](./planejamentoRelatoResultados.md).

> [3] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1. Acesso em: 27 mai. 2023.


## 12. Histórico de versão

| Versão | Data       | Descrição            | Autor(es)   | Revisor(es)    |
|--------|------------|----------------------|-------------|----------------|
| `1.0`  | 11/06/2023 | Estruturação e adição do conteúdo até seção 6 | Pedro M. | Carlos E. |
| [`1.1`](relatoResultadosv1.md)  | 11/06/2023 | Adição de dados obtidos através da entrevista realizada | Amanda N. | Carlos E. |
| `2.0`  | 19/06/2023 | Refeitura da avaliação e relato | Pedro M. | Amanda N. | 
