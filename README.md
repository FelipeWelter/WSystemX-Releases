# WSystemX

**Monitore o hardware, diagnostique o Windows e analise o desempenho dos seus jogos.**

Desenvolvido por **Felipe Welter**, o WSystemX é um aplicativo desktop para **Windows 10 e 11 (x64)**, construído com **C# / .NET 10 e WPF**.

Este é o **repositório público oficial de distribuição**. O código-fonte e o histórico de desenvolvimento permanecem no repositório privado `FelipeWelter/PC-Toolkit`.

## Versão atual

**WSystemX v0.3.1 — Estável** · homologada pelo proprietário e publicada em 16/11/2026.

[**Baixar instalador Windows x64**](https://github.com/FelipeWelter/WSystemX-Releases/releases/download/v0.3.1/WSystemX-v0.3.1-win-x64-Setup.exe) · [Notas e arquivos da versão](https://github.com/FelipeWelter/WSystemX-Releases/releases/tag/v0.3.1) · [SHA256SUMS.txt](https://github.com/FelipeWelter/WSystemX-Releases/releases/download/v0.3.1/SHA256SUMS.txt)

<details>
<summary>Detalhes do instalador e verificação SHA-256</summary>

- **Arquivo:** `WSystemX-v0.3.1-win-x64-Setup.exe`
- **Tamanho:** 61.554.734 bytes
- **SHA-256:** `7dc8368545d0ddca08b885a09ed3322c725e505a5acfc9c779c14c95de0826fb`
- **Distribuição:** instalador Windows x64; o runtime .NET é incluído no pacote.

</details>

## WSystemX em uso

- **Visão geral.** Consulte as temperaturas de CPU e GPU, a utilização da memória e o espaço ocupado no disco pelo Dashboard.
- **Desempenho em jogos.** Abra uma sessão gravada para analisar gráficos de FPS e frametime, identificar picos e consultar as métricas de 1% low e 0,1% low.
- **Monitoramento em tempo real.** Acompanhe os últimos 60 segundos de temperatura e utilização de CPU e GPU e o histórico de uso da RAM.

## Principais recursos

| Área | Recursos |
| --- | --- |
| **Dashboard** | Visão geral de CPU, GPU, RAM, armazenamento, bateria e indicadores de saúde do computador. |
| **Hardware** | Inventário, sensores, temperaturas e dados disponíveis dos componentes. |
| **Jogos e FPS** | Monitoramento de FPS e frametime, histórico de sessões, executáveis cadastrados e overlay (OSD) personalizável. |
| **Armazenamento** | Discos e volumes, utilização de espaço, consultas SMART e análise controlada de temporários. |
| **Rede** | Adaptadores, Wi-Fi, Bluetooth, tráfego e ferramentas de diagnóstico de conectividade. |
| **Windows** | Eventos, drivers, Windows Update, Microsoft Defender e Firewall. |
| **Manutenção** | Monitoramento de processos e ferramentas de diagnóstico. |
| **Histórico e relatórios** | Registros locais e exportações de informações coletadas. |
| **Configurações** | Preferências de monitoramento, alertas, aparência, OSD, dados e atualizações. |

A disponibilidade de sensores, RPM de ventoinhas, SMART, captura de FPS e outros dados depende do hardware, dos drivers, das permissões e dos recursos suportados pelo Windows. Uma leitura indisponível não equivale a um valor zero.

## Instalação

1. Baixe o instalador oficial na seção **Versão atual**.
2. Opcionalmente, confira o SHA-256 com `Get-FileHash` no PowerShell.
3. Execute o instalador e confirme as solicitações do Windows.
4. Abra o WSystemX e configure suas preferências.

A instalação pode exigir privilégios de administrador. O Windows Defender, SmartScreen e UAC continuam aplicando suas proteções conforme as configurações do sistema.

## Atualizações: Estável e Beta

O WSystemX consulta as releases deste repositório e permite escolher o canal de atualização:

- **Estável:** versões finais publicadas, sem incluir pré-lançamentos.
- **Beta:** versões candidatas disponíveis para testes, além das versões finais elegíveis.

O atualizador verifica a origem HTTPS, o tamanho e o **SHA-256** do instalador. A instalação requer confirmação do usuário; não é silenciosa. As preferências e o histórico local são mantidos fora dos arquivos de instalação, em `%LOCALAPPDATA%\PCToolkit`.

**Importante:** a compatibilidade do fluxo de atualização foi verificada, mas isso não substitui a recomendação de manter backup dos dados antes de grandes mudanças de versão.

## Segurança e integridade

O instalador **v0.3.1 não possui assinatura digital Authenticode**. Essa funcionalidade foi adiada; portanto, o Windows pode apresentar avisos de reputação ou confirmação. Não desative as proteções do Windows para instalar o aplicativo.

O SHA-256 permite verificar a integridade dos bytes baixados, mas **não substitui uma assinatura digital que autentique o desenvolvedor**. Baixe sempre pelo repositório oficial e confira os arquivos publicados.

Metadados da distribuição: [BUILD-INFO.json](https://github.com/FelipeWelter/WSystemX-Releases/releases/download/v0.3.1/BUILD-INFO.json) · [DEPENDENCIES.json](https://github.com/FelipeWelter/WSystemX-Releases/releases/download/v0.3.1/DEPENDENCIES.json).

## Histórico de versões

As versões anteriores e os pré-lançamentos permanecem disponíveis na [página de Releases](https://github.com/FelipeWelter/WSystemX-Releases/releases). O repositório público hospeda os **artefatos de distribuição**, e não o código-fonte privado do aplicativo.

---

**Desenvolvido por Felipe Welter** · [GitHub](https://github.com/FelipeWelter)
