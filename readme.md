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
Num dia comum do SIMPAC na UniViçosa, a membro essencial do NUPEX Luana Pereira, se encontrou em uma situação desafiadora. Após um longo dia de avaliações de projetos, a professora perdeu as folhas onde havia registrado a avaliação de seus designados grupos. Foi a primeira vez que algo assim acontecia, e a sensação de desespero tomou conta dela.

O não apenas abalou Luana, mas também acendeu uma luz de alerta na secretaria do NUPEX, que atende a uma necessidade urgente de evitar futuros problemas semelhantes. Além disso, o processo de avaliação manual, apesar do tradicional, era lento e vulnerável a riscos, como o ocorrido com Luana.

A busca por uma solução levou a cordenadora do NUPEX a um momento de reflexão sobre inovação no sistema de avaliação do SIMPAC. Em seu braid storme, ela se deparou com uma abordagem revolucionária: um aplicativo que simplificava todo o processo de avaliação, tornando-o digital e seguro.

Esse sistema inovador permitiu que as avaliações fossem realizadas e organizadas por meio de um aplicação web no celular, eliminando assim os riscos de perda, otimizando o tempo e facilitando a vida dos avaliados. Com login e senha, o sistema garante a segurança e acessibilidade exclusiva aos avaliados, protegendo a confidencialidade das avaliações.

A implementação desse novo sistema transformou a dinâmica do SIMPAC. Agora, o aplicativo de avaliações não apenas mitigava a possibilidade de incidentes como o de Luana, mas também tornava todo o processo mais eficiente e prático. A narrativa evidencia como a introdução de uma tecnologia inovadora pode redefinir um processo burocrático, atendendo às necessidades e frustrações dos usuários finais, e marcando uma nova era de eficiência no SIMPAC da Univiçosa.

## OMS - Análise das Partes Interessadas

### Personas
Baseado no storytelling, as personas foram criadas para representar os stakeholders.
![persona](./Processos/Sprint_3/Relatorio%20Atualizado/Persona-1_page-0001.jpg)
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
3. Estruturação do Mapa da Empatia:
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


---

## Engenharia de requisitos

### Elicitação de requisitos

A Elicitação de requisitos foi realizada através de uma reunião com um cliente que junto com nossa equipe foram levantados os requisitos para resolver o atual problema da avalição do SIMPAC, 
estes requisitos foram documentados a nível de usuário, ou seja, a um nível de explicação mais simples que o próprio cliente consegue compreender.

- [Documento de requisitos a nível de usuário](Processos/Sprint_3/Requisitos_de_usuário.pdf)

