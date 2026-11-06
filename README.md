# God of War PSP Recomp Android

**🇧🇷 Português | 🇺🇸 English**

Projeto comunitário independente para Android ARM64 que reúne as recompilações nativas de **God of War: Chains of Olympus** e **God of War: Ghost of Sparta** em um único aplicativo. O launcher permite selecionar qual jogo iniciar e mantém os dados de cada título separados. O APK não inclui arquivos específicos dos jogos.

Independent community Android ARM64 project combining the native recompilations of **God of War: Chains of Olympus** and **God of War: Ghost of Sparta** in one app. The launcher lets players choose a game and keeps each title's data separate. The APK does not include game-specific files.

> **Aviso legal / Legal notice:** projeto de fãs, sem afiliação ou aprovação da Sony Interactive Entertainment ou da Santa Monica Studio. God of War é uma marca de seu titular. O usuário deve fornecer suas próprias cópias dos jogos, obtidas legalmente. Este repositório e os APKs de lançamento não devem distribuir ISOs, dumps ou outros arquivos protegidos dos jogos.
>
> Unofficial fan project, not affiliated with or endorsed by Sony Interactive Entertainment or Santa Monica Studio. God of War is a trademark of its owner. Players must provide their own legally obtained game copies. This repository and release APKs must not distribute ISOs, dumps, or other copyrighted game files.

---

## 🇧🇷 Português

### Jogos disponíveis

| Jogo | ID PSP | Estado da integração |
|---|---|---|
| God of War: Chains of Olympus | `UCUS98653` | Integrado ao APK Dual |
| God of War: Ghost of Sparta | `UCUS98737` | Integrado ao APK Dual |

**Os dois jogos já foram iniciados e testados pelo usuário no mesmo aplicativo.** Isso confirma a integração funcional no aparelho usado no teste; compatibilidade e desempenho em outros dispositivos ainda podem variar. O APK não deve conter `image.bin`, ISOs ou dumps; cada usuário importa seus próprios arquivos.

### Recursos

- Um único aplicativo Android com seleção entre os dois jogos.
- Bibliotecas nativas independentes para cada título, sem colisão entre `libmain_coo.so` e `libmain_gos.so`.
- Dados, arquivos de jogo, saves e logs organizados por ID do jogo.
- Controles por toque e suporte a controles externos.
- Opções de gráficos, proporção de tela e desempenho.
- HUD configurável com FPS, tempo de quadro, RAM e posição.
- Interface em português e inglês.
- Verificador de atualizações que consulta as releases publicadas no GitHub.

### Instalação

1. Abra [Releases / Lançamentos](https://github.com/flavinxs0/gow-psp-recomp-android/releases).
2. Baixe o APK Dual anexado à versão desejada.
3. Instale o APK no Android.
4. No launcher, selecione o jogo e importe os arquivos da sua própria cópia legal: `game.iso` e `image.bin`.
5. Mantenha espaço livre suficiente para os arquivos dos jogos e dados gerados.

O aplicativo mantém os arquivos de cada jogo separados usando os IDs `UCUS98653` e `UCUS98737`. Em **Instalar arquivos do jogo**, importe os dois arquivos correspondentes ao título selecionado. O APK e o repositório não devem distribuir esses arquivos.

### Atualizações

O aplicativo possui um verificador de atualizações em **Extras**. Ele consulta a última release publicada; builds de teste do GitHub Actions são artefatos temporários e não aparecem como versões publicadas no atualizador.

Consulte também a página de [Releases](https://github.com/flavinxs0/gow-psp-recomp-android/releases).

### Relatar problemas

Abra uma [Issue](https://github.com/flavinxs0/gow-psp-recomp-android/issues) com o modelo do aparelho, versão do Android, versão do app, jogo selecionado e passos para reproduzir o problema. Envie apenas logs técnicos. **Não envie ISOs, arquivos do jogo, dumps ou conteúdo protegido por direitos autorais.**

---

## 🇺🇸 English

### Available games

| Game | PSP ID | Integration status |
|---|---|---|
| God of War: Chains of Olympus | `UCUS98653` | Integrated into the Dual APK |
| God of War: Ghost of Sparta | `UCUS98737` | Integrated into the Dual APK |

**The user has launched and tested both games in the same app.** This confirms the integration on the tested device; compatibility and performance may vary on other devices. The APK must not contain `image.bin`, disc images, or dumps; each player imports their own files.

### Features

- One Android app with a selector for both games.
- Independent native libraries for each title, avoiding `libmain_coo.so` / `libmain_gos.so` collisions.
- Per-game storage for game files, saves, and logs.
- On-screen touch controls and external controller support.
- Graphics, aspect-ratio, and performance settings.
- Configurable HUD for FPS, frame time, RAM, and position.
- Portuguese and English interface.
- In-app update checker for published GitHub releases.

### Installation

1. Open [Releases](https://github.com/flavinxs0/gow-psp-recomp-android/releases).
2. Download the Dual APK attached to the desired release.
3. Install it on Android.
4. Select a game in the launcher and import the files from your own legal copy: `game.iso` and `image.bin`.
5. Keep enough free storage for game files and generated data.

The app keeps each game's files separate using IDs `UCUS98653` and `UCUS98737`. Use **Install game files** to import both files for the selected title. The APK and repository must not distribute those files.

### Updates and bug reports

The update checker is available under **Extras**. It checks published GitHub releases; temporary Actions artifacts are not published versions and are not offered by the in-app updater.

Report issues at [Issues](https://github.com/flavinxs0/gow-psp-recomp-android/issues). Include device, Android version, app version, selected game, and reproduction steps. Share technical logs only—never game images, dumps, or copyrighted files.

---

## Links

- [Releases / Lançamentos](https://github.com/flavinxs0/gow-psp-recomp-android/releases)
- [Actions / Compilações automáticas](https://github.com/flavinxs0/gow-psp-recomp-android/actions)
- [Issues / Problemas e sugestões](https://github.com/flavinxs0/gow-psp-recomp-android/issues)
- [Código-fonte / Source code](https://github.com/flavinxs0/gow-psp-recomp-android/tree/android)
