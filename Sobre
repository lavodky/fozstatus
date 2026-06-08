sequenceDiagram
    participant U as Usuário
    participant B as Bot
    participant A as API OsClass

    U->>B: !init
    B->>U: Lista cidades (1-6)
    U->>B: 2 (Foz do Iguaçu)
    B->>U: Lista categorias (1-8)
    U->>B: 4 (Balada)
    B->>U: ✅ Cadastro concluído!
    B->>A: Busca anúncios
    A-->>B: Lista de anúncios
    B->>U: Envia notificação
    Note over U,B: A cada 30 minutos
