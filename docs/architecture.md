# Especificação Técnica - TripKey Hotels

## Arquitetura
Aplicação web client-side criada com HTML5, CSS/Materialize CSS e JavaScript (jQuery). O armazenamento de dados utiliza **JSON Server** (API fake) e **localStorage**.

---

## Modelo de Dados (DER)

```mermaid
erDiagram
    USUARIO ||--o{ FAVORITO : possui
    HOTEL ||--o{ FAVORITO : pertence_a

    USUARIO {
        string id PK
        string nome
        string email
        string senha
        string cep
    }

    HOTEL {
        string id PK
        string nome
        number preco_diaria
        number avaliacao
        string cidade
    }

    FAVORITO {
        string id PK
        string usuario_id FK
        string hotel_id FK
    }
