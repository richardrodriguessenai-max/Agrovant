# AGROVANT

Projeto prático da unidade curricular **AGROVANT**, do curso Técnico em Desenvolvimento de Sistemas — SESI/SENAI Itapeva.

## Informações do projeto

| Informação | Dados |
|---|---|
| **Aluno** | Richard Antonio Polidoro Rodrigues |
| **Turma** | 2º Ano B |
| **Professores** | Rafael Ribas / João Paulo |
| **Data** | 17/08/2026 |

## Sobre o projeto

O AGROVANT é uma landing page de um drone agrícola fictício voltado para pulverização e monitoramento de lavouras. O objetivo da página é apresentar o produto e convencer o agricultor a agendar uma demonstração.

Neste projeto desenvolvi toda a estrutura da página utilizando HTML semântico e CSS, seguindo o layout criado no Figma. A parte mais difícil foi deixar a página responsiva e organizar os elementos para diferentes tamanhos de tela.

## Página publicada

**Vercel:** https://agrovant-nine.vercel.app/

**Repositório GitHub:** https://github.com/richardrodriguessenai-max/Agrovant.git

## Estrutura do projeto

```text
Agrovant/
├── index.html
├── README.md
├── css/
│   └── style.css
└── img/
```

## Seções concluídas

- [x] Menu (cabeçalho)
- [x] Hero Section
- [x] Especificações
- [x] Vídeo do produto
- [x] Cards de benefícios
- [x] Depoimentos
- [x] Formulário de contato

## Tecnologias utilizadas

- HTML semântico (`header`, `main`, `section`, `footer`)
- CSS com variáveis (`:root`)
- Flexbox para organização dos layouts.
- Grid para distribuição de elementos.
- Responsividade com media queries.
- Unidades relativas (`rem`, `%` e `vw`).

## Responsividade

A página foi construída com foco em funcionar bem em celulares e computadores.

| Tela | Comportamento |
|---|---|
| **Celular** | Os cards ficam empilhados, as imagens se ajustam à largura da tela e o layout fica em uma coluna. |
| **Desktop** | Os cards ficam lado a lado, o menu aparece completo e o conteúdo ocupa melhor o espaço da tela. |

**Media Query utilizada:** a partir de **768px**.

## Como executar o projeto

```bash
git clone https://github.com/richardrodriguessenai-max/Agrovant.git
cd Agrovant
```

Depois é só abrir o arquivo `index.html` no navegador.

## Créditos

- Protótipo do layout: material da disciplina.
- Imagens e vídeos: material fornecido pelos professores.
- Fontes: Roboto e Inter (Google Fonts).

---

**Projeto acadêmico, sem fins comerciais. O drone AGROVANT é um produto fictício.**