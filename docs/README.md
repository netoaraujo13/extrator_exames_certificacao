# Guia PL-300 no tablet

`index.html` é o guia completo, com navegação, respostas expansíveis e marcações de revisão salvas no navegador. `guia_revisao_pl300.pdf` é a versão para download.

Para atualizar estes arquivos após regenerar o guia e o PDF, execute na raiz do projeto:

```powershell
.venv\Scripts\python scripts\preparar_github_pages.py
```

O GitHub Pages deve usar a branch `main`, pasta `/docs`. Apenas o material de estudo desta pasta precisa ser publicado; os dados locais e sessões de login não fazem parte do site.
