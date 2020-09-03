## Executar projeto por IDE
É possível executar os projetos dentro de cada IDE (Android Studio e XCode), irei mostrar como fazer isso.

### Android:

Primeiramente você precisa fazer download do [Android Studio](https://developer.android.com/studio)

De forma resumida:

1. Faça o download e instalação do Android Studio.
2. Com o Android Studio aberto, selecione `Open an existing Android Studio project`.
3. Navegue até a pasta do projeto a pasta `android`.
4. Na barra de menu superior, selecione `Tools>AVD Maneger`.
5. Clique em `Create Virtual Device,` selecione o emulador desejado (recomendo o Pixel2 ou superior).
6. Na Tela `System Image`, selecione a aba `x86 Images` e faça download de uma imagem que seja `x86_64`.
7. Renomeie seu dispositivo com um nome de sua preferência e clique em Finish.

Após o download e instalação do emulador, você poderá iniciar o projeto, acessando a barra de menu superior `Run>Run 'app'`

**Atenção:** Verifique se o servidor está rodando antes de executar o projeto, em alguns casos o Android Studio não faz isso automaticamente, então certifique-se rodar o `yarn start` antes.

### iOS

Para executar o projeto no iOS você precisa fazer download do [XCode](https://apps.apple.com/br/app/xcode/id497799835?mt=12)

De forma resumida, caso não queira ver o vídeo:

1. Acesse a AppStore e faça download do XCode.
2. Abra o XCode e clique em `Open another project`.
3. Navegue até a pasta do projeto e entre na pasta `ios`.
4. Abra com o xcode o arquivo `NOME_DO_PROJETO.xcworkspace` ou `NOME_DO_PROJETO.xcodeproj` (recomendo que abra sempre o `.xcworkspace` em projetos que possuem o arquivo com essa extensão).
5. Para rodar o projeto, acesse o menu superior `Product>Run`
