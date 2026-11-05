# Pasta `audio/`

**Estudo Dirigido I | Universidade Tuiuti do Paraná | 2026**

## Sobre a pasta

Reúne o arquivo de áudio utilizado pelo player da página temática do site.

## Conteúdo

| Arquivo | Utilizado em | Descrição |
|---|---|---|
| `[ost] (spi)ritual.mp3` | `ed01.html` | Faixa executada pelo elemento `<audio>` da página temática |

## Funcionamento

O áudio é inserido na página com o elemento `<audio>` do HTML5, sem uso de JavaScript:

```html
<audio controls>
    <source src="audio\[ost] (spi)ritual.mp3" type="audio/mpeg">
</audio>
```

---

**Observação:** O áudio pertence ao respectivo autor e é utilizado apenas para fins educacionais. O nome do arquivo contém espaços, colchetes e parênteses; caso o player não funcione após a publicação online, recomenda-se renomear o arquivo para um nome simples (por exemplo, `ritual.mp3`) e ajustar o caminho no HTML.
