# Cenários

## Introdução

Cenários são, essencialmente, histórias sobre pessoas realizando uma atividade. São narrativas que detalham uma situação de uso de uma aplicação e que, por sua natureza, envolvem dados reais ou potenciais, usuários e processos [1].
Os cenários também descrevem os atores que dele participam. Assim, seus objetivos dirigem a tarefa que ele realiza no sistema. Cada cenário possui um ator principal e um **objetivo** principal que pode ser desdobrado em subobjetivos [1].

## Metodologia

Cada cenário será detalhado tal qual modelo descrito por Milene Serrano [2]. Portanto, cada cenário deverá conter:

- **Título**: O título do cenário.
- **Objetivo**: O que o cenário objetiva descrever.
- **Contexto**: Onde o cenário está situado em relação a outras partes do software, atores e recursos.
- **Atores**: Os participantes do cenário que interagem com o sistema.
- **Recursos**: O que está disponível aos atores.
- **Episódios**: O que efetivamente acontece neste cenário.

É importante observar que podem ser definidas restrições nos episódios, isto é, cada episódio pode ter uma série de condições a obedecer [2].

Também é importante denotar que não serão todas as funcionalidades do site que poderão ser abordadas neste artefato. Para tanto, foram selecionadas algumas funcionalidades mais importantes do site Detran GO.

## Cenários

Abaixo estão descritos todos os cenários identificados para o projeto.

### Cenário 01

* **Título**: Consulta de dados de um veículo
* **Objetivo**: Conseguir consultar dados importantes de um veículo a partir da placa e do Renavam do mesmo.
* **Contexto**: 
    * **Local**: Em casa;
    * **Tempo**: Após o final do expediente;
    * **Pré-condições**: Disponibilidade de internet, disponibilidade de computador ou celular.
* **Ator**: Condutor habilitado.
* **Recursos**:
    * Internet;
    * Computador ou celular;
    * Número do Renavam;
    * Placa do carro.
* **Episódios**:
    * O condutor habilitado entra no site do Detran GO;
    * O condutor habilitado clica na aba "Veículos";
    * O condutor habilitado digita a placa e o Renavam nos campos solicitados;
    * O condutor habilitado obtém os dados de seu veículo.

### Cenário 02

* **Título**: Registro para primeira habilitação
* **Objetivo**: Conseguir realizar o pré-cadastro para o processo de primeira habilitação.
* **Contexto**: 
    * **Local**: Em casa;
    * **Tempo**: Após o final das aulas;
    * **Pré-condições**: Disponibilidade de internet, disponibilidade de computador ou celular.
* **Ator**: Estudante de curso superior.
* **Recursos**:
    * Internet;
    * Computador ou celular;
    * Dados pessoais;
    * Impressora (opcional);
    * Aplicativo bancário com leitor de código de barras (opcional).
* **Episódios**:
    * O estudante entra no site do Detran GO;
    * O estudante clica na aba "Habilitação";
    * O estudante seleciona o item "Primeira CNH";
    * O estudante identifica-se;
    * O estudante preenche seus dados pessoais;
    * O estudante informa a/as categorias para as quais quer tirar a habilitação;
    * O estudante informa o CFC (opcional);
    * O estudante emite o boleto para pagamento.

### Cenário 03

* **Título**: Consulta de multas de outras UFs
* **Objetivo**: Conseguir consultar informações sobre infrações cometidas no Goiás por veículos de outras UFs.
* **Contexto**:
    * **Local**: Em casa;
    * **Tempo**: Após o fim do expediente;
    * **Pré-condições**: Disponibilidade de internet, disponibilidade de computador ou celular.
* **Ator**: Condutor habilitado.
* **Recursos**:
    * Internet;
    * Computador ou celular;
    * Placa do carro.
* **Episódios**:
    * O condutor habilitado entra no site do Detran GO;
    * O condutor habilitado clica na aba "Veículos";
    * O condutor habilitado seleciona o item "Consulta Multas de Veículos de Outra UF";
    * O condutor habilitado insere a placa do carro;
    * O condutor habilitado obtém um resultado negativo ou uma lista de infrações.


### Cenário 04

* **Título**: Consulta de CFCs para CNH Social
* **Objetivo**: Conseguir consultar quais CFCs são credenciados ao programa de CNH Social.
    * **Local**: Em casa;
    * **Tempo**: Após o fim do expediente;
    * **Pré-condições**: Disponibilidade de internet, disponibilidade de computador ou celular.
* **Ator**: Condutor habilitado.
* **Recursos**:
    * Internet;
    * Computador ou celular.
* **Episódios**:
    * O condutor habilitado entra no site do Detran GO;
    * O condutor habilitado clica na aba "CNH Social";
    * O condutor habilitado seleciona o item "CFCs Credenciados ao programa CNH SOCIAL";
    * O condutor habilitado obtém uma lista com todos os CFCs credenciados, seus municípios e seus telefones.

### Cenário 05

