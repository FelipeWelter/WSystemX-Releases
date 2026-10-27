# WSystemX — releases oficiais

Este repositório público existe exclusivamente para distribuir releases oficiais do WSystemX. A fonte única de código e de compilação é o repositório privado [FelipeWelter/PC-Toolkit](https://github.com/FelipeWelter/PC-Toolkit).

## Política de distribuição

- O workflow `.github/workflows/wssystemx-release-sync.yml` no repositório privado constrói o pacote uma única vez a partir da tag privada validada.
- O release privado é conferido antes de copiar os mesmos bytes para um release público em rascunho. Não há build independente neste repositório.
- Cada release oficial contém o instalador, `WSystemX-<tag>.release.json`, `WSystemX-<tag>.release.sig` e `SHA256SUMS.txt`.
- A proveniência assinada registra versão, nome/tamanho/SHA-256 do pacote e o SHA exato do commit privado de origem.
- O nome da tag pública corresponde à tag privada. O commit privado não é copiado como objeto Git, para não expor código ou histórico privados; seu SHA é autenticado pela proveniência assinada.
- Uma release só deve ser publicada após conferência de versão, tag, proveniência e igualdade de checksums/ativos. O workflow de sincronização prepara rascunhos e não publica releases.

**Estado atual:** ainda não há releases ou binários publicados neste repositório.