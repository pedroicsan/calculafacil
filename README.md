# CalculaFácil

**Ferramentas gratuitas para facilitar sua vida.**

**Portal:** [CalculaFácil](https://pedroicsan.github.io/calculafacil/)  
**Relatório da Fase 2:** [Relatório final em português](Relatorio-final.md)  
**Fontes completas:** [Baixar o ZIP portátil](CalculaFacil-portal-fonte.zip)

O portal tem 18 calculadoras gratuitas em português brasileiro, 7 categorias e 31 rotas públicas pré-geradas. A Fase 2 preserva as 15 ferramentas originais e acrescenta calculadoras de quantidade de tinta, rolos de papel de parede e média ponderada.

As contas são feitas no navegador. Não há login, banco de dados, servidor de aplicação, API paga, serviço de IA, checkout ou dependência de domínio próprio. O conteúdo inclui instruções, fórmulas, exemplos, FAQs específicas e páginas informativas. Depois de uma primeira visita online, o service worker pode disponibilizar páginas no cache offline.

O workflow em `.github/workflows/pages.yml` executa as suítes de testes, constrói HTML/CSS/JavaScript estáticos e publica pelo GitHub Pages na branch `main`. Para compilar o ZIP localmente, extraia os arquivos, entre na pasta `calculafacil` e execute:

```sh
python3 scripts/build_site.py --site-origin https://pedroicsan.github.io --base-path /calculafacil
node --test tests/calculators.test.mjs
python3 -m unittest discover -s tests -p 'test_*.py' -v
```

O repositório é público, portanto o código-fonte também é visível. Não inclua credenciais ou dados privados. Analytics, AdSense e afiliados permanecem desativados até que o proprietário forneça configurações legítimas e conclua as etapas documentadas. Nenhum serviço pago ou domínio foi ativado.
