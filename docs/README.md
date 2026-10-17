# Guia PL-300 no tablet

`index.html` é o guia completo, com navegação, respostas expansíveis e marcações de revisão salvas no navegador. `guia_revisao_pl300.pdf` é a versão para download.

A edição didática de 16/10/2026 tem 42 páginas e usa situações de trabalho, tabelas comparativas e pistas de raciocínio para quem já usa Power BI. O roteiro de 3 horas seleciona as leituras principais; o restante serve de consulta.

Para atualizar estes arquivos após regenerar o guia e o PDF, execute na raiz do projeto local do extrator (os scripts não fazem parte deste repositório de publicação):

```powershell
.venv\Scripts\python scripts\preparar_github_pages.py
```

O GitHub Pages deve usar a branch `main`, pasta `/docs`. Apenas o material de estudo desta pasta precisa ser publicado; os dados locais e sessões de login não fazem parte do site.
