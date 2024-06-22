## Sumário

<details>
<summary>Sumário</summary>


1. [Visão Geral](#visão-geral)
2. [Desafios](#desafios)
3. [Contexto](#contexto)
4. [Ciclo de Vida](#ciclo-de-vida)
    - [Ciclo de Vida Estrela](#ciclo-de-vida-estrela)
5. [Análise de Tarefas, Usuários e Função](#análise-de-tarefas-usuários-e-função)
    - [WHY](#why)
        - [Cenário Atual](#cenário-atual)
        - [Motivo e Objetivo do Sistema](#motivo-e-objetivo-do-sistema)
        - [Otimização da Eficiência Operacional](#otimização-da-eficiência-operacional)
        - [Aprimoramento da Colaboração](#aprimoramento-da-colaboração)
        - [Facilidade de Acesso e Usabilidade](#facilidade-de-acesso-e-usabilidade)
        - [Transparência e Acompanhamento](#transparência-e-acompanhamento)
        - [Segurança de Dados e Controle de Acesso](#segurança-de-dados-e-controle-de-acesso)
        - [Objetivo do Sistema](#objetivo-do-sistema)
        - [Quais seriam os problemas?](#quais-seriam-os-problemas)
        - [Usuários-Alvo](#usuários-alvo)
6. [Narrativa](#narrativa)
7. [OMS - Análise das Partes Interessadas](#oms---análise-das-partes-interessadas)
    - [Personas](#personas)
    - [Mapa de Empatia](#mapa-de-empatia)
8. [Avaliação - Análise de Tarefa Usuários e Função](#avaliação---análise-de-tarefa-usuários-e-função)
9. [Engenharia de Requisitos](#engenharia-de-requisitos)
    - [Elicitação de Requisitos](#elicitação-de-requisitos)
10. [Análise de Requisitos](#análise-de-requisitos)
    - [Casos de Uso](#casos-de-uso)
        - [Usuários](#usuários)
        - [Funcionalidades do Sistema](#funcionalidades-do-sistema)
        - [Sequência](#sequência)
        - [Classes](#classes)
        - [Colaboração](#colaboração)
        - [Estados](#estados)
        - [Atividades](#atividades)
    - [Fluxograma](#fluxograma)
11. [Avaliação - Especificação de Requisitos](#avaliação---especificação-de-requisitos)
    - [Validação de Requisitos com o Cliente](#validação-de-requisitos-com-o-cliente)
12. [Projeto Conceitual e Concepção do Design](#projeto-conceitual-e-concepção-do-design)
    - [Identidade Visual](#identidade-visual)
        - [Tipografia](#tipografia)
        - [Logotipo](#logotipo)
        - [Paleta de Cores](#paleta-de-cores)
    - [Design e Iteração](#design-e-iteração)
        - [Soluções Propostas](#soluções-propostas)
13. [Wireframe](#wireframe)
    - [Versão de Baixa Fidelidade](#versão-de-baixa-fidelidade)
14. [Protótipo de Alta Fidelidade](#protótipo-de-alta-fidelidade)
    - [Prototipação](#prototipação)

</details>

# Projeto Evoluir Ti
#### Desenvolvido por: ATOMIC CODE
<p align="center">
  <img src="./Processos/Sprint_1/Logo/Logo_Atomic_Code400x400.jpeg" alt="Logo Atomic Code" />
  <br />
  Figura 1 - Logo da Atomic Code
</p>

# Visão Geral
## Desafios 
O NUPEX (Núcleo de Apoio à Pesquisa e Extensão da Univiçosa) responsável por gerenciar as avaliações feitas no SIMPAC (Simpósio de Pesquisa e Extensão da Univiçosa), enfrenta desafios na entrega eficiente de resultados e na gestão manual das avaliações. O projeto visa otimizar esse processo por meio de uma aplicação que proporciona eficiência na organização de projetos por curso, resultando em entregas mais rápidas e menos trabalho repetitivo para os organizadores.

## Contexto
Atualmente, a equipe da NUPEX  liderada por Eliene da Silva Martins Viana, CEO da NUPEX, realiza o processo de avaliação de forma manual, o que consome tempo, aumenta o risco de erros e dificulta a organização dos dados. A necessidade de uma solução digital para substituir o processo manual tornou-se crucial, e é neste contexto que o projeto Evoluir Ti foi proposto.

# Ciclo de vida
## Ciclo de vida Estrela
O modelo estrela representa o ciclo de vida do desenvolvimento de software, focando em uma abordagem iterativa e centrada no usuário. Este modelo destaca a flexibilidade e a capacidade de adaptação às necessidades e feedback dos usuários ao longo de todo o processo de desenvolvimento. É especialmente útil em projetos onde os requisitos podem mudar frequentemente ou onde a validação contínua com o usuário é essencial para o sucesso do sistema. O modelo estrela promove um desenvolvimento ágil e adaptativo, alinhando-se às práticas modernas de engenharia de software e ao desenvolvimento centrado no usuário, garantindo que o produto final atenda de forma precisa e eficaz às expectativas e necessidades dos seus utilizadores.

<p align="center">
  <img src="Processos/Ciclo De vida estrela.png" alt="Ciclo de vida em estrela"/>
  <br />
  Figura 2 - Ciclo de vida de uma estrela
</p>



# Análise de tarefas usuários e função

## WHY

### CENÁRIO ATUAL
Atualmente, durante o SIMPAC , o processo de avaliação é organizado pela equipe da NUPEX, este processo é realizado manualmente, o que demanda um considerável investimento de tempo, aumentando os riscos de erros e perca ou danificação dos documntos de avaliação, além de tornar a organização dos dados mais desafiadora. A necessidade de uma solução digital para substituir esse método tornou-se crucial. 

### Motivo e Objetivo do Sistema

A implementação do Evoluir Ti é fundamentada em uma série de razões estratégicas e
funcionais, visando aprimorar a eficiência, a colaboração e a experiência global no
gerenciamento de projetos do SIMPAC. Abaixo estão os principais motivos que respaldam
a adoção deste sistema.

### Otimização da Eficiência Operacional 
O Evoluir Ti oferece uma plataforma centralizada e integrada, permitindo
aos administradores  gerenciarem dados, prazos e notificações de
forma eficiente. Isso resulta em uma redução significativa no tempo dedicado a
tarefas administrativas, liberando recursos para focar em atividades mais
estratégicas.

### Aprimoramento da Colaboração 
A implementação do sistema promove uma comunicação mais eficaz
entre administradores, avaliadores e participantes. Facilita a troca de
informações, feedbacks e atualizações em tempo real, fortalecendo a
colaboração e a sinergia na comunidade acadêmica. 

### Facilidade de Acesso e Usabilidade 
A natureza baseada na web do sistema proporciona maior faciliadde, 
permitindo que usuários acessem a plataforma de qualquer lugar, a
qualquer momento. Sua interface intuitiva e amigável facilita a adoção e o uso
efetivo, independentemente do nível de familiaridade com tecnologia. 

### Transparência e Acompanhamento 
O Evoluir Ti oferece transparência no processo de submissão e avaliação
de projetos, prazos e feedbacks. Isso permite que administradores acompanhem
o progresso dos projetos de forma clara e eficaz.

### Segurança de Dados e Controle de Acesso 
A implementação do sistema promove a segurança de dados, com a
utilização de protocolos modernos de criptografia e práticas de segurança. 
Administradores e avaliadores deverão acessar o sistema utilizando um e-mail e senha de
segurança. O controle de acesso é centralizado, permitindo que administradores definam
permissões conforme o necessário, garantindo a confidencialidade e a integridade dos
dados. 

## Objetivo do Sistema 

Após a reunião com a Eliene, pensamos em um sistema com o objetivo de facilitar os processos, com
as principais funções:
- Menu para escolha de login para administradores e avaliadores.
- Cadastro de administradores, avaliadores e trabalhos (Administradores).
- Menu de escolha de projetos (Avaliadores).
- Menu de acesso para ver os resultados dos projetos (Administradores) .
- Redução do trabalho manual para otimizar o tempo gasto. 

Administradores e avaliadores deverão acessar o sistema utilizando um e-mail e senha de
segurança. O sistema contará com recursos que permitirão que todos os usuários possam acessá-lo
para ver os resultados dos projetos. No entanto, o acesso a informações privadas será
restrito, com cadastro permitido apenas para pessoas autorizadas, tais como:
Professores envolvidos, Avaliadores e Administradores.
O sistema será acessível via web, garantindo
flexibilidade e conveniência para os usuários. 

### Quais seriam os problemas? 

- Tentativa de cadastro de projetos a serem avaliados faltando dados no formulário.
- Atrasos na conclusão das tarefas devido ao serviço ser feito de forma manual,
afetando outras pessoas envolvidas. 


### Usuários-Alvo
- Gestores/Organizadores do SIMPAC
- Avaliadores
- Público Afetado pelos Resultados


## Narrativa
Em um dia onde estava ocorrendo as avaliações do SIMPAC, a Luana Pereira uma avaliadora se encontrou em uma situação desafiadora. Após uma longa noite de avaliações de projetos, a professora perdeu as folhas onde havia registrado a avaliação de seus designados grupos. Foi a primeira vez que algo assim acontecia, e a sensação de desespero tomou conta dela.
O não apenas abalou Luana, mas também acendeu uma luz de alerta na secretaria do NUPEX, que atende a uma necessidade urgente de evitar futuros problemas semelhantes. Além disso, o processo de avaliação manual, apesar do tradicional, era lento e vulnerável a riscos, como o ocorrido com Luana.
A busca por uma solução levou a cordenadora do NUPEX a um momento de reflexão sobre inovação no sistema de avaliação do SIMPAC. Em sua reflexão, ela se deparou com uma abordagem um aplicativo que simplificava todo o processo de avaliação, tornando-o digital e seguro.
Esse sistema inovador permitiu que as avaliações fossem realizadas e organizadas por meio de um aplicação web no celular, eliminando assim os riscos de perda, otimizando o tempo e facilitando a vida dos avaliados. Com login e senha, o sistema garante a segurança e acessibilidade exclusiva aos avaliados, protegendo a confidencialidade das avaliações.
A implementação desse novo sistema transformou a dinâmica do SIMPAC. Agora, o aplicativo de avaliações não apenas mitigava a possibilidade de incidentes como o de Luana, mas também tornava todo o processo mais eficiente e prático.
<br>A narrativa evidencia como a introdução de uma tecnologia inovadora pode redefinir um processo burocrático, atendendo às necessidades e frustrações dos usuários finais, e marcando uma nova era de eficiência no SIMPAC da Univiçosa.

## OMS - Análise das Partes Interessadas

### Personas
Baseado no storytelling, as personas foram criadas para representar os stakeholders.
![persona](./Processos/Sprint_3/Relatorio%20Atualizado/Persona-1_page-0003.jpg)
Figura 3 - Persona de Marcos Silva
![persona2](./Processos/Sprint_3/Relatorio%20Atualizado/Persona-1_page-0002.jpg)
Figura 4 - Persona Luana Pereira


### Mapa de Empatia
- Para entender melhor as necessidades dos stakeholders, utilizamos o mapa de empatia, assim tivemos uma visão de onde focar nossos estudos para criarmos uma solução de agrado a todos.
![Mapa_Empatia](./Processos/Sprint_3/Relatorio%20Atualizado/Mapa_de_Empatia_1.pdf.png)
Figura 5 - Mapa de Empatia Marcos Silva
![Mapa_Empatia2](./Processos/Sprint_3/Relatorio%20Atualizado/Mapa_de_Empatia_2.pdf.png)
Figura 6 - Mapa e Empatia de Luana Pereira


## Avaliação - análise de tarefa usuários e função

#### 1. Identificação do Público-Alvo e Coleta de Requisitos:
Iniciamos o processo identificando o público-alvo para o qual o mapa da empatia seria
criado. Este público-alvo foi definido com base nas informações fornecidas pelo cliente.
Realizamos reuniões e sessões de brainstorming para abstrair os requisitos principais. A
partir dessas interações, conseguimos entender quem são os usuários finais e suas
principais características.
#### 2. Criação de Personagens Abstratos:
Com base nos dados coletados, criamos personagens (ou personas) abstratos que
representavam diferentes tipos de usuários. Cada personagem foi detalhado com
informações demográficas, comportamentais e psicográficas para refletir os diversos
perfis de usuários identificados. Esses personagens ajudaram a visualizar e empatizar
melhor com os diferentes segmentos de usuários.
#### 3. Estruturação do Mapa da Empatia:
O mapa da empatia foi dividido em seis seções principais, cada uma destinada a
capturar um aspecto diferente da experiência dos personagens:
- 1 O que vê?
- 2 O que ouve?
- 3 O que pensa e sente?
- 4 O que fala e faz?
- 5 Esforços (Dores)
- 6 Resultados (Ganhos)
Cada seção foi preenchida com base nas percepções e dados coletados durante a fase de
requisitos.
#### 4. Coleta de Dados para as Seções:
Para preencher cada seção do mapa, utilizamos as seguintes abordagens:
- O que vê?: Observamos os ambientes e cenários que os personagens
frequentam.
- O que ouve?: Registramos as influências externas e fontes de informação
relevantes para os personagens.
- O que pensa e sente?: Exploramos os pensamentos internos, preocupações e
emoções mais profundas.
- O que fala e faz?: Analisamos os comportamentos e comunicações dos
personagens em situações típicas.
- Esforços (Dores): Identificamos as principais frustrações e obstáculos
enfrentados.
- Resultados (Ganhos): Definimos os objetivos, desejos e necessidades dos
personagens.
#### 5. Análise e Refinamento:
Após preencher as seções com informações detalhadas, analisamos o mapa da empatia
em equipe. Discutimos os insights obtidos e refinamos os detalhes para garantir que
todos os aspectos importantes fossem considerados. Esta análise permitiu identificar
padrões e oportunidades para melhorar a experiência do usuário.
#### 6. Aplicação dos Insights:
Os insights obtidos a partir do mapa da empatia foram utilizados para guiar o
desenvolvimento do produto/serviço. As informações foram aplicadas para criar
soluções que atendem melhor às necessidades e expectativas dos usuários, resultando
em um produto mais alinhado com os requisitos do cliente e satisfatório para os
usuários finais.


## Engenharia de requisitos
### Elicitação de requisitos
A Elicitação de requisitos foi realizada através de uma reunião com um cliente que junto com nossa equipe foram levantados os requisitos para resolver o atual problema da avalição do SIMPAC, 
estes requisitos foram documentados a nível de usuário, ou seja, a um nível de explicação mais simples que o próprio cliente consegue compreender.
- [Documento de requisitos a nível de usuário](Processos/Sprint_3/Requisitos_de_usuário.pdf)

<br>



## Análise de requisitos
## Casos de Uso
### Introdução casos de uso
Um caso de uso é um método da engenharia de software que representa as interações entre um sistema e seus atores, descrevendo as ações que cada ator (usuário) pode realizar no sistema. Ele inclui os conceitos de include, onde um caso de uso pode incluir outro caso de uso para representar uma funcionalidade compartilhada, e extend, onde um caso de uso pode opcionalmente adicionar funcionalidade a outro caso de uso.
- [Diagrama casos de uso](https://drive.google.com/file/d/1yVZspcJCOXUUYTCCWBUkr8FXfLzX_vi6/view?usp=sharing)
#### Usuários:
- Admin: O administrador do sistema, que tem várias responsabilidades de gerenciamento.
- Avaliador: A pessoa que realiza as avaliações dos trabalhos.
- Usuários: Admin e Avaliadores.
#### Funcionalidades do Sistema:
#### Login e Logout
- Todos os usuários podem entrar e sair do sistema com segurança.
#### Gerenciamento de Trabalhos
- Os administradores podem criar, editar e organizar os trabalhos que precisam ser avaliados.
#### Atribuição e gerenciamento de Avaliadores
- Os administradores designam avaliadores específicos para cada trabalho.
- Os administradores também gerenciam o cadastro e as informações dos avaliadores.
#### Visualização de Trabalhos
- Adminstradores podem ver todos trabalhos.
- Avaliadores só podem vizualizar os trabalhos a quais foram designados.
#### Realização de Avaliações
- Os avaliadores realizam as avaliações dos trabalhos atribuídos a eles, seguindo critérios específicos.
#### Visualização de Avaliações
- Adminstradores podem ver as avaliações de todos trabalhos .
- Avaliadores só podem vizualizar os trabalhos a quais foram designado.
#### Visualização de Resultados
- Adminstradores podem ver os resultados de trabalhos.
- Avaliadores só podem vizualizar os trabalhos a quais foram designado.

<br>

## Classes
### Introdução ao Diagrama de Classe
No diagrama, observamos diversas classes que representam diferentes entidades do sistema, como usuários, administradores, avaliadores e os próprios trabalhos. Cada classe contém atributos e métodos que definem as suas propriedades e comportamentos.

- [Diagrama de classes](https://drive.google.com/file/d/1AuMt8c_RJhknCfidFCA7WQmffumdQa0K/view?usp=sharing) <br>

### Descrição das Classes:
#### Usuário:
- Atributos: UUID, Nome, Sobrenome, Email, Senha.
- Métodos: Login, Logout, Avaliar.
- Representa um usuário genérico no sistema que pode realizar login, logout e potencialmente avaliar trabalhos.
#### Admin:
- Atributos: Data Nascimento, ListaTrabalho.
- Métodos: PreencherTrabalho, SelecionarAvaliadores, InserirTrabalho, GerenciarAvaliadores, VisualizarResultados.
- Subclasse de Usuário com privilégios especiais para gerenciar trabalhos e avaliadores.
#### Avaliador:
- Atributos: Lista Trabalhos Atribuídos.
- Métodos: AcessarTrabalho, AvaliarTrabalho.
- Subclasse de Usuário focada na avaliação dos trabalhos atribuídos.
#### Trabalho:
- Atributos: UUID, Resumo, Protocolo, Modelo Avaliativo, Lista Avaliadores, Resumo.
- Métodos: Criar, Editar, AtribuirAvaliador.
- Representa os trabalhos submetidos no sistema, com funcionalidades para criação e edição.
#### Sistema:
- Atributos: Lista Admin, Lista Avaliadores, Lista Trabalhos.
- Métodos: AutenticarUsuario, EnviarNotificação, GerarRelatório.
- Classe que representa o sistema como um todo, lidando com autenticação e comunicação entre usuários e trabalhos.
<br>


## Sequência
- [Diagrama de sequência](https://drive.google.com/drive/folders/1lt1sOdz3DocAN1NUy9vbQR6oxZJey5mK?usp=sharing)
### Diagrama de Sequência de Login
Descrição: Este diagrama de sequência descreve o processo de autenticação de um usuário no sistema, incluindo a verificação de credenciais e os possíveis resultados (credenciais válidas ou inválidas).
#### Passo a Passo da Interação:
- Inserção de Credenciais:
    - O Usuário insere seu nome de usuário e senha na interface do sistema.
    - A Interface do Sistema recebe as credenciais e envia uma solicitação ao Banco de Dados para verificar sua validade.
- Verificação de Credenciais:
    - O Banco de Dados verifica as credenciais fornecidas.
    - O resultado da verificação (credenciais válidas ou inválidas) é enviado de volta para a Interface do Sistema.
- Resultados da Autenticação:
    - Credenciais válidas:
        - A Interface do Sistema redireciona o Usuário para a interface principal.
    - Credenciais inválidas:
        - A Interface do Sistema exibe uma mensagem de erro e oferece ao Usuário a opção de recuperação de senha.
- Recuperação de Senha (se necessário):
    - Se o Usuário optar por recuperar a senha, ele insere seu e-mail associado ao nome de usuário.
    - A Interface do Sistema verifica se o e-mail está associado ao nome de usuário no Banco de Dados.
    - E-mail encontrado:
        - Um link de redefinição de senha é enviado ao e-mail do usuário.
        - O Usuário clica no link e insere uma nova senha, que é atualizada no Banco de Dados.
    - E-mail não encontrado:
        - A Interface do Sistema exibe uma mensagem de erro informando que o e-mail não foi encontrado.
#### Intuito do Diagrama: 
O diagrama de sequência de autenticação visa representar de forma clara o fluxo de login de um usuário no sistema, destacando as interações entre o usuário, a interface do sistema e o banco de dados. Ele mostra como o sistema lida com credenciais válidas e inválidas, bem como o processo de recuperação de senha. Esse diagrama é essencial para entender o funcionamento do processo de autenticação, ajudar no desenvolvimento e garantir a segurança do sistema.
#### O que o diagrama comunica: 
Este diagrama comunica o processo completo de autenticação, incluindo como o sistema verifica as credenciais do usuário, gerencia a recuperação de senha e garante a segurança dos dados de login. Ele destaca as diferentes possibilidades (credenciais válidas e inválidas) e os passos subsequentes que o sistema toma em cada caso, proporcionando uma visão clara e detalhada do fluxo de autenticação.
- [Diagrama de sequência(Login)](https://drive.google.com/drive/folders/1lt1sOdz3DocAN1NUy9vbQR6oxZJey5mK?usp=sharing)
<br>

### Diagrama de Sequência de Gerenciamento de Avaliadores pelo Administrador
Descrição: Este diagrama de sequência descreve o processo de gerenciamento de avaliadores pelo administrador, incluindo a adição, edição e remoção de avaliadores.
#### Passo a Passo da Interação:
- Adicionar Avaliador:
    - O Administrador insere os dados do novo avaliador.
    - A Interface do Sistema envia os dados ao Banco de Dados para salvamento.
    - O Banco de Dados confirma o salvamento e a Interface do Sistema exibe uma mensagem de sucesso ao Administrador.
- Editar Avaliador:
    - O Administrador seleciona um avaliador para editar.
    - A Interface do Sistema consulta o Banco de Dados para obter os dados do avaliador.
    - Os dados do avaliador são retornados para a Interface do Sistema e exibidos para o Administrador.
    - O Administrador insere novos dados para o avaliador.
    - A Interface do Sistema envia os novos dados ao Banco de Dados para atualização.
    - O Banco de Dados confirma a atualização e a Interface do Sistema exibe uma mensagem de sucesso ao Administrador.
- Remover Avaliador:
    - O Administrador seleciona um avaliador para remover.
    - A Interface do Sistema envia a solicitação ao Banco de Dados para remover o avaliador.
    - O Banco de Dados confirma a remoção e a Interface do Sistema exibe uma mensagem de sucesso ao Administrador.
#### Intuito do Diagrama: 
O diagrama de sequência de gerenciamento de avaliadores pelo administrador visa representar de forma clara o fluxo de atividades envolvidas na adição, edição e remoção de avaliadores. Ele destaca as interações entre o administrador, a interface do sistema e o banco de dados.
#### O que o diagrama comunica: 
Este diagrama comunica o processo completo de gerenciamento de avaliadores pelo administrador, mostrando como ele pode adicionar, editar e remover avaliadores. Ele proporciona uma visão clara das operações e interações necessárias para manter e gerenciar os avaliadores dentro do sistema.
- [Diagrama de sequência(Gerenciamento de Avaliadores)](https://drive.google.com/file/d/1ue9iJtYE2NeKLiRNSS403QZ4qFy3PfPL/view?usp=sharing)
<br>

### Diagrama de Sequência de Criação de Trabalho pelo Administrador
Descrição: Este diagrama de sequência descreve o processo de criação de um novo trabalho pelo administrador, incluindo a geração de um UUID único e a atribuição de avaliadores ao trabalho.
#### Passo a Passo da Interação:
- Criar Novo Trabalho:
    - O Administrador insere os dados do novo trabalho.
    - A Interface do Sistema gera um UUID único para o trabalho e o salva no Banco de Dados.
    - O Banco de Dados confirma o salvamento e a Interface do Sistema exibe uma mensagem de sucesso ao Administrador.
- Atribuir Avaliadores:
    - O Administrador seleciona avaliadores para o trabalho recém-criado.
    - A Interface do Sistema recupera a lista de avaliadores do Banco de Dados e a exibe ao Administrador.
    - O Administrador atribui avaliadores ao trabalho.
    - A Interface do Sistema salva os avaliadores atribuídos no Banco de Dados.
    - O Banco de Dados confirma a atribuição e a Interface do Sistema exibe uma mensagem de sucesso ao Administrador.
#### Intuito do Diagrama: 
O diagrama de sequência de criação de trabalho pelo administrador visa representar de forma clara o fluxo de atividades envolvidas na criação de um novo trabalho e na atribuição de avaliadores. Ele destaca as interações entre o administrador, a interface do sistema e o banco de dados.
#### O que o diagrama comunica: 
Este diagrama comunica o processo completo de criação de trabalhos pelo administrador, mostrando como ele pode criar um novo trabalho e atribuir avaliadores a ele. Ele proporciona uma visão clara das operações e interações necessárias para a criação e gestão inicial de trabalhos dentro do sistema.
- [Diagrama de sequência(Criação de trabalhos)](https://drive.google.com/file/d/1Rx4RfoG6sUpl11-e4mwz7d3X8Dq3RXUC/view?usp=sharing)
<br>

### Diagrama de Sequência de Gerenciamento de Trabalhos pelo Administrador
Descrição: Este diagrama de sequência descreve o processo de gerenciamento de trabalhos pelo administrador, incluindo a seleção, edição e exclusão de trabalhos.
#### Passo a Passo da Interação:
- Seleção de Trabalho:
    - O Administrador seleciona um trabalho para gerenciar na interface do sistema.
    - A Interface do Sistema consulta o Banco de Dados para obter os dados do trabalho.
    - Os dados do trabalho são retornados para a Interface do Sistema e exibidos para o Administrador.
- Edição de Trabalho:
    - O Administrador insere novos dados para o trabalho.
    - A Interface do Sistema envia os novos dados ao Banco de Dados para atualização.
    - O Banco de Dados confirma a atualização e a Interface do Sistema exibe uma mensagem de sucesso ao Administrador.
- Atualização de Avaliadores:
    - O Administrador seleciona avaliadores para atribuir ao trabalho.
    - A Interface do Sistema atualiza os avaliadores no Banco de Dados.
    - O Banco de Dados confirma a atualização e a Interface do Sistema exibe uma mensagem de sucesso ao Administrador.
- Exclusão de Trabalho:
    - O Administrador confirma a exclusão do trabalho.
    - A Interface do Sistema remove o trabalho do Banco de Dados.
    - O Banco de Dados confirma a remoção e a Interface do Sistema exibe uma mensagem de sucesso ao Administrador.
#### Intuito do Diagrama: 
O diagrama de sequência de gerenciamento de trabalhos pelo administrador visa representar de forma clara o fluxo de atividades envolvidas na seleção, edição e exclusão de trabalhos. Ele destaca as interações entre o administrador, a interface do sistema e o banco de dados.
#### O que o diagrama comunica: 
Este diagrama comunica o processo completo de gerenciamento de trabalhos pelo administrador, mostrando como ele pode selecionar, editar e excluir trabalhos, bem como atribuir avaliadores a esses trabalhos. Ele proporciona uma visão clara das operações e interações necessárias para manter e gerenciar os trabalhos dentro do sistema.
- [Diagrama de sequência(Gerenciamento de trabalhos)](https://drive.google.com/file/d/1i_CcQOk6pSvROf1FrsG-r21rXKukuhmA/view?usp=sharing)
<br>

### Diagrama de Sequência de Avaliação de Trabalhos pelo Avaliador
Descrição: Este diagrama de sequência descreve o processo de avaliação de trabalhos pelo avaliador, incluindo a solicitação da lista de trabalhos, a seleção de um trabalho para avaliação e a submissão da avaliação.
#### Passo a Passo da Interação:
- Solicitar Lista de Trabalhos:
    - O Avaliador solicita a lista de trabalhos atribuídos a ele para avaliação.
    - A Interface do Sistema recupera a lista de trabalhos do Banco de Dados e a exibe ao Avaliador.
- Selecionar Trabalho para Avaliação:
    - O Avaliador seleciona um trabalho para avaliar.
    - A Interface do Sistema recupera os detalhes do trabalho do Banco de Dados e os exibe ao Avaliador.
- Submeter Avaliação:
    - O Avaliador submete sua avaliação para o trabalho.
    - A Interface do Sistema salva a avaliação no Banco de Dados.
    - O Banco de Dados confirma o salvamento e a Interface do Sistema exibe uma mensagem de sucesso ao Avaliador.
#### Intuito do Diagrama: 
O diagrama de sequência de avaliação de trabalhos pelo avaliador visa representar de forma clara o fluxo de atividades envolvidas na solicitação da lista de trabalhos, seleção de um trabalho para avaliação e submissão da avaliação. Ele destaca as interações entre o avaliador, a interface do sistema e o banco de dados.
#### O que o diagrama comunica: 
Este diagrama comunica o processo completo de avaliação de trabalhos pelo avaliador, mostrando como ele pode solicitar a lista de trabalhos, selecionar um trabalho para avaliação e submeter sua avaliação. Ele proporciona uma visão clara das operações e interações necessárias para a avaliação de trabalhos dentro do sistema.
- [Diagrama de sequência(Avaliação de trabalhos)](https://drive.google.com/file/d/1wW3R-2jUuCo7btbpttFYmxBUA8zmL4Iw/view?usp=sharing)
<br>


  
## Colaboração
- [Pasta com todos diagramas de Colaboração](https://drive.google.com/drive/folders/1vpisEvQR0p8IOuLrUGXmo1yTITPketCB?usp=sharing)

### Diagrama de Colaboração de Login
Descrição: Este diagrama de colaboração representa o processo de autenticação de um usuário no sistema, incluindo a inserção das credenciais e o início da verificação.
#### Passo a Passo da Interação:
- Inserção de Credenciais:
    - Usuário insere nome de usuário e senha.
    - Interface do Sistema envia as credenciais para verificação.
- Verificação de Credenciais:
    - Interface do Sistema solicita ao Banco de Dados a verificação das credenciais.
- Solicitação de Recuperação de Senha (se necessário):
    - Se as credenciais forem inválidas, o Usuário pode solicitar recuperação de senha.
#### Intuito do Diagrama: 
O diagrama de colaboração de autenticação visa mostrar como o sistema interage internamente para processar as credenciais inseridas pelo usuário e iniciar o processo de verificação. Ele é útil para compreender o fluxo básico de autenticação no sistema e para desenvolver funcionalidades relacionadas à segurança e login.
- [Diagrama de colaboração (Login)](https://drive.google.com/file/d/1jyJ5MwAnfk_vx1dCT8zRd29jZM2AeouW/view?usp=sharing)
<br>

### Diagrama de Colaboração de Gerenciamento de Avaliadores pelo Administrador
Descrição: Este diagrama de colaboração ilustra as interações envolvidas no gerenciamento de avaliadores pelo administrador, incluindo adicionar, editar e remover avaliadores.
#### Passo a Passo da Interação:
- Adicionar Avaliador:
    - Administrador insere os dados do novo avaliador na Interface do Sistema.
- Editar Avaliador:
    - Administrador seleciona um avaliador para edição na Interface do Sistema.
    - Administrador insere novos dados para o avaliador na Interface do Sistema.
- Remover Avaliador:
- Administrador seleciona um avaliador para remoção na Interface do Sistema.
#### Intuito do Diagrama: O diagrama de colaboração de gerenciamento de avaliadores pelo administrador mostra como o administrador interage com o sistema para adicionar, editar e remover avaliadores. Ele é útil para entender as operações básicas de gerenciamento de usuários dentro do sistema de avaliação.
- [Diagrama de colaboração (Gerenciamento de avaliadores)](https://drive.google.com/file/d/1Bbc4E94rikqaKT7pZjew-Kxcpg-Yw1pj/view?usp=sharing)
<br>

### Diagrama de Colaboração de Criação de Trabalho pelo Administrador
Descrição: Este diagrama de colaboração ilustra as interações envolvidas na criação de um novo trabalho pelo administrador, incluindo a geração de um identificador único (UUID), a atribuição de avaliadores e o salvamento do trabalho no banco de dados.
#### Passo a Passo da Interação:
- Criação de Trabalho:
    - Administrador solicita a criação de um novo trabalho na Interface do Sistema.
- Geração de UUID:
    - Interface do Sistema gera um identificador único (UUID) para o novo trabalho.
- Atribuição de Avaliadores:
    - Administrador seleciona avaliadores para atribuir ao novo trabalho na Interface do Sistema.
- Salvar Trabalho no Banco de Dados:
    - Interface do Sistema salva os detalhes do novo trabalho, incluindo os avaliadores atribuídos, no Banco de Dados.
#### Intuito do Diagrama: 
O diagrama de colaboração de criação de trabalho pelo administrador mostra como o administrador interage com o sistema para criar, atribuir avaliadores e salvar um novo trabalho. Ele é útil para entender o fluxo completo de criação de novos registros dentro do sistema de gerenciamento de trabalhos, desde a geração de UUID até a atribuição de avaliadores e persistência dos dados no banco de dados.
- [Diagrama de colaboração (Criação de trabalho)](https://drive.google.com/file/d/1p7i-qp19SjAjGpb1xwV7zqhJch2UpyJ-/view?usp=sharing)
<br>

### Diagrama de Colaboração de Gerenciamento de Trabalhos pelo Administrador
Descrição: Este diagrama de colaboração descreve as interações envolvidas no gerenciamento de trabalhos pelo administrador, incluindo a seleção, edição e exclusão de trabalhos.
#### Passo a Passo da Interação:
- Seleção de Trabalho:
    - Administrador seleciona um trabalho na Interface do Sistema.
- Edição de Trabalho:
    - Administrador insere novos dados para o trabalho na Interface do Sistema.
- Atualização de Avaliadores:
    - Administrador seleciona avaliadores para o trabalho na Interface do Sistema.
- Exclusão de Trabalho:
    - Administrador confirma a exclusão do trabalho na Interface do Sistema.
#### Intuito do Diagrama: 
O diagrama de colaboração de gerenciamento de trabalhos pelo administrador mostra as interações básicas envolvidas na administração de trabalhos dentro do sistema. Ele é útil para visualizar como o administrador interage com a interface para realizar operações como edição, exclusão e atribuição de avaliadores aos trabalhos.
- [Diagrama de colaboração (Gerenciamento de trabalhos)](https://drive.google.com/file/d/1sjTLFPFPX6KZ-mCS_CdfXxAMD1k71iMt/view?usp=sharing)
<br>


### Diagrama de Colaboração de Avaliação de Trabalhos pelo Avaliador
Descrição: Este diagrama de colaboração descreve as interações envolvidas na avaliação de trabalhos por parte do avaliador, incluindo a solicitação de trabalhos, seleção de um trabalho para avaliação e submissão da avaliação.
#### Passo a Passo da Interação:
- Solicitação de Trabalhos:
    - Avaliador solicita a lista de trabalhos atribuídos a ele na Interface do Sistema.
- Seleção de Trabalho para Avaliação:
    - Avaliador seleciona um trabalho para avaliação na Interface do Sistema.
- Submissão de Avaliação:
-- Avaliador submete sua avaliação na Interface do Sistema.
#### Intuito do Diagrama: 
O diagrama de colaboração de avaliação de trabalhos pelo avaliador mostra como o avaliador interage com o sistema para visualizar, selecionar e avaliar trabalhos atribuídos a ele. Ele é útil para compreender o fluxo de trabalho do avaliador durante o processo de avaliação dentro do sistema de gestão de trabalhos.
- [Diagrama de colaboração (Avalição de trabalhos)](https://drive.google.com/file/d/15XkvaZYEfuC9eOoVTAwpmSPujEoYA4f7/view?usp=sharing)<br>
<br>




## Estados
### Introdução diagrama de estado
Um diagrama de estado é uma representação visual que mostra todas as possíveis situações em que um objeto ou entidade específica pode estar e como ela muda de uma situação para outra em resposta a eventos externos ou condições internas.
- [Diagrama de estado](https://drive.google.com/file/d/10JsNKK1O93fwbIdvtsBgtqpQqwzxTpdp/view?usp=sharing)<br>
#### Para o sistema de gerenciamento de submissão e avaliação de projetos SIMPAC, o diagrama de estado pode ser usado da seguinte maneira: 
- Login: Administradores e avaliadores usam o diagrama para entender o fluxo de login, incluindo o que acontece em caso de sucesso ou falha. <br>
- Cadastro e Avaliação: O diagrama mostra claramente como os administradores cadastram novos projetos e como os avaliadores realizam suas avaliações, incluindo possíveis erros e suas correções .
- Usuários do Sistema: Visualização de Resultados: O diagrama ajuda os usuários a entender como podem acessar os resultados das avaliações de projetos, partindo do menu principal. 
- Desenvolvimento e Manutenção: implementação: Os desenvolvedores seguem o diagrama para garantir que todos os estados e transições estão implementados corretamente. 
- Atualizações: Em caso de atualizações ou manutenção do sistema, o diagrama ajuda a identificar rapidamente como novos estados ou transições devem ser adicionados ou modificados. O diagrama de estado é, portanto, uma ferramenta poderosa para visualizar, planejar, implementar e manter sistemas complexos, garantindo que todos os aspectos do comportamento do sistema sejam compreendidos e bem gerenciados.
<br>




## Atividade
### Introdução aos diagramas de atividade
Os diagramas de atividades são ferramentas essenciais em projetos de software e de negócios, utilizadas para modelar e visualizar processos e fluxos de trabalho. Utilizando a notação da UML (Unified Modeling Language), esses diagramas descrevem a sequência de atividades ou ações que compõem um processo, incluindo decisões, bifurcações e paralelismos. Eles trazem clareza e compreensão dos processos, fornecem documentação detalhada, permitem a análise e melhoria dos processos existentes e servem como base para a automação de processos complexos.
- [Diagrama de atividades](https://drive.google.com/file/d/1QDAD4aZ3M_reVsbW9c4UJNqmsZpzd4px/view?usp=sharing) <br>
No projeto em questão, foram utilizados diversos diagramas de atividades para diferentes processos.

### Diagrama de logout
Modela o processo de um usuário se desconectando do sistema, começando com a escolha da opção de "Sair", passando pela confirmação do logout, encerramento da sessão e redirecionamento para a página de login. Isso garante que o processo de logout seja executado corretamente, assegurando a segurança e usabilidade do sistema.

### Diagrama de login 
Descreve o processo de entrada no sistema, desde o acesso à página de login, a inserção e validação das credenciais, até a concessão de acesso aos recursos disponíveis. Ele também inclui um fluxo alternativo para a recuperação de senha, caso o usuário a esqueça. Este diagrama melhora a usabilidade e a segurança do sistema, detalhando claramente o processo de autenticação do usuário.

### Diagrama Visualização dos resultados do simpósio
Modela como o administrador visualiza os resultados, permitindo a filtragem por curso e apresentando os resultados em uma tabela organizada por tipo de apresentação. Isso assegura que o processo de visualização dos resultados seja eficiente e compreensível, proporcionando uma maneira clara de acessar as informações.

### Diagrama atribuição de avaliadores 
Descreve o processo de atribuir avaliadores a um trabalho específico, começando com a solicitação do administrador, a apresentação de uma lista de avaliadores disponíveis, a seleção e associação dos avaliadores ao trabalho, e a confirmação da atribuição. Ele também inclui fluxos alternativos para lidar com a indisponibilidade de avaliadores ou a decisão de cancelar a atribuição. Este diagrama garante que o processo de atribuição seja compreendido e executado corretamente.

### Diagrama de avaliação de trabalhos
Descreve como um avaliador revisa um trabalho atribuído, atribui uma nota, fornece comentários adicionais e registra a avaliação. Ele também permite que o avaliador interrompa e retome a avaliação posteriormente. Este diagrama assegura que o processo de avaliação seja realizado de forma organizada e eficiente.

### Diagrama de gerenciamento de avaliadores 
Detalha o processo pelo qual o administrador gerencia os avaliadores, começando com a solicitação de gerenciamento, a apresentação das opções de visualizar, excluir ou cadastrar novos avaliadores, a escolha de uma dessas opções e o preenchimento das informações necessárias para o cadastro de um novo avaliador. Ele inclui um fluxo alternativo para lidar com avaliadores já cadastrados ou informações incorretas, retornando ao fluxo principal. Este diagrama assegura que o processo de gerenciamento de avaliadores seja claro e eficiente.

### Diagrama Visualização de trabalhos 
Descreve como o administrador visualiza os trabalhos, começando com a solicitação de visualização, a listagem dos trabalhos pelo sistema, a exibição dos detalhes dos trabalhos e a navegação pela lista de trabalhos para acessar todas as informações disponíveis. Ele inclui um fluxo alternativo para o caso do administrador cancelar a visualização, retornando ao menu. Este diagrama assegura que o processo de visualização dos trabalhos seja eficiente e compreensível.

### Diagrama gerenciamento de trabalhos 
Modela o processo pelo qual o administrador gerencia os trabalhos, começando com a solicitação de gerenciamento, a apresentação das opções de criar um novo trabalho ou visualizar os trabalhos existentes, a escolha de uma dessas opções e o preenchimento das informações necessárias para o cadastro de um novo trabalho. Ele inclui um fluxo alternativo para lidar com problemas na validação dos dados do novo trabalho ou durante a edição de um trabalho existente, notificando o administrador sobre os erros encontrados e solicitando as correções necessárias. Este diagrama assegura que o processo de gerenciamento de trabalhos seja claro e eficiente.

### Objetivo:
Esses diagramas ajudam a garantir que os processos sejam claros, compreensíveis e corretamente executados, melhorando a eficiência, segurança e usabilidade do sistema.
<br>



## Fluxograma
- Foi organizado um fluxograma para orgarnizar as informações, identificar ações que podem ser feitas para os objetivos da organização ou avaliador.
- [Fluxograma do sistema](https://drive.google.com/file/d/1n8rzIqqmWy4uYPwh4GzWloxJ3DBx3u-o/view?usp=sharing) <br>

## Avaliação - Especificação de requisitos 
Foi realizado o refinamento dos requisitos de nível de usuário para o nível de sistema para auxiliar os desenvolvedores na etapa de prototipação do sistema.

- [Documento de requisitos a nível de sistema](Processos/Sprint_3/Requisitos_do_Sistema_para_o_Projeto_SIMPAC.pdf)
<br>

## Avaliação - Especificação de requisitos
### Validação de requisitos com o cliente
- Foi feita uma reunião com o cliente a fim de validar os requisitos de usuário e sistema
- O responsável pelo projeto vizualizou a falta de alguns requisitos em algumas funcionalidades.
    - Cadastrar trabalhos: Falta de um atributo para os trabalhos do SIMPAC sendo eles para selecionar uma opção entre as três: trabalho de ensino, pesquisa, extensão.
    - Avaliação de trabalhos: Ao final da avaliação o avaliador deve definir se o trabalho é poster ou oral.
    - O sistema de avalição sofreu uma alteração em que as notas passaram a ser fracionadas de 1 a 10. 
- Além disso o cliente sinalizou a preferencia de um requisito não funcional:
    - Após um finalizar a avaliação de um trabalho o trabalho avalido fica em verde na lista de trabalhos.
- Anotamos as correções necessárias para realizar as alterações no protótipo.
- Todas as alterações necessárias foram feitas.
- A cliente assinou o Documento de Validação de Requisitos, contendo os requisitos de usuário e de sistema, validando assim os requisitos. <br>
[Documento de validação dos requisitos assinado pela responsável](https://drive.google.com/file/d/1k55bVL8fmbQikqs3sFH9G-W-cGIN8-WT/view?usp=sharing)

## Projeto conceitual e concepção do design
### Identidade visual

<p align="center">
  <img src="ID visual.png" alt="Identidade Visual" />
  <br />
 Figura 7 - Identidade Visual
</p>

#### Tipografia:

- Imagem 1: Representa o "Simpósio de Produção Acadêmica," destacando a interação e apresentação de trabalhos acadêmicos.

- Imagem 2: Representa o "Sistema para calcular os resultados de maneira rápida e eficaz," destacando a automatização e eficiência do sistema.

##### Logotipo:

- Nome: Utilizado com a fonte específica da que estava no site da univicosa.

- Símbolo: Inclui a edição do simpósio, representada pelo elemento "XV" no exemplo, que pode ser atualizado conforme necessário.

- A fonte utilizada é "League Spartan" em suas variações Bold e Regular.

##### Paleta de Cores:

- #000000 (Preto): Cor sólida que passa uma sensação de seriedade e formalidade.

- #205483 (Azul Escuro): Transmite confiança, segurança e estabilidade. mantendo a identidade visual da faculdade.

- #00AFEFF (Azul Claro): Cor vibrante que sugere modernidade e dinamismo.

- #2C2D48 (Azul Marinho): Cor elegante e profissional que complementa as outras tonalidades de azul.

- #FFFFFF (Branco): Representa clareza e simplicidade, utilizada como cor de fundo para contrastar com as demais cores.

### Design e Iteração
#### Soluções Propostas
- Padronização do Método Avaliativo
- Sistema com Níveis de Acesso
- Criação de Login e Senha para Avaliadores
- Facilidade na Criação e Deleção de Avaliadores
- Comunicação Segura por E-mail e Celular
- Reformulação Geral do Design
- Criação e Edição de Trabalhos Simplificadas


## Wireframe
A partir do fluxograma, foi criado então o wireframe, que é uma representação visual básica e esquemática da estrutura de nossa aplicação web. Seu objetivo principal pe definir a distribuição de elementos da natela, sem se preocupar muito com detalhes visuais.

- Pela tela inicial será possível observar informações como em qual edição o evento se encontra. E qual caminho o usuario gostaria de seguir.
- Para todas escolhas elas serão necessárias um login para confirmar a identidade porém alguns podem ser organizadores e terão um maior nível de acesso.
- O administrador poderá criar os trabalhos para serem avaliados, alterar eles caso tenham cometido erros ou até mesmo apagar, conferir os resultados, checar os avaliadores cadastrados além de poder adicionar ou excluir caso seja necessário.
-  O Avaliador quando terminar suas avaliações lhe será mostrado uma tabela com informações de seus votos e caso o mesmo queira trocar ele terá a oportunidade.
- Para os resultados, que serão disponíveis apenas à organização do evento, lhe será disposto um login e ao entrar, basta escolher o curso que deseja olhar no momento, e será mostrado uma tabela com as notas tanto em poster quanto apresentações orais.

![Wireframe](./DIAGRAMAS/Wireframe-SIMPAC(1).png)
Figura 8 - Wireframe

### Versão de baixa fidelidade
<details>
<summary>Clique para expandir as imagens</summary>


![V.1 Atomic Code](./Processos/Sprint_3/V.%20Intermediaria%20da%20solucao/d-1%20papel.jpg)
Figura 9 - Versão de baixa fidelidade
![V.1-1 Atomic Code](./Processos/Sprint_3/V.%20Intermediaria%20da%20solucao/d1.1%20papel.jpg)
Figura 10 - Versão de baixa fidelidade
![V.1-2 Atomic Code](./Processos/Sprint_3/V.%20Intermediaria%20da%20solucao/d-1.2%20papel.jpg)
Figura 11 - Versão de baixa fidelidade

</details>

# Protótipo de Alta Fidelidade
## Prototipação

O Figma foi utilizado como ferramenta de prototipação desenolvendo assim o prototipo de alta fidelidade, corrigndo alguns pontos e refinando ainda mais a usabilidade do sistema para fornecer uma experiência mais agradável aos usuários.
-Existem dois protótipos, o desenvolvido pensado em dispositivos móveis e desktop.

- [Protótipo_Mobile](https://www.figma.com/proto/hQG8Ps6ihemtjCYfmpa5NJ/SIMAPAC-por-Vinicius?node-id=1-1254&t=Eg1O8OMdSZnxBV7A-1)
- [Protótipo_Desktop](https://www.figma.com/proto/yDMbtaIZQP5urNRLNSLaIW/SIMPAC-por-Vinicius?node-id=659-877&t=6aQJH7TexvGHqaKf-1&scaling=scale-down&page-id=0%3A1&starting-point-node-id=557%3A4148&show-proto-sidebar=1)
- [Vídeo apresentando o protótipo mobile](https://drive.google.com/file/d/1xcAjiEQ-fimfI_R7E-5RjRhMnTQBAMBA/view?usp=sharing)
- [Vídeo apresentando o protótipo desktop](https://drive.google.com/file/d/1eX4Vxp6FyY1Kj83jH9EisYLPSSTS6XEk/view?usp=sharing)

# Avaliação do protótipo
## Metodologia de Avaliação
Foi realizada uma reunião presencial com o cliente utilizando a segunda versão do protótipo (pós Avaliação Especificação de requisitos). Durante o encontro foram definidas algumas metadas que o cliente deveria alcançar no aplicativo, tais como, criar projeto, definir avaliador para projeto, avaliar projeto. O intuito era testar todas funcionaliades do sistema e e se sua interface era de fácil entendimento.
## Execução da Avaliação
O cliente utilizou o prototipo livremente tentando alcançar as metas. 
## Resultado da Avaliação
O cliente ficou extremamente satisfeito, apenas não dando nota máxima para funções bem entegradas e facilidade de utilizar o sistema, mais detalhes sobre o resultado da avalição podem ser consultadas no questionario.
- [Questionário de avalição do Evoluir Ti](https://drive.google.com/file/d/1XYwb2_f2M5CAHD5g2rS246TM8mdB1nfj/view?usp=sharing)
## Conclusão
O cliente validou o prótotipo.
- [Documento do protótipo](Processos/Documento_de_Validacao_de_Prototipo_assinado.pdf)




# Processo contínuo
- Sera realizado um Pitch do projeto ao cliente, especialistas e investidores, frisar novamente todas as funcionalidades do protótipo e mostrar o sitema (protótipo), e como iria auxilar as partes interessadas (avaliadores e avaliados no SIMPAC) a solucinar os problemas relacionados a falta de informatização no processo de avaliação de projetos do SIMPAC-UNIVIÇOSA;

# Projetos Futuros
## Implementação
O projeto atual está sendo desenvolvido com base nas matérias de Interação Humano Computador e Engenharia de Software II, a implementação do trabalho em questão será feita no próximo semestre na matéria de Arquitetura de Software e Projeto Integrador.
## Modificações
Os dados a serem cadastrados serão importados de de outro sistema, podendo assim utilizar o arquivo do banco de dados do outro sistema e subir esse arquivo no sistema Evoluir TI.

# Conclusão
Finalizamos assim mais um projeto integrador, esse que foi proposta e orientado pela professora Cristiane Aparecida Lana, com o objetivo de atender as demandas da NUPEX da Univiçosa. O projeto em questão tem o intuito de criar uma empresa simulada, promovendo o trabalho em equipe, o atendimento de clientes reais com desesafios reais. Dessa forma, a ATOMIC CODE desenvolvel todos processos reais de um projeto de desenolvimento de software, desde a fase de documentação até a criação de um prototipo de alta filidade. 

### Esse projeto foi desenvolvido por:

- Antônio Henrico Aguiar Lopes, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Vinicius Fontes, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Lucas Fontes, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Gabriel Ribas Pena, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- André, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Pedro, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Reberth, Estudante de Desenvolvimento de Software da UNIVIÇOSA
    

