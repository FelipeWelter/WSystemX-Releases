# WSystemX — releases oficiais

Este repositório público existe exclusivamente para distribuir releases do WSystemX. A fonte única de código e de compilação é o repositório privado FelipeWelter/PC-Toolkit. Código-fonte, histórico Git e credenciais privados não fazem parte desta distribuição.

## Downloads e estado atual

A distribuição pública disponível é a [v0.2.8 RC2](https://github.com/FelipeWelter/WSystemX-Releases/releases/tag/v0.2.8-rc.2), classificada como pré-lançamento. Consulte suas notas antes de instalar.

A v0.2.8 está marcada como estável no repositório privado, mas sua publicação estável neste repositório permanece pendente de alinhamento da versão do produto, validação do novo pacote e atendimento à política de proveniência assinada. Não existe release pública estável v0.2.8 nesta revisão de 09/11/2026.

## Instalação e limitações conhecidas

- Compatibilidade declarada: Windows 10 e Windows 11 x64. A disponibilidade de sensores e informações de dispositivos depende do hardware e dos drivers.
- O instalador disponível não possui assinatura Authenticode. O Windows poderá apresentar avisos de editor desconhecido ou do SmartScreen. Não desative as proteções do Windows.
- A distribuição manual sem Authenticode é uma limitação aceita pelo proprietário. Isso não comprova autenticidade criptográfica nem certificação de segurança.
- A versão portátil não está disponível devido a uma pendência de segurança na execução elevada a partir de diretório gravável.
- A instalação automática de atualizações permanece desabilitada. Consultas de novas versões continuam habilitadas por padrão e não instalam atualizações automaticamente.
- Preserve uma cópia das configurações e do histórico antes de atualizar. Migração de instalações legadas por usuário exige procedimento assistido e permanece sem homologação completa com pacote legado real.

## Política de distribuição

- Este repositório não contém código-fonte nem workflows de compilação.
- Compilações e verificações devem ocorrer exclusivamente no repositório privado, a partir da origem aprovada.
- O conjunto exigido para novas releases oficiais é: instalador WSystemX para Windows x64, `WSystemX-<tag>.release.json`, `WSystemX-<tag>.release.sig` e `SHA256SUMS.txt`.
- A proveniência assinada deve vincular versão, nome, tamanho e SHA-256 do pacote ao commit privado de origem. A exigência permanece vigente.
- O nome da tag pública deve corresponder à tag privada. Nenhum objeto Git privado deve ser copiado para este repositório.
- O workflow de sincronização prepara rascunhos; a publicação depende das validações e da autorização aplicável.
- Hashes SHA-256 conferem integridade dos bytes. Publicados no mesmo canal do instalador, não comprovam sozinhos a identidade do desenvolvedor.
- O pipeline definitivo de assinatura permanece bloqueado. A aceitação da ausência de Authenticode não dispensa a proveniência assinada nem autoriza contornar verificações.

## Distribuição histórica

A RC2 existente contém o instalador, `SHA256SUMS.txt` e `PROVENANCE.txt`. Esse arquivo de texto não substitui os arquivos de proveniência criptograficamente assinada exigidos pela política para novas releases.

O instalador RC2 existente possui o SHA-256 registrado nos metadados do GitHub:

```text
8722205816f7823190b3b49b1e87e3bbca04d0da08ac907a1375cd7284442706
```

As notas históricas e os arquivos existentes foram preservados. Nenhuma nova release é anunciada por esta atualização do README.

Desenvolvedor: Felipe Welter.
