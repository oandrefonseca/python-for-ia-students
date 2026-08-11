# Material: Python para IA

Este repositório contém o material do curso "Python para IA" em formato Quarto. O site gerado fica em `_book/` (já incluído no repositório de exemplo).

Como gerar localmente:

- Instale o Quarto: https://quarto.org
- No diretório do repositório, execute:

```
quarto render
```

Publicação automática (GitHub Pages):

Incluí um workflow do GitHub Actions que gera o site com `quarto render` e publica o conteúdo de `_book/` no branch `gh-pages`.

Se quiser testar localmente, gere o site e abra `_book/index.html` no navegador.

---
Pequena nota: o workflow usa o token padrão do GitHub (`GITHUB_TOKEN`) para publicar. Ajuste a branch de origem ou permissões se necessário.
