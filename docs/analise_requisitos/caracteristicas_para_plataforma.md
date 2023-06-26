# Características para Plataforma do Projeto

## 1. Introdução

A análise das capacidade e restrições da plataforma é uma das tarefas propostas pelo ciclo de vida de Mayhew, onde devem ser examinadas as possibilidades e restrições em equipamentos, sistemas operacionais, recursos de redes e outras especificações da plataforma onde o sistema irá ser instalado e utilizado.

## 2. Objetivos 

Este artefato visa especificar quais as características, limitações e possibilidades da plataforma de uso do site do Detran GO.

## 3. Metodologia

De acordo com Mayhew (1999) [9], ao se desenvolver uma aplicação para a Web, a definição das características da plataforma fica mais complexa, por ter de considerar elementos como tamanho de tela e resolução, velocidade de internet, capacidades de browsers (controles do browser, interpretadores, plugins instalados). Também é lembrado que não é aconselhável que todas as funcionalidades mais recentes da internet sejam implementadas a fim de não deixar o site inutilizável para parte significativa dos usuários.

Este artefato deverá primeiramente definir se há documentação específica para se basear além da bibliografia, a fim de auxiliar na definição de características da plataforma. Também enumerará as possibilidades e limitações do sítio atual. Para a definição de características da plataforma, deve-se identificar claramente características de hardware e de software. 

## 4. Documentação 

Até a data da versão `2.0` deste artefato, não foi encontrada documentação sobre o trabalho de interface do site do Detran GO.

## 5. Site atual

## 5.1. Limitações

O site possui algumas limitações que estão listadas abaixo.

- É necessário que o usuário possua acesso à internet para acessar o site;
- Na página inicial do site possui muita informação, causando uma imagem carregada e confusão do usuário
- A organização dos ícons não são proporcionais aos botões criados na interface;
- As cores usadas nas fontes da interface do site causa estranhamento no usuário pelas devido ao destoamento das cores escolhidas;
- A inteface não deixa a ação do usuário intuitiva, causando ruído no uso do site;
- Os ícons não estão padronizados;
- O scroll da página não é muito efetiva por estar em uma configuração diferente, o usuário pode se confundir, podendo pensar por exemplo que são notícias recente, quando na verdade é a ferramenta de exploração do site;
- O site possui um rodapé com informações de ouvidoria, mas sua forma não está responsiva, causando estranhamento como informações sobre outras;
- O site possui um fórum de dúvidas, mas está quase inmperceptível para o usuário então esse recurso pode passar despercepido;

## 5.2. Possibilidades

Apesar das limitações, o site possui muitas funcionalidades por se tratar de um site de serviçoes como informações de veículos, certidão de posse, consulta de CNH, acompanhamento processual e muitas outras funcionalidades. Estas possibilidades estão listadas abaixo:

- É possível logar no site;
- É possível consultar veículos, solicitar segunda via de CNH, consultar CRLV-e digital, realizar agendamentos para atendimentos como transferência de veículos, consultar dívida ative, consulta de multas, consulta do Renevam;
- O usuário consegure buscar o conteúdo que deseja por uma pesquisa rápida feita no site sem precisar sair da tela inicial;
- O usuário consegue atendimento rápido pelo atendente virtual;
- O usuário consegue ter acesso à palestras em empresas gratuitas sobre direção defenciva e relacionamento interpessoal;
- O usuário tem a opção de acompanhar o processo do serviço pelo site;
- O usuário consegue consultar taxas;
- O usuário consegue agendar atendimento no VAPT-VUPT.

## 6. Definição de características da plataforma

Em se tratando de um sistema para a Web, é notável que os hardwares e os softwares nestes implementados não serão uniformes. Dessa forma, urge a necessidade de pesquisas sobre o domínio em que o público alvo do site está inserido. Também deve ser notado que, para este artefato, dispositivos móveis não serão considerados.

### 6.1 Características de hardware

#### 6.1.1 Conectividade à internet

Considerando a unidade federativa na qual o site irá operar (Goiás), é importante verificar a aspectos de conexão de internet goianos.

##### 6.1.1.1 Velocidade de internet

Até a data da versão `2.0` deste artefato, não foi possível definir claramente uma característica de velocidade de internet da plataforma.

