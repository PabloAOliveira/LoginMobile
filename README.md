# Login Flutter Dart

Este é um projeto Flutter que implementa uma tela de login estilizada.

## Visão Geral

O projeto consiste em uma única tela de login com um design moderno, apresentando um fundo com gradiente, campos de entrada personalizados para e-mail e senha, e botões para login, recuperação de senha e registro.

## Funcionalidades

- **Design Atraente:** Fundo com gradiente que vai de um tom escuro a um azul acinzentado.
- **Campos de Formulário Personalizados:** Campos para E-mail e Senha com ícones e bordas estilizadas.
- **Validação Visual:** O campo de senha oculta o texto digitado.
- **Interatividade:**
    - Botão "Entrar" com destaque em gradiente vermelho.
    - Opção para "Esqueceu a senha?".
    - Link para "Cadastre-se" para novos usuários.
- **Layout Responsivo:** O uso de `SingleChildScrollView` garante que a tela se adapte a diferentes tamanhos de tela sem quebrar o layout.

## Tecnologias Utilizadas

- **Flutter:** O projeto é construído utilizando o framework Flutter.
- **Dart:** A linguagem de programação utilizada no projeto.
- **Material Design:** Os componentes visuais são baseados no sistema de design do Material, mas personalizados para se adequarem à identidade visual do aplicativo.

## Estrutura do Projeto

```
login_flutter_dart/
├── lib/
│   ├── page/
│   │   └── login_page.dart  # Contém a UI da tela de login
│   └── main.dart            # Ponto de entrada da aplicação
├── assets/
│   └── images/
│       └── cgi.png          # Logo/imagem usada na tela de login
└── pubspec.yaml             # Definições e dependências do projeto
```
