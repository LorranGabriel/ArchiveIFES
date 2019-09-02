# Archive IFES - Projeto de Sistemas

### 1) Descrição do Contexto(Minimundo)
> Atualmente o IFES campus serra é uma das referencias em inovações no ambito academico. O campus possui muitos laboratorios de pesquisa e com frequencia ocorrem publicações dos mesmos. Um sistema Web que fornece informações sobre os projetos desenvolvidos dentro do IFES - Campus Serra seria de muita utilidade. Ele armazenará informações referentes a dados técnicos do projeto, pessoas que estão envolvidas, competições e eventos as quais já participou ou irão participar, além de possuir vídeos, fotos, comentários dos autores e usuários. Possuirá tambem uma área dedicada a informar se o projeto está em desenvolvimento ou finalizado, caso esteja em desenvolvimento terá a possibilidade de visualizar as vagas para o mesmo.

### 2) Requisitos Não Funcionais

Identificador | Descrição | Categoria | Escopo 
:---------: | ---------- | :---------: | :---------: |
RNF01 |O sistema deve possuir uma linguagem simples e ser de facil navegabilidade        | Usabilidade | Sistema|
RNF02 |O sistema deve ser capaz de autenticar usuários                                   |Segurança de acesso |Sistema|
RNF03 |O sistema deve ser capaz de validar a permissão para editar projetos              |Segurança de acesso |Sistema|
RNF04 |O sistema deve ser capaz de futuramente possuir uma versão mobile                 |Portabilidade|Funcionalidade|
RNF05 |O sistema deve ser capaz de receber upload de videos e fotos                      |Eficiência de recursos|Sistema |
RNF06 |O sistema deve ser capaz de facilitar a comunicação entre parcerias e novos contratos     |           |Sistema| 
RNF07 |O sistema deve ser capaz de receber mensagens e sugestões da comunidade externa           |           |Sistema|


### 3) Táticas para tratar Atributos de qualidade

Categoria | Requisitos Não Funcionais | Condutor de Arquitetura | Tática  
:---------: | :----------: | --------- | --------- |
Facilidade de Operação |   RNF01      |           |Mensagens de auxilio ao usuário, simplificar textos e utilizar imagens autoexplicativas.             |
Segurança de Acesso | RNF02, RNF03  |           |Validação dos campos, exibir mensagens de erro/informações, histórico de edição/visualização dos projetos, autenticação por login e senha, confirmação por email.          |
   Portabilidade   |    RNF04      |           |Utilizar ferramenta que permite expansão do sistema para outra plataforma (mobile), construir um sistema responsivo.           |
 Eficiência de recursos |    RNF05      |           |Padronizar formato, tamanho e extensão dos dados de entrada no sistema. Ou disponibilizar o link do arquivo.|
Facilidade de Operação |   RNF06      |           |Feed de mensagens e notificações para pesquisadores e para as parcerias.|
Facilidade de Operação |   RNF07      |           |Feed de mensagens e notificações para pesquisadores e para as parcerias.| 


          
### 4) Protótipos de Tela do Sistema

