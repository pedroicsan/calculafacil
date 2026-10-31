# Relatório final da Fase 2 — CalculaFácil

Em 30 de outubro de 2026, a versão validada do CalculaFácil reúne 18 calculadoras, 7 categorias e 31 rotas públicas pré-geradas. O portal permanece estático: as fórmulas são executadas no navegador, sem login, banco de dados, servidor de aplicação, API paga ou conta de IA. A publicação permanece em GitHub Pages, sem compra de domínio ou ativação de hospedagem paga.

## 1. Quantidade final de calculadoras

São 18 calculadoras: consumo de energia elétrica; custo de combustível para viagem; comparador de preço por kg, litro ou unidade; descontos e promoções; porcentagem; salário por hora; divisão de despesas; economia mensal; conversor de medidas; custo de eletrodomésticos; aumento e redução percentual; juros simples; custo de uma viagem; economia entre produtos; preço por quantidade; quantidade de tinta; rolos de papel de parede; e média ponderada.

As 31 rotas são a página inicial, as 18 ferramentas, as 7 páginas de categoria e 5 páginas institucionais: Sobre, Contato, Política de Privacidade, Termos de Uso e Anuncie no CalculaFácil. A página 404 não é contada como conteúdo indexável.

## 2. Melhorias de SEO implementadas

Cada calculadora ganhou título, meta description, palavra-chave principal e termos secundários próprios. O conteúdo inicial explica o problema atendido e os dados necessários. As páginas também apresentam fórmula e limites do cálculo, instruções, exemplo numérico, situações de uso, fontes e ligações para ferramentas relacionadas. As categorias recebem descrições próprias e caminhos legíveis; as páginas de ferramenta incluem navegação contextual e breadcrumbs.

As páginas são geradas como HTML completo antes da visita, em vez de depender de JavaScript para revelar o conteúdo principal. A geração inclui canonical e metadados sociais com a origem pública real, JSON-LD coerente com o conteúdo, sitemap e robots.txt. A auditoria de saída testa as 31 páginas, títulos e descriptions exclusivos, conteúdo, FAQs, rotas, links e arquivos locais. A estrutura segue o princípio de publicar conteúdo útil, original e correto, sem texto repetitivo criado apenas para mecanismos de busca [1].

A pesquisa de palavras-chave foi qualitativa: identifica intenção de busca e variações naturais a partir das páginas e referências examinadas, mas não atribui volumes numéricos não verificados. Os grupos e fontes registrados por calculadora estão em [`docs/fase-2/pesquisa-seo.json`](fase-2/pesquisa-seo.json).

## 3. Palavras-chave por categoria

- **Casa e energia:** principal — “calculadora de consumo de energia”; secundárias — “casa e energia”, “calculadora online” e “ferramentas gratuitas”.
- **Compras e preços:** principal — “comparador de preços por unidade”; secundárias — “compras e preços”, “calculadora online” e “ferramentas gratuitas”.
- **Finanças do dia a dia:** principal — “calculadoras financeiras do dia a dia”; secundárias — “finanças do dia a dia”, “calculadora online” e “ferramentas gratuitas”.
- **Viagens:** principal — “calculadora de viagem e combustível”; secundárias — “viagens”, “calculadora online” e “ferramentas gratuitas”.
- **Conversões:** principal — “conversor de medidas”; secundárias — “conversões”, “calculadora online” e “ferramentas gratuitas”.
- **Construção e reformas:** principal — “calculadora para construção e reformas”; secundárias — “calculadora de tinta por m²”, “calculadora de papel de parede” e “quantidade de material para reforma”.
- **Matemática cotidiana:** principal — “calculadora de média ponderada”; secundárias — “calcular média com pesos”, “média ponderada de notas” e “fórmula da média ponderada”.

## 4. Palavras-chave por calculadora

