# Análise VeritasSec - Nilton 2

Site estático pronto para GitHub Pages.

## Conteúdo

- `index.html`: relatório principal.
- `analises-veritassec.html`: painel separado para as análises de `VeritasSec-Aanalises`, com divisão entre contextual e analítico.
- `*.png`: gráficos usados pelo relatório.
- `dados/*.csv`: tabelas derivadas usadas na análise.
- `dados/tabela_custos_modelos_llm.csv`: estimativa comparativa de custos por modelo com base nos tokens estimados.
- `dados_veritassec/analises-resumo.json`: resumo estruturado usado pelo novo painel.
- `.nojekyll`: evita processamento Jekyll no GitHub Pages.

## Publicação no GitHub Pages

1. Crie um repositório vazio no GitHub.
2. Adicione o remoto neste diretório:

```bash
git remote add origin git@github.com:SEU_USUARIO/SEU_REPOSITORIO.git
```

3. Envie a branch principal:

```bash
git push -u origin main
```

4. No GitHub, habilite Pages em `Settings > Pages > Deploy from a branch`, branch `main`, pasta `/root`.
