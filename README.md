# CalculaFácil



**Ferramentas gratuitas para facilitar sua vida.**



Portal estático em português com 15 calculadoras gratuitas. As contas são executadas no navegador; não exigem login, banco de dados, servidor ou APIs pagas. Depois do primeiro carregamento, as páginas e ferramentas ficam disponíveis offline quando o navegador mantém o cache local.



O GitHub Actions extrai o pacote-fonte, executa os testes e publica o site no GitHub Pages. O pacote completo, com fontes, testes e instruções, está em [`CalculaFacil-portal-fonte.zip`](./CalculaFacil-portal-fonte.zip).



Para compilar localmente: extraia o ZIP, entre na pasta `calculafacil` e execute `python3 scripts/build_site.py`. O gerador usa apenas a biblioteca padrão do Python.
