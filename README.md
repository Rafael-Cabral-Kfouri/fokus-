# 🍅 Fockus - App de Técnica Pomodoro

Um aplicativo mobile desenvolvido em **React Native** com **Expo** para gerenciar seus ciclos de estudo e descanso usando a famosa Técnica Pomodoro.

<p align="center">
  <img src="./assets/Imagem%20foco.png" width="200" alt="Imagem do modo Foco do Fockus">
</p>

## ✨ Funcionalidades (Atuais e Previstas)

-   [x] **Seleção de Modo:** Escolha entre os tempos de Foco (25min), Pausa Curta (5min) e Pausa Longa (15min).
-   [x] **Interface Intuitiva:** Design moderno e fácil de usar.
-   [ ] Contagem Regressiva em Tempo Real.
-   [ ] Notificações Sonoras e Visuais.
-   [ ] Histórico de Sessões.

## 🚀 Como Executar o Projeto

Siga os passos abaixo para rodar o Fockus na sua máquina:

**Pré-requisitos:** Node.js e npm/yarn instalados.

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/fockus.git
    cd fockus
    ```

2.  **Instale as dependências:**
    ```bash
    npm install
    # ou
    yarn install
    ```

3.  **Inicie o servidor de desenvolvimento:**
    ```bash
    npx expo start
    ```
    Um terminal com um QR Code será aberto.

4.  **Execute no seu celular:**
    *   Instale o app **Expo Go** ([Android](https://play.google.com/store/apps/details?id=host.exp.exponent) | [iOS](https://apps.apple.com/br/app/expo-go/id982107779)).
    *   Abra o app Expo Go e escaneie o QR Code com a câmera do seu celular.

5.  **Execute em um emulador:**
    *   **Android:** Pressione `a` no terminal onde o Expo está rodando.
    *   **iOS:** Pressione `i` no terminal (é necessário um Mac com Xcode instalado).

## 🛠️ Tecnologias Utilizadas

-   [React Native](https://reactnative.dev/)
-   [Expo](https://expo.dev/)
-   JavaScript

## 📦 Estrutura do Projeto (Resumida)
```bash
fockus/
├── assets/ # Imagens e ícones do projeto
│ ├── Imagem foco.png
│ ├── Imagem descanso curto.png
│ └── Imagem descanso longo.png
├── App.js # Componente principal da aplicação
└── package.json # Dependências e scripts do projeto
```

## 🤝 Como Contribuir

Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir uma **Issue** ou um **Pull Request**.

1.  Faça um Fork do projeto
2.  Crie uma Branch para sua Feature (`git checkout -b feature/AmazingFeature`)
3.  Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4.  Push para a Branch (`git push origin feature/AmazingFeature`)
5.  Abra um Pull Request

---

**Nota:** Este é um projeto de estudo desenvolvido durante o curso da Alura. Sem fins comerciais.
