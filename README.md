LIST OF ACADEMIC PROJECTS:

[PROJECT-SEMESTRE-01-2019.2 - *Python Web Scrapper - Public Safety Monitor*](https://github.com/ODAGAMMXIX/PFOLIO1_DANZO) 
[PROJECT-SEMESTRE-02-2020.1 - *Java Stand Alone GANTT Chart tool*](https://github.com/ODAGAMMXIX/PFOLIO2_GANTT)
[PROJECT-SEMESTRE-03-2020.2 - *Java Web App - Benefits According Credit Score*](https://github.com/ODAGAMMXIX/PFOLIO3_VALCODE) 
[PROJECT-SEMESTRE-04-2021.1 - *Oracle HR API  for searching candidates* ](https://github.com/ODAGAMMXIX/PFOLIO4_JOBNATION) 
[PROJECT-SEMESTRE-05-2021.2 - *Pentaho & Data Warehouse Analytics of Education* ](https://gitlab.com/rafaelEstevam/back-educalytics) 


FIRST PROJECT, SEMESTRE-01-2019.2 - *Python Web Scrapping - Public Safety Monitor*


i. ABOUT THIS PROJECT.

The first project in the first semestre was evolutionary, although hectic.

Without significant contact with the technological resources needed for a working application, there was an imersion in new vocabulary, colleagues and procedures.

Eventually, a web (bot) scrapper was delivered, plotting a heat map of crime in the surrounding of the school, extracting data from the São Paulo State website.

For academic purposes, the description below will be delivered in Portuguese, though I am available to speak about this project in full English should you be interested in hiring me. Here, I acted as P.O. and second S.M. and R&D agent.
 

I - DESCRIÇÃO DO PROJETO.

O primeiro projeto integrador trouxe o tema 'web bot', com liberdade para buscar ferramentas tecnologicas para a efetiva entrega de um Mapeador de Criminalidade ao Redor da FATEC.

Houve dificuldades de natureza humana, estrutural e tecnológica. No primero semestre, encontrando pela primeira vez os colegas e professores, com limitações estruturais e conhecendo novo vocabulário: nomes e neologismos, bem como de gerência de projetos, ambos de TI (metodologia Agile).

Com o suporte de alunos mais experientes do último semestre, os membros da equipe foram revelando suas características e contribuindo livremente com ideias.

Por critério social e utilitarista e no contexto de fatos ocorridos ao redor da FATEC, elegemos um webbot que pudesse mostrar índices de criminalidade nas redonndezas de seu prédio. Ao final, verificamos a possibilidade de comerciaização da solução tanto para o Poder Público como para o mercado imobiliário, securitário, de segurança, transporte e entretenimento em qualquer região do Estado de São Paulo.

Neste semestre, como estréia deste modelo de aprendizado (por projeto), havia ampla liberdade oriunda da amplitude do escopo. Ademais, o processo de criação e aprendizado tem velocidade diferente entre alunos.

Assim, implantamos uma metodologia que denominamos "competing codes". Dois colegas buscavam solução para o mesmo problema, vencendo o código que melhor atendesse as necessidades dos projetos.

Nesse processo, estudamos e aprendemos a respeito de diversas ferramentas e bibliotecas do Python que não foram utilizadas na solução em si (*v.g.* matplotlib).

Ao final, o webbot foi capaz de realizar as seguintes tarefas:

1 - Escolha do usuário na página DANZO;​

2 – Obtenção de dados do sítio Transparência SSP-SP;​

3 – Tratamento de arquivo obtido: criação de pasta local, renomeação;​

4 – Tratamento de dados: Leitura do arquivo obtido, coluna por coluna LISTAS), para  inserção em BD;​

5 – Inserção incremental em BD Sqlite3;​

6 – Leitura do BD Sqlite3;​

7 – Apresentação dos dados: mapa de calor, barras; ​

II - TECNOLOGIAS

Em fase embrionária de aprendizado, a euipe elegeu o Python por ser linguagem de programação de alto nível mais amigável ao programador.

No contexto do Python, contamos com a orientação do Docente e muita pesquisa em fóruns virtuais  especializados para implementar blocos de códigos com propósito específico.

As bibliotecas mais importantes foram:

- selenium: emulação de ações humanas para acessar o sitio da Secretaria de Segurança Pública do Estado de São Paulo, baixando os dados das métricas de crimes em arquivo em formato .CSV, após escolher município, bairro, tipo de crime e período. Escolhemos os crimes contra o patrimônio (furto ou roubo), de aparelhos celulares, automóveis, casas ou estabelecimentos comerciais.

-  pandas: agrupamento de dados por localização, entregando os dados tratados para a apresentação em mapa de calor. Recebemos um curso extracurricular de "Python para Jornalistas", aprendendo as principais funcionalidades para demostrar dados com significância para o usuário final. aqui, nasceu para mim a curiosidade por Ciência de Dados. Com meu conhecimento prévio na área jurídica, tonou-se mais fácil explicar conceitos e etender o que seria mais adequado demonstrar.

-  folium: 
- flask: 
- flask_googlecharts: 

III - CONTRIBUIÇÕES INDIVIDUAIS.

A definição do MVP (MINIMUM VIABLE PRODUCT) foi mais simples 

![](imgs/20211026-202145.png)


 - Contribuições individuais: esta parte é central! Descreva suas contribuições individuais de forma aprofundada, colocando trechos de código que você fez numerando as linhas e comentando estas linhas, coloque diagramas por exemplo de arquitetura que você fez explicando decisões arquiteturais (por que foi feito desta forma?), e etc... (as possibilidades são grandes, além das coisas já citadas você podem pensar em outras como, por exemplo, citar tecnologias que foram empregadas e não ficaram boas, explicar por que não deu certo, como você pensou na solução e etc - se você pensar em solução de problemas encontrará muitos tópicos que teve problemas e conseguiu resolver e poderá aprofundar esta escrita o máximo possível)


 - Aprendizados efetivos: essa parte também é central Enfatizar aqueles aprendizados que você sabe fazer com autonomia! Mostrar como esses aprendizados foram aplicados no API e, agora que você domina isso, como você poderá aplicar futuramente em seus próximos projetos como seus próximos projetos profissionais. Mostrar que estes aprendizados podem ser aplicados em novos projetos (até porque você utilizará estes portfólios para conseguir novos empregos de acordo com suas metas profissionais) 




![Danzo Logo](https://i.imgur.com/9V0mPnm.png)
   
   
### Resumo do Projeto 

### Tecnologias adotadas na solução 

### Contribuições individuais/pessoais 

### Aprendizados Efetivos 

### Contribuições individuais/pessoais. 

##	MVP – MINIMUM VIABLE PRODUCT  
O Produto Mínimo Viável ou, no Inglês “MVP” do DANZO consistirá em disponibilizar os dados em uma página na Internet sobre o índice de violência na região da FATEC e Parque Tecnológico. 
Inicialmente, os usuários serão os alunos da FATEC, a página será aberta, sem precisar realizar cadastro ou login na página.

•	Qual o objetivo de ter acesso aos dados fornecidos pela página?  
•	Compra/Aluguel de casa;  
•	Abertura de empresas/comércios;  
•	Estudo na região;  
•	Trabalho na região;  
•	Prática esporte na região;  
•	Lazer (evento cultural, maratona geek, ou festa na região);  
•	Morador/Frequentador da região.  

Ao entrar na página, o usuário terá acesso às informações de acordo com as opções de entrada, podendo inicialmente fazer o filtro do período (ex: de junho/2019 a agosto/2019 e o tipo de violência (ex: tentativa de ou, furto/roubo de carro, celulares, pertences pessoais etc.). Essas informações serão indicadas em um Gráfico para melhor visualização.
Future:
Uma ideia para o futuro seria criar uma conta na rede social Instagram nomeado “Mapeador de Criminalidade”, conforme os resultados exibidos no sistema, automaticamente as imagens seriam publicadas no Instagram.
Além, de criar uma extensão da página (aplicativo) que dê as informações, e que também elabore uma rota mais segura para o usuário, podendo ser monitorada.
Outra ideia para captação de recursos seria tratar os dados de entrada de usuários de forma que eles se tornem atraentes para clientes potenciais interessados como:
-Empresas de segurança: com esses dados poderiam definir uma demanda de vendas/colaboradores por região;  
-Imobiliárias/Construtoras: com esses dados poderiam traçar o perfil de clientes para determinadas regiões;  
-Empreendedores: que teriam acesso a informações sobre o perfil da pessoa que frequenta a região, abrindo um restaurante ou loja que atenda a este público alvo.  


## 	POR QUE E COMO SERÁ UTILIZADA METODOLOGIA SCRUM?

•  **Metodologia Scrum:**  

Scrum é uma metodologia utilizada para gerenciar o trabalho em produtos complexos desde o início de 1990. 
O termo “scrum” vem do meio esportivo: no jogo de rugby este termo refere-se ao reinício da partida após uma infração leve, tratando-se, em elaboração de um projeto como uma área ou tela estrutura (framework estrutural) para colacionar ideias. 
É composta por ciclos de atividades programadas — os sprints —, com planejamento de tarefas e datas de início e de fim determinados.
Um framework no qual pessoas podem solucionar problemas complexos e soluções adaptativas, enquanto criam de forma produtiva agregando o mais alto valor possível. 
Ferramentas de Scrum

•	**Sprints**

No Scrum, o trabalho é realizado em interações ou ciclos de até um mês, chamado de Sprints. Durante o planejamento do sprint, a equipe de desenvolvimento e o cliente (neste caso, product owner) devem chegar a um acordo sobre qual o objetivo do sprint. Com este objetivo traçado, determinam quais os itens da lista de pendências (backlog) devem ser priorizados para serem executados neste sprint.

•	**Daily Scrum**

Todos os dias, idealmente no mesmo horário, os membros da equipe devem realizar uma reunião (15 minutos ou menos), chamado Daily Scrum. Comumente nesta reunião o líder do projeto (Scrum Master) irá perguntar para cada membro da equipe essas três perguntas:

i.	O que fiz ontem que ajudou o time a atingir a meta do sprint?  
ii.	O que vou fazer hoje para ajudar o time a atingir a meta do sprint?  
iii.	Existe algum impedimento/dificuldade que não permita a mim ou ao time atingir a meta do sprint?  

•	**Kanban Scrum**

Mostrar o trabalho de forma visual usando um quadro/tela:
Em geral, perde-se muito tempo em reuniões com apontamentos sobre o que está sendo feito, o que foi concluído e o que está parado. Uma maneira mais simples de resolver isso é criar um registro visual para demonstrar o curso das tarefas. Para isso, o quadro Kanban Scrum é a ferramenta ideal. Basta criar um quadro com todas as atividades (e o status de cada uma) e colocá-lo onde todos possam ver. Assim, não é preciso perder tempo falando e as pessoas já saberão sobre o status do projeto apenas observando. 

•	**Dinâmica do Scrum**

Tudo começa com a visão do produto final, que é determinado pelo product owner, pode ser através de um business case, por exemplo, ou qualquer outra visão macro do produto. Em seguida isso será desmembrado em todas as funcionalidades necessárias, que é chamada de product backlog. Essas funcionalidades serão organizadas por ordem de prioridade:
 
Assim como outros métodos com um enfoque semelhante, a proposta do scrum é prover contribuição para o gerenciamento de atividades intricadas, porém de maneira flexível e que promova a adaptação do projeto diante das inevitáveis alterações. São três as ideias principais em que o método Scrum se ampara:  
•   Transparência  
•   Inspeção  
•   Adaptação  

A noção de transparência deve ser compreendida como a existência de uma concordância mútua entre todos os participantes do projeto, regras que caracterizam processos e andamento dentre outros. 
Outro ponto importante é a inspeção do que está sendo feito. A verificação contínua do que é produzido, seja nas reuniões diárias ou no sprint review é fator determinante para que se tenha a certeza de que o projeto caminha dentro do prazo estipulado, bem como para diagnosticar desvios indesejáveis e atuar de forma corretiva sobre estes últimos.
E por fim a adaptação vai de encontro a um dos principais objetivos dos métodos ágeis: a flexibilidade para mudanças. O produto que está sendo construído durante o projeto, não raro, sofre mutações.  Desde que preservados os valores e práticas, pode-se adaptar os processos do scrum para a realidade de seu projeto/empresa.
No final do sprint, duas atividades são fundamentais: o sprint review, onde o objetivo é validar e adaptar o produto que está sendo construído, verificar se o que está sendo feito está de acordo com o esperado; é a apresentação do que foi feito no sprint. É neste ponto que surgem as mudanças e quando se atualiza o backlog.
 
##	POR QUE E COMO SERÁ UTILIZADO O GITLAB?

Criado por Linus Torvalds em 2005 para desenvolvimento do Kernel do Linux, o Git acabou tornando-se uma ferramenta popular para os desenvolvedores de software.
O GIT é um sistema utilizado para fazer o controle de versões de arquivos, com ele é possível criar um repositório e fazer alterações no código sem o risco de sobrescrevê-los, sendo possível retornar a versão anterior do arquivo caso seja necessário. 
Com o Git é possível que um grupo de pessoas trabalhe simultaneamente no mesmo arquivo, tornando o processo de desenvolver códigos mais ágil, evitando confusão de versões. Para utilizar o GIT é necessário baixar o programa pelo site https://git-scm.com/.
GitLab
Desenvolvido em 2011 por Dmitriy Zaporozhets e Valery Sizov, o GitLab é um software livre gerenciador de repositórios. Com ele, temos a possibilidade de criar um projeto onde várias pessoas possam contribuir no desenvolvimento, dividi-lo em tarefas e saber como está o andamento dele. Para utilizar o GitLab é necessário criar uma conta no site (https://gitlab.com/), assim você poderá criar um novo projeto ou ser adicionado a algum existente através do seu e-mail ou usuário. Importante citar que para utilizá-lo é necessário integrá-lo ao Git, para poder enviar e receber os arquivos que ficarão armazenados no repositório online. Existem outros gerenciadores de repositórios, um dos mais conhecidos são: GitLab, GitHub, Google Code, BitBucket entre outros.
Para o desenvolvimento do nosso projeto utilizaremos o GitLab, com ele será possível dividir as tarefas do grupo e saber o andamento das mesmas, nele tem uma ferramenta similar a um “kanban”, onde nós adicionamos as atividades (issues) e todos os integrantes do grupo terão acesso aos arquivos, poderão verificar como está o andamento das atividades e poderão contribuir para o desenvolvimento das mesmas. As atividades concluídas terão seus arquivos anexados em seus respectivos itens assim que finalizadas. Além de todas essas funções o GitLab é gratuito, diferente do GitHub, que é pago dependendo do número de usuários e caso seja necessário utilizar repositórios privados onde o código não fica aberto para o público.

##	POR QUE E COMO SERÁ UTILIZADO O SLACK?



*   Slack   
O Slack foi lançado em 2014, por um Startup desenvolvedor de Software de mesmo nome, com a principal função de se tornar um facilitador da comunicação interna na empresa, através das suas funcionalidades semelhantes a um chat, com intuito de diminuir as trocas de e-mails, reuniões e informações divergentes entre equipes. 



*   Slack  no Projeto Integrador  
O Slack é uma das principais ferramentas utilizadas para o desenvolvimento do Projeto Integrador, pois é um meio de comunicação ágil e instantâneo, por este canal de comunicação, são decididos os próximos encontros presenciais, saneamentos de dúvidas das atividades desenvolvidas. Foram criados seis canais de comunicação no grupo do Slack.
•	Avisos importantes: São postadas as informações mais importantes referentes ao projeto, como a data da entrega da Sprint, data da próxima reunião presencial da equipe, atividades que devem ser entregues.
•	Geral: Canal destinado para discussões das atividades realizadas do projeto e dúvidas.
•	Library: Este canal é apenas para compartilhamento de cursos, livros, programas e qualquer outra informação que ajude no estudo do projeto e no curso Banco de Dados.
•	Outros assuntos: É um canal mais informal, podendo ser conversado sobre qualquer assunto, como compartilhamento de notícias, vagas de empregos, troca de conhecimentos etc. 
•	Web bot: Neste canal serão postadas apenas informações dos avanços e entregas referentes ao projeto Web bot deste desta equipe de projeto.
•	Daily: Utilizado para o envio da das informações diárias da metodologia scrum, que são todas as segundas, quartas e sextas até às 18h00.

##	POR QUE E COMO SERÁ UTILIZADO O PYTHON?  

Python é uma linguagem de programação de alto nível, desenvolvida por Guido van Rossum em 1991. Os objetivos desta linguagem são desenvolver códigos bom, ágil e objetiva. Além da linguagem de fácil interpretação o Python conta com uma biblioteca que fornece várias coleções de funções.
Para o desenvolvimento do Projeto Integrador (Web Bot), foi escolhida a linguagem Python pelos integrantes do grupo por estarem familiarizados/por recomendação de especialistas e será utilizado para desenvolver as raspagens do bot.

##	DIAGRAMAS DAS ENTIDADES QUE SERÃO CONSTRUÍDAS.  
a.	Banco de Dados;  
b.	Processos  
    i.	Processo 01;  
    ii.	Processo 02;  
    iii.	Processo 03;  
    iv.	Processo n;  

 
{diagrama - Scrum-image-README}

##	CRONOGRAMA  
O cronograma deste projeto será desenvolvido após a validação da primeira entrega datada para 06/09/19, prazo após o qual será apresentado o cronograma geral do Projeto Integrador ditado pelos professores, a instância superior ao qual este projeto Web Bot está submetido.

##	CONSIDERAÇÕES FINAIS  
Os assistentes de projeto estudaram a documentação necessária para cada tópico desta descrição de projeto, concluindo, por consenso/por maioria, de que o objeto e os processos acima tendem a ser suficientes para o desenvolvimento do projeto em sua integralidade, dentro do prazo estipulado e de acordo com o conhecimento atual e dos recursos definidos pelo Projeto Integrador da FATEC. Após, será definindo a segunda entrega e, possivelmente, as demais até data final ainda não determinada pelos professores.  

 ***INTEGRANTES***  
    📉 Caroline Sousa  
    📉 Denise Oliveira
    📉 Leonardo Lindgren  
    📉 Wilson Amore  
 
 
##	COMO USAR O GIT:  

1. Criar uma pasta na sua area de trabalho (ex: pastateste)
2. Abra o terminal do Git. Caso esteja direcionado na pasta **C:** utilizar o comando **cd** *(change directory)* para navegar entre as pastas
3. Ex: cd *Users/MyName/Desktop*. Isso ira me direcionar a pasta Users, depois para pasta Meu nome e por fim para minha area de trabalho
4. Se ao caso errar o caminho, use o comando **cd ..** para retornar uma pasta para tras Ex: se eu estou na pasta *Users/MyName/Desktop* e der o comando **cd ..** eu irei para pasta *Users/MyName *
5. Entre na pasta criada na area de trabalho C:/Users/MyName/Desktop/pastateste.
6. Nesta pasta usa o comando git clone https://gitlab.com/web-bot-project/projeto-web-bot.git. Ctrl V normalmente nao funciona entao usa o botao direito do mouse para colar
7. Ele irá criar uma pasta com o projeto. Então precisamos entrar nesta pasta. *cd web-bot-project*
8. Por enquanto ainda estamos na Branch master e tudo que alterarmos seta alterado nela. Por isso sempre é bom estar em outra branch para fazermos nossas alterações nessa branch especifica
9. Dar o comando git chekout **<nome da branch>** para trocar de branch
10. Depois de fazer alguma alteração e quiser enviar para o git precisamos adicionar essas mudanças com o comando **git add .** *(ainda dentro da pasta do projeto)*
11. Depois o com o comando **git commit -m "alteração de bla bla bla"** salvar o arquivo na sua pasta Git/web-bot-project local. É obrigatória uma mensagem entre as aspas após o –m.
12. Agora que o arquivo ja esta salvo na sua maquina basta envia-lo novamente ao gitlab, use o comando **git push** para empurrar o arquivo.
13. Pronto, suas alterações ja estão no git na sua branch

##	Comandos básicos de terminal e git 

Comando Git	
git config --global user.name "nome do usuário": Seta seu usuario git no seu terminal
git config --global user.email "email do usuário": Seta seu email git no seu terminal
git clone:	Clona o projeto
git pull:	Baixa as alterações feitas do projeto
git add: 	Adiciona arquivos
git commit -m: "texto de commit ex: alteracao bla"	Comita as coisas no seu Rep local
git status:	Verifica o que foi alterado
git push:	Sobe suas alterações para o git
git checkout: <nome_da_branch_existente>	Trocando para uma branch existente


## Comandos Terminal Windows
cd nome da pasta:	Entra na pasta indicada
cd ..:	Volta uma pasta
dir: Mostra todas os diretorios na pasta
cls:	Limpa o terminal


**Passo a passo para rodar o programa:**

1° clonar o repositório do git https://gitlab.com/web-bot-project/projeto-web-bot.git  
2° instalar o python 3.4       https://www.python.org/  
3° abrir o cmd na pasta do projeto   
4° instalar as seguintes bibliotecas caso não estejam instaladas:  
	4.1 pip install flask  
	4.2 pip install flask_googlecharts  
	4.3 pip install selenium  
	4.4 pip install folium  
	4.5 pip install pandas  
5° executar o comando flask run terminal  
6° acessar no navegador o endereço http://localhost:5000/  

