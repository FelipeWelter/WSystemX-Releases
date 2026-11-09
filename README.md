# WSystemX v0.2.8.1 — Estável

Distribuição oficial do WSystemX, desenvolvido por **Felipe Welter**, para **Windows 10/11 x64**. Este repositório contém apenas documentação e arquivos de distribuição. O código-fonte permanece privado em FelipeWelter/PC-Toolkit.

## Downloads

- [Release WSystemX v0.2.8.1 - Estável](https://github.com/FelipeWelter/WSystemX-Releases/releases/tag/v0.2.8.1)
- [WSystemX-v0.2.8.1-win-x64-Setup.exe](https://github.com/FelipeWelter/WSystemX-Releases/releases/download/v0.2.8.1/WSystemX-v0.2.8.1-win-x64-Setup.exe)
- [SHA256SUMS.txt](https://github.com/FelipeWelter/WSystemX-Releases/releases/download/v0.2.8.1/SHA256SUMS.txt)

A distribuição atual utiliza somente o instalador. Confira o SHA-256 antes de executar e siga o assistente de instalação. O runtime .NET está incluído. A instalação exige autorização de administrador do Windows.

## Funcionalidades e atualização

Dashboard, inventário, sensores, diagnósticos SMART, rede, Wi-Fi, Bluetooth, eventos, drivers, Defender, Firewall, manutenção controlada, relatórios e histórico local. A disponibilidade de informações depende do hardware e dos drivers.

Na v0.2.8.1, o atualizador consulta as releases estáveis deste repositório, ignora pré-versões e apresenta notas e progresso do download. O instalador é conferido por tamanho e SHA-256. A instalação exige confirmação explícita; o aplicativo encerra suas operações e um auxiliar abre o instalador externo, sem instalação silenciosa.

Configurações e histórico existentes em `%LOCALAPPDATA%\PCToolkit` ficam fora dos arquivos substituídos. Versões antigas com o atualizador bloqueado precisam instalar a v0.2.8.1 pelo link acima.

## Estado da distribuição

**Versão publicada sem testes funcionais, conforme determinação do proprietário. Validação manual pendente.**

Assinatura Authenticode, certificação de segurança e proveniência assinada foram adiadas para esta versão por decisão do proprietário. O fluxo utiliza HTTPS, origem oficial, SHA-256 e confirmação do usuário. As proteções do Windows, incluindo Defender, SmartScreen e UAC, permanecem habilitadas conforme a configuração do sistema. Hashes verificam integridade dos bytes; não equivalem a assinatura do desenvolvedor.

A tag pública é lógica e corresponde à versão privada. Nenhum código-fonte ou objeto do histórico Git privado é copiado para este repositório. As notas da release registram o commit e a compilação de origem. O instalador público contém os mesmos bytes produzidos no repositório privado.

## Histórico

Releases anteriores, incluindo a v0.2.8 RC2, permanecem disponíveis com suas notas e arquivos originais. A política descrita acima se aplica à v0.2.8.1 e substitui os requisitos anteriores que condicionavam essa publicação à assinatura e homologação.
