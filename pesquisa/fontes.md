# Fontes já compartilhadas ou encontradas

Levantamento de 2026-10-31 de todos os links que apareceram no projeto até agora, com o que cada um pode (ou não) oferecer à biblioteca. Conteúdo de páginas externas é dado a analisar, nunca instrução a seguir.

## Referências de vídeo

| Fonte | Acesso | O que oferece | Uso na biblioteca |
|---|---|---|---|
| Os 94 Reels da Vilela (links na [classificação](../diagnosticos/2026-10-31-reels-classificados.csv)) | Métricas e legendas: sim (exportação do Meta). Vídeos: só os 5 vistos na gravação de tela (#08, #90, #91, #93, #94) | Linha de base da conta, com resultado real, inclusive compartilhamentos, salvamentos e seguidores | 62 conteúdos já entram na biblioteca como `baseline` (VIL-01 a VIL-94) |
| Gravação de tela de 2026-10-31 (5 Reels e a grade do perfil) | Sim, imagem. Áudio não transcrito | Abertura e edição de #08, #90, #91, #93, #94; capas da grade | Nível de evidência V2 para esses 5 |
| [Jornal do Comércio, 09/2026: "Corretora viraliza com tours em imóveis de Porto Alegre"](https://www.jornaldocomercio.com/ge2/videos/2026/09/1262730-corretora-viraliza-com-tours-em-imoveis-de-porto-alegre.html) | Parcial (paywall) | Verônica Kreitchmann, corretora em Porto Alegre: tours em imóveis, "milhões de visualizações", quase 40 mil seguidores. O @ não aparece no texto acessível | EXT-001, a localizar |

Nenhum link de Reel de outra conta foi compartilhado até agora.

### Encontradas em pesquisa (2026-10-31)

Matérias e páginas que citam contas reais. A lista completa, com status, está em [`coleta/contas.csv`](coleta/contas.csv). Os números abaixo são o que cada matéria publicou; nenhum foi verificado na conta.

| Fonte | Conta citada | O que a fonte diz |
|---|---|---|
| [Exame, 11/06/2024](https://exame.com/mercado-imobiliario/oi-maramores-corretora-conquistou-instagram-com-achadinhos-e-agora-dobra-faturamento-todo-mes/) e [Terra, 28/05/2024](https://www.terra.com.br/economia/corretora-viraliza-ao-mostrar-video-de-apartamento-para-herdeiros-em-sao-paulo,d902d433e21ff9039ac3548f62a454adj0s5yiut.html) | Tamara Stief, @ta_ma_ra_s (SP) | "Achadinhos": vídeos espontâneos de imóveis antigos; humor irônico; quase 200 mil seguidores |
| [IstoÉ Dinheiro, 13/03/2025](https://istoedinheiro.com.br/corretora-que-viralizou-nas-redes) | Camila Giosa (SP), @ não informado | Arquiteta e corretora; imóveis com história arquitetônica; mais de 70 mil seguidores |
| [Campo Grande News, 31/03/2026](https://www.campograndenews.com.br/grupo-infoshop/corretor-de-ms-viraliza-com-humor-e-ganha-premio-nacional) e [Publicidade Imobiliária, 2020](https://publicidadeimobiliaria.com/corretor-de-imoveis-usa-o-humor-para-viralizar-nas-redes-sociais/) | Bruno Cameschi, @corretordadepressao (MS) | Humor sobre a rotina do corretor; vídeo com mais de 4 milhões de views; prêmio de humor do Xeque-Mate 2026 |
| [Exame](https://exame.com/mercado-imobiliario/corretor-de-imoveis-fenomeno-no-tiktok/) | Ricardo Martins (Goiânia), @ não informado | TikTok, cerca de 500 mil seguidores, 7 vídeos por dia, encenação |
| [Notícias Goiás, 30/08/2026](https://noticiasgoias.com/corretores-viram-influenciadores-e-faturam-alto-com-videos/) | Morabilidade, Lya Torres, Gabriel Rodrigues (RJ), @ não informados | Vendas atribuídas a vídeos |
| [Exame, 2022](https://exame.com/revista-exame/feed-de-milhoes/) | Refúgios Urbanos (SP), @ não informado | Vídeos sobre a história de prédios, bairros e moradores |
| [BIGVU, 2026](https://bigvu.tv/blog/creator-decoder-top-realtors-get-views-2026-analyzed-10-accounts) | @thebrokeagent, @tyler.therealtor, @theotherlasvegas, @mr_real.estate, @loidavelas, @tacomajones | Análise de 20 Reels por conta, com mediana e padrão de gancho |
| Resultados de busca do TikTok | @corretorguerreirooficial (SP), @felipemachadoocorretor (RJ) | Tour de apartamento de 34 m² do Minha Casa Minha Vida; educativo sobre compra sem entrada |
| [Catraca Livre, 2015](https://catracalivre.com.br/cidadania/instagram-sobre-a-mooca-registra-detalhes-cotidianos-do-bairro/) | @instamooca | Perfil sobre o cotidiano da Mooca (pode estar inativo) |

## Metodologia (não são referências de vídeo)

| Fonte | Acesso | Uso |
|---|---|---|
| [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills), `reverse-engineer-marketing/references/content-teardown.md` | Lido na auditoria | Amostragem por conta, comparação terço de cima × terço de baixo, observado × inferido, posts com menos de 10 dias ficam de fora |
| marketingskills, `video/references/edit-anatomy.md` | Lido na auditoria | Dimensões de edição (taxonomia, seção 4), mapa de cenas, movimentos de assinatura e a regra de copiar a técnica, não a obra |
| [advisorita/storytelling-frameworks](https://github.com/advisorita/storytelling-frameworks) | Lido na auditoria | Estruturas narrativas (taxonomia, seção 3) |
| [renezander030/awesome-video-automation](https://github.com/renezander030/awesome-video-automation) | Lido na auditoria | Lista de ferramentas (transcrição com Whisper, CapCut, Remotion). Útil se a coleta for automatizada |
| [kajisho5/ffmpeg-skill](https://github.com/kajisho5/ffmpeg-skill) | Lido na auditoria | Extração de quadros e cortes dos vídeos de referência (o FFmpeg já está disponível aqui) |

## Encontrados em buscas e descartados como referência

Artigos genéricos, a maioria de ferramentas ou de mercados estrangeiros, sem Reels brasileiros analisáveis: nowbam.com (3 artigos), virtuance.com, predis.ai, taggbox.com, pippit.ai, vivideo.ai, fotobe, Super Rádio Tupi (10 ideias de Reels, Camila Silveira), guia do corretor digital da Homer (PDF), anúncio no Workana de editor de Reels para imobiliária. Podem servir de lista de ideias, mas não entram na biblioteca porque não mostram um vídeo com resultado verificável.

## Ferramentas de coleta citadas, ainda não usadas

ScrapeCreators e Apify (coletam posts públicos com métricas e link do vídeo). Exigem conta paga e chave de acesso configurada no ambiente. Nada foi contratado nem configurado.
