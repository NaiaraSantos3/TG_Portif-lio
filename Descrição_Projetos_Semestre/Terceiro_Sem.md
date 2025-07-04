## 3º Semestre – 2024/1
<details> 
### Apresentação do Parceiro: Dom Rock

A _DOM ROCK_ é uma empresa voltada para apoioar clientes de diversos setores e que geram todo o tipo de dado (áudio, e-mail, imagem, etc.) a realizarem análises de dados através do uso da Inteligência Artificial. Com os dados tratatos e analisados, possibilitam aos seus clientes maior acertividade e segurança para as tomadas de decisões.


Segue o link para conhecer a _DOM ROCK_:

[_Dom Rock_](https://www.domrock.net/)


### Objetivo do Projeto
Para o denvolvimento da API do 3° Semestre, aplicado na primeira etapa de 2024, tivemos o seguinte desafio:

A instituição possui um sistema de processamento de dados em cascata chamado pipeline, que consiste em vários estágios que são coordenados automaticamente com base nas características das fontes de dados e nas necessidades dos clientes em termos de algoritmos de IA ou modelos matemáticos. 
Na metodologia de implementação do sistema, é necessário configurar as fontes de dados envolvidas para que a plataforma funcione corretamente. No entanto, a configuração das fontes de dados é feita manualmente, sendo um ponto crítico que consome muito tempo dos técnicos e cria uma dependência excessiva de especialistas para realizar tal tarefa.
Para superar esse obstáculo, foi proposto a criação de uma interface amigável para a configuração das fontes de dados em alguns estágios, proporcionando maior agilidade na implantação para os clientes da _Dom Rock_ e reduzindo a sua dependência de técnicos especializados.

Segue link para conhecer a aplicação _DataFlow_:

[Aplicação _DataFlow_](https://github.com/iNineBD/DataFlow-3Sem2024)

#### Tecnologias Utilizadas
" Apresente brevemente as tecnologias utilizadas. Uma tecnologia por linha. Indique qual a importância de cada tecnologia para o projeto."


#### Contribuições Pessoais
Para a elaboração e desenvolvimento do projeto no 3° semestre as minhas contribuições foram as seguintes atribuições:
- Protótipo
Para o decorrer da API, a equipe julgou necessário a elaboração de protótipos das telas a serem exibidas. Isso foi realizado para que as validações realizadas com o cliente e o entendimento da equipe não se perdessem com o desenrolar do projeto. Dessa forma, durante todo o semestre, auxiliei na idealização das telas, bem como nas correções quando solicitados pelo cliente ou pelo time de desenvolvimento.
- Front-end
Para esse projeto, seguimos a divisão de front-end / back-end. Minhas atribuições foram realizadas junto ao desenvolvimento de front-end, que apartir da idealização dos protótipos, as telas foram divididas entre os integrantes para realizar a integração junto com o back-end elaborado. 
Antes do início das tasks, cada integrante planejava a quantidade de tempo (em horas) a ser gasto para a realização da tarefa. Ao final, cada um deveria lançar o total de horas efetivamente utilizadas para finalizar determinada atribuição.
Dessa forma, seguem os desenvolvimentos de cada sprint, estruturadas da seguinte forma:

  	- _Sprint 1_: Criação da Tela Home
   
	A primeira tela desenvolvida nesta API, tinha como propósito a exibição dos arquivos que foram “importados” no sistema, status, organização e a exposição dessas informações eram restritas a cada usuário, ou seja, só poderiam ver essas informações, o usuário atribuído para ter essa visão, de acordo com o seu nível de acesso e sua organização.
![image](https://github.com/user-attachments/assets/28b978b3-03fd-4d1f-a82d-d73652705949)

 	- _Sprint 2_: Criação da Tela de Login e Conexão com Back-end
   
	A tela de login, foi desenvolvida a fim de limitar os acessos e garantir maior segurança a aplicação. Além da parte visual (front-end), foi elaborada a conexão entre front-end e back-end, garantindo o funcionamento real e adequado para acessar todas as funcionalidades desenvolvidas.
![image](https://github.com/user-attachments/assets/cfa59c82-18ef-48fa-b4d1-89e97356fc76)

	- _Sprint 3_: Tela Validação Silver Zone e Editar DePara
   
	A tela de Validação Silver consiste em uma etapa em que o usuário responsável precisa verificar os dados e decidir se o que foi realizado na etapa da Bronze Zone está reprovado ou aprovado.
	Visualização da tela de Validação da Silver Zone:

	![image](https://github.com/user-attachments/assets/c775d238-588a-4d0c-a01e-59f21a90c6cf)

	Dessa forma, existem as seguintes exibições de mensagens:

 	 Quando o usuário reprova as informações recebidas na validação da Silver Zone, todos os dados retornam para a etapa anterior (Bronze Zone) para que sejam reajustados, impendindo que sigam de maneira inconsistente.
  
 	 ![image](https://github.com/user-attachments/assets/c874d656-330e-49f3-b34d-025c330defd5)

	 Quando o usuário aprova as informações recebidas, todos os dados seguem para as etapas seguintes da Silver Zone.
  
	 ![image](https://github.com/user-attachments/assets/5c33128f-89a9-4363-8a5b-03d6a0ef3b32)
	
	 Já a tela de Editar DePara foi desenvolvida para que o usuário conseguisse realizar alteração dos metadados, sendo possível realizar a inclusão ou exclusão de uma linha inteira, excluir tudo ou apenas alterar o De (que consiste na alteração da coluna "O valor De") e também o Para (que cosiste na alteração da coluna "É igual a").
	 ![image](https://github.com/user-attachments/assets/aeb258b4-988a-4b51-8f79-504f1f3974e3)
 
 	_- Sprint 4:_ Controle de Usuários e Manual da Aplicação
	Foi adicionado para o perfil do usuário Master, um botão de Controle de Acesso na tela home (no canto direito superior), para que seja possível acessar as funcionalidades de "Cadastrar Usuário" (entregue em etapas anteriores) e adicionado o "Log de Usuários" (todos esses privilégios são restritos apenas ao Master, já que ele é o usuário que faz a administração da aplicação)
  	![image](https://github.com/user-attachments/assets/e194d50c-ce73-46d1-aa29-f0dd26995c05)

   	![image](https://github.com/user-attachments/assets/5f816240-66fd-426d-9d41-3a31b50cb00d)

 	Foram elaborados dois modelos de Manuais da Aolicação, sendo:
  
  	_Manual do Usuário - Parceiros:_ focado em explicar a utilização do sistema para os parceiros(clientes) da Dom Rock, fazendo que utilizassem o sistema com mais facilidade e menor dependência do Time da _Dom Rock_.
  	
	| [Clique aqui para acessar ao Manual do Usuário - Parceiros](https://github.com/iNineBD/DataFlow-3Sem2024/blob/main/doc/Manuais/Manual%20do%20Usu%C3%A1rio%20-%20Parceiros.pdf) |

   	_Manual do Usuário - Master e Full:_ focado em explicar a utilização do sistema para os usuários que fazem a gestão e administração do sistema, neste caso, voltado para o time da _Dom Rock_.
  
	| [Clique aqui para acessar ao Manual do Usuário - Master e Full](https://github.com/iNineBD/DataFlow-3Sem2024/blob/main/doc/Manuais/Manual%20do%20Usu%C3%A1rio%20-%20MASTER%20e%20FULL.pdf) |

- GitHub

#### Hard Skills
Apresente as hard skills que você utilizou/desenvolveu durante o projeto e o nível de proficiência alcançado. Exemplo: CSS - Sei fazer com autonomia

#### Soft Skills
Apresente as soft skills que você utilizou/desenvolveu durante o projeto e em quais situações elas foram fundamentais. Exemplo: Comunicação - Precisei exercitar minhas habilidades de comunicação para viabilizar as reuniões semanais levando em conta as disponibilidades dos membros, que não cursavam as mesmas disciplinas.

</details>
