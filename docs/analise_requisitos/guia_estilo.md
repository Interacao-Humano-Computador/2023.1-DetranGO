# Guia de Estilo

## 1. Introdução
O guia de estilo reúne as diretrizes e princípios utilizados no projeto e registra as principais decisões de design tomadas. Isso é feito com o intuito de evitar a perda dessas informações e permitir que elas sejam facilmente acessíveis para serem implementadas no produto final e reutilizadas durante as etapas de extensão do projeto. Esse documento também pode ser usado para facilitar a comunicação entre a equipe de design e a equipe de desenvolvimento. Neste caso, as diretrizes serão aplicadas ao sítio eletrônico DetranGO, levando em consideração as [Metas de Usabilidade](#) do ciclo de vida para engenharia de usabilidade de Mayhew [1].

## 2. Objetivo
O objetivo desse documento é compreender o design proposto para o projeto, analisando elementos como:

- Elementos de interface (Design de telas, visualização de informações, disposição espacial e grid (layout), elementos de interface (widgets), janelas, tipografia, símbolos, logo e cores)

- Elementos de interação (estilos de interação, seleção de um estilo e aceleradores (teclas de atalho))

- Elementos de ação (preenchimento de campos, seleção e ativação) com o intuito de documentá-los e com esse entendimento propor melhorias para alguns elementos. Para que no futuro seja possível dar prosseguimento ao projeto nas etapas de design, avaliação e desenvolvimento.

### 2.1 Organização e conteúdo do guia de estilo
O guia de estilo seguirá a estrutura comum adotada por Mayhew, na seguinte organização:

- **Introdução**
    * Objetivo
    * Organização e Conteúdo
    * Público-alvo
    * Como Utilizar e Manter o Guia de Estilo
- **Análise do Ambiente de Trabalho**
- **Elementos de Interface**
    * Janelas
    * Tipografia
    * Cores
- **Elementos de Interação**
    * Estilos de Interação
    * Seleção de Estilos
    * Aceleradores (teclas de atalho)
- **Elementos de Ação**
    * Preenchimento de Campos
    * Seleção
    * Ativação
- **Vocabulário e Padrões**
    * Terminologia
    * Sequência de Diálogos

### 2.2 Público-alvo do guia de estilo
O público-alvo deste guia de estilo são os alunos da disciplina de Interação Humano Computador, grupo responsável pela análise da plataforma DetranGO no escopo da matéria, que por meio deste poderá realizar as outras etapas do projeto.

### 2.3 Como utilizar e manter o guia
O guia de estilo é essencial para garantir consistência no projeto e deve ser atualizado regularmente. Ele é a fonte primária de estilização da aplicação e deve ser consultado para decisões de design. Sempre que novas ideias surgirem, o guia deve ser atualizado para garantir que seja a base principal para artefatos de prototipação.

## 3. Análise do Ambiente de Trabalho
Antes da realização do Guia de estilo em si é importante entender o contexto de trabalho do usuário para saber quais elementos devem ser trabalhados, assim foi feita uma análise dos principais recursos que o usuário tem acesso dentro do site. O usuário precisa que o ambiente seja minimalista e, principalmente, com boa disposição dos elementos para que se tenha um bom entendimento das funcionalidades. Dessa forma, foram escolhidos dois componentes para serem analisados nesta etapa que estão destacados na figura 1.
<center>

![Página inicial DetranGO](../assets/guia_estilo/pagIni.png)
Figura 1 - Página inicial DetranGO (fonte: [DetranGO](https://www.detran.go.gov.br/psw/#/pages/pagina-inicial), Acesso: 11 de maio de 2023).
</center>

## 4. Elementos de Interface
Uma das partes importantes do guia de estilo são os elementos de interface. Esses elementos são responsáveis por compor as interfaces gráficas que os usuários terão contato durante o uso do sistema. Segue abaixo cada um dos elementos trabalhados neste tópico.

### 4.1 Janelas
Foram consideradas pelo grupo as janelas sendo todo o espaço que contempla a interface de uma das páginas do site. Para garantir a padronização dos diferentes ambientes foi pensado em um modelo simples, escalável e que facilite as atividades do usuário para orientar os designers no momento de pensar em uma interface para o sistema. O modelo feito é o apresentado na figura 2.
<center>

![Modelo de janelas]()
Figura 2 - Modelo de janelas(fonte: autor, 2023).
</center>

### 4.2 Tipografia
A tipografia escolhida foi a fonte Inter. A escolha da fonte foi pensada por ter uma boa leitura, para apresentar as informações, além de ser uma fonte mais moderna para o site. Segue abaixo uma ilustração mostrando os diferentes pesos, contextos e suas aplicações da fonte escolhida, na Figura 3.
<center>

![Tipografia utilizada](../assets/guia_estilo/fontes.png)
Figura 3 - Tipografia utilizadas(fonte: autor, 2023).
</center>

### 4.3 Cores
As cores são um elemento essencial no guia de estilo e são responsáveis por grande parte da mensagem comunicada pela interface ao usuário. Para a escolha das cores foi pensada em uma paleta minimalista focando em apenas 3 cores, com suas respectivas variações para garantir a adaptação em diferentes contextos do sistema. Segue abaixo a ilustração mostrando cada uma das cores definidas, na Figura 4.
<center>

![Cores escolhidas](../assets/guia_estilo/cores.png)
</br>Figura 4 - Cores escolhidas(fonte: autor, 2023).
</center>

#### 4.3.1 Primária
A cor primária escolhida foi o azul, já identificado na interface do site atual. Foram escolhidas diversas tonalidades a partir da cor para garantir a versatilidade da sua aplicação em diferentes contextos do sistema.

#### 4.3.2 Secundária
O laranja ficou como cor secundária por conta do contraste que conseguimos com o azul, utilizada para dar destaque a elementos específicos. Também foram escolhidas tonalidades para serem utilizadas em diferentes contextos.

#### 4.3.3 Cinza
O cinza, uma cor neutra característica de ambientes digitais voltada para a aplicação no de telas e em demais contextos onde é necessário baixo contraste.


## 5. Elementos de Interação

### 5.1 Estilos de Interação
O usuário interage com o site por meio de ícones, botões e formulários.

### 5.2 Seleção de um estilo
O estilo escolhido para botões, ícones e formulários foi pensado para ser objetivo e simples, visando uma padronização em como a interface e suas interações são feitas no sistema.

### 5.3 Aceleradores (teclas de atalho)
No sistema existem teclas de atalho, como aquelas voltadas para as abas mais acessadas e que serão utilizadas, as abas são:

* Veículos
* Habilitação
* CNH Social
* Atendimento
* Processos
* Educação
* Notícias
* Barra de pesquisa

Todos os atalhos podem ser visualizados pela figura 5 a seguir.

<center>

![Aceleradores](../assets/guia_estilo/aceleradores.png)
Figura 5 - Teclas de atalho do DetranGO (fonte: [DetranGO](https://www.detran.go.gov.br/psw/#/pages/pagina-inicial), Acesso: 11 de maio de 2023).
</center>

## Elementos de Ação

## Vocabulário e Padrões

## Bibliografia

> BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010

> Sítio DetranGO: <https://www.detran.go.gov.br/psw/#/pages/pagina-inicial>, Acesso em 11 de maio de 2023

# Histórico de Versão

| Versão | Data       | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ---------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 09/05/2023 | Criação do documento.              | Carlos Eduardo, João Morbeck, Pedro Henrique | Pedro Muniz |
