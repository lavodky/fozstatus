![Logo do Projeto](https://github.com/lavodky/fozstatus/blob/main/fluxograma.svg)



### Fluxo principal:

```mermaid
graph LR
    A[Usuário tira foto] --> B[Envia pelo Web App]
    B --> C[Conta homens/mulheres]
    C --> D[Sincroniza com OsClass]
    D --> E[Atualiza anúncio]
    E --> F[Notifica usuários via WhatsApp]
