<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/⚽_MATRIXBALL-cliente_haxball-da7b3a?style=for-the-badge&logo=hackthebox&logoColor=fff">
  <img alt="MatrixBall" src="https://img.shields.io/badge/⚽_MATRIXBALL-cliente_haxball-da7b3a?style=for-the-badge&logo=hackthebox&logoColor=fff">
</picture>

### O cliente de **HaxBall** da comunidade Matrix

Leve, rápido e de código-fonte fechado — feito com **Tauri 2** (Rust + WebView).
Nada de Electron rodando um Chrome inteiro: o MatrixBall ocupa pouca memória,
abre voando e coloca o jogo na sua área de trabalho com um clique.

**Windows 10/11** &nbsp;•&nbsp; **Debian/Ubuntu** &nbsp;•&nbsp; **Qualquer Linux (AppImage)**

[![Baixar agora][btn-dl]][latest] [![Site][btn-site]][site] [![Discord][btn-discord]][discord]

[![Downloads total][b-dl]][latest]
[![Última versão][b-ver]][latest]
[![Stars][b-star]][repo]
[![Tauri][b-tauri]][tauri]
[![Plataformas][b-plat]][latest]

</div>

---

## :package: Instaladores

A release mais recente fica sempre no topo. Escolha o arquivo do seu sistema:

| Sistema | Arquivo | Como instalar |
| :-- | :-- | :-- |
| **Windows 10/11 (64-bit)** | `MatrixBall_x.y.z_x64-setup.exe` | dê dois cliques e siga o instalador (NSIS) |
| **Windows (MSI)** | `MatrixBall_x.y.z_x64_en-US.msi` | alternativo para implantação/GPO |
| **Debian / Ubuntu** | `matrix-ball_x.y.z_amd64.deb` | `sudo apt install ./matrix-ball_*.deb` |
| **Qualquer Linux** | `MatrixBall_x.y.z_amd64.AppImage` | `chmod +x` e execute — não precisa instalar |

<details>
<summary><b>Windows</b> — detalhe da instalação</summary>

1. Baixe o `...-setup.exe` em [Releases][latest].
2. Execute o arquivo. Se o SmartScreen avisar, clique em **Mais informações → Executar assim mesmo** (o app ainda não tem assinatura de código).
3. Pronto — abra o **MatrixBall** pelo menu Iniciar.

</details>

<details>
<summary><b>Linux</b> — .deb e AppImage</summary>

```bash
# Debian/Ubuntu (.deb)
sudo apt install ./matrix-ball_*_amd64.deb

# Qualquer distro (AppImage)
chmod +x MatrixBall_*_amd64.AppImage
./MatrixBall_*_amd64.AppImage
```

> O AppImage precisa de `libwebkit2gtk-4.1` instalada (já vem na maioria das distros recentes).

</details>

---

## :sparkles: O que já dá pra fazer

- :one: Abra o **MatrixBall** e cai direto na tela inicial animada no estilo do site.
- :two: Clique em **JOGAR** — o jogo abre em uma janela dedicada, pronta pra entrar numa sala.
- :three: Bate o papo, ajusta as configurações e joga — tudo pelo cliente oficial do HaxBall embutido.

> A interface própria (lista de salas, uniformes, chat e visual customizado) está sendo construída **aos poucos**. O app atual já abre o jogo; as próximas releases trocam o visual por dentro.

## :arrows_counterclockwise: Atualizando

Não precisa reinstalar na mão: a CI publica cada versão nova em [Releases][latest].
O botão **"Baixar agora"** acima sempre aponta pra mais recente.

---

<div align="center">

## :star: Evolução do projeto

[![Star History Chart][starhist]][starhist-link]

Quanto mais estrelas, mais longe a comunidade chega. Deixa a tua! :hugs:

</div>

---

## :office: Sobre este repositório

O **código-fonte é fechado** — este repositório publica **somente os binários**
gerados pela CI a cada versão. O site oficial é
[rrrustico.github.io][site].

Feito com :heart: e [Tauri 2][tauri] pela comunidade **Matrix**.

<div align="center">

[![Discord][btn-discord]][discord]

**:ringed_planet: MATRIX Community**

</div>

> [!NOTE]
> Projeto em desenvolvimento ativo. Binários são publicados assim que o build da CI é validado.

<!-- links -->
[repo]: https://github.com/rrrustico/MatrixClient-Releases
[latest]: https://github.com/rrrustico/MatrixClient-Releases/releases/latest
[site]: https://rrrustico.github.io
[discord]: https://discord.gg/Bx8WGyM9q7
[tauri]: https://tauri.app
[starhist]: https://api.star-history.com/svg?repos=rrrustico/MatrixClient-Releases&type=Date
[starhist-link]: https://star-history.com/#rrrustico/MatrixClient-Releases&Date

<!-- badges -->
[b-dl]: https://img.shields.io/github/downloads/rrrustico/MatrixClient-Releases/total?style=flat-square&logo=download&color=e8823a
[b-ver]: https://img.shields.io/github/v/release/rrrustico/MatrixClient-Releases?style=flat-square&logo=github&color=e8823a
[b-star]: https://img.shields.io/github/stars/rrrustico/MatrixClient-Releases?style=flat-square&logo=star&color=f5b942
[b-tauri]: https://img.shields.io/badge/built%20with-Tauri%202-24c8db?style=flat-square&logo=tauri&logoColor=000
[b-plat]: https://img.shields.io/badge/plataforma-Windows%20%7C%20Linux-0078D6?style=flat-square&logo=linux&logoColor=fff

<!-- buttons -->
[btn-dl]: https://img.shields.io/badge/⬇_BAIXAR_AGORA-e8823a?style=for-the-badge&logo=download&logoColor=fff
[btn-site]: https://img.shields.io/badge/🌐_VER_O_SITE-24c8db?style=for-the-badge&logo=internet-explorer&logoColor=000
[btn-discord]: https://img.shields.io/badge/💬_DISCORD-5865f2?style=for-the-badge&logo=discord&logoColor=fff
