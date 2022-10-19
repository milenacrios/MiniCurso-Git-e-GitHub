# *_MiniCurso Git & GitHub_* 
Repositório criado a fim de expor os conteúdos ministrados no minicurso de Introdução ao Git e GitHub na XV Semana Acadêmica de Ciência da Computação - UFT. 

* Lembrando que você pode utilizar esse repositório para consultas futuras! Recomendo que você favorite esse repositório, bastando clicar na opção de **star** ali em cima, assim, esse repositório vai estar sempre atrelado ao seu perfil, bastando ir na lista de todos os seus stars para verificar!
 
### Mas afinal, o que é GIT?
* É um sistema de *versionamento de arquivos*!
  * Imagine que você está desenvolvendo um software com sua equipe desenvolvedora. Várias pessoas vão programar partes diferentes desse software, correto? O joão vai ser responsável por criar a app bar da página inicial, a Joana vai ficar responsável pela autenticação com database e por ai vai. Concordamos que fica muito difícil, se para áreas independentes desse software, uma pessoa esperar a outra fazer, te enviar e você começar a sua parte, não é mesmo? E tudo que queremos no mundo da programação, é sempre otimizar nosso serviço! Com o git, você pode desenvolver, enquanto seu colega também desenvolve, o outro também e assim por diante, bastando baixar as atualizações na sua máquina! E ao final? É só unir todas as **branches**. Calma que você já vai aprender o que é isso! Mas então, o que é um sistema de versionamento de arquivos e o que o **GIT faz**?

       #### O Git controla versões = versionamento de arquivos
  * Constantemente, nós programadores desenvolvemos uma aplicação e necessitamos *modificá-la ou otimizá-la*. Ainda no contexto acima, de você e sua equipe, imagine que finalmente, todos os devs terminaram suas devidas funcionalidades e o software tem sua primeira *versão*, mas o cliente encontrou um bug ou acha que de um outro jeito deve ficar melhor...Enfim inúmeras situações podem levar a modificações. Nesse caso, novamente você e sua equipe constroem uma nova versão e assim vai, até chegar na versão final, que é aceita. A qualquer momento você pode *resgatar* uma versão anterior. Isso tudo através do git! Imagine que você fez algo errado no código e levou o software a quebrar, através do git você pode retornar a uma última versão estável! 
 
 E olhe...Levaria muito tempo, se eu ficasse aqui só apresentando as vantagens que o git oferece! Mas já deu para ter uma ideia, né?
 
 * O git nasceu com a necessidade de *controlar as mudanças nos códigos, sincronia na equipe de desenvolvimento e melhor visualização de todas as etapas do projeto* e muito mais! Ele guarda todo o **histórico** de versões como na **imagem!**
  
    ![Captura de tela de 2022-10-15 18-44-45](https://user-images.githubusercontent.com/64020657/196008706-7fe21d4f-81cd-484a-bbe8-e8000f20c24e.png)
    
### Como funciona o **versionamento de código* do GIT*

  * Antes de mais nada, vale salientar que o git é um **Sistema de Controle de Versão Distribuído** e funciona da seguinte maneira,
    * Cada desenvolvedor vai ter uma cópia do seu código armazenado localmente, ou seja, na sua própria máquina e poderá enviar suas modificações para um **repositório remoto** que pode ser...Spoiler!...o **github**. Dessa forma, o **git** apresenta **três estados**, que são eles:
      * **Commited** 
      * **modified** = modificado
      * **staged** = preparado
    * Então basicamente, você modifica seus arquivos ali, no seu diretório de trabalho. Posteriormente, deve preparar esses arquivos e adicioná-los à área de stage, ou seja, na área de preparo e por fim, dá um **commit**, indicando que seus arquivos estarão copiados para uma área segura e permanente do diretório git. Em suma, o que acontece é que você vai **commitar** (ah, chamamos assim para indicar que você usou o comando **git commit**, logo logo você vai saber mais sobre!) as modificações ali na sua máquina e posteriormente vai **empurrar**, **git push** para o repositório remoto. Assim como na imagem abaixo!
    * 
    ![Captura de tela de 2022-10-15 19-41-17](https://user-images.githubusercontent.com/64020657/196010198-e0653073-f578-4b87-84df-5398252c4ff0.png)
### Vantagens de se utilizar o GIT
  * Controle de Histórico
  * Trabalho em equipe
  * Segurança
  * Organização
  * **Ramificações**
### Mas o que são ramificações?
  * Um outro conceito muito importante é o de ramificações. Isso porque, as **ramificações** são um recurso indispensável no processo de desenvolvimento diário utilizando o **git**. Quando falamos em um desenvolvimento de um x projeto, é sempre muito importante definir quem será responsável por desenvolver o que desse projeto e é por isso que há muitas especializações na computação. Afinal, não da pra dar conta de tudo, não é mesmo? Nesse sentido, o git possibilita você criar várias **branches**, permitindo que você desenvolva recursos, funcionalidades, corrija bugs e por ai vai. Cada **branch** criada terá uma importância nas modificações do projeto. Você pode imaginar que funciona como uma **árvore**, onde ela completa é o projeto inteiro e cada **galho** é uma parte desse projeto que está sendo desenvolvida, seja por exemplo, uma branch para corrigir **bugs**, que podemos nomeá-la de **bugfix** ou uma branch para adicionar uma determinada funcionalidade ao projeto, que podemos chamar, por  exemplo, de **features** 
  
     ![Captura de tela de 2022-10-16 17-33-50](https://user-images.githubusercontent.com/64020657/196056943-e4db297b-7350-4d94-ab84-b40bc911b2f7.png)
  
* A imagem acima pode te ajudar a entender melhor! Ela representa um repositório com a branch principal, que muitas vezes é denominada de **main** ou **master** e ela é criada no instante que **você cria um repositório git**. Ou seja, assim que um repositório é criado, automaticamente, **uma branch** chamada de **principal** também é criada e é nela, que você vai unir todas as outras branchs quando estiverem prontas, com o famoso **git merge**, que você irá aprender depois. Bom, voltando a imagem, além da **branch main**, temos outras duas branchs ou outras duas linhas de desenvolvimento **independentes** que nesse exemplo, será o desenvolvimento **back end** de um sistema, por exemplo, e a outra **branch** será o **front end**. Isso permite um trabalho em paralelo, lembra do que ta escrito no comecinho desse arquivo? Você não precisa esperar uma pessoa terminar, para poder começar a sua parte! E além disso, mantem a **branch principal** livre de códigos que ainda não estão finalizados. 

#### Agora que você já entendeu como funciona o git, o que é versionamento de arquivos, ramificações e branches...Já está pronta para praticar os principais comandos, mas antes, você já **instalou** o git na sua máquina? Nessa parte, não vou me aprofundar muito, mas para instalar, basta acessar o **próprio site do git**, escolher seu sistema operacional e baixar. 
  * [para baixar, basta clicar aqui](https://git-scm.com/downloads)
  * E aqui está toda a documentação que ensina a instalar o git em cada *sistema operacional* (windows, mac e linux), [só clicar aqui](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  
## Chega de conversa e vamos aprender o git na prática!
  * Vamos criar o nosso primeiro *projeto* com git. Mas, calma, vamos ver tudo passo a passo!
    ### Novo projeto
      * Se você instalou o git, pode abrir o seu **git bash** se tiver no windows, mas também o próprio **CMD** e nos sistemas de kernel **linux**, abra o **terminal** e vamos para o seu **primeiro comando**, mas antes vou precisar que você siga alguns desses passos:
        * Crie uma nova pasta no seu computador e pode nomeá-la de **Minicurso GIT**
        * Dentro dessa pasta, crie um arquivo qualquer, pode ser desse mesmo tipo (md) e chame de **readme.md**
      * Agora vamos inicializar um repositório git vazio nessa pasta. Abra o **terminal** ou **git bash** e digite:
        * **_git init_**
          * Perceba que ao abrir a pasta (**Minicurso GIT**), você vai ter criado um novo diretório ali dentro *.git* e é ali que está todas as configurações necessárias para você usar o **git** no seu novo projeto! Se tudo der certo, seu terminal se parecerá com isso:
          
           ![Captura de tela de 2022-10-16 18-11-46](https://user-images.githubusercontent.com/64020657/196058532-89eb08d8-d3b8-4fb3-86ff-648a68aaef80.png)
         * Pronto, você criou seu primeiro repositório git! Agora, você pode verificar o status da sua **árvore de trabalho** com o comando:
            * **_git status_**
         * Como resultado, ele irá mostrar os arquivos modificados que ainda não foram adicionado à **área de preparo**. Nesse caso, os arquivos que o git ainda não esta **"rastreando"** ou **"monitorando"**. No caso ele irá avisar sobre o arquivo que nós criamos **readme.md** e vai indicar que devemos adicionar à **área de staging**. Seu terminal pode se parecer como o meu:
         
         ![Captura de tela de 2022-10-16 18-20-46](https://user-images.githubusercontent.com/64020657/196058896-08ce25b6-d706-404a-84b0-20e65f2fc620.png)
        * Então vamos adicionar nossas modificações à área de preparo com o comando:
          * **_git add readme.md_**
          * Nesse caso ele adicionou o arquivo, mas também podemos utilizar da seguinte forma:
            * **_git add ._**
          * Assim, ele adiciona todas as modificações encontradas. 
          * Resumindo, nós estamos **preparando** nosso arquivo para o nosso **primeiro commit**, indicando que estamos **gravando** nosso arquivo no repositório git criado, para que ele possa **monitorar** esse arquivo! Para **commitar**, basta inserir o comando:
            * **_git commit -m "Primeiro commit"_**
          * O **-m** indica uma mensagem que devemos escrever sobre o que esse commit representa. Seja bastante específico, você pode dizer por exemplo:
              * **_"Commit para correção na linha 47 do arquivo da landing page"_** 
          * Então resumindo, nosso terminal deve-se parecer com isso:
          
            ![Captura de tela de 2022-10-16 18-28-59](https://user-images.githubusercontent.com/64020657/196059209-8931c9ba-b1e3-4690-8831-03188e0db21c.png)
            
### Criando um repositório no github
  #### Mas afinal, o que é GitHub?
  * GitHub é uma plataforma que possibilita a **hospedagem** de arquivos usando o controle de versionamento de arquivos do **git**. É um dos mais famosos **repositórios remotos** existentes, permitindo que você descarregue seus **repositórios locais** de forma **pública**, onde toda a comunidade tem acesso e de forma **privada**, somente você e os colaboradores possuem acesso. Além disso, o **GitHub** vem sendo muito utilizando como **portfólio**, muitos recutradores querem ver o que você anda desenvolvendo, como você desenvolve e normalmente o **GitHub** sempre é solicitado. Ele serve basicamente como uma **_"rede social"_**, uma vez que você expõe sua vida em projetos hahaha e todo mundo pode colaborar! É uma ótima comunidade! E você deve-se recordar daquela primeira imagem que mostramos aqui, o github é o **repositório remoto!** 
  
   ![Captura de tela de 2022-10-16 19-00-28](https://user-images.githubusercontent.com/64020657/196060317-89f0c370-04f8-4208-a510-5399cf9ba726.png)
    
  * Agora que já sabemos o que é **GitHub**, vamos criar nosso primeiro **repositório remoto** e **clonar** para nossa máquina!
  
  * Para criar um repositório, tendo já criado uma conta no github, basta ir em seu **perfil** e na aba de **repositórios**, você logo irá ver um botão na cor de verde esrito **New**, é onde você deve clicar para criar o primeiro **repositório remoto**
  
    ![Captura de tela de 2022-10-16 19-05-02](https://user-images.githubusercontent.com/64020657/196060512-8a422056-9fa1-405e-8e78-6d81d68a5463.png)
    
  * Você deverá preencher algumas informações como nome do repositório, uma descrição, se é **público** ou **privado**, se deseja adicionar **um arquivo readme.md** e por fim, **create repository**!
    
    ![Captura de tela de 2022-10-16 19-08-21](https://user-images.githubusercontent.com/64020657/196060629-54c05066-5612-4ed3-9117-5ddbc227f0f5.png)
    
  * Agora iremos adicionar o nosso repositório que está **localmente**, ou seja, na nossa máquina, o **Minicurso Git** ao reposiório remoto que acabamos de criar no github, basta inserirmos o seguinte comando ao **terminal** ou **git bash**
    * **_git remote add origin <link do repositório>_**
      * Onde esse link é disponibilizado na página do repositório que você criou no github. E ele está disponível em duas formas, **HTTPS** ou **SSH**. Nesse tutorial, vamos utilizar o link no formato **HTTPS**. Basta selecionar a opção e copiar o link para adicionarmos ao terminal com o comando anterior: 
      
      ![Captura de tela de 2022-10-16 19-17-26](https://user-images.githubusercontent.com/64020657/196060985-3b8718ca-611b-4311-ba1c-091c2b66b4ce.png)
      
     * E origin é como chamamos o repositório de **origem** do github! Pronto, passamos o **commit** da nosa máquina para o repositório no **github**. Agora vamos atualizar o **repositório remoto**, **_empurrando_** esse commit da branch atual (**main**) para o github com o seguinte comando:
      * **git push -u origin main**
     
     Quando estiver no terminal, você pode se deparar com o seguinte erro:
      * **"error: failed to push some refs to 'https://github.com/username/nomedorepositório.git'**. Isso porque, o **GitHub** utiliza atualmente o nome **main** para suas branchs, mas o git, que ta na sua máquina chamou de **master** e por isso, o comando não conseguiu encontrar nenhuma branch com nome main para enviar. Dessa forma, uma boa prática, é chamar todas as branchs de main, por isso você pode mudar através do comando:
        * **_git branch -M "main"_**
      * Então recapitulando:
        * Você adicionou o **commit** da **sua máquina** para o **repositório remoto** com o comando:
          * **_git remote add origin <link do seu repositório>_**
        * Depois, você precisa atualizar o **repositório remoto** para receber esse commit, com o comando:
          * **_git push -u origin main_**
        * Caso ele tenha reconhecido um erro devido ao nome da branch, você corrigiu com o comando:
          * **_git branch -M "main"_**
        * AH, e você deve ter percebido que o git solicitou um **_username_**, que provavelmente você deve ter configurado após a instalação do git na sua máquina, mas se ainda está com dificuldade pode verificar o comando certinho que você deve realizar para configurar seu username por [aqui](https://docs.github.com/pt/get-started/getting-started-with-git/setting-your-username-in-git); e uma senha, que na verdade é um token de acesso que você tem que gerar no github através desse [link](https://github.com/settings/tokens)
      * Assim, seu terminal deve se parecer mais ou menos como o meu:
      
          ![Captura de tela de 2022-10-16 19-37-20](https://user-images.githubusercontent.com/64020657/196061767-82229b9d-808c-4382-b202-d76bd51b8beb.png)
          
        * Pronto, se você voltar ao seu **repositório** no **GitHub**, verá que o commit que o que você tinha feito apenas na **sua máquina** agora está no **GitHub**
        
#### Como clonar um repositório remoto para sua máquina
  * Esse comando que você vai aprender agora, permite que você **descarregue** o repositório lá do **GitHub** para um diretório na sua máquina. Bastando que você abra o terminal no **diretório** que deseja que o clone seja **armazenado**, copie o **link** no formato **HTTPS** do **repositório** do **GitHub** e insira no comando:
    * **_git clone <link do repositório>**
    * Dessa forma:
    
      ![Captura de tela de 2022-10-16 19-51-29](https://user-images.githubusercontent.com/64020657/196062259-77e8f271-74ad-41f4-a057-74a06d638b8a.png)

### Alterando na nossa máquina e atualizando o repositório remoto!
  * Bom, já sabemos que modificações acontece a todo momento na vida de um programador. Mas como iremos enviar essas atualizações que estão na **nossa máquina** para o **github**? Vamos ao teste, modifique o arquivo **readme.md** e acrescente a seguinte frase: 
    * **"Estou alterando esse arquivo"** e não esqueça de **salvar**!
    * Agora se você der um **git satus** vai perceber que o que o **estado** do repositório git agora é **modified**, já que você fez uma alteração e ainda não adicionou para **área de staging** e nem **commitou** para que o git possa receber essa alteração. E é justamente isso que você vai realizar após a **modificação no arquivo**:   
        * **_git add ._**
        * **_git commit -m "Acrescentei uma linha ao meu arquivo!"_** 
    * Agora o seu **repositório remoto** lá no **github** precisa receber isso, não é mesmo? e qual comando fazemos? **push!**
        * **_git push origin main_**
     * E....pronto, seu **repositório remoto** já contém a sua modificação e você pode verificar no **github** que a alteração que você fez já está lá. E assim vai, você irá empurrar muitas modificações no fim de um dia de trabalho _hahaha!_
     * Resumindo, seu terminal deve-se encontrar assim:
        
        ![Captura de tela de 2022-10-16 20-04-40](https://user-images.githubusercontent.com/64020657/196062757-7339dfef-0eab-4904-ac8c-75c3d12dfa5e.png)
      
### Exibir as alterações realizadas
 * O comando que você vai aprender agora, possibilita que você consiga identificar o que foi **alterado** e ainda não está sendo **monitorado** pelo git, o que quer dizer que não foi **adicionado** à **área de staging** e nem **commitado**. Diferentemente do git status, que indica o arquivo em questão e o **estado** dele, que pode ser **modiffied** quando sofreu uma **modificação**, o **git diffi** mostra exatamente as linhas alteradas por exemplo. 
 * Para entender melhor, adicione mais uma linha no arquivo **readme,md** com a seguinte frase:
   * **"Alterando mais uma vez este arquivo!"**
 * Posteriormente, digite o comando **_git diffi_** no terminal e ele indicará exatamente a **modificação** realizada e que ainda não foi enviado ao repositório git. Seu terminal pode ser parecer como esse!
 
  ![Captura de tela de 2022-10-17 14-27-21](https://user-images.githubusercontent.com/64020657/196243510-37aec133-237e-4d98-8a5a-7877fa251006.png)
 
### Remoção de um arquivo do repositório git
 * Para entedermos melhor o comando a seguir, crie um novo arquivo para teste, do tipo html. Você pode escrever uma frase qualquer e salvar como sendo?
   * **_index.html_**
 * Agora, vamos supor que vocẽ não deseja mais que o arquivo seja **monitorado** pelo git, ou seja, que ele pertença ao **repositório git** e nem ao **repositório remoto** (_GitHub_). Se você apenas excluir da pasta **Minicurso Git**, ou seja, do seu diretório local, esse arquivo irá para uma área de **_unstaging_**, que é área de arquivos modificados e ainda não preparados, e ainda sim, vai continuar no **repositório remoto** (apenas dê um **push** depois para atualizar sobre a remoção). Sendo assim, existe o comando:
   * **_git rm_** ele remove o arquivo por completo da árvore e do seu diretório, pasta especificar qual arquivo deseja remover. 
    * **_git rm index.html_**
   * Ao dar um **_git satatus_**, perceberá o resultado: **_deleted: index.html_**
   
     ![Captura de tela de 2022-10-17 14-47-34](https://user-images.githubusercontent.com/64020657/196247093-1cca0e4d-7da1-4f0f-a007-ebe5ae4972f7.png)
 ### Como vizualizar o Histórico de todos os commits?
  * Você desenvolve uma funcionalidade, termina e...**commita**. Você corrige um bug e **commita**. Você termina o requisito e **commita**. É possível visualizar _todos_ os **commits** realizados? A resposta é **sim**. Você pode tanto visualizar os **commits** do seu repositório quanto de um repositório **clonado**! E é bastante simples, basta utilizar o comando abaixo no seu terminal e ele mostrará todos os commits:
    * **_git log_**
    
    ![Captura de tela de 2022-10-17 14-54-17](https://user-images.githubusercontent.com/64020657/196248267-c844f1a2-3e75-410f-b7a2-ad77f2a65951.png)
    
### Atualizando seu repositório local
 * Continuando nosso trajeto em aprender como o git funciona, vamos entender agora como atualizar nosso repositório local com base em **objetos** e **referências** do repositório remoto, lá do **github**. Mas por quê? Bem, imagine que uma grande equipe está trabalhando no desenvolvimento de um software e você é um dos desenvolvedores responsáveis por certa parte do software. Acontece que alguns trabalhos dependem um dos outros e você precisa **receber** as aplicações dos seus outros colegas na sua máquina, mantendo a sua **branch** atualizada! 
 * O comando responsável por procurar por todos os **commits**, **arquivos** e **referências** de um **repositório remoto** para seu **repositório local**, possibilitando vizualizar a aplicação completa naquele instante e podendno analisar o **histórico** da produção, acompanhando como a equipe está progredindo e principalmente, manter a sua **branch** com funcionalidades desenvolvidades que podem ser requisito para o seu desenvolvimento, é o:
   * **_git fetch_**
 
   ![Captura de tela de 2022-10-17 15-38-12](https://user-images.githubusercontent.com/64020657/196256359-750ede12-7f5c-4346-a67c-2683aa294bbc.png)
 
 * No entando, o comando apenas baixa o conteúdo do **repositório remoto**, mas não atualiza o estado de trabalho do seu **repositório local**, deixando seu trabalho atual intacto. Para **unir** o conteúdo do **repositório remoto** com o seu, é necessário utilizar o comando:
   * **_git pull_**
 * Ele irá executar um outro comando automaticamente, o **_git merge_**, mas não se preocupe que você vai aprender ainda sobre isso. Por enquanto, apenas absorva as definições de **git fetch** e **git pull**!


### Agora, vamos falar de branch!
 * Vamos fazer uma breve revisão sobre a definição de **branch**! Vamos imaginar uma situação hipotética, onde você, **desenvolvedor** deseja adicionar uma nova funcionalidade à sua aplicação web, um **formulário**, por exemplo. Para isso, você cria uma nova branch para desenvolver essa funcionalidade sem interferir diretamente em outras partes do código. E nomeia sua branch de **formulário** e começa a desenvolver. Nesse sentido, a árvore de trabalho poderá ser semelhante como essa, onde possui a **branch main** e as outras **branchs** independentes. 
   
   ![Captura de tela de 2022-10-17 16-03-39](https://user-images.githubusercontent.com/64020657/196260891-4b96558d-90cb-4bdf-950d-e4ba11d81694.png)
 #### Mas então, como criamos uma branch? Como criar a branch _formulário_?
  * Nós podemos criar uma branch de duas maneiras:
    * A primeira, usando o seguinte comando: 
     * **git branch >nome da branch<** : para a branch formulário, temos: **_git branch formulário_**
     * Nesse caso, ele apenas cria a branch sem dar **checkout** nela, ou seja, sem mudar da **branch anterior** para a nova criada. Para mudar de ramo, use o comando: 
      * **git checkout >nome da branch<**
      
    * A segunda, usando o comando:
     * **git checkout -b >nome da branch<**
     * Se você estiver na branch main, e criar a nova branch **formulário** com o checkout, automaticamente, você sai da branch **main** e muda para a branch **formulário**. Você pode verificar isso com o comando **_git status_** e poderá verificar a lista de branchs da sua árvore de trabalho, com o comando:
     * **_git branch_**
  * Para criar a branch formulário, eu fiz dessa forma:
  
     ![Captura de tela de 2022-10-17 16-21-56](https://user-images.githubusercontent.com/64020657/196264301-4a9d6463-d20c-475f-b231-d8be41c526cd.png)
  
### Add, commit e push na nova branch
 * Já fizemos isso na branch principal e como fazemos na branch nova que acabamos de criar? É simples, basta especificar o nome da branch na hora do **push**
    * **_git add ._**
    * **_git commit -m "Primeiro commit na branch nova!"_**
    * **_git push origin formulario_**
* AH, basta verificar que no repositório remoto a branch já está lá!
* 
    ![Captura de tela de 2022-10-17 16-35-55](https://user-images.githubusercontent.com/64020657/196266718-b016b8b0-454b-4ba5-a428-2ca6c3736052.png)

### Em relação a branchs, quais comandos é importante saber?
   * **_git branch_** = lista todas as branchs da sua árvore de trabalho
   * **_git branch >nome da branch<_** = cria uma nova branch
   * **_git branch -d >nome da branch<_** = apaga uma branch na sua máquina
   * **_git push origin --delete >nome da branch<_** = apaga uma branch no repositório remoto
   * **_git branch -M >novo nome<_** = renomeia a branch
   * **_git branch -a_** = lista todas as branchs do repositório remoto
### Hora de aprender sobre Merge!
 * Suponha que você acaba de receber um email de alguém avisando que há um problema no site que você está desenvolvendo. Como já aprendemos sobre **ramificações**, você não precisa adicionar a correção do problema junto à **branch** principal de desenvolvimento e, portanto, pode criar uma branch **independente** e **paralela**, que vamos chamar de **bugfix**. Assim sua árvore de trabalho, além de outras branchs ou não, terá com certeza um formato parecido com esse: 
    
    ![Captura de tela de 2022-10-17 22-40-33](https://user-images.githubusercontent.com/64020657/196315407-de09ca2b-80aa-4151-9ec5-432a042a6e1c.png)
 * A branch **bugfix** foi criada a partir da branch **main**, ou seja, você estava (**checkout**) na branch **main** quando criou a branch **bugfix**. Mas também há outros tipos de branchs, como a **hotfix** que é criada a partir de branchs de **procução**. Você pode entender melhor, acessando a documentação do [gitflow](https://www.atlassian.com/br/git/tutorials/comparing-workflows/gitflow-workflow). E vamos continuar!
      * Após criar a branch **bugfix**, você programou e programou e, finalmente, corrigiu o erro no site e agora? Agora, você já pode _enviar_ essa correção à linha **principal**, ou seja, para a branch **main**. E para fazermos isso, você vai voltar para a branch **main**, ou seja, dando **checkout** nela e vai executar o famoso **git merge** na branch **bugfix**. Desse jeitinho:
        * **_git checkout -b bugfix_** = aqui você criou a branch para correção do erro, a partir da branch main pois era nela que você estava
          * Após realizar os commits com a correção, você finaliza sua função e precisa voltar para branch **main**     
              * **_git checkout main_**
          * Agora, você vai unir a main com a **bugfix**
              * **_git merge bugfix_**
      
 #### Resolvendo conflitos 
  * Nem sempre quando se da **merge** entre branchs ocorre sem nenhum problema, e acostume-se com isso! Se houveram duas alterações na mesma parte de um arquivo em **branchs diferentes** e você tentar unir essas duas branchs, o **não** poderá mesclá-las. Isso porque, é como se ele tivesse ficado **"confuso"** já que você adicionou uma linha exatamente igual que o seu colega e no mesmo arquivo. Qual ele deve inserir na main? Qual a linha de código **"certa"?**. Para entender melhor, vamos praticar?
   * Na branch **main**, crie um arquivo **index.html** e crie um código html com um título h1: **"Aprendendo GIT"** (não esqueça de commitar e empurrar para o repositório remoto). Dessa forma:    
    ![Captura de tela de 2022-10-18 00-00-31](https://user-images.githubusercontent.com/64020657/196325618-24eba59d-e519-4c3b-b65e-f44290fec6ab.png)
   * Seu terminal pode está assim:    
    ![Captura de tela de 2022-10-18 00-04-24](https://user-images.githubusercontent.com/64020657/196326042-d136dd18-c3a1-4289-8cc1-3e45dabdb073.png)
   * Agora, você irá criar uma nova branch, chame ela de **FrontEnd** e atualize com a branch **main**. Ou seja, receba os arquivos da branch **main** para a branch **FrontEnd** e para isso, basta da **checkout** na branch **main** e um **merge** com a branch **FrontEnd**. Seu terminal deve está assim:
    ![Captura de tela de 2022-10-18 00-15-44](https://user-images.githubusercontent.com/64020657/196327395-6dde7190-b2b5-4c8f-9a9a-beeb3d7ea8ea.png)
   * Então, basicamente o que fizemos acima foi criar a branch **FrontEnd**, da **checkout** na **main**, **mesclar** com a branch **FrontEnd**, e empurrar para o **repositório remoto** com o **git push origin FrontEnd**. Assim, todas as branchs estão com o mesmo arquivo. 
   * Agora, vamos alterar o **index.html** na branch **main** e alterar o título **h1** para: **"Aprendendo a corrigir conflitos"**. Depois disso, adicione à **área de staging**, **commit** e **push** assim como já aprendemos. Posteriormente, dê **checkout** na branch **FrontEnd** e altere o arquivo **index.html** na mesma linha que alteramos na branch main, mudando o **h1** para: **"Aprendendo a corrigir conflitos com o git"**, adicione à **área de staging**, **commit** e **push** na branch FrontEnd. Ao abrir o **github**, você verá que os arquivos nas duas branchs (main e FrontEnd) estão diferentes:
   
   ![Captura de tela de 2022-10-18 22-12-20](https://user-images.githubusercontent.com/64020657/196574037-1b05e4f3-9654-4ccf-81a0-3cc2c3a6f3a0.png)
   
  * Até ai tudo certo, já que alteramos o mesmo arquivo em **branchs diferentes**, mas e se chegou ao fim da minha aplicação e eu queira unir a branch **FrontEnd** com a branch **main**? Qual linha o git vai aceitar como a certa, o **h1** da branch **main** ou o **h1** da branch **FrontEnd**? Para isso, dê **checkout** na branch **main** e em seguida mescle com a **FrontEnd**, assim como já vimos: **git merge FrontEnd**. E...CONFLITO! seu terminal deve apresentar:
   
   ![Captura de tela de 2022-10-18 22-18-33](https://user-images.githubusercontent.com/64020657/196574692-a4648edb-2bf6-478a-978a-35239f9063c2.png)
 * Ou seja, o **git** nos retornou um **conflito de mesclagem** ao tentar unir o conteúdo do arquivo **index.html** da branch **FrontEnd** com a branch **main** e, portanto,  o merge falhou e você precisa resolver primeiro os conflitos e tentar unir novamente. Para resolver os conflitos, você pode usar o **visual studio code** e ele irá indicar o conflito com algumas opções de resolver, tal qual a imagem abaixo:
  
  ![Captura de tela de 2022-10-18 22-22-19](https://user-images.githubusercontent.com/64020657/196575143-c7cbb954-5e4f-48df-b8c6-452f094d57c4.png)
 * Bom, ele mostrou as duas linhas alteradas e é como se estivesse perguntando pra você: Qual é a linha que deve ficar? Você pode utilizar o comando **git diff** para verificar as diferenças entre os arquivos ou o **vscode**, dessa forma:
  ![Captura de tela de 2022-10-18 22-27-52](https://user-images.githubusercontent.com/64020657/196575742-0a1527fa-c7e9-4197-97a3-ad644b87414e.png)
 * No **VSCODE** você pode aceitar algumas opções:
    * **_Accept current change_** = você indica que o código correto é o **current change**, ou seja, o código que tava na sua máquina quando você deu **merge** e escolher essa opção, que é o bloco verde do visual studio code, indica que ela será a que permanecerá no código. 
    * **_Accept incoming change_** = você irá aceitar como código "correto" o que está indicado em azul, ou seja, o arquivo da branch FrontEnd e só essa parte permanecerá no arquivo. 
    * **_Accept booth change_** = indica que você "aceitou" os dois trechos de códigos. 
    * **_Compare changes_** = mostrará as diferenças lado a lado para que escolha a "correta". 
 * No nosso exemplo, vamos supor que eu queira a opção **_accept current change_**, deixando apenas o que estava na branch **main**. Agora é só **commitar**, indicando que o conflito foi resolvido. 
 
  ![Captura de tela de 2022-10-18 22-51-42](https://user-images.githubusercontent.com/64020657/196578527-fee26549-3024-42dd-960e-f8a75433d1d2.png)
 
### Chegou a hora do Pull Request
 * Quando você termina de desenvolver sua função, você pode avisar aos seus colegas de equipe sobre o término, através de um **pull request**. Assim, quando eles recebem a requisição, deve ser feita uma **revisão** afim de verificar se está tudo ok mesmo com o que você desenvolveu e, portanto, pode subir para **main** ou carece de mais algum trabalho. É uma forma de você receber um **feedback** sobre o que desenvolveu!
 * O pull request é feito aqui no próprio **github** e você deve escolher a branch de comparação, que é aquela que você é "dono", ou seja, onde você terminou sua função e a branch base, que no caso é a main. 
 * Para maiores informações sobre pull request, você pode acessar a [documentação](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)!
 
 ### Conclusão
  * O git é, sem dúvidas, _essencial_ na vida de um programador e aprender sobre, torna a sua função mais otimizada possível. Não deixe de compartilhar seus projetos no **github**, é só um **push** para admirar seu percursso como desenvolvedor!
  * Acesse a documentação do [git](https://www.git-scm.com/doc), [gitflow](https://www.atlassian.com/br/git/tutorials/comparing-workflows/gitflow-workflow) e [github](https://docs.github.com/pt). 
