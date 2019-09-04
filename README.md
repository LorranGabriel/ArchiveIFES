# Archive IFES - Projeto de Sistemas

### 1) Descrição do Contexto(Minimundo)
> Atualmente o IFES campus serra é uma das referências em inovações no âmbito acadêmico. O campus possui muitos laboratórios de pesquisa e com frequência ocorrem publicações dos mesmos. O projeto Arquivo IFES será desenvolvido tanto na plataforma mobile quanto para web, tendo como principal objetivo fornecer e receber informações sobre os projetos desenvolvidos dentro do IFES - Campus Serra. Ele armazenará informações referentes a dados técnicos do projeto, colaboradores que estão envolvidos, competições e eventos as quais o laboratório/projeto já participou ou irão participar, além de exibir vídeos, fotos, comentários dos autores e usuários. Possuirá também uma área dedicada a informar se o projeto está em desenvolvimento ou finalizado, caso esteja em desenvolvimento terá a possibilidade de visualizar as vagas para o mesmo. O projeto é direcionado a usuários do IFES e da comunidade externa, como instituições financiadoras e visitantes em geral, porém a comunidade externa terá acesso restrito a plataforma. Nem sempre esse usuario de fora do meio academico possui o conhecimento tecnico necessario para entender com plenitude a linguagem empregada nos artigos e documentos, logo é de grande importancia o sistema ser moldado para o melhor entendimento dos projetos, mesmo que a linguagem das publicações sejam imutaveis. Apenas alunos e professores integrantes de projetos e laboratorios de pesquisa poderão editar, adicionar ou remover informações da plataforma mediante avaliação dos administradores do sistema, todos as alterações serão salvas em um histórico com as versões do projeto. Futuramente pretende-se expandir a plataforma Arquivo IFES para outros campus da grande Vitória.

### 2) Requisitos Não Funcionais

Identificador | Descrição | Categoria | Escopo 
:---------: | ---------- | :---------: | :---------: |
RNF01 |O sistema deve possuir uma linguagem simples e ser de facil navegabilidade.        |Usabilidade| Sistema|
RNF02 |O sistema deve ser capaz de autenticar usuários.                                   |Segurança de acesso |Sistema|
RNF03 |O sistema deve ser capaz de validar a permissão para editar projetos e armazenar o historico de edições, o histórico deve conter informações referentes ao usuário,data , hora e a modificação realizada no projeto. |Segurança de acesso |Sistema|
RNF04 |O sistema deve ser capaz de futuramente possuir uma versão mobile.                 |Portabilidade|Funcionalidade|
RNF05 |O sistema deve ser capaz de receber upload de videos e fotos referentes aos projetos desenvolvidos.  |Eficiência de recursos|Sistema |
RNF06 |O sistema deve ser capaz de facilitar a comunicação entre parcerias e novos contratos atravéz de mensagens pela plataforma e a partir de emails cadastrados.     |Usabilidade|Sistema| 
RNF07 |O sistema deve ser capaz de receber mensagens e sugestões de qualquer visitante que seja uma pessoa fisica.           |Usabilidade|Sistema|
RNF08 |A persistência das informações deverão ser implementadas em um primeiro momento utilizando ElephantSQL (armazenamento na nuvem). Entretanto no futuro deve ser possível utilizar outras tecnologias de persistência.| Portabilidade | Sistema  |
RNF09 |As funcionalidades dos administradores deverão ser acessiveis apenas via plataforma desktop, já os usuários cadastrados(alunos e professores) poderão ter acesso a suas funcionalidades tanto na versão mobile quanto na versão desktop.| Funcionalidade | Sistema |
RNF10 | Um usuário novato/visitante deverá aprender qualquer funcionalidade em no máximo 5 minutos, visto que a maioria das funcionalidades serão de visualização e envio de mensagens|    Facilidade de Operação   |   Funcionalidade    |
RNF11 | A entrada de dados/preenchimento dos campos deve durar no máximo 1 minuto, para usuários experientes e que já estão cadastrados na plataforma|   Operacionalidade    |   Funcionalidade   | 


### 3) Táticas para tratar Atributos de qualidade

Categoria | Requisitos Não Funcionais | Condutor de Arquitetura | Tática  
:---------: | :----------: | :---------: | --------- |
Facilidade de Operação |   RNF01      |     Não      |Mensagens de auxilio ao usuário, simplificar textos e utilizar imagens autoexplicativas.             |
Segurança de Acesso | RNF02, RNF03  |  Não  |Validação dos campos, exibir mensagens de erro/informações, histórico de edição/visualização dos projetos, autenticação por login e senha, confirmação por email.          |
   Portabilidade   |    RNF04      |   Sim   |Utilizar ferramenta que permite expansão do sistema para outra plataforma (mobile), construir um sistema responsivo.           |
 Eficiência de recursos |    RNF05      |           |Padronizar e especificar formato, tamanho e extensão dos arquivos de entrada no sistema. Ou disponibilizar o link do arquivo em um campo destinado.|
Facilidade de Operação |   RNF06, RNF07   |           |Caixa de mensagens e spans de notificações referentes ao contato entre pesquisadores/professores com parcerias.|
Modificabilidade | RNF08, RNF09 |     Sim    | Construir o projeto com base em uma arquitetura (de camadas, por exemplo), além de dividir o sistema em módulos, o que facilitará o isolamento de suas interfaces com usuário, lógica de negócio e persistência.|
 Apreensibilidade |   RNF10    |   Não   | Dar a possibilidade de um modo tutorial para o usuário iniciante/visitante, indicando onde as ações devem ser realizadas e exemplos.|
 Operacionalidade |   RNF11    | Não   | Prover mecanismos para autocompletar campos. Quando possível, deixar alguns campos preenchidos com dados padrões.|



          
### 4) Protótipos de Tela do Sistema

[Mockup feito com Balsamiq](/ArquivoIfes_Prototipo.pdf)
