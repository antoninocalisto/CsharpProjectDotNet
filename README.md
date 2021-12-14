# 1. Criando um projeto que suporte .NET e uma programação C#

- O primeiro passo é configurar o ambiente:
    - Fazer o download do VS Community 2019:
        - [Downloads - Visual Studio Subscriptions Portal](https://my.visualstudio.com/Downloads?q=visual%20studio%202019&wt.mc_id=o~msft~vscom~older-downloads)
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/38273860-01f0-4812-9ae2-753fc48c2b34/Untitled.png)
        
    - Durante a instalação deve-se escolher as funcionalidades de download dos pacotes:
        - [ASP.NET](http://asp.net/) e desenvolvimento Web;
        - Desenvolvimento multiplataforma com .NET Core.
    - Fazer o download do VS Code 2019:
        - [Visual Studio Code - Code Editing. Redefined](https://code.visualstudio.com/)
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c007ea1e-ff50-4802-bc4a-d0666a7b704b/Untitled.png)
        
    - Fazer o download do SDK:
        - [Download .NET 5.0 (Linux, macOS, and Windows) (microsoft.com)](https://dotnet.microsoft.com/en-us/download/dotnet/5.0)
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2cedd4e4-6d92-4fd7-988a-baa3586d5cbd/Untitled.png)
        

- Está atualmente na versão 5, mas já está falando da versão 6. É multiplataforma de plataforma de codigo aberto e tem suporte para o c#.
- Para criar um projeto c# com suporte para .NET tem-se que fazer os seguintes passos:
    - Ao abrir o visual studio 2019, deve-se clicar na opção "Criar um projeto":
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1a7578ed-2a32-4798-be18-ca59a888b3f4/Untitled.png)
        
    - Em seguida deve-se clicar para criar um "aplicativo de console" em c# e clicar em "próximo":
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b11c4b0d-21f0-4415-9b76-e6962b6326dd/Untitled.png)
        
    - Deve-se definir o nome do projeto e depois clicar em próximo:
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ce478282-01d7-4b01-bed5-d7f646611c04/Untitled.png)
        
    - Em seguida tem-se que escolher o .NET da versão 5 (o mais atual e estável) e clicar em criar:
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6ee78464-0e92-4763-8b35-190207f73d91/Untitled.png)
        
    - Agora, deve-se esperar a criação do projeto:
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/522c544b-5c83-4d63-8059-2fad1966b8f2/Untitled.png)
        
    - Caso o projeto seja criado com êxito, essa deve ser a visão mostrada:
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/df16ac47-ed9c-4961-8a70-c11eea06593e/Untitled.png)
        
    - Basicamente esse escopo apresentado é composto por um "namespace" que será o nome do projeto, como se fosse um 'empacotador' (definido no Bloco A da figura); esse "namespace" terá classe que podem representar nosso objeto (definido no Bloco A da figura); basicamente toda aplicação de console log terá um método estático (static) chamado "Main" (definido no Bloco C da figura). Além disso, pode-se observar uma árvore no "Gerenciador de Soluções", nele pode-se acessar diversas configurações do projeto além de uma visualização macro do projeto (definido no Bloco D da figura). Por fim, para validar a criação do projeto, pode-se executar o programa (definido no Bloco E da figura) cuja mensagem que será apresentada em um prompt de comando está definida dentro da classe "Main"(definido no Bloco C da figura).
        
        ![curso_cshap.drawio.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ac644e76-4f2a-4272-9a55-500237f82d2a/curso_cshap.drawio.png)
        
    - Feito isso, a tela que deve ser apresentada tem que ser semelhante à tela mostrada abaixo com a mensagem de "Hello world" em um prompt de comando:
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/40f438bf-210a-46bd-b44f-a398d8f5eacd/Untitled.png)
        
    - Vale salientar a importância de entender o que está sendo feito. Para isso pode-se navegar para a pasta do projeto ao clicar com o botão direito do mouse sobre o projeto no "Gerenciado de Soluções" (definido no Bloco A da figura abaixo), das opções que aparecem (definido no Bloco B da figura abaixo) escolher a opção "Abrir pasta no Gerenciador de Arquivos" (definido no Bloco C da figura abaixo).
        
        ![curso_cshap.drawio (1).png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/85a6dd9a-0d9e-4b5d-b970-08baf1eab00a/curso_cshap.drawio_(1).png)
        
    - Ao fazer isso, o projeto criado será aberto no Gerenciador de Arquivos do windows, e ao navegar para o caminho "bin\Debug\net5.0\" pode-se observar os arquivos Assembly gerados pela compilação, como mostrados na figura abaixo:
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bdf7c339-5085-4f23-bd4f-e4d87e8cc93d/Untitled.png)
        
    - 
    -