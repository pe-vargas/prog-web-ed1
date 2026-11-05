# Estudo Dirigido I — Website Estático com HTML e CSS

**Universidade Tuiuti do Paraná | 2026**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

## Sobre o trabalho

Projeto desenvolvido como atividade acadêmica da disciplina de **Programação Web**, do curso de Análise e Desenvolvimento de Sistemas da Universidade Tuiuti do Paraná (UTP).

O trabalho consiste em um website estático pessoal, de múltiplas páginas interligadas, desenvolvido exclusivamente com HTML e CSS, sem JavaScript, frameworks ou templates. O site adota uma estética de terminal cyberpunk, com fundo preto, fonte monoespaçada e destaques em rosa e ciano.

## Acesso online

O site está publicado com GitHub Pages:

**https://pe-vargas.github.io/prog-web-ed1/index.html**

## Objetivos

Aplicar, na prática, os conceitos estudados em aula sobre:

- Estruturação de páginas Web com HTML;
- Navegação entre páginas;
- Inserção de imagens, listas, tabelas e formulários;
- Estilização com CSS externo;
- Organização de arquivos e boas práticas de nomenclatura.

## Tecnologias utilizadas

- HTML5
- CSS3

## Páginas do site

| Página | Arquivo | Conteúdo |
|---|---|---|
| Home | `index.html` | Título, menu de navegação para as demais páginas e rodapé |
| Sobre mim | `sobre.html` | Gostos musicais, mangás e jogos favoritos, com galeria de quatro imagens legendadas |
| Trabalhos | `trabalhos.html` | Lista de estudos dirigidos, com acesso ao Estudo Dirigido 01 |
| Contato | `forms.html` | Formulário com campos de nome, e-mail, assunto e mensagem |
| Estudo Dirigido 01 | `ed01.html` | Página temática sobre o projeto Post Human, com player de áudio, textos, imagens, tabela cronológica de músicas e lista de fontes |

## Requisitos atendidos

| Requisito da atividade | Onde foi aplicado |
|---|---|
| Estrutura básica de um documento HTML | Todas as páginas |
| Títulos e parágrafos | Todas as páginas |
| Links de navegação entre páginas | Menu da home e botão de retorno em todas as páginas |
| Listas | Menu em `index.html` e lista de fontes em `ed01.html` |
| Inserção de imagens | `sobre.html` e `ed01.html` |
| Tabelas | Tabela cronológica de músicas em `ed01.html` |
| Formulários com diferentes tipos de campos | `forms.html`: texto, e-mail, seleção, área de texto e botão |
| Estruturação semântica | `header`, `nav`, `main`, `section`, `article`, `figure` e `footer` |
| CSS externo | Pasta `css/`, com um arquivo por página |

## Estrutura do projeto

```text
index.html
sobre.html
trabalhos.html
forms.html
ed01.html

css/
├── home.css
├── sobre.css
├── trabalhos.css
├── forms.css
└── nexgen.css

imagens/
audio/

documentacao/
├── enunciado.pdf
└── relatorio.pdf
```

Cada pasta possui seu próprio README: [css](css/README.md) · [imagens](imagens/README.md) · [audio](audio/README.md)

## Como executar

Não há necessidade de instalação. Basta baixar o repositório e abrir o arquivo `index.html` no navegador, ou acessar o link do GitHub Pages.

## Limitações

- O formulário de contato é apenas visual: não envia nem armazena os dados;
- O site não possui JavaScript, conforme exigido na atividade;
- O segundo estudo dirigido aparece como bloqueado na página de trabalhos, pois ainda não foi desenvolvido.

## Autor

- Pedro Dambiski de Vargas

## Informações acadêmicas

| Informação | Detalhes |
|---|---|
| Instituição | Universidade Tuiuti do Paraná (UTP) |
| Curso | Análise e Desenvolvimento de Sistemas |
| Disciplina | Programação Web |
| Professor | Luiz Adolpho Baroni |
| Período | Primeiro Semestre de 2026 |
| Tipo | Trabalho acadêmico individual |

---

**Observação:** Este repositório tem finalidade acadêmica e documental, reunindo os arquivos desenvolvidos para a atividade proposta na disciplina. Imagens e áudio pertencem aos respectivos autores e são utilizados apenas para fins educacionais.