* **Título**: Agendamento de atendimento no Detran GO
* **Objetivo**: Conseguir agendar um atendimento em uma unidade de atendimento que possua o serviço seleconado
    * **Local**: Em casa;
    * **Tempo**: Após o fim do expediente;
    * **Pré-condições**: Disponibilidade de internet, disponibilidade de computador ou celular.
* **Ator**: Condutor habilitado.
* **Recursos**:
    * Internet;
    * Computador ou celular;
    * Dados pessoais.
* **Episódios**:
    * O condutor habilitado entra no site do Detran GO;
    * O condutor hbilitado clica na aba "Atendimento";
    * O condutor habilitado seleciona o item "Agendar Atendimento";
    * O condutor habilitado avança na página de informações;
    * O condutor habilitado identifica-se com o CPF;
    * O condutor habilitado identifica-se com mais dados pessoais (**Restrição:** Não se pode agendar outro atendimento caso um atendimento esteja em curso);
    * O condutor habilitado seleciona a categoria de seu agendamento, o serviço solicitado e, por fim, uma das unidades que possuem o serviço;
    * O condutor habilitado confirma que leu s orientações sobre os agendamentos;
    * O condutor habilitado confirma as informações sobre o agendamento;
    * O condutor habilitado obté um comprovante do agendamento.

### Cenário 06

* **Título**: Verificação de atendimento
* **Objetivo**: Conseguir verificar os dados pessoais de um solicitante e o atendimento solicitado
    * **Local**: Ciretran de Goiás;
    * **Tempo**: Durante o expediente;
    * **Pré-condições**: Disponibilidade de internet, disponibilidade de computador.
* **Ator**: Atendente.
* **Recursos**:
    * Internet;
    * Computador.
* **Episódios**:
    * O atendente entra no sistema do Ciretran;
    * O atenednte consulta os dados fornecidos pelo Detran GO.

### Cenário 07

* **Título**: Consulta ao calendário de licenciamento
* **Objetivo**: Conseguir consultar o calendário de licenciaento de veículos.
    * **Local**: Em casa;
    * **Tempo**: Após o expediente;
    * **Pré-condições**: Disponibilidade de internet, disponibilidade de computador ou celular.
* **Ator**: Dono de veículo.
* **Recursos**:
    * Internet;
    * Computador ou celular.
* **Episódios**:
    * O dono de veículo entra no site do Detran GO;
    * O dono de veículo seleciona a aba "Veículos";
    * O dono de veículo seleciona o item "Calendário de Licenciamento/IPVA";
    * O dono de veículo obtém um calendário com datas apra cada final da placa e cada parcela.


### Cenário 08

* **Título**: Inscrição em curso de reciclagem
* **Objetivo**: Conseguir inscrever-se em curso de reciclagem em caso de suspensão da CNH.
    * **Local**: Em casa;
    * **Tempo**: Após o expediente;
    * **Pré-condições**: Disponibilidade de internet, disponibilidade de computador ou celular.
* **Ator**: Condutor com habilitação suspensa.
* **Recursos**:
    * Internet;
    * Computador ou celular;
    * Impressora (opcional);
    * Aplicativo bancário com leitor de código de barras (opcional).
* **Episódios**:
    * O condutor entra no site do Detran GO;
    * O condutor seleciona a aba "Habilitação";
    * O condutor seleciona o item "Curso de reciclagem";
    * O condutor seleciona a modalidade e o CFC;
    * O condutor imprime o boleto ou paga-o com um aplicativo.

### Cenário 09

* **Título**: Agendamento de vistoria veicular
* **Objetivo**: Conseguir agendar uma vistoria veicular para auxiliar compra ou venda de automóveis.
    * **Local**: Em casa;
    * **Tempo**: Após o expediente;
    * **Pré-condições**: Disponibilidade de internet, disponibilidade de computador ou celular.
* **Ator**: Dono de veículo ou comprador.
* **Recursos**:
    * Internet;
    * Computador ou celular.
* **Episódios**:
    * O dono de veículo entra no site do Detran GO;
    * O dono de veículo selecioa a aba "Veículos";
    * O dono de veículo seleciona o item "Agendamento de Vistorias Veiculares";
    * O dono de veículo seleciona o município em que deseja realizar a vistoria;
    * O dono de veículo obtém uma tabela com os prestadores de serviços, seus endereços, contatos e municípios.
    * O dono de veículo seleciona um prestador de serviços e é redirecionado.

## Bibliografia

> [1] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1. Acesso em; 07 mai. 2023.

> [2]  Milene Serrano e Maurício Serrano. Slides da disciplina de Requisitos de Software. Requisitos - Aula 10. Elicitação, modelagem e análise. Acesso em: 07 mai. 2023.


## Histórico de Versão

| Versão | Data     | Descrição                                 | Autor(es)      | Revisor(es) |
| ------ | -------- | ----------------------------------------- | -------------- | ----------- |
| `1.0`  | 02/05/23 | Criação do documento e adição do conteúdo | Pedro Muniz | Felipe Corrêa |