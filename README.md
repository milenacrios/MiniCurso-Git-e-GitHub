# *_MiniCurso Git & GitHub_* 
Repositório criado a fim de expor os conteúdos ministrados no minicurso de Introdução ao Git e GitHub na XV Semana Acadêmica de Ciência da Computação - UFT. 

* Lembrando que você pode utilizar esse repositório para consultas futuras! Recomendo que você favorite esse repositório, bastando clicar na opção de **star** ali em cima, assim, esse repositório vai estar sempre atrelado ao seu perfil, bastando ir na lista de todos os seus stars para verificar!
 
### Mas afinal, o que é GIT?
* É um sistema de *versionamento de arquivos*!
  * Imagine que você está desenvolvendo um software com sua equipe desenvolvedora. Várias pessoas vão programar partes diferentes desse software, correto? O joão vai ser responsável por criar a app bar da página inicial, a Joana vai ficar responsável pela autenticação com database e por ai vai. Concordamos que fica muito difícil, se para áreas independentes desse software, uma pessoa esperar a outra fazer, te enviar e você começar a sua parte, não é mesmo? E tudo que queremos no mundo da programação, é sempre otimizar nosso serviço! Com o git, você pode desenvolver, enquanto seu colega também desenvolve, o outro também e assim por diante, bastando baixar as atualizações na sua máquina! E ao final? É só unir todas as **branches**. Calma que você já vai aprender o que é isso! Mas então, o que é um sistema de versionamento de arquivos e o que o **GIT faz**?

       #### O Git controla versões = versionamento de arquivos
  * Constantemente, nós programadores desenvolvemos uma aplicação e necessitamos *modificá-la ou otimizá-la*. Ainda no contexto acima, de você e sua equipe, imagine que finalmente, todos os devs terminaram suas devidas funcionalidades e o software tem sua primeira *versão*, mas o cliente encontrou um bug ou acha que de um outro jeito deve ficar melhor...Enfim inúmeras situações podem levar a modificações. Nesse caso, novamente você e sua equipe constroem uma nova versão e assim vai, até chegar na versão final, que é aceita. A qualquer momento você pode *resgatar* uma versão anterior. Isso tudo através do git! Imagine que você fez algo errado no código e levou o software a quebrar, através do git você pode retornar a uma última versão estável! 
 
 E olhe...Levaria muito tempo, se eu ficasse aqui só apresentando as vantagens que o git oferece! Mas já deu para ter uma ideia, né?
 
 * O git nasceu com a necessidade de *controlar as mudanças nos códigos, sincronia na equipe de desenvolvimento e melhor visualização de todas as etapas do projeto* e muito mais!
  
    ![Captura de tela de 2022-10-15 18-44-45](https://user-images.githubusercontent.com/64020657/196008706-7fe21d4f-81cd-484a-bbe8-e8000f20c24e.png)
    
### Como funciona o **versionamento de código* do GIT*

  * Antes de mais nada, vale salientar que o git é um **Sistema de Controle de Versão Distribuído** e funciona da seguinte maneira,
    * Cada desenvolvedor vai ter uma cópia do seu código armazenado localmente, ou seja, na sua própria máquina e poderá enviar suas modificações para um **repositório remoto** que pode ser...Spoiler!...o **github**. Dessa forma, o **git** apresenta **três estados**, que são eles:
      * **Commited** 
      * **modified** = modificado
      * **staged** = preparado
    * Então basicamente, você modifica seus arquivos ali, no seu diretório de trabalho. Posteriormente, deve preparar esses arquivos e adicioná-los à área de stage, ou seja, na área de preparo e por fim, dá um **commit**, indicando que seus arquivos estarão copiados para uma área segura e permanente do diretório git. Em suma, o que acontece é que você vai **commitar** (ah, chamamos assim para indicar que você usou o comando **git commit**, logo logo você vai saber mais sobre!) as modificações ali na sua máquina e posteriormente vai **empurrar**, **git push** para o repositório remoto. Assim como na imagem abaixo!
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
            * *_git commit -m "Primeiro commit"_**
          * O **-m** indica uma mensagem que devemos escrever sobre o que esse commit representa. Seja bastante específico, você pode dizer por exemplo:
              * **_"Commit para correção na linha 47 do arquivo da landing page"_** 
          * Então resumindo, nosso terminal deve-se parecer com isso:
          
            ![Captura de tela de 2022-10-16 18-28-59](https://user-images.githubusercontent.com/64020657/196059209-8931c9ba-b1e3-4690-8831-03188e0db21c.png)
            
### Criando um repositório no github
  #### Mas afinal, o que é GitHub?
  * GitHub é uma plataforma que possibilita a **hospedagem** de arquivos usando o controle de versionamento de arquivos do **git**. É um dos mais famosos **repositórios remotos** existentes, permitindo que você descarregue seus **repositórios locais** de forma **pública**, onde toda a comunidade tem acesso e de forma **privada**, somente você e os colaboradores possuem acesso. Além disso, o **GitHub** vem sendo muito utilizando como **portfólio**, muitos recutradores querem ver o que você anda desenvolvendo, como você desenvolve e normalmente o **GitHub** sempre é solicitado. Ele serve basicamente como uma **_"rede social"_**, uma vez que você expõe sua vida em projetos hahaha e todo mundo pode colaborar! É uma ótima comunidade! E você deve-se recordar daquela primeira imagem que mostramos aqui, o github é o repositório remoto! 
  
   ![Captura de tela de 2022-10-16 19-00-28](https://user-images.githubusercontent.com/64020657/196060317-89f0c370-04f8-4208-a510-5399cf9ba726.png)
    
  * Agora que já sabemos o que é **GitHub**, vamos criar nosso primeiro **reoisitório remoto** e **clonar** para nossa máquina!
  
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
      * **"error: failed to push some refs to 'https://github.com/username/nomedorepositório.git'. Isso porque, o **GitHub** utiliza atualmente o nome **main** para suas branchs, mas o git, que ta na sua máquina chamou de **master** e por isso, o comando não conseguiu encontrar nenhuma branch com nome main para enviar. Dessa forma, uma boa prática, é chamar todas as branchs de main, por isso você pode mudar através do comando:
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
    * **_git clone <link do repositório>
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
      
        
          
     