#### 6.1.2 Tamanho de tela e resolução

Considerando pesquisa de 2015 que mostra a preferência do brasileiro por notebooks em favor de computadores desktop [14], é possível demarcar tamanhos e resoluções de tela.

Os tamanhos de tela para notebooks variam de 12 a 17 polegadas e, dentro desta faixa, as resoluções de tela variam de 800 x 600 pixels a 1920 x 1200 pixels [4].

### 6.2 Características de software

#### 6.2.1 Navegador 


Para a análise desta característica, foi considerado o ranking de 2023 dos navegadores mais usados no planeta. Em ordem e com porcentagens, tem-se os cinco navegadores mais populares [5]:

* Google Chrome - 66,13%
* Apple Safari - 11,87%
* Microsoft Edge - 11%
* Mozilla Firefox - 5,65%
* Opera - 3,09%

Desta forma, o projeto de interface deve ser capaz de execução nestes navegadores.

#### 6.2.2 Capacidades do navegador

Para as capacidades de navegador, serão consideradas funções exclusivas dos mesmos e as versões de HTML, CSS e Javascript que os mesmos suportam.

É importante notar que há especificidades quanto a implementação de funções mais recentes do CSS3 que não são suportadas por todos os browsers simultaneamente [7].

##### 6.2.2.1 Google Chrome

O Google Chrome tem como principal funcionalidade diferencial a integração offline com ferramentas do Google Workspace como o Gmail, Google Docs e outros [6]. Esta característica específica, no entanto, não interfere diretamente com o uso do site do Detran GO.

A versão de HTML suportada pelo Google Chrome é o HTML 5 [13]; a versão de CSS, CSS3 [7]. A versão de Javascript suportada pelo Google Chrome é a ES2021, a partir da versão 75 (junho de 2019) [15].

##### 6.2.2.2 Apple Safari

O Safari tem como principal diferencial sua alta performance, executando Javascript e conteúdo animado mais rapidamente que outros browsers, bem como maior responsividade []. Esta característica pode interferir com o uso do site do Detran GO.

A versão de HTML suportada pelo Apple Safari é o HTML5 [13]; a versão de CSS, CSS3 [7]. A versão de Javascript suportada pelo Apple Safari é a ES2021, a partir da versão 13.1 (setembro de 2019) [15].

##### 6.2.2.3 Microsoft Edge

O Microsoft Edge tem como principais diferenciais sua integração com ferramentas de inteligência artificial e ferramentas de organização de guias [10]. Estas características específicas, no entanto, não interferem diretamente com o uso do site do Detran GO.

A versão de HTML suportada pelo Microsoft Edge é o HTML5 [13]; a versão de CSS, CSS3 [7]. A versão de Javascript suportada pelo Microsoft Edge é a ES2021, a partir da versão 79 (janeiro de 2020) [15]

##### 6.2.2.4 Mozilla Firefox

O Mozilla Firefox tem como principais diferenciais sua disponibilidade em múltiplos SOs e a baixa coleta de dados pessoais para uso futuro [11]. Estas características específicas, no entanto, não interferem diretamente com o uso do site do Detran GO.

A versão de HTML suportada pelo Mozilla Firefox é o HTML5 [13]; a versão de CSS, CSS3 [7]. A versão de Javascript suportada pelo Mozilla Firefox é a ES2021, a partir da versão 74 (outubro de 2019) [15].

##### 6.2.2.5 Opera

O Opera tem como principais diferenciais sua integração com ferramentas de inteligência artificial e bloqueador de anúncios e VPN embutidos [12].

A versão de HTML suportada pelo Opera é o HTML5 [13]; a versão de CSS, CSS3 [7]. A versão de Javascript suportada pelo Opera é a ES2021, a partir da versão 67 (junho de 2019) [15].

#### 6.2.2 Sistema operacional

Para a análise desta característica, foi considerada uma pesquisa para observar a porcentagem de usuários de vários sistemas operacionais. Em ordem e com porcentagens, tem-se os sistemas operacionais mais populares [7]:

* Windows - 74,73%
* macOS - 14,4%
* Linux - 2,81%
* Chrome OS - 1,86%
* FreeBSD - 0,01%