- **Consumo de energia elétrica:** principal — “calculadora de consumo de energia elétrica”; secundárias — “calcular consumo de energia em kWh”, “consumo mensal de aparelho elétrico”, “calcular gasto de energia por aparelho”, “custo de energia por kWh” e “consumo de aparelho em watts”.
- **Custo de combustível para viagem:** principal — “calculadora de combustível para viagem”; secundárias — “calcular gasto de combustível na viagem”, “custo de gasolina por km”, “litros de combustível por distância” e “consumo do veículo em km por litro”.
- **Comparador de preço por kg, litro ou unidade:** principal — “comparador de preço por kg, litro ou unidade”; secundárias — “comparar preço por quilo”, “preço por litro”, “preço por unidade”, “calculadora de preço unitário” e “comparar embalagens por preço por medida”.
- **Descontos e promoções:** principal — “calculadora de desconto”; secundárias — “calcular preço com desconto”, “preço final com desconto percentual”, “comparar desconto percentual e fixo”, “calcular economia em promoção” e “desconto em reais ou porcentagem”.
- **Calculadora de porcentagem:** principal — “calculadora de porcentagem”; secundárias — “quanto é X% de um valor”, “calcular porcentagem de um valor”, “porcentagem de uma quantia” e “como achar o percentual de um valor”.
- **Salário por hora:** principal — “calculadora de salário por hora”; secundárias — “quanto ganho por hora”, “valor da hora trabalhada”, “calcular salário mensal por hora” e “salário mensal dividido por horas trabalhadas”.
- **Divisão de despesas:** principal — “dividir despesas igualmente entre pessoas”; secundárias — “dividir conta entre amigos”, “quanto cada pessoa paga na conta”, “calculadora para rachar despesas” e “divisão igual de despesas em grupo”.
- **Economia mensal:** principal — “calculadora de economia mensal para meta”; secundárias — “quanto tempo para juntar dinheiro para uma meta”, “calcular meses para alcançar uma meta financeira”, “quanto guardar por mês para atingir uma meta” e “calculadora de prazo para economizar”.
- **Conversor de medidas:** principal — “conversor de medidas”; secundárias — “converter km em metros”, “converter kg em gramas”, “conversor de temperatura Celsius Fahrenheit” e “conversão de litros para mililitros”.
- **Custo de eletrodomésticos:** principal — “custo de eletrodomésticos”; secundárias — “custo mensal de um eletrodoméstico”, “consumo mensal em kWh por aparelho”, “gasto de energia de um aparelho” e “calcular custo de energia por mês”.
- **Aumento e redução percentual:** principal — “calculadora de aumento e redução percentual”; secundárias — “calcular aumento percentual”, “calcular redução percentual”, “novo valor com aumento percentual”, “valor após redução percentual” e “reajuste de preço percentual”.
- **Juros simples:** principal — “calculadora de juros simples”; secundárias — “fórmula de juros simples”, “calcular juros simples por período”, “juros simples com taxa mensal” e “montante de juros simples”.
- **Custo de uma viagem:** principal — “custo total de viagem”; secundárias — “calcular gastos de viagem de carro”, “calculadora de custo de viagem”, “orçamento de viagem de carro” e “gastos com combustível pedágio hospedagem e alimentação”.
- **Economia entre produtos:** principal — “comparar ofertas com frete”; secundárias — “comparar preço total de produtos”, “diferença de preço entre produtos”, “calcular economia entre ofertas” e “comparar preço e frete”.
- **Preço por quantidade:** principal — “preço por quantidade”; secundárias — “calcular preço proporcional”, “preço por grama”, “custo por quantidade desejada” e “calcular custo de ingrediente por gramas”.
- **Calculadora de quantidade de tinta:** principal — “calculadora de tinta por m²”; secundárias — “calcular quantidade de tinta para parede”, “quantos litros de tinta por metro quadrado” e “quantidade de tinta por demão”.
- **Calculadora de rolos de papel de parede:** principal — “calculadora de papel de parede”; secundárias — “quantos rolos de papel de parede preciso”, “calcular rolos de papel de parede por parede” e “quantidade de papel de parede por m²”.
- **Calculadora de média ponderada:** principal — “calculadora de média ponderada”; secundárias — “calcular média ponderada de notas”, “média ponderada com pesos” e “média ponderada passo a passo”.

## 5. Perguntas frequentes exclusivas

Foram implementadas 72 perguntas e respostas: quatro próprias para cada uma das 18 calculadoras. O teste automatizado verifica a presença do conteúdo e a ausência de perguntas duplicadas. As perguntas são visíveis nas páginas e a marcação estruturada corresponde às FAQs apresentadas.

