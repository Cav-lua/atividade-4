# **APP Troca de Imagens**

> Um aplicativo Android simples para alternar entre diferentes imagens ao toque de um botão.

## 📱 Descrição

O **APP Troca de Imagens** permite ao usuário alterar a imagem exibida na tela principal com apenas um clique em um dos botões. 
Ideal para quem deseja uma aplicação prática para visualização e mudança rápida de imagens.

## 🔧 Funcionalidades

- [x] Exibição de uma imagem inicial na tela
- [x] Botões para:
  - Alterar para Imagem 1
  - Alterar para Imagem 2
  - Retornar para a imagem original
- [x] Interface simples com um layout em vermelho vibrante

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Koala | 2024.1.2)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para estrutura da interface
- [x] **ImageView** para exibição de imagem
- [x] **Button** para alternar entre as imagens
- [x] **TextView** para exibir instruções de uso

## 🛠️ Como Rodar o Projeto

Para executar este projeto em seu ambiente de desenvolvimento local, siga os passos abaixo:

1. Clone o repositório:

    ```bash
    git clone https://github.com/Cav-lua/troca-de-imagens-app.git
    ```

2. Abra o projeto no Android Studio.
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

```bash
├── app
│   ├── src
│   │   ├── main
│   │   │   ├── java/com/example/myapplication
│   │   │   │   └── MainActivity.java       # Classe principal para as trocas de imagem
│   │   │   └── res
│   │   │       ├── layout
│   │   │       │   └── activity_main.xml   # Layout da tela principal
│   │   │       ├── drawable                # Imagens utilizadas no app
│   │   │       └── values
│   │   │           ├── strings.xml         # Strings usadas no app
│   │   │           ├── colors.xml          # Cores definidas no projeto
│   └── build.gradle                        # Configuração do Gradle
└── README.md                               # Este arquivo
```
🎨 Design e Prototipagem
A interface do app foi criada usando ConstraintLayout para manter a simplicidade e a clareza em diferentes tamanhos de tela. O fundo é vermelho (#FF0000), criando contraste com as imagens e botões.

🖥️ Telas do Aplicativo
Tela Principal

Na tela principal, o usuário vê uma imagem padrão, com opções para alternar para outras imagens ou voltar à original.

![TelaPadrão](https://github.com/user-attachments/assets/7fcc2353-0cca-4d39-92c0-f04b87375d3b)
![TrocaDeTela](https://github.com/user-attachments/assets/356323cf-6924-4f4e-bf30-3400a3c71c3f)



👨‍💻 Desenvolvedores
Cav-lua - Desenvolvedor - GitHub

📄 Licença
Este projeto está licenciado sob os termos da licença MIT.
