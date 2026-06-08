![Logo do Projeto](https://github.com/lavodky/fozstatus/blob/main/fluxograma.svg)



### Fluxo principal:

```mermaid
graph LR
    A[Conteúdo do lugar como videos, fotos ...] --> B[Sistema processa]
    B --> C[Conta homens/mulheres e descreve como está o lugar e outros atributos]
    C --> D[Sincroniza]
    D --> E[Atualiza anúncio]
    E --> F[Notifica usuários via WhatsApp]