Uma pergunta representativa por ferramenta:

- **Consumo de energia:** “Como informo o uso de um aparelho que funciona só alguns dias na semana?”
- **Combustível para viagem:** “Para calcular ida e volta, devo dobrar a distância ou usar dois trechos?”
- **Comparador de preço:** “Posso comparar uma embalagem em gramas com outra em quilogramas?”
- **Descontos:** “Como comparar 20% de desconto com R$ 20 fixos?”
- **Porcentagem:** “O que preciso informar para saber quanto é 12% de uma conta?”
- **Salário por hora:** “Preciso usar 220 horas no mês?”
- **Divisão de despesas:** “A calculadora mostra quem deve pagar a quem depois que alguém adianta a conta?”
- **Economia mensal:** “Por que o resultado mostra um mês a mais do que a divisão exata?”
- **Conversor:** “O conversor transforma centímetros quadrados ou metros quadrados?”
- **Custo de eletrodomésticos:** “Como uso o consumo mensal em kWh indicado para o aparelho?”
- **Aumento e redução:** “A calculadora encontra o percentual de aumento entre um preço antigo e um preço novo?”
- **Juros simples:** “Como informo uma taxa de 2% ao mês nesta calculadora?”
- **Custo de viagem:** “A distância deve incluir a volta ou informo apenas o trecho de ida?”
- **Economia entre produtos:** “Como comparar um produto mais barato com frete alto e outro mais caro com frete menor?”
- **Preço por quantidade:** “Como calculo o custo de 200 g quando só sei o preço do pacote de 1 kg?”
- **Tinta:** “Como descubro o rendimento por litro da tinta?”
- **Papel de parede:** “Como informar a repetição do padrão do papel?”
- **Média ponderada:** “Os pesos precisam somar 100%?”

As três respostas adicionais de cada página tratam de dúvidas específicas, como conversões aceitas, hipóteses da fórmula, limitações do resultado, unidades de entrada e interpretação de exemplos.

## 6. Novas ferramentas e justificativas

Foram adicionadas três ferramentas, cada uma com página, fórmula, explicação, exemplo, casos de uso, palavras-chave, fontes, FAQs e testes próprios:

- **Quantidade de tinta:** resolve a estimativa de litros e embalagens a partir da área informada, áreas a excluir, demãos, rendimento da tinta e tamanho da embalagem. É útil para planejamento de reforma e não inventa rendimento de fabricante.
- **Rolos de papel de parede:** estima faixas e rolos com base nas dimensões que a pessoa informa, incluindo repetição de padrão. A regra torna explícito o efeito do alinhamento do desenho no aproveitamento.
- **Média ponderada:** calcula média de valores com pesos e é útil para notas e outros cálculos cotidianos em que as contribuições são diferentes. Não exige uma API nem uma lista fixa de avaliações.

As três foram escolhidas por terem intenção e fórmulas distinguíveis das ferramentas existentes, entradas controláveis pelo visitante e implementação estática. Não foi alegado volume de busca numérico.

## 7. Velocidade e experiência mobile

O Lighthouse 12.8.2, em uma auditoria local de laboratório com configuração mobile, mediu **99 em desempenho** e **100 em acessibilidade** após a correção de contraste e nome acessível. A página inicial obteve FCP de 1,4 s, LCP de 1,6 s, TBT de 0 ms e CLS de 0. São métricas laboratoriais de uma execução no ambiente de teste; não são Core Web Vitals de campo nem representam a experiência de todos os visitantes. O relatório de Core Web Vitals do Google depende de dados reais suficientes e pode não existir para propriedades novas [5].

Playwright confirmou que a página inicial não tem rolagem horizontal nas larguras de 320, 390 e 1280 px. Também validou pesquisa, recálculo das três ferramentas novas, funcionamento do link de privacidade e aceitação/recusa do Analytics em uma rota aninhada. Depois de uma primeira visita online e instalação do service worker, a média ponderada foi aberta e recalculada sem rede. A primeira visita ainda precisa de conexão para baixar a página e instalar o cache offline.

## 8. Situação do Google AdSense

O AdSense está **desativado**. Não há ID de editor, slots reais, anúncios ativos ou aprovação presumida. A página inicial e as páginas de calculadoras têm espaços identificados como “Publicidade”; sem configuração válida, exibem apenas a mensagem de reserva. Há uma verificação de formato dos identificadores antes de gerar um slot e nenhuma requisição de anúncio é feita na configuração padrão.

A ativação depende de o proprietário criar e conectar uma conta, solicitar análise e receber aprovação, fornecer IDs legítimos e revisar a Política de Privacidade e as políticas aplicáveis. O Google não garante aprovação ou receita; não há anúncios exibidos antes da aprovação segundo as instruções do serviço [3] [4].

## 9. Estrutura de afiliados

A lista `affiliateLinks` está vazia. Nenhuma marca, produto, URL, preço, comissão ou parceria foi inventada. A estrutura aceita somente links HTTPS com rótulo e escopo real por ferramenta ou categoria; os links comerciais são apresentados com aviso e `rel="sponsored nofollow noopener noreferrer"`, em linha com a orientação de qualificação de links pagos do Google [6]. A configuração permanece dependente de adesão e autorização do proprietário em programas reais.

## 10. Página de patrocínios

A página [Anuncie no CalculaFácil](https://pedroicsan.github.io/calculafacil/anuncie-no-calculafacil/) descreve possibilidades de formatos publicitários e de parceria sem alegar audiência, número de visitantes, resultados ou alcance não comprovados. O site não tem formulário que armazene mensagens. O e-mail comercial continua sem configuração; só deve ser exibido depois que o proprietário informar um endereço verdadeiro.

## 11. Oportunidades de produtos digitais

O documento [`docs/oportunidades-produtos-digitais.md`](oportunidades-produtos-digitais.md) registra cinco hipóteses para validação futura: planilha de orçamento mensal da casa; controle de custo de energia por aparelho; planejador de orçamento de viagem; planilha de comparação de compras; e material educativo sobre matemática financeira cotidiana.

Nenhum desses produtos foi criado. Não existe checkout, pagamento, assinatura ou coleta de dados. O documento recomenda avaliar consultas reais do Search Console e necessidades observadas antes de produzir qualquer material; não há alegação de demanda, venda ou receita.

## 12. Sitemap e indexabilidade

A compilação de produção é configurada para o endereço real `https://pedroicsan.github.io/calculafacil/`, com caminho-base `/calculafacil`. O sitemap lista as URLs públicas canônicas geradas e o robots.txt anuncia o sitemap e permite o rastreamento público. As páginas têm conteúdo no HTML inicial, títulos e descriptions próprios, canonicals coerentes e JSON-LD testável. A página de erro não é incluída como conteúdo indexável, e uma rota inexistente deve responder com HTTP 404.

O sitemap auxilia a descoberta das URLs, mas não garante rastreamento nem inclusão na Pesquisa Google [2]. A propriedade de prefixo `https://pedroicsan.github.io/calculafacil/` foi criada e verificada no Search Console por arquivo HTML. O arquivo gerado pelo Google está na raiz pública do site. O painel informa “Não foi possível buscar o sitemap”. Em checagens independentes, a URL do sitemap respondeu HTTP 200 com `application/xml`, e o XML era válido, com 31 URLs, tanto para navegador quanto para user-agent Googlebot; `robots.txt` e os dois arquivos de verificação também responderam HTTP 200. A divergência com o painel permanece sem diagnóstico confirmado. Portanto, este relatório não afirma que o Google concluiu a leitura, rastreou ou indexou as páginas.

## 13. Testes e validações

Antes da publicação final, os seguintes testes passaram:

- **Node.js:** 6 grupos de teste, incluindo as 18 fórmulas, unidades, conversões, campos opcionais, decimais com vírgula, empates, limites e entradas inválidas.
- **Python:** 10 testes de geração, cobrindo as 18 calculadoras, 31 rotas, metadados únicos, FAQs, fontes, categorias, páginas institucionais, saída 404 não indexada, consentimento e configuração do GA4, privacidade de Ads/afiliados, links internos, arquivos de verificação, sitemap, robots, manifesto e cache offline.
- **Chromium/Playwright:** responsividade em 320/390/1280 px, busca, cálculos de tinta, papel de parede e média ponderada, página de patrocínio, recálculo offline após cache e fluxo de consentimento. A recusa persistente não carrega o tag; mudar para aceitar carrega uma única cópia simulada, sem enviar hits reais. O teste confirmou que o GA4 não recebe consulta/hash nem dados digitados nas calculadoras.
- **Lighthouse:** no build atualizado, a auditoria mobile local marcou 99 em desempenho e 100 em acessibilidade, práticas recomendadas e SEO; não restaram violações de acessibilidade reportadas.

A geração estática usa a biblioteca padrão do Python; a execução das calculadoras não usa pacotes npm. Os testes de saída repetem a geração em diretório temporário com uma origem de teste para validar os caminhos.

## 14. Pendências do proprietário

O Search Console já tem a propriedade de prefixo verificada por arquivo HTML. O sitemap foi enviado, mas o painel mostra “Não foi possível buscar o sitemap”, apesar das respostas HTTP 200 verificadas. O estado deve ser acompanhado após o recrawl; se continuar sem ser buscado, confira o diagnóstico no painel e reenvie o URL completo na propriedade correta. A presença do arquivo não garante indexação [2] [7].

A propriedade GA4 **CalculaFácil** e o fluxo Web **CalculaFácil — site público** foram criados; o ID de medição é `G-47YHEZD21Z`. O fluxo usa fuso de São Paulo e BRL, com métricas otimizadas desligadas. A tag foi configurada no site para carregar somente após consentimento afirmativo, e os parâmetros de consulta e fragmentos são removidos das URLs enviadas. O Google informou que os primeiros dados podem levar até 48 horas; nenhuma visita de teste foi enviada à propriedade [8] [9].

Para publicidade, o proprietário precisa fornecer um e-mail real se quiser exibi-lo; obter aprovação AdSense e IDs legítimos; confirmar os slots e avisos necessários; ou aderir a programas de afiliados e fornecer os URLs autorizados. O domínio próprio é opcional e exige compra e configuração de DNS; o endereço gratuito `github.io` não depende disso.

## 15. Endereço publicado

O endereço público configurado para o portal é [https://pedroicsan.github.io/calculafacil/](https://pedroicsan.github.io/calculafacil/), servido pelo repositório público [pedroicsan/calculafacil](https://github.com/pedroicsan/calculafacil). A atualização do GA4, o relatório e o README foram publicados no commit `e65b193` da branch `main`. O workflow `Publish CalculaFácil #6` concluiu com sucesso a compilação e o deploy.

## 16. Custos e garantias

Nenhum serviço pago foi ativado para implementar ou publicar esta versão. As ferramentas funcionam com HTML, CSS e JavaScript estáticos; o site não depende de servidores, banco de dados, APIs pagas, IA, assinaturas ou domínio comprado. O repositório é público e o Pages é a opção gratuita escolhida; o README e a documentação explicam a visibilidade do código-fonte.

As melhorias técnicas e editoriais foram implementadas para facilitar compreensão, uso e descoberta orgânica. Elas não garantem tráfego, posição no Google, indexação, aprovação de monetização ou faturamento. A ativação de serviços de terceiros depende do proprietário e das regras vigentes de cada provedor.

## Referências

[1]: https://developers.google.com/search/docs/fundamentals/creating-helpful-content "Google Search Central — conteúdo útil e people-first"
[2]: https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap "Google Search Central — criar e enviar sitemaps"
[3]: https://support.google.com/adsense/answer/7584263?hl=pt-BR "Google AdSense Help — conectar um site e solicitar análise"
[4]: https://support.google.com/adsense/answer/48182?hl=pt-BR "Google AdSense Help — políticas do programa"
[5]: https://developers.google.com/search/docs/appearance/core-web-vitals "Google Search Central — Core Web Vitals"
[6]: https://developers.google.com/search/docs/crawling-indexing/qualify-outbound-links "Google Search Central — qualificar links externos"
[7]: https://support.google.com/webmasters/answer/9008080?hl=pt-BR "Google Search Console — verificar a propriedade do site"
[8]: https://support.google.com/analytics/answer/9304153?hl=pt-br "Google Analytics Help — configurar coleta de dados"
[9]: https://support.google.com/analytics/answer/12270356?hl=pt-br "Google Analytics Help — localizar o ID de medição"
