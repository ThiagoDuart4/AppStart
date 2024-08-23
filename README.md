# Rede Social da Igreja

Este é um projeto de uma rede social desenvolvido para a igreja, utilizando React Native com Expo. O objetivo é criar uma plataforma onde os membros possam se conectar, compartilhar mensagens, eventos e manter a comunidade unida.

## Funcionalidades

- **Cadastro e Login**: Permite que os usuários se cadastrem e façam login na plataforma.
- **Feed de Notícias**: Exibe as postagens mais recentes dos membros da igreja.
- **Perfil do Usuário**: Cada membro tem um perfil personalizado onde pode atualizar suas informações e foto de perfil.
- **Chat em Grupo e Individual**: Comunicação entre membros por mensagens diretas e em grupos.
- **Eventos**: Área dedicada para divulgar eventos da igreja, com possibilidade de confirmação de presença.
- **Devocionais Diários**: Seção onde devocionais e reflexões diárias são postadas.

## Pré-requisitos

- Node.js v14 ou superior
- Expo CLI
- Yarn ou NPM

## Instalação

1. **Clone o repositório**:

    ```bash
    git clone https://github.com/seuusuario/rede-social-igreja.git
    cd rede-social-igreja
    ```

2. **Instale as dependências**:

    ```bash
    yarn install
    ```

    ou

    ```bash
    npm install
    ```

3. **Inicie o projeto**:

    ```bash
    expo start
    ```

    Isso abrirá o Metro Bundler em seu navegador. Você pode escanear o QR code com o aplicativo Expo Go em seu dispositivo móvel para rodar o projeto.

## Estrutura do Projeto

- **src/components/**: Componentes reutilizáveis da aplicação.
- **src/screens/**: Telas principais da aplicação (Login, Feed, Perfil, etc).
- **src/navigation/**: Configuração da navegação entre as telas.
- **src/services/**: Serviços para integração com APIs, como Firebase ou qualquer outro backend.
- **src/assets/**: Imagens, ícones e outros recursos estáticos.

## Tecnologias Utilizadas

- **React Native**: Para desenvolvimento mobile.
- **Expo**: Framework para facilitar o desenvolvimento e deploy.
- **React Navigation**: Para navegação entre telas.
- **Firebase**: (
