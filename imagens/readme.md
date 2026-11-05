# Pasta `imagens/`

**Estudo Dirigido I | Universidade Tuiuti do Paraná | 2026**

## Sobre a pasta

Reúne as imagens utilizadas nas páginas do site.

## Conteúdo

| Arquivo(s) | Utilizado em | Descrição |
|---|---|---|
| `img1.jpg`, `img2.png`, `img3.jpg`, `img4.png` | `sobre.html` | Imagens da página sobre o autor |
| `img5.png`, `img6.png`, `img7.jpg` | `ed01.html` | Imagens das seções da página temática |
| `amo.png`, `PHSH.jpg`, `PHNG.png` | `ed01.html` | Capas de álbuns exibidas na página temática |

## Funcionamento

As imagens são inseridas com o elemento `<img>`, usando o caminho relativo à raiz do site:

```html
<img src="imagens/img1.jpg" alt="Descrição da imagem">
```

---

**Observação:** As imagens pertencem aos respectivos autores e são utilizadas apenas para fins educacionais. Os nomes dos arquivos devem ser idênticos aos usados no HTML, incluindo maiúsculas e minúsculas, pois servidores Linux (como o do GitHub Pages) diferenciam `PHSH.jpg` de `phsh.jpg`. O arquivo `Thumbs.db`, gerado pelo Windows, deve ser removido antes do envio ao repositório.