Há de se considerar que o Apple Safari, nas condições apresentadas na seção 6.2.1, não está disponível para outros sistemas que não macOS. Apenas versões como a 5.1.7 e anteriores estão disponíveis para Windows [1].

Os SOs não apresentam empecilhos para os navegadores, sendo estes últimos os principais definidores das características da plataforma. 

## 7. Referências Bibliográficas

> [1] APPLE. Atualizar para a versão mais recente do Safari. Disponível em: https://support.apple.com/pt-br/HT204416. Acesso em: 26 jun. 2023.

> [2] APPLE. Safari. 2023. Disponível em: https://www.apple.com/safari/. Acesso em: 26 jun. 2023.

> [3] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1

> [4] BRINGIT. Qual o tamanho de tela de notebook em cm? Disponível em: https://www.bringit.com.br/blog/duvidas-frequentes/qual-o-tamanho-de-tela-de-notebook-em-cm/. Acesso em: 26 jun. 2023.

> [5] CIRIACO, Douglas. Ranking dos navegadores mais usados no PC tem novidade no 2º lugar. 2023. Via Canaltech. Disponível em: https://canaltech.com.br/apps/ranking-dos-navegadores-mais-usados-no-pc-tem-novidade-no-2o-lugar-248298/. Acesso em: 26 jun. 2023.

> [6] GOOGLE. O Chrome é único. Disponível em: https://www.google.com/intl/pt-BR/chrome/. Acesso em: 26 jun. 2023.

> [7] LAZARIS, Louis. Browser Support for CSS3: What's the status? 2022. Disponível em: https://www.impressivewebs.com/css3-browser-support/. Acesso em: 26 jun. 2023.

> [8] LISBOA, Alveni. Qual o sistema operacional de PC mais usado do mundo? 2022. Via Canaltech. Disponível em: https://canaltech.com.br/software/qual-o-sistema-operacional-de-pc-mais-usado-do-mundo-224432/. Acesso em: 26 jun. 2023.

> [9] MAYHEW, Deborah J.. The usability engineering lifecycle: a practitioner's handbook for user interface design. São Francisco: Morgan Kaufmann Publishers, 1999. Disponível em: https://archive.org/details/usabilityenginee0000mayh. Acesso em: 26 jun. 2023

> [10] MICROSOFT. Escolha o Microsoft Edge. Disponível em: https://www.microsoft.com/pt-br/edge?form=MA13FJ. Acesso em: 26 jun. 2023.

> [11] MOZILLA. Instale o navegador que protege o que é importante. Disponível em: https://www.mozilla.org/pt-BR/firefox/new/. Acesso em: 26 jun. 2023.

> [12] OPERA. Seu browser do seu jeito. Disponível em: https://www.opera.com/pt-br. Acesso em: 26 jun. 2023.

> [13] TEJ, Krishna. How to test Browser Compatibility for HTML5. 2022. Disponível em: https://www.browserstack.com/guide/html5-browser-compatibility-test. Acesso em: 26 jun. 2023.

> [14] TI INSIDE. Pesquisa mostra que 56% dos brasileiros preferem notebooks para uso doméstico. 2015. Disponível em: https://tiinside.com.br/22/07/2015/pesquisa-mostra-que-56-dos-brasileiros-preferem-notebooks-para-uso-domestico/. Acesso em: 26 jun. 2023.

> [15] W3SCHOOLS. ECMAScript 2021. Disponível em: https://www.w3schools.com/js/js_2021.asp. Acesso em: 26 jun. 2023. 

## 8. Histórico de versão
| Versão | Data       | Descrição            | Autor(es)   | Revisor(es)    |
|--------|------------|----------------------|-------------|----------------|
| `1.0`  | 10/05/2023 | Criação do documento | Amanda N. e Pedro H. | Pedro M. |
| `1.1`  | 11/05/2023 | Adição das características e objetivos | Amanda N. e Pedro H. | Pedro M. |
| `1.2`  | 11/05/2023 | Adição das limitações e possibilidades | Amanda N. e Pedro H. | Pedro M. |
| `2.0`  | 26/06/2023 | Correção baseada na verificação | Felipe M. | Pedro H. |
