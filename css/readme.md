# Pasta `css/`

**Estudo Dirigido I | Universidade Tuiuti do Paraná | 2026**

## Sobre a pasta

Reúne as folhas de estilo externas do site, uma para cada página.

## Conteúdo

| Arquivo | Utilizado em | Função |
|---|---|---|
| `home.css` | `index.html` | Estilos da página inicial e do menu de navegação |
| `sobre.css` | `sobre.html` | Estilos da página sobre o autor |
| `trabalhos.css` | `trabalhos.html` | Estilos da página de trabalhos |
| `forms.css` | `forms.html` | Estilos da página de contato e do formulário |
| `nexgen.css` | `ed01.html` | Estilos da página temática |

## Funcionamento

Cada página HTML carrega apenas a sua própria folha de estilo, por meio do elemento `<link>`:

```html
<link rel="stylesheet" href="css/home.css">
```

---

**Observação:** Todo o CSS foi escrito manualmente, sem uso de frameworks ou templates, conforme exigido na atividade.
