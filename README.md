
# Projeto Disciplina: IHC


Olá! Este repositório faz parte do projeto da disciplina de Interação Homem Computador da UTFPR - Campus Cornélio Procópio. 

## 1. Introdução (Até dia 04/04)

***1.1.  Seven***

**Felipe Bezerra**

**Gustavo Henrique**

**Leonardo Girotto**

**Lucas Gabriel**

**Messias X. Magalhães**

**Wenio Oliveira Silva** 

***1.2.  Problema***

Atualmente, o Grupo ELLP enfrenta dificuldades devido ao uso de métodos manuais para o controle dos voluntários envolvidos e das oficinas ofertadas. Esse processo manual consome tempo significativo e pode resultar em filas para a conclusão das tarefas individuais, impactando negativamente a eficiência e a organização das atividades do projeto. Isso repercute diretamente na experiência dos voluntários e coordenador do projeto, prejudicando a qualidade do ensino oferecido e comprometendo a dinâmica geral do ELLP.
Com a implementação do software proposto, buscamos eliminar esses obstáculos, proporcionando uma solução eficiente e integrada para o gerenciamento dos voluntários e oficinas. Ao automatizar o processo de documentação e disponibilizar orientações específicas através de um programa desktop, esperamos melhorar significativamente a eficiência e a organização do projeto. Isso resultará em uma experiência mais fluida e eficaz para todos os envolvidos, proporcionando um ambiente de trabalho mais produtivo e colaborativo.


***1.3.  Análise dos sistemas concorrentes***

Como concorrente pode-se ser implementado um voluntário para exercer apenas essa função dentro do projeto, porém dessa maneira haveria um conflito no controle do coordenador para supervisionar essa função e outro voluntário.
Outro concorrente que pode ser citado é o excel, fazendo o controle através de planilhas, mesmo funcionando não seria o ideal, isso por não suprir todas as necessidades dos público alvo.

***1.2.  Público Alvo***

Após aplicado o formulário e realizado a entrevista, obtivemos os seguintes resultados e avaliações:

- [Formulario](https://docs.google.com/forms/d/e/1FAIpQLScExnCS4WenUT4uYPOtUoMP9fodJMs4NRS2oCz9RrmibJ14Pg/viewform?usp=sf_link)
- [Graficos de Pesquisa](https://github.com/leonardofgirotto/Seven/blob/main/Perfil%20do%20usu%C3%A1rio/GRAFICOS%20DA%20PESQUISA.pdf)
- [Entrevista Transcrita](https://docs.google.com/document/d/1-11R3eVuyAWT4ujsGSH8uhgkwWXZKmoNSDNPkPdqZ2A/edit?usp=sharing)

## 2. Perfil do usuário (Até dia 18/04)

### 2.1. Descrição dos Usuários: Personas

- [Canva Personas](https://drive.google.com/drive/folders/1vaEoyT-PEI2fVdPiR_zEJskEAyUVh_hP?usp=drive_link)




### 2.2. Análise de Tarefas: ANTES

Devido a grande quantidade de papelada e a disponibilidade de ambos participantes, tanto coordenador quanto voluntário, o processo de inscrição acaba sendo pouco eficiênte.

→ [StoryBoard Antes](https://github.com/leonardofgirotto/Seven/blob/main/antes.pdf)

### 2.3. Análise de Tarefas: DEPOIS

Com a utilização do software, ambos participantes, tanto coordenador quanto voluntário, podem realizar as tarefas necessárias em seu próprio tempo disponível e da sua própria casa, agilisando assim o processo e diminuindo as tarefas manuais.

→ [StoryBoard Depois](https://github.com/leonardofgirotto/Seven/blob/main/depois.pdf)

### 2.4. Cenários

#### Descrição do Cenário:

**Ambiente e Contexto:**
No escritório do Grupo ELLP, localizado na UTFPR - Campus Cornélio Procópio, o Prof. Antonio Carlos Fernandes da Silva, coordenador do projeto, está sobrecarregado devido ao uso de métodos manuais para o controle dos voluntários e das oficinas. Sua mesa está repleta de pilhas de papéis relacionados à documentação e organização das atividades do projeto.

**Atores:**
- Prof. Antonio Carlos Fernandes da Silva (coordenador do projeto)
- Voluntários do Grupo ELLP

**Objetivos:**
Garantir o controle eficiente dos voluntários e das oficinas do projeto ELLP, sem utilizar métodos manuais.

**Planejamento:**
O coordenador precisa revisar e organizar manualmente todos os documentos relacionados aos voluntários e às oficinas do ELLP, o que consome muito tempo e recursos.

**Ações:**
O coordenador passa horas organizando e revisando os documentos, enquanto os voluntários aguardam orientações e os alunos esperam pelo início das oficinas.

**Eventos:**
A sobrecarga de trabalho do coordenador resulta em atrasos na organização das atividades do projeto e na insatisfação dos voluntários e alunos.

**Avaliação:**
O processo manual de controle dos voluntários e das oficinas compromete a eficiência e a organização do projeto, afetando negativamente a qualidade do ensino oferecido e a experiência dos envolvidos.

#### Cenário: Antes

No escritório do Grupo ELLP, situado na UTFPR - Campus Cornélio Procópio, o Prof. Antonio Carlos Fernandes da Silva, coordenador do projeto, é retratado em sua rotina diária. Sua mesa é uma paisagem caótica de pilhas de papéis relacionados ao controle dos voluntários e das oficinas do ELLP, onde ele mergulha em meio a montanhas de documentos.
Junto a ele, encontra-se Lucas, um voluntário ativo do Grupo ELLP, igualmente imerso na organização das atividades. Juntos, eles se dedicam à árdua tarefa de revisar e organizar meticulosamente os papéis, em meio a uma atmosfera de desordem, assegurando o adequado funcionamento do projeto. 
Posteriormente, Lucas se envolve na preparação das oficinas, contribuindo para oferecer uma experiência de ensino lúdico de qualidade aos alunos.

#### Cenário: Depois

Maria, a professora voluntária, desempenha um papel central na transformação do cenário do projeto ELLP, de sua casa, assume a responsabilidade, acessando o computador e navegando pelo site do ELLP para gerenciar todas as informações relacionadas às oficinas e aos voluntários. 
Com determinação e eficiência, Maria organiza os detalhes necessários para as atividades do dia. Ao chegar à UTFPR-CP, é recebida na entrada pelo coordenador do projeto com um gesto cordial de saudação. 
Maria entra na sala de aula com confiança, pronta para iniciar as atividades com os alunos. Este novo processo automatizado e integrado, proporciona uma experiência mais eficiente e organizada para todos os envolvidos no projeto, elevando a qualidade e a eficácia do Ensino Lúdico de Lógica e Programação.

## 3. Design (Até dia 16/05)

***3.1. Requisitos Funcionais***

| ID  | Funcionalidade | Prioridade |
|-----|----------------|------------|
| RF01 | O sistema deve permitir o cadastro de voluntários exigindo nome, data de nascimento, CPF, nacionalidade, status de estudante da UTFPR, curso, período, RA, endereço, cidade, estado, telefone e e-mail. | Essencial |
| RF02 | O sistema deve permitir o cadastro do coordenador responsável, exigindo nome, CPF, departamento, telefone e e-mail. | Essencial |
| RF03 | O sistema deve permitir a criação de uma senha na etapa de cadastro, tanto para voluntários quanto para coordenador, para posteriormente ser utilizada para realizar o login. | Essencial |
| RF04 | O sistema deve permitir que os voluntários realizem o login para acessar o sistema, utilizando o RA e a senha cadastrada. | Essencial |
| RF05 | O sistema deve permitir que o coordenador realize o login para acessar o sistema, utilizando o e-mail e a senha cadastrada. | Essencial |
| RF06 | O sistema deve permitir o cadastro dos dados da ação pelo coordenador, exigindo o título da ação (ELLP), qual a modalidade e a vigência, incluindo a data de início e fim. | Essencial |
| RF07 | O sistema deve permitir que o coordenador cadastre as atividades a serem desenvolvidas pelo voluntário. | Essencial |
| RF08 | O sistema deve permitir que o coordenador cadastre o cronograma das atividades a serem desenvolvidas pelo voluntário. | Essencial |
| RF09 | O sistema deve permitir a consulta do perfil pelo voluntário. | Importante |
| RF10 | O sistema deve permitir a consulta dos dados do voluntário pelo coordenador. | Importante |
| RF11 | O sistema deve permitir a alteração dos dados do voluntário pelo coordenador. | Importante |
| RF12 | O sistema deve permitir ao coordenador incluir a data de saída do voluntário, possibilitando ter um histórico de voluntários. | Importante |
| RF13 | O sistema deve permitir o cadastro da oficina pelo coordenador ou pelo voluntário, exigindo qual o tema da oficina, o voluntário que desempenhará o papel de professor, sala onde irá ocorrer e período, incluindo data de início e fim. | Importante |
| RF14 | O sistema deve possuir os dados da instituição, como nome da instituição e câmpus, pré-cadastrados. | Essencial |
| RF15 | O sistema deve possuir as condições gerais do termo de adesão pré-cadastrado. | Essencial |
| RF16 | O sistema deve permitir a geração e impressão do termo de adesão de voluntariado, contendo informações como dados da instituição, dados da ação, dados do coordenador, dados do voluntário, atividades a serem desenvolvidas pelo voluntário, cronograma dessas atividades e condições gerais. Além disso, o termo deve seguir as especificações e requisitos estipulados pela instituição universitária. | Essencial |

    
***3.2. Descrição textual***    

Apresente uma descrição textual resumida do seu design.  Quais as funcionalidades, principais escolhas de design, dentre outros. 

***3.3. Design preliminar***      

Apresente uma ilustrações do design: incluir os desenhos (sketches) das telas relativas à interface do seu sistema.

- [Sketches](https://drive.google.com/drive/u/0/folders/1vaEoyT-PEI2fVdPiR_zEJskEAyUVh_hP)

## 4. Protótipo (Até dia 23/05)
- [Figma - ELLP Manager](https://www.figma.com/design/VfouutCSlftGXb7kTlFvya/ELLP-Manager?node-id=0-1&t=FLbvzKjwgVqtNi9b-1)

## 5. Avaliação e Re-Design (Até dia 13/06)

***5.1. Avaliação com usuários*** 

Esta avaliação consiste na aplicação do método Think  Aloud com dois usuários. Vocês devem gravar o áudio do usuário e a tela do protótipo durante o teste.

-   Apresentar um vídeo de 3 minutos que resume os principais problemas encontrados.    

ANTES de conduzir o teste, defina as seguintes questões:

-   O que se deseja obter?    
-   Quando e onde vai acontecer?    
-   Qual a duração prevista de cada sessão?    
-   Qual o estado do sistema no início do teste?    
-   Quem serão os usuários?    
-   Quais tarefas serão solicitadas aos usuários?    
-   Qual critério será utilizado para decidir que os usuários terminaram cada tarefa corretamente?    

Por fim, os resultados devem ser analisados e apresentados da seguinte forma:

-   Descrever  a avaliação e os resultados obtidos (quais problemas foram identificados no seu design?).    
-   Resumir os resultados das avaliações com análise crítica referente a se os princípios e metas de usabilidade considerados importantes para o seu sistema foram satisfeitos ou não.
- Apresentar uma análise crítica da avaliação realizada, com identificação de problemas e sugestões de melhorias (quais modificações devem ser realizadas na próxima versão do protótipo?).

## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.

[2] Stackedit.io <edição de texto para o GitHub>
