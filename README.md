
## Estrutura que organiza onde está cada lugar
### Cidades

* Salvador:
* Curitiba:
* Rio de Janeiro:
* Foz do iguaçu:
  * CATEGORIAS:
      * Baladas e bares
        * looby, authentic, europa centro ...
          * Status em tempo real(qtd de homens/mulheres e atributos gerais) do local incluindo descrição daquele momento e video do lugar
      * Bairros:
        * Vila A, Centro, Porto Belo ...
          * Status em tempo real(qtd de homens/mulheres e atributos gerais) do local incluindo descrição daquele momento e video do lugar
      * Instituições educacionais 
        * UDC(centro), unioeste campus 1, Fafig, Unifoz, Uniamerica
          * Status em tempo real(qtd de homens/mulheres e atributos gerais) do local incluindo descrição daquele momento e video do lugar







![imagem1](https://github.com/lavodky/fozstatus/blob/main/Fluxograma_.svg)



### Fluxo principal:

```mermaid
graph LR
    A[Conteúdo do lugar como videos, fotos ...] --> B[Sistema processa]
    B --> C[Conta homens/mulheres e descreve como está o lugar e outros atributos]
    C --> D[Sincroniza]
    D --> E[Atualiza anúncio]
    E --> F[Notifica usuários via WhatsApp]


