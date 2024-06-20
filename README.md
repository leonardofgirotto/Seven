
# Projeto Disciplina: IHC


Olá! Este repositório faz parte do projeto da disciplina de Interação Homem Computador da UTFPR - Campus Cornélio Procópio. 

## 1. Introdução 

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

## 2. Perfil do usuário

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

## 3. Design

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

    
**3.2. Descrição textual**

Para o Coordenador, as funcionalidades incluem:

- Realizar cadastro
- Identificação e autenticação
- Consultar e alterar dados dos voluntários
- Cadastrar oficinas, dados da ação, atividades e cronograma
- Geração e impressão do termo de adesão de voluntariado

Para os Voluntários:

- Realizar cadastro
- Identificação e autenticação
- Cadastrar oficina
- Consultar perfil
- Geração e impressão do termo de adesão de voluntariado

 Trazendo um design intuitivo, limpo e atual.

***3.3. Design preliminar***      

- [Protótipo Baixa Fidelidade](https://drive.google.com/drive/u/0/folders/1vaEoyT-PEI2fVdPiR_zEJskEAyUVh_hP)

## 4. Protótipo

- [Protótipo Alta Fidelidade](https://www.figma.com/design/VfouutCSlftGXb7kTlFvya/ELLP-Manager?node-id=0-1&t=FLbvzKjwgVqtNi9b-1)

## 5. Avaliação e Re-Design 

***5.1. Avaliação com usuários*** 

Esta avaliação consiste na aplicação do método Think Aloud com dois usuários. 

- [Teste de Usabilidade com Usuários](https://drive.google.com/drive/u/0/folders/1NNN1JqZIuAbRXBu1tbBXDjnuxxmtmKg4)

    
-   O que procuramos obter com os testes:

        - Identificar os principais problemas de usabilidade do protótipo.
        - Coletar feedback sobre a experiência do usuário.
        - Verificar se os usuários conseguem completar as tarefas sem dificuldade.
        - Avaliar a eficiência, eficácia e satisfação dos usuários ao interagir com o sistema.
    
-   Quando e onde vai acontecer?
  
        Data: 13/06/2024
        Local: Casa de um dos membros da equipe. 
-   Qual a duração prevista de cada sessão?
  
        Aproximadamente 5 minutos por usuário.
-   Qual o estado do sistema no início do teste?
  
        - O sistema deve estar configurado no protótipo funcional que os usuários irão testar.
        - Dados de exemplo (como informações de voluntários e oficinas) devem estar pré-carregados.
-   Quem serão os usuários?
  
        - Coordenador do ELLP.
        - Voluntário do ELLP.
-   Quais tarefas serão solicitadas aos usuários?
  
  Para o Aluno:

        Cadastrar
        Sair
        Login
        Consultar perfil
        Gerar termo de adesão
            - Imprimir o termo
        Visualizar oficinas
        Sair

  Para o Coordenador:

    Cadastrar
    Sair
    Login
    Consultar voluntários
        - Pesquisar por um voluntário
        - Visualizar as informações dele
        - Editar informações do voluntário selecionado
    Gerar e imprimir o termo de adesão do voluntário selecionado
    Visualizar a lista de oficinas cadastradas
        - Cadastrar uma nova oficina
    Visualizar as atividades cadastradas
        - Cadastrar uma nova atividade
    Sair
-   Qual critério será utilizado para decidir que os usuários terminaram cada tarefa corretamente?
  
    Cadastro:
    
        Usuário preenche todos os campos obrigatórios e envia o formulário com sucesso.
        Sistema confirma o cadastro com uma mensagem de sucesso.
    
    Login:
    
        Usuário insere credenciais corretas e acessa a página inicial.
        Sistema redireciona o usuário para a área correta (Aluno ou Coordenador).
    
    Consultar perfil:
    
        Usuário navega até a página de perfil e visualiza suas informações pessoais.
    
    Gerar termo de adesão:
    
        Usuário navega até a funcionalidade de gerar termo de adesão e visualiza o documento gerado.
    
    Imprimir o termo:
    
        Usuário acessa a opção de imprimir o termo e confirma que a impressão foi iniciada (simulada se necessário).
    
    Visualizar oficinas:
    
        Usuário acessa a lista de oficinas disponíveis e visualiza as informações detalhadas de pelo menos uma oficina.
    
    Consultar voluntários (Coordenador):
    
        Usuário realiza uma busca por um voluntário e visualiza as informações dele.
        Usuário edita informações do voluntário e confirma a atualização.
    
    Gerar e imprimir o termo de adesão do voluntário selecionado (Coordenador):
    
        Usuário gera o termo de adesão de um voluntário específico e inicia a impressão do documento.
    
    Cadastrar nova oficina ou atividade (Coordenador):
    
        Usuário preenche o formulário de cadastro de oficina/atividade e confirma o cadastro com sucesso.
    
***5.2. Resultados Obtidos e Conclusão*** 

A avaliação do sistema foi realizada com dois usuários-chave, sendo eles um voluntário e um coordenador. Ambos os usuários forneceram feedback positivo, destacando que o sistema é rápido e possui uma navegação intuitiva. Foi mencionado por parte do coordenador apenas um ponto a melhorar no design, na questão de exibir horario que ocorre as oficinas, na tela de visualizar oficinas.
  
Os resultados das avaliações indicam que os princípios e metas de usabilidade considerados importantes para o sistema foram, em sua maioria, satisfeitos:

- Efetividade: Os usuários foram capazes de utilizar o sistema sem relatar dificuldades significativas, sugerindo que o sistema permite aos usuários alcançar seus objetivos de forma eficaz.
- Eficiência: O feedback positivo sobre a rapidez do sistema indica que os usuários podem realizar suas tarefas sem gastar mais tempo do que o necessário.
- Satisfação: A navegação intuitiva contribui para uma experiência de usuário positiva, resultando em alta satisfação.

**Sugestões de Melhorias**
  
Troca da Data por Horário das Oficinas:
Substituir a data pelas informações de horários específicos em que ocorrerão as oficinas. Isso pode ajudar os usuários a planejar melhor sua participação, especialmente quando as oficinas ocorrem em múltiplos horários em um mesmo dia.

**Conclusão:**

Os feedbacks iniciais foram positivos, indicando que o sistema está no caminho certo em termos de usabilidade e desempenho. No entanto, para garantir uma melhoria contínua, é crucial implementar a sugestão de substituir a data pelas informações de horário das oficinas, expandir a avaliação para incluir uma base de usuários mais ampla e diversificada, utilizar métodos de coleta de feedback mais variados e detalhados, e criar um ambiente onde a crítica construtiva seja incentivada. Essas sugestões de melhorias devem ser consideradas na próxima versão do protótipo para garantir que o sistema continue evoluindo e atendendo às necessidades de todos os seus usuários.




