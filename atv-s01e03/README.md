# Sistemas Distribuídos

## O que é um sistema distribuído:

Para Couloris Sistema Distribuído é uma coleção de computadores autônomos interligados através de uma rede de computadores e equipamentos que permitem compartilhar entre si recursos. Para Tanenbaum é uma coleção de computadores independentes que se apresentam como um sistema único.

Observando o conceito desse grandes autores podemos subtrair a ideia de que sistema distribuindo é um a junção de vários computadores e tem como objetivo compartilhar recursos. 

## Outros objetivos importantes:

Existem no mínimo 4 outros objetivos que são importantes no estudo de sistemas distribuídos, são eles:
* **Interoperabilidade**: Capacidade  de sistemas ou componentes de fornecedores diferente coexistirem e trabalharem em conjunto.
* **Portabilidade**: Capacidade de uma aplicação desenvolvida para ser utilizada em um sistema A ser compatível e utilizável em um sistema B.
* **Extensibilidade**: Capacidade de adicionar serviços em um sistema sem alterar outros que já existem.
* **Escabilidade**: Capacidade de atender uma demanda específica.

## Tipos de Sistemas Distribuídos: 

### Sistemas de Computação Distríbuidos

Essa categoria consiste em sistemas distribuídos que utilizam computadores de alto desempenho. 
Geralmente são sistemas computacionais que estão ligados à uma rede local, em geral focada em computação paralela. 
Costumam ser homôgeneas, ou seja hardware e Sistema Operacional são idênticos ou similares nos computadores utilizados, o nó mestre, computador central, gerencia todas os outros nós, e por exemplo no processamento de imagem, o nó centra fatia uma imagem e distríbui essa fatia para ser processada em cada nó e quando finalizado cada fatia é reagrupada.

Esse tipo de sistema é muito utizado em computação em grade e clusterização.

### Sistemas de Informação Distribuídos

Uma arquitetura distríbuida que realiza diferentes operações, transações concorrentes nesse sistema não interferem um nas outras.

Esse tipo de sistema é utilizado em operações bancarias.

### Sistemas Distríbuidos Pervasivos

São sistemas de computação móvel e pervasivos.

Utilizado em ambientes que necessita descoberta dinâmica de recursos e serviços para isso utilizam sensores e análise de dados. 

# Middleware

O middleware funciona como uma camada oculta de tradução e escodem o baixo nível das passagem de mensagens assim permitem a comunicação de dados em sistemas distribuídos. Por isso, o middleware é chamado de "encanamento".
É muito utilizado em gerenciamento de dados, serviços de aplicações, sistema de mensageria, autenticação e gerenciamento de recursos de APIs.