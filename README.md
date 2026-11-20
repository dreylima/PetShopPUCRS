# PetAmigo Petshop - Arquivo de Ajuda

## Descrição do Projeto

O **PetAmigo Petshop** é um sistema web de front-end desenvolvido para a Fase 1 do Projeto da Disciplina de Desenvolvimento Web da PUCRS. O site apresenta as informações de um petshop fictício, com catálogo de produtos e serviços.

---

## Estrutura do Site

O site é composto pelas seguintes páginas:

| Página | Arquivo | Descrição |
|--------|---------|-----------|
| Início | `index.html` | Página inicial com apresentação do petshop |
| Rações | `racoes.html` | Catálogo de rações para cães e gatos |
| Brinquedos | `brinquedos.html` | Catálogo de brinquedos para pets |
| Higiene | `higiene.html` | Catálogo de produtos de higiene |
| Serviços | `servicos.html` | Tabela de serviços e valores |
| Contato | `contato.html` | Formulário de contato e informações |

---

## Funcionalidades

### Navegação
- **Menu de navegação** no cabeçalho (header) presente em todas as páginas
- **Links de navegação** no rodapé (footer) em todas as páginas
- **Link de retorno** para a página inicial em cada página interna

### Produtos (3 Categorias)

#### Rações (`racoes.html`)
- **Ração PetAmigo Premium Dog** - Ração para cães adultos, 15kg - R$ 189,90
- **Ração PetAmigo Premium Cat** - Ração para gatos adultos, 10kg - R$ 159,90
- Cada produto possui: foto, nome, descrição completa, especificações e valor

#### Brinquedos (`brinquedos.html`)
- **Osso de Borracha Resistente** - Brinquedo para cães - R$ 34,90
- **Vara com Penas para Gatos** - Brinquedo interativo - R$ 22,50
- Cada produto possui: foto, nome, descrição completa, especificações e valor

#### Higiene (`higiene.html`)
- **Shampoo PetAmigo Pelo Brilhante** - 500ml - R$ 28,90
- **Escova Removedora de Pelos PetAmigo** - Profissional - R$ 45,00
- Cada produto possui: foto, nome, descrição completa, especificações e valor

### Serviços (`servicos.html`)
Tabela completa com os seguintes campos:
- **Serviço**: nome do serviço
- **Descrição**: detalhamento do que é oferecido
- **Valor**: preço do serviço
- **Tele-busca**: indica se o serviço possui opção de coleta e entrega do pet em domicílio

Serviços disponíveis:
- Banho (porte pequeno, médio e grande)
- Banho para Gatos
- Tosa Higiênica e Completa
- Consulta Veterinária
- Vacinação
- Hotel para Pets
- Adestramento

### Formulário de Contato (`contato.html`)
- Campos: Nome, E-mail, Telefone, Assunto (seleção) e Mensagem
- Horário de funcionamento do petshop
- Informações completas de contato (endereço, telefone, WhatsApp, e-mail)

---

## Estrutura de Arquivos

```
petshop-web/
├── index.html          # Página inicial
├── racoes.html         # Página de rações
├── brinquedos.html     # Página de brinquedos
├── higiene.html        # Página de higiene
├── servicos.html       # Página de serviços
├── contato.html        # Página de contato
├── README.md           # Este arquivo de ajuda
└── imagens/
    ├── racao_cao.jpg       # Foto da ração para cães
    ├── racao_gato.jpg      # Foto da ração para gatos
    ├── brinquedo_osso.jpg  # Foto do osso de borracha
    ├── brinquedo_pena.jpg  # Foto da vara com penas
    ├── shampoo_cao.jpg     # Foto do shampoo
    └── escova_pet.jpg      # Foto da escova
```

---

## Tecnologias Utilizadas

- **HTML5** semântico puro
- Sem uso de CSS externo, Bootstrap ou JavaScript
- Elementos semânticos utilizados: `header`, `nav`, `main`, `section`, `article`, `footer`, `figure`, `figcaption`, `address`, `table`

---

## Requisitos Atendidos

- [x] Cabeçalho com nome do petshop, contato e navegação
- [x] 3 categorias de produtos (Rações, Brinquedos, Higiene)
- [x] 2 produtos por categoria com foto, descrição e valor
- [x] Página de serviços com descrição, valor e indicação de tele-busca
- [x] Rodapé com informações legais, contato e navegação
- [x] HTML semântico sem CSS customizado ou Bootstrap
- [x] Sem JavaScript (Fase 2)

---

## Informações do Projeto

- **Disciplina**: Desenvolvimento Web
- **Instituição**: PUCRS - Pontifícia Universidade Católica do Rio Grande do Sul
- **Fase**: 1 - Estrutura HTML básica
- **Petshop**: PetAmigo (fictício)

---

## Como Visualizar

1. Clone o repositório ou faça o download dos arquivos
2. Abra o arquivo `index.html` em qualquer navegador web moderno
3. Navegue pelo site usando os links do menu de navegação

Ou acesse diretamente pelo **GitHub Pages**: [link será disponibilizado após publicação]