## Análise de requisitos
### Casos de Uso
- [Diagráma casos de uso](https://drive.google.com/file/d/1HSCV19wCrxr_p65Y4pJA0-9oUrmQJJSd/view?usp=sharing) <br>

#### Usuários:
- Admin: O administrador do sistema, que tem várias responsabilidades de gerenciamento.
- Avaliador: A pessoa que realiza as avaliações dos trabalhos.
- Usuários: Admin e Avaliadores.
#### Funcionalidades do Sistema:
##### Login e Logout
- Todos os usuários podem entrar e sair do sistema com segurança.
##### Gerenciamento de Trabalhos
- Os administradores podem criar, editar e organizar os trabalhos que precisam ser avaliados.
##### Atribuição e gerenciamento de Avaliadores
- Os administradores designam avaliadores específicos para cada trabalho.
- Os administradores também gerenciam o cadastro e as informações dos avaliadores.
##### Visualização de Trabalhos
- Adminstradores podem ver todos trabalhos.
- Avaliadores só podem vizualizar os trabalhos a quais foram designados.
##### Realização de Avaliações
- Os avaliadores realizam as avaliações dos trabalhos atribuídos a eles, seguindo critérios específicos.
##### Visualização de Avaliações
- Adminstradores podem ver as avaliações de todos trabalhos .
- Avaliadores só podem vizualizar os trabalhos a quais foram designado.
##### Visualização de Resultados
- Adminstradores podem ver os resultados de trabalhos.
- Avaliadores só podem vizualizar os trabalhos a quais foram designado.

#### Sequência
- [Diagráma de sequência](https://drive.google.com/file/d/1kqzm1ggbv5xz82-ZDJbS10ESY5_t3-ZP/view?usp=sharing) <br>
#### Classes
- [Diagráma de classes](https://drive.google.com/file/d/1AuMt8c_RJhknCfidFCA7WQmffumdQa0K/view?usp=sharing) <br>
#### Colaboração
- [Diagráma de colaboração](https://drive.google.com/file/d/17flyofmhTykFYNmgYqyAsTEph1lcKjSO/view?usp=sharing) <br>
#### Estados
- [Diagráma de estados](https://drive.google.com/file/d/17flyofmhTykFYNmgYqyAsTEph1lcKjSO/view?usp=sharing) <br>
##### Para o sistema de gerenciamento de submissão e avaliação de projetos SIMPAC, o diagrama de estado pode ser usado da seguinte maneira: 
- Login: Administradores e avaliadores usam o diagrama para entender o fluxo de login, incluindo o que acontece em caso de sucesso ou falha. <br>
- Cadastro e Avaliação: O diagrama mostra claramente como os administradores cadastram novos projetos e como os avaliadores realizam suas avaliações, incluindo possíveis erros e suas correções .
- Usuários do Sistema: Visualização de Resultados: O diagrama ajuda os usuários a entender como podem acessar os resultados das avaliações de projetos, partindo do menu principal. 
- Desenvolvimento e Manutenção: implementação: Os desenvolvedores seguem o diagrama para garantir que todos os estados e transições estão implementados corretamente. 
- Atualizações: Em caso de atualizações ou manutenção do sistema, o diagrama ajuda a identificar rapidamente como novos estados ou transições devem ser adicionados ou modificados. O diagrama de estado é, portanto, uma ferramenta poderosa para visualizar, planejar, implementar e manter sistemas complexos, garantindo que todos os aspectos do comportamento do sistema sejam compreendidos e bem gerenciados.
#### Atividades
- [Diagráma de atividades](https://drive.google.com/file/d/1QDAD4aZ3M_reVsbW9c4UJNqmsZpzd4px/view?usp=sharing) <br>



### Fluxograma
- Foi organizado um fluxograma para orgarnizar as informações, identificar ações que podem ser feitas para os objetivos da organização ou avaliador.

[Fluxograma](https://drive.google.com/file/d/1n8rzIqqmWy4uYPwh4GzWloxJ3DBx3u-o/view?usp=sharing)
Figura 7 - Fluxo Grama do sitema

## Avaliação - Especificação de requisitos 
Foi realizado o refinamento dos requisitos de nível de usuário para o nível de sistema para auxiliar os desenvolvedores na etapa de prototipação do sistema.

- [Documento de requisitos a nível de sistema](Processos/Sprint_3/Requisitos_do_Sistema_para_o_Projeto_SIMPAC.pdf)

## Avaliação - Especificação de requisitos
### Validação de requisitos com o cliente
- Entramos em contato com a cliente por meio do aplicativo de mensagens WhatsApp para validar os requisitos de usuário e de sistema.
- Os responsáveis pelo projeto apresentaram algumas dúvidas sobre os requisitos que não ficaram claras.
- Anotamos as correções necessárias para realizar as alterações no protótipo.
- A cliente assinou o Documento de Validação de Requisitos, contendo os requisitos de usuário e de sistema, validando assim os requisitos. (Não houve nenhuma queixa da cliente sobre os requisitos já registrados)<br>
[Documento de validação dos requisitos assinado pela responsável](https://drive.google.com/file/d/1k55bVL8fmbQikqs3sFH9G-W-cGIN8-WT/view?usp=sharing)

## Projeto conceitual e concepção do design
### Identidade visual

<p align="center">
  <img src="ID visual.png" alt="Identidade Visual" />
  <br />
  Figura XX
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

### Versão de baixa fidelidade
<details>
<summary>Clique para expandir as imagens</summary>


![V.1 Atomic Code](./Processos/Sprint_3/V.%20Intermediaria%20da%20solucao/d-1%20papel.jpg)
imagem XX
![V.1-1 Atomic Code](./Processos/Sprint_3/V.%20Intermediaria%20da%20solucao/d1.1%20papel.jpg)
imagem XX
![V.1-2 Atomic Code](./Processos/Sprint_3/V.%20Intermediaria%20da%20solucao/d-1.2%20papel.jpg)
imagem XX

</details>

Figura XX - WireFrame Final

# Protótipo de Alta Fidelidade
## Prototipação

O Figma foi utilizado como ferramenta de prototipação desenolvendo assim o prototipo de alta fidelidade, corrigndo alguns pontos e refinando ainda mais a usabilidade do sistema para fornecer uma experiência mais agradável aos usuários.
-Existem dois protótipos, o desenvolvido pensado em dispositivos móveis e desktop.

- [Protótipo_Mobile](https://www.figma.com/proto/yDMbtaIZQP5urNRLNSLaIW/SIMPAC-por-Vinicius?type=design&node-id=1-4&t=I9H7ZyO9Fwrh1jV3-1&scaling=scale-down&page-id=32%3A289&starting-point-node-id=1%3A4&show-proto-sidebar=1&mode=design)
- [Protótipo_Desktop](https://www.figma.com/proto/bKh50EThTPfSIAmffkghy4/Untitled?type=design&node-id=0-3&t=LEdIqh2ObP9xoNPn-1&scaling=scale-down-width&page-id=0%3A1&starting-point-node-id=0%3A3&mode=design)

## Avaliação do protótipo
[AINDA NÃO FEITO]
# Processo contínuo

- [Vídeo explicativo sobre o protótipo]
- Sera realizado um Pitch do projeto ao cliente, especialistas e investidores, frisar novamente todas as funcionalidades do protótipo e mostrar o sitema (protótipo), e como iria auxilar as partes interessadas (avaliadores e avaliados no SIMPAC) a solucinar os problemas relacionados a falta de informatização no processo de avaliação de projetos do SIMPAC-UNIVIÇOSA;

# Implementação
O projeto atual está sendo desenvolvido com base nas matérias de Interação Humano Computador e Engenharia de Software II, a implementação do trabalho em questão será feita no próximo semestre na matéria de Arquitetura de Software e Projeto Integrador.

### Esse projeto foi desenvolvido por:

- Antônio Henrico Aguiar Lopes, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Vinicius Fontes, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Lucas Fontes, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Gabriel Ribas Pena, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- André, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Pedro, Estudante de Desenvolvimento de Software da UNIVIÇOSA
- Reberth, Estudante de Desenvolvimento de Software da UNIVIÇOSA
    

