# Pasta `css/`

**Estudo Dirigido I | Universidade Tuiuti do Paraná | 2026**

## Sobre a pasta

Reúne as folhas de estilo externas do site, uma para cada página.

## Conteúdo

| Arquivo | Utilizado em | Função |
|---|---|---|
| `home.css` | `index.html` | Centraliza o conteúdo na tela, estiliza o título com sombra rosa e o menu de navegação em ciano |
| `sobre.css` | `sobre.html` | Título em destaque, bloco de texto com borda lateral rosa e galeria de imagens lado a lado |
| `trabalhos.css` | `trabalhos.html` | Lista de trabalhos centralizada, com item ativo, item bloqueado e descrição |
| `forms.css` | `forms.html` | Formulário centralizado, campos escuros com borda rosa e botão de envio |
| `nexgen.css` | `ed01.html` | Estilo de terminal da página temática: cabeçalho, título com efeito glitch, tabela, blocos de imagem, lista de fontes e rodapé |

## Identidade visual

Todas as páginas compartilham a mesma base:

- Fundo preto;
- Fonte monoespaçada;
- Destaques em rosa (`#ff007f`) e ciano (`#00ffff`).

## Funcionamento

Cada página HTML carrega apenas a sua própria folha de estilo, por meio do elemento `<link>`:

```html
<link rel="stylesheet" href="css/home.css">
```

---

**Observação:** Todo o CSS foi escrito manualmente, sem uso de frameworks ou templates, conforme exigido na atividade.
