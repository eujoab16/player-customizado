# JMPlayer Generator & Custom Player

> Um gerador de players de vídeo customizados, leves e seguros, com suporte a múltiplos servidores (YouTube, OK.ru, Google Drive e Links Diretos MP4/WebM), desenvolvido para ser hospedado no **GitHub Pages** e embutido via `<iframe>` em blogs e sites.

🔗 **Acesse o projeto online:** [https://eujoab16.github.io/player-customizado/](https://eujoab16.github.io/player-customizado/)

---

## 🚀 Principais Recursos

* **Multi-Plataforma:** Suporte integrado para streaming de vídeos do YouTube, OK.ru, Google Drive e arquivos de vídeo diretos (`.mp4`, `.webm`, `.m3u8`).
* **Interface de Preview e Gerador:** Dashboard intuitiva para colar o link da mídia, testar o player ao vivo e gerar automaticamente o código `<iframe>` pronto para uso no seu blog.
* **Segurança Avançada Integrada:**
  * **Bloqueio de Menu de Contexto:** Impede o clique direito do mouse na página.
  * **Bloqueio de Atalhos:** Desativa atalhos de inspeção e cópia (`F12`, `Ctrl+Shift+I/J/C`, `Ctrl+U`, `Ctrl+C`, `Ctrl+S`).
  * **Proteção de Seleção:** Desativa a seleção de texto globalmente (mantendo funcional apenas em campos de formulário e inputs).
  * **Sandbox de Iframe:** Proteção contra redirecionamentos maliciosos gerados por players de terceiros (como OK.ru).
* **Controles Customizados:** Interface própria de reprodução (Play/Pause, Barra de Progresso com Seek, Controle de Volume, Ajuste de Velocidade de Reprodução e Tela Cheia).
* **Marca d'Água Discreta:** Identificação visual elegante fixada no player (`JMPlayer`).

---

## 🛠️ Como Publicar no GitHub Pages

Para colocar este projeto no ar de forma totalmente gratuita utilizando o GitHub Pages, siga os passos abaixo:

1. **Crie um Repositório no GitHub:**
   * Acesse [GitHub](https://github.com/) e crie um **New repository**.
   * Defina um nome para o projeto (ex: `player-customizado`).
   * Deixe o repositório como **Public** (Obrigatório para o GitHub Pages gratuito).
   * Marque a opção **Add a README file** e clique em **Create repository**.

2. **Adicione o Código Principal:**
   * No seu repositório, clique em **Add file** > **Create new file**.
   * Nomeie o arquivo exatamente como **`index.html`**.
   * Cole todo o código HTML/JavaScript do player.
   * Clique em **Commit changes...** para salvar.

3. **Ative o GitHub Pages:**
   * Vá até a aba **Settings** (Configurações) do seu repositório.
   * No menu lateral esquerdo, clique em **Pages** (dentro de *Code and automation*).
   * Em **Build and deployment** > **Branch**, altere de *None* para **`main`** (ou `master`) e mantenha a pasta em `/ (root)`.
   * Clique em **Save**.

O GitHub gerará o link oficial do seu site em instantes.

---

## 💡 Como Usar

1. Acesse o player em [https://eujoab16.github.io/player-customizado/](https://eujoab16.github.io/player-customizado/).
2. Na caixa de seleção, escolha a origem do vídeo (**YouTube**, **OK.ru**, **Google Drive** ou **Link Direto**).
3. Cole a URL correspondente do vídeo no campo de entrada.
4. Clique em **Gerar Player**.
5. O sistema exibirá uma pré-visualização interativa e gerará o código HTML do `<iframe>` logo abaixo. Copie esse código e cole no HTML do seu site ou blog.

---

## 📄 Licença

Este projeto é de código aberto e disponibilizado para uso livre em projetos pessoais e profissionais.
