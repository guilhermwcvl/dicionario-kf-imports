# Dicionário de Dados - KF Imports

Dicionário de dados interativo do banco de dados **Sistema de Gestão Operacional, Vendas e Assistência Técnica**, desenvolvido para a KF Imports, microempresa de varejo de acessórios de telefonia e assistência técnica de smartphones em São Paulo/SP.

**Site publicado:** https://guilhermwcvl.github.io/dicionario-kf-imports/

## Sobre o projeto

Projeto da disciplina de Modelagem de Banco de Dados (UNICID, Ciência da Computação), com orientação do Prof. Dr. Diego Marques de Carvalho. O dicionário documenta as 22 tabelas e 164 colunas do banco, com foco em governança de dados (DAMA-DMBOK e COBIT).

Para cada coluna, o dicionário apresenta:

- descrição e regra de negócio;
- tipo e tamanho, conforme o script DDL;
- constraints (PK, FK, UNIQUE, CHECK, NULL);
- classificação de privacidade LGPD (DPS, DP ou N/A);
- linhagem do dado (origem e destino);
- controle de acesso (RBAC).

## Recursos

- Busca em tempo real por tabela ou coluna.
- Alternância entre modo claro e modo escuro.
- Visualizador do DER em modal, com zoom por scroll, arraste (pan) e botões de Zoom +, Zoom - e Reset.
- Download da Especificação de Requisitos e Regras de Negócio em PDF.
- Menu lateral responsivo, adaptado a celulares.

## Tecnologias

- MySQL 8.4 LTS (InnoDB, utf8mb4, utf8mb4_0900_ai_ci)
- HTML, CSS e JavaScript
- Panzoom.js 4.5.1 (via CDN jsDelivr)
- GitHub Pages

## Estrutura de pastas

```text
.
├── index.html
├── style.css
├── script.js
├── docs/
│   └── Especificacao_Requisitos_Regras_Negocio_BD.pdf
└── assets/
    └── der.png
```

## Equipe

| Papel | Nome |
|---|---|
| Data Owner (regras de negócio) | Kaique Vieira (KF Imports) |
| Data Steward | Guilherme Lima Araujo (RGM 47058773) |
| Data Steward | Diogo Cora (RGM 47071974) |
| Data Steward | Júlio César Rocha (RGM 47422432) |
| Data Steward | Giovanni Henrique Tartaro (RGM 47048026) |
| Data Steward | Arthur Henrique Alves (RGM 47332361) |
| Data Steward | Vitor Arruda dos Santos (RGM 47351241) |

Grupo 2D1 - Ciência da Computação. O artefato pertence a todos os integrantes do grupo.
