# WSystemX — releases oficiais

Este repositório público existe exclusivamente para distribuir releases oficiais do WSystemX. A fonte única de código e de compilação é o repositório privado [FelipeWelter/PC-Toolkit](https://github.com/FelipeWelter/PC-Toolkit).

## Política de distribuição

- Este repositório não contém código-fonte nem workflows de build, e o GitHub Actions está desativado para impedir compilações independentes.
- Quando habilitado após a configuração de credenciais e chaves, o workflow executado no repositório privado compila uma vez a partir de uma tag validada e prepara drafts em ambos os repositórios.
- O pacote, a tag e a proveniência são conferidos no repositório privado antes da cópia. Os bytes no draft público devem corresponder exatamente aos do build privado e ao draft privado.
- Cada release oficial contém o instalador, `WSystemX-<tag>.release.json`, `WSystemX-<tag>.release.sig` e `SHA256SUMS.txt`.
- A proveniência assinada registra versão, nome/tamanho/SHA-256 do pacote e o SHA exato do commit privado de origem.
- O nome da tag pública corresponde à tag privada. O commit privado não é copiado como objeto Git, para não expor código ou histórico privados; seu SHA é autenticado pela proveniência assinada.
- O workflow privado prepara rascunhos e não publica releases. Publicação exige conferência e autorização separadas.

**Estado atual:** nenhum release, tag de distribuição ou binário foi publicado neste repositório.