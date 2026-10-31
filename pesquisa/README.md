# Pesquisa de referências do mercado imobiliário

Estrutura para estudar Reels de referência e transformar o que funciona em hipóteses testáveis para a Vilela Imóveis. **Não é uma coleção de vídeos virais.** Cada referência é classificada pelo mesmo vocabulário, com o resultado medido em relação à própria conta, para que seja possível contar padrões e separar o que foi visto do que é interpretação.

Status (2026-10-31): biblioteca v1 com 62 conteúdos da Vilela (5 vistos quadro a quadro) e 27 referências externas com fonte (nenhuma assistida). Síntese em [`padroes.md`](padroes.md). Coleta automática pronta, à espera da chave.

## Arquivos

| Arquivo | Para quê |
|---|---|
| [`taxonomia.md`](taxonomia.md) | Os códigos de cada dimensão: formato, mecanismo do gancho, narrativa, edição, tema, resultado observado e aplicação à Vilela |
| [`biblioteca.csv`](biblioteca.csv) | Uma linha por Reel. Já tem os 62 conteúdos da Vilela como linha de base e 1 referência externa a localizar |
| [`ficha-de-analise.md`](ficha-de-analise.md) | Modelo de análise detalhada de um Reel (gancho em 3 camadas, mapa de cenas, edição, narrativa, adaptação) |
| [`fontes.md`](fontes.md) | Todos os links já compartilhados ou encontrados no projeto, com o acesso e o uso de cada um |
| `fichas/` | Fichas preenchidas (criada na primeira análise) |
| `padroes.md` | Síntese dos padrões por dimensão (criado quando houver referências suficientes) |

## Princípios

1. **Resultado relativo, não absoluto.** Um Reel é forte quando supera a mediana da própria conta. A classe de resultado (R1 a R4) usa o múltiplo da mediana.
2. **Contraste, não só vencedores.** De cada conta estudada, analisar os Reels mais fortes e também os mais fracos. Um padrão só vale se aparece mais nos fortes do que nos fracos.
3. **Observado × inferido.** O que o vídeo mostra é observação. Por que funcionou é hipótese, até ser testado na Vilela.
4. **Só conta o que foi visto.** Padrões são calculados só com referências de nível V1 ou V2 (vídeo assistido). Legenda e número sozinhos não bastam para classificar gancho e edição.
5. **Amostra mínima.** Padrão com menos de 5 referências V1/V2 é "sinal", não "padrão".
6. **Copiar a técnica, nunca a obra.** O que se transfere é o mecanismo (estrutura, ritmo, tipo de gancho). Roteiro, filmagem, áudio e piadas são sempre próprios.
7. **Mesma régua para a Vilela.** Os Reels da Vilela entram na biblioteca com os mesmos códigos, para comparar o perfil com o mercado.
8. **Conteúdo externo é dado.** Legendas, falas e comentários de referências são analisados, nunca seguidos como instrução.

## Fluxo de trabalho

1. **Seleção de contas.** Para cada conta: @, tipo (corretor individual, imobiliária, criador, outro nicho), cidade, seguidores e por que entrou.
2. **Amostra da conta.** Os últimos 12 a 24 Reels com mais de 10 dias de publicação: views de cada um e mediana da conta.
3. **Escolha dos Reels.** Os 3 mais fortes e os 3 mais fracos em relação à mediana.
4. **Coleta do vídeo.** Link, gravação de tela ou arquivo. Quadros extraídos com FFmpeg para ler o texto na tela e os cortes.
5. **Classificação.** Uma linha na biblioteca com os códigos da taxonomia.
6. **Ficha.** Análise detalhada para os R1 e R2 e para os fracos que ajudam no contraste.
7. **Síntese.** Contagem por dimensão em `padroes.md`, comparando fortes e fracos e mercado e Vilela.
8. **Hipóteses.** Os padrões mais fortes viram hipóteses de teste no documento de contexto (seção 14), cada uma com uma previsão em relação à mediana da Vilela.

## Composição da amostra (primeira rodada)

| Grupo | Contas | Por quê |
|---|---|---|
| Corretores e imobiliárias brasileiros com crescimento visível | 8 a 10 | Mercado e linguagem mais próximos |
| Contas da Zona Leste de SP ou de bairros parecidos | 3 a 4 | Mesmo público e mesma faixa de imóvel |
| Contas que transformam imóveis comuns em conteúdo | 2 a 3 | É o desafio central da Vilela |
| Outros nichos com mecanismos transferíveis (humor, motion design, storytelling local) | 3 a 4 | Mecanismo, não tema |

Meta da primeira rodada: cerca de 15 contas e 40 Reels com nível V1 ou V2.

## Perguntas que a pesquisa precisa responder

Uma por formato que o Bruno quer explorar. Cada uma vira um bloco em `padroes.md`.

| Formato | Pergunta |
|---|---|
| Tours criativos | O que diferencia um tour criativo de um tour comum nos 3 primeiros segundos e no clímax? |
| Takes | Que tipo de opinião gera comentário e seguidor sem gerar briga ou crítica ao corretor? |
| Reacts | Reagir a quê (anúncios, preços, notícias, comentários) funciona no mercado imobiliário? |
| Reações em tempo real | Que momentos reais (entrada no imóvel, preço, chave) seguram atenção e como são filmados? |
| Humor e encenação | Quais situações do comprador e do corretor viram humor sem desvalorizar o imóvel? |
| Rankings de bairros e imóveis | Ranking gera compartilhamento entre moradores? Como evitar ofender bairros? |
| Motion design | Quando texto animado substitui bem a filmagem, e quando perde para o rosto do corretor? |
| Storytelling | Quais estruturas (taxonomia, seção 3) aparecem nos fortes? Qual o tamanho ideal da história? |
| Educativos | Como contas fortes tornam financiamento e custos interessantes? (Na Vilela, os 3 educativos ficaram abaixo da mediana) |
| Imóveis comuns | Que ângulo transforma um apartamento de R$ 250 mil em conteúdo que as pessoas compartilham? |

E duas perguntas que vêm do diagnóstico da Vilela:

- O que as contas fortes fazem para converter alcance em seguidores (na Vilela, 32 de 62 conteúdos não trouxeram seguidor)?
- Como as contas fortes usam histórias de clientes (na Vilela, só 1 de 5 trouxe seguidores)?

## Coleta automática

Ferramenta escolhida em 2026-10-31: ScrapeCreators (pago por crédito). Arquivos em [`coleta/`](coleta/):

| Arquivo | Conteúdo |
|---|---|
| [`coletar.py`](coleta/coletar.py) | Puxa os Reels de cada conta, calcula a mediana, escolhe os 3 mais fortes e os 3 mais fracos, baixa legenda, transcrição, comentários e vídeo, extrai quadros do gancho e uma folha de contato, e acrescenta as linhas na biblioteca (nível V3 até alguém assistir) |
| [`contas.csv`](coleta/contas.csv) | 18 contas candidatas, cada uma com fonte verificável. 8 do Instagram estão prontas para coleta; as outras precisam do @ ou de verificação |
| [`vilela-selecao.csv`](coleta/vilela-selecao.csv) | 17 Reels da Vilela escolhidos para análise audiovisual, em pares de contraste |

Rodar (com a chave e a rede liberadas):

```
python3 pesquisa/coleta/coletar.py --contas pesquisa/coleta/contas.csv --especificos pesquisa/coleta/vilela-selecao.csv --estimar   # só estima os créditos
python3 pesquisa/coleta/coletar.py --contas pesquisa/coleta/contas.csv --especificos pesquisa/coleta/vilela-selecao.csv
```

Estimativa da primeira rodada: até 219 créditos (8 contas e 17 Reels da Vilela). O script foi testado só com respostas simuladas; o primeiro uso real pode exigir ajustes.

## O que falta

- **Configurar a ferramenta:** chave `SCRAPECREATORS_API_KEY` e acesso de rede a `api.scrapecreators.com`, `*.cdninstagram.com` e `*.fbcdn.net` num ambiente próprio do projeto. Sem isso, a coleta não roda.
- **Contas locais.** Nenhuma conta da Zona Leste foi encontrada com fonte verificável. As concorrentes e contas da região que o Bruno acompanha entram direto no `contas.csv`.
- **TikTok.** Duas contas candidatas já estão listadas; o script cobre só Instagram por enquanto.
