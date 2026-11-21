# OGC Tela: downloads

Compartilhador de tela entre amigos, sem servidor e criptografado de ponta a ponta.
Este repositório tem **só os instaladores**. Para entrar numa sala, você precisa de um convite de alguém do grupo.

## Baixar a versão mais nova

Vá em **[Releases → Latest](../../releases/latest)** e baixe:

| Sistema | Arquivo |
|---|---|
| Windows 10/11 | `OGC-Tela_x.y.z_x64-setup.exe` |
| Linux (Ubuntu 22.04+, Debian 12+) | `OGC-Tela_x.y.z_amd64.AppImage` |

## Instalar

**Windows:** abra o `.exe`. Se aparecer "O Windows protegeu o computador", clique em **Mais informações → Executar assim mesmo** (o app não tem certificado pago da Microsoft).

**Linux:**
1. Uma vez só: `sudo apt install libfuse2` (Ubuntu 22.04 / Debian 12) ou `sudo apt install libfuse2t64` (Ubuntu 24.04+).
2. `chmod +x OGC-Tela*.AppImage && ./OGC-Tela*.AppImage`

No Linux dá para assistir e, na sessão **X11**, também transmitir. Para transmitir, instale uma vez: `sudo apt install ffmpeg`. No Linux o som do Discord vai junto na transmissão; no Wayland ainda não dá para transmitir.

## Atualizações

A partir da versão 0.3, o app avisa sozinho quando sai versão nova: é só clicar em **Atualizar agora**.
Toda atualização é assinada digitalmente, e o app recusa qualquer arquivo que não tenha a assinatura do dono do projeto.
