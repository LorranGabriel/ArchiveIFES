# Archive IFES - Projeto de Sistemas

### 1) Descrição do Contexto(Minimundo)
> Atualmente o IFES campus serra é uma das referências em inovações no âmbito acadêmico. O campus possui muitos laboratórios de pesquisa e com frequência ocorrem publicações dos mesmos. O projeto Arquivo IFES será desenvolvido tanto na plataforma mobile quanto para web, tendo como principal objetivo fornecer e receber informações sobre os projetos desenvolvidos dentro do IFES - Campus Serra. Ele armazenará informações referentes a dados técnicos do projeto, colaboradores que estão envolvidos, competições e eventos as quais o laboratório/projeto já participou ou irão participar, além de exibir vídeos, fotos, comentários dos autores e usuários. Possuirá também uma área dedicada a informar se o projeto está em desenvolvimento ou finalizado, caso esteja em desenvolvimento terá a possibilidade de visualizar as vagas para o mesmo. O projeto é direcionado a usuários do IFES e da comunidade externa, porém a comunidade externa terá acesso restrito na plataforma, apenas alunos e professores integrantes de projetos e laboratorios de pesquisa poderão editar, adicionar ou remover informações da plataforma mediante avaliação dos administradores do sistema, todos as alterações serão salvas em um histórico com as versões do projeto.

### 2) Requisitos Não Funcionais

Identificador | Descrição | Categoria | Escopo 
:---------: | ---------- | :---------: | :---------: |
RNF01 |O sistema deve possuir uma linguagem simples e ser de facil navegabilidade        |Usabilidade| Sistema|
RNF02 |O sistema deve ser capaz de autenticar usuários                                   |Segurança de acesso |Sistema|
RNF03 |O sistema deve ser capaz de validar a permissão para editar projetos              |Segurança de acesso |Sistema|
RNF04 |O sistema deve ser capaz de futuramente possuir uma versão mobile                 |Portabilidade|Funcionalidade|
RNF05 |O sistema deve ser capaz de receber upload de videos e fotos                      |Eficiência de recursos|Sistema |
RNF06 |O sistema deve ser capaz de facilitar a comunicação entre parcerias e novos contratos     |Usabilidade|Sistema| 
RNF07 |O sistema deve ser capaz de receber mensagens e sugestões da comunidade externa           |Usabilidade|Sistema|


### 3) Táticas para tratar Atributos de qualidade

Categoria | Requisitos Não Funcionais | Condutor de Arquitetura | Tática  
:---------: | :----------: | --------- | --------- |
Facilidade de Operação |   RNF01      |           |Mensagens de auxilio ao usuário, simplificar textos e utilizar imagens autoexplicativas.             |
Segurança de Acesso | RNF02, RNF03  |           |Validação dos campos, exibir mensagens de erro/informações, histórico de edição/visualização dos projetos, autenticação por login e senha, confirmação por email.          |
   Portabilidade   |    RNF04      |           |Utilizar ferramenta que permite expansão do sistema para outra plataforma (mobile), construir um sistema responsivo.           |
 Eficiência de recursos |    RNF05      |           |Padronizar formato, tamanho e extensão dos dados de entrada no sistema. Ou disponibilizar o link do arquivo.|
Facilidade de Operação |   RNF06, RNF07     |           |Feed de mensagens e notificações para pesquisadores e para as parcerias.|


          
### 4) Protótipos de Tela do Sistema

