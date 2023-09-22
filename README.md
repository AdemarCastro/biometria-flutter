# Flutter Biometric Authentication App

Este é um projeto acadêmico que demonstra a autenticação biométrica, de senha e de Face ID em um aplicativo Flutter multiplataforma usando a linguagem Dart. O objetivo deste projeto é fornecer uma introdução prática à autenticação biométrica em aplicativos Flutter, abrangendo várias formas de autenticação.

## Pré-requisitos

Antes de começar, você precisa ter o ambiente de desenvolvimento Flutter configurado em sua máquina. Certifique-se de que você possui o Flutter e o Dart instalados. Se não o tiver, siga as instruções de instalação na [documentação oficial do Flutter](https://flutter.dev/docs/get-started/install).

## Instalação

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/flutter-biometric-authentication.git
```

2. Navegue até o diretório do projeto:

```bash
cd flutter-biometric-authentication
```

3. Execute o aplicativo em seu dispositivo ou emulador:

```bash
flutter run
```

## Recursos do Projeto

Este projeto demonstra as seguintes funcionalidades:

### 1. Autenticação Biométrica

- Utiliza a biblioteca `local_auth` para verificar a compatibilidade e autenticar com a biometria do dispositivo (impressão digital ou reconhecimento facial).
- Mostra uma mensagem de motivo personalizada para o usuário durante a autenticação.

### 2. Autenticação de Senha

- Fornece uma opção para o usuário inserir uma senha manualmente como alternativa à autenticação biométrica.

### 3. Interface do Usuário

- Exibe uma tela de carregamento inicial enquanto a autenticação biométrica está ocorrendo.
- Navega para a tela principal do aplicativo após a autenticação bem-sucedida.

## Estrutura do Projeto

O projeto consiste em três partes principais:

- `main.dart`: Arquivo de entrada do aplicativo que define o `MyApp`.
- `authentication.dart`: Classe `Authentication` que gerencia a lógica de autenticação.
- `loading_screen.dart` e `my_home_page.dart`: Telas do aplicativo que são exibidas durante o carregamento e após a autenticação bem-sucedida, respectivamente.

## Contribuição

Sinta-se à vontade para contribuir com melhorias ou correções neste projeto. Basta seguir estas etapas:

1. Faça um fork deste repositório.
2. Crie uma nova branch com suas alterações: `git checkout -b minha-feature`.
3. Faça commit das suas alterações: `git commit -m 'Adicione uma nova feature'`.
4. Envie as alterações para a sua branch: `git push origin minha-feature`.
5. Envie um pull request para este repositório.

---

## Contato

e-mail: ademar.castro.curriculo@gmail.com

Este projeto foi criado com fins acadêmicos para demonstrar conceitos de autenticação biométrica em aplicativos Flutter. Esperamos que você ache útil para aprender mais sobre esse tópico interessante. Se tiver alguma dúvida ou precisar de ajuda, sinta-se à vontade para entrar em contato!