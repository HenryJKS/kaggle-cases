# Case: Projeção Semanal de Demanda
## Descrição do Problema:
Você recebeu uma base de dados contendo as unidades de produtos farmacêuticos vendidos semanalmente. Seu
objetivo é construir um modelo preditivo para prever a demanda dos produtos por distribuidor e região geográfica das
lojas responsáveis pelas vendas.
Os dados fornecidos para este case provavelmente caberão na memória do seu computador. Todavia, seria interessante
que você desenvolvesse a sua solução buscando eficiência em termos de memória e processamento.

## Forma de entrega:
Os artefatos do desenvolvimento da solução poderão ser entregue em arquivo compactado, ou compartilhados via link
para repositório de código (i.e. GitHub, GitLab, Bitbucket, AzureDevops, etc). No caso de compartilhamento de link para
repositório, garanta que o projeto esteja público para que consigamos acessar sua solução. Você pode desenvolver sua
solução em notebooks (.ipynb) ou scripts (.py).
A apresentação de resultados deverá ser entregue na forma de uma apresentação de slides salva no formato .ppt.

## Tarefas:
1. Preparação dos dados:
- Carrega e verificação da integridade dos dados.
- Tratamento de valores ausentes e limpeza dos dados, se necessário.
- Codificação de variáveis categóricas.
- Normalização ou padronização as variáveis numéricas, se necessário.
- Criação novas variáveis que possam ser úteis para o modelo.
  
2. Análise exploratória:
- Análise descritiva para entender as principais características dos dados.
- Criação visualizações para identificação padrões e tendências sazonais na demanda.
-  Descrição de quaisquer insights relevantes obtidos durante a análise.
  
3. Construção e avaliação do modelo:
- Seleção de variáveis.
- Validação cruzada.
- Escolha e justificativa da seleção de uma técnica de modelagem.
- Escolha e justifica da seleção da métrica de avaliação.

## Dicionário de variáveis:
- week_dt: data correspondente ao primeiro dia da semana.
- dsupp_id: código de identificação do distribuidor do produto.
- product_id: código de identificação do produto.
- region_nm: macrorregião do ibge cuja loja, na qual o produto foi vendido, está situada.
- units_qty: quantidade de unidades vendidas na semana.
- product_attr_1, product_attr_2 e product_attr_3: atributos específicos dos produtos.