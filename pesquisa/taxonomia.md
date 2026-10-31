# Taxonomia da biblioteca de referências

Vocabulário fixo para classificar cada referência. Usar sempre os mesmos códigos permite contar padrões ("7 de 10 Reels fora da curva abrem com situação cotidiana") em vez de colecionar impressões.

Regras:

- Cada referência recebe **um** código principal por dimensão e, se precisar, **um** secundário.
- Classificar pelo que o vídeo mostra, não pela legenda nem pelo dia da semana. Se o vídeo não foi visto, a referência fica com nível de evidência "só legenda" (ver dimensão 6).
- Código novo só entra quando aparecer em pelo menos 2 referências que não cabem em nenhum código existente. Registrar a inclusão no fim deste arquivo.
- Os exemplos "Vilela" vêm do diagnóstico de 2026-10-31 (números = ordem de publicação).

## 1. Formato (o que a câmera mostra)

| Código | Formato | Definição | Exemplo Vilela |
|---|---|---|---|
| F01 | Tour clássico | Percurso pelo imóvel, cômodo a cômodo, com legenda ou música | Maioria dos 49 tours do período (#90 visto na gravação) |
| F02 | Tour criativo | Tour com um conceito: personagem, desafio, ordem inesperada, ponto de vista, roteiro com clímax | Não identificado |
| F03 | Corretor falando para a câmera | O corretor conduz o vídeo, em pé ou andando, falando direto com quem assiste | #08 (abertura), #93 (vistos na gravação) |
| F04 | Take (opinião) | Uma opinião ou posição clara sobre o mercado, o bairro ou a compra | Não identificado |
| F05 | React | Reação a outro conteúdo (anúncio, notícia, vídeo, comentário de seguidor) | Não identificado |
| F06 | Reação em tempo real | Registro da reação de alguém no momento: cliente entrando no imóvel, recebendo a chave, vendo o preço | #54, #91 (registro de cliente) |
| F07 | Humor ou encenação | Esquete, situação encenada, personagens, atuação | Não identificado |
| F08 | POV | Cena em primeira pessoa que coloca quem assiste na situação ("POV: você...") | #59 (pela legenda) |
| F09 | Ranking ou lista | Top N de bairros, imóveis, erros, custos | Não identificado |
| F10 | Comparação lado a lado | Dois imóveis, dois bairros, aluguel × parcela, antes × agora | #57, #71 (pela legenda) |
| F11 | Motion design ou texto animado | Vídeo feito de texto, gráficos, mapas e imagens animadas, sem filmagem principal | #75, #85, #94 |
| F12 | Bastidor | Rotina do corretor, obra, visita, negociação, captação | #66 (obra, pela legenda) |
| F13 | Educativo explicado | Explica um tema (financiamento, custos, documentação) com fala, texto ou quadro | #60, #82 |
| F14 | Narração em off | História ou tour com voz por cima das imagens | A verificar |
| F15 | Antes e depois | Transformação de um imóvel, de um cômodo, de uma vida | Não identificado |
| F16 | Trend ou áudio em alta | Usa um formato ou áudio que está circulando | A verificar |
| F17 | Gerado com IA | Imagem, vídeo, voz ou personagem gerado por IA como parte central | Não identificado |

## 2. Mecanismo do gancho (por que a pessoa para nos primeiros 3 segundos)

O gancho tem três camadas que são lidas separadamente: **visual** (a primeira imagem), **texto na tela** e **fala**. A biblioteca registra as três quando o vídeo é visto.

| Código | Mecanismo | Definição | Exemplo Vilela |
|---|---|---|---|
| G01 | Situação cotidiana | Uma dor ou cena que a pessoa reconhece da própria vida | #87 "Cansou do vizinho de cima?" |
| G02 | Dor do aluguel | Provoca quem paga aluguel | #57, #71 "Esse apê vai te fazer repensar...", #94 |
| G03 | Número ou preço surpreendente | Um valor que contraria a expectativa | #58 "por R$ 219.900!" |
| G04 | Comparação | Coloca dois valores ou opções lado a lado | #90 m² × média do bairro, #93 parcela × aluguel |
| G05 | Pergunta de palpite | Pede para a pessoa adivinhar ou opinar | #78 "Quanto você acha que custa...", #55 "Você construiria o quê aqui?" |
| G06 | Lacuna de curiosidade | Promete uma informação que a pessoa não tem | #75 "Você mora no São Lucas e não sabia disso" |
| G07 | Quebra de expectativa | Afirma algo que parece errado ou improvável | #85 "O gol mais bonito do Pelé foi na Mooca, e ninguém filmou" |
| G08 | Atributo incomum | Mostra algo raro no imóvel | #74 "8 vagas com edícula? Eu precisei ver." |
| G09 | Começar pelo fim | Abre no momento de maior emoção ou resultado e depois conta como chegou lá | #54 "20 anos de confiança e, hoje, a chave da casa nova" |
| G10 | Projeção | Coloca a pessoa morando ali ("seu novo começo") | #24 "Seu novo começo pode estar aqui!" |
| G11 | Identidade local | Fala de pertencimento ao bairro, com gíria ou referência local | #89 "Mooca é Mooca, belo." |
| G12 | Bastidor ou segredo do setor | "O que ninguém conta sobre..." | #66 "Muita gente não sabe, mas a Vilela também constrói" |
| G13 | Humor ou absurdo | Uma piada, exagero ou situação absurda | Não identificado |
| G14 | Tensão ou problema real | Algo deu errado e há suspense sobre o desfecho | #91 "A Caixa entrou em greve no meio da compra" |
| G15 | Ficha técnica | Abre com tipo, bairro e metragem, sem outro mecanismo | 27 conteúdos até 22/09 |

## 3. Narrativa (como o vídeo se organiza do início ao fim)

As estruturas N06 a N11 vêm de [advisorita/storytelling-frameworks](https://github.com/advisorita/storytelling-frameworks), usado sem alterações no original.

| Código | Estrutura | Definição |
|---|---|---|
| N01 | Sem narrativa (lista) | Sequência de informações sem conflito nem virada |
| N02 | Revelação progressiva | Guarda o melhor do imóvel ou da informação para o fim |
| N03 | Problema → solução | Apresenta uma dor e o imóvel ou a informação que a resolve |
| N04 | Pergunta → resposta | Abre com pergunta e responde no corpo |
| N05 | Comparação | Duas opções avaliadas até um veredito |
| N06 | Big Goal/Dream | Um sonho e o caminho até ele |
| N07 | Challenge | Um obstáculo concreto e como foi superado |
| N08 | Breakthrough | O momento de virada, a descoberta |
| N09 | About Me | Quem é o narrador e por que confiar nele |
| N10 | Hero's Journey | O cliente como herói, o corretor como guia |
| N11 | Man in a Hole | Estava bem, caiu num problema, saiu melhor |
| N12 | Começar pelo fim | Abre no desfecho e volta para contar a história |
| N13 | Loop | O final reconecta com o começo e convida a assistir de novo |

## 4. Edição (como o vídeo é montado)

Dimensões de [edit-anatomy](https://github.com/coreyhaines31/marketingskills) (skill `video`, referência `edit-anatomy.md`), usadas sem alterações no original. Na biblioteca, cada referência vista recebe um código para cada linha abaixo e um resumo de 3 a 5 "movimentos de assinatura" ("corte seco a cada frase com zoom de 5%").

| Dimensão | Códigos |
|---|---|
| E1 Presença humana | corretor em cena · cliente em cena · ator · só voz · ninguém |
| E2 Enquadramento | rosto em close · plano aberto · câmera na mão andando · gimbal · drone · tela/texto |
| E3 Ritmo de corte | lento (mais de 3 s por plano) · médio (1,5 a 3 s) · rápido (menos de 1,5 s) · sem cortes (plano-sequência) |
| E4 Texto na tela | nenhum · legenda da fala · frase de impacto no topo · ficha do imóvel · texto como protagonista |
| E5 Estilo da legenda | palavra a palavra · linha inteira · com destaque de cor · sem legenda |
| E6 Movimento | estático · zoom de impacto · transições rápidas · aceleração/câmera lenta |
| E7 Som | fala original · música em alta · música de fundo · efeitos sonoros · silêncio intencional |
| E8 Curva de ritmo | constante · gancho rápido e corpo lento · crescente até o clímax |
| E9 Duração | até 15 s · 16 a 30 s · 31 a 60 s · 61 a 90 s · mais de 90 s |

## 5. Tema (sobre o que o vídeo fala)

| Código | Tema |
|---|---|
| T01 | Imóvel à venda (registrar o tipo: apartamento, casa, sobrado, terreno, salão, outro) |
| T02 | Bairro ou região |
| T03 | Mercado e preços |
| T04 | Financiamento e processo de compra |
| T05 | Aluguel × compra |
| T06 | História de cliente |
| T07 | Rotina e bastidores do corretor |
| T08 | Curiosidade ou história local |
| T09 | Institucional |
| T10 | Humor do setor imobiliário |
| T11 | Potencial do imóvel (reforma, decoração, uso) |
| T12 | Fora do setor (referência de mecanismo de outro nicho) |

Para T01, registrar também a faixa de preço e se é um imóvel comum (dentro de R$ 245 mil a R$ 700 mil) ou de alto padrão. Um dos objetivos da pesquisa é aprender a transformar imóveis comuns em conteúdo.

## 6. Resultado observado

Viralidade absoluta engana: 50 mil views numa conta de 1 milhão de seguidores é fraco, e 15 mil numa conta de 3.400 é muito forte. Por isso o resultado é sempre relativo à própria conta.

| Campo | Como preencher |
|---|---|
| Mediana da conta | Mediana de views dos últimos 12 a 24 Reels da conta com mais de 10 dias, contando cada conteúdo uma vez |
| Múltiplo da mediana | Views do Reel ÷ mediana da conta |
| Classe de resultado | R1 fora da curva (3× ou mais) · R2 acima (1,5× a 3×) · R3 na média (0,67× a 1,5×) · R4 abaixo (menos de 0,67×) |
| Sinais públicos | Curtidas e comentários por 1.000 views. Compartilhamentos e salvamentos só aparecem em contas próprias; em referências externas ficam como "não disponível" |
| Teor dos comentários | Intenção de compra · pergunta sobre o imóvel · marcação de amigo · elogio · crítica · não lido |
| Nível de evidência | V1 vídeo visto inteiro · V2 vídeo visto em parte ou por gravação · V3 só legenda e números · V4 só citado por terceiros |

A análise de uma referência só entra na contagem de padrões com nível V1 ou V2.

## 7. Aplicação à Vilela

| Campo | Como preencher |
|---|---|
| Por que funcionou | **Sempre marcado como inferência.** O que o vídeo mostra é observado; a explicação é hipótese |
| Mecanismo transferível | A parte que pode ser usada com outro imóvel, outra pessoa e outra história |
| Como adaptar sem copiar | Ideia concreta para a Vilela, com outro roteiro, outra filmagem e outro áudio |
| Executável pelo Bruno sozinho? | Sim · com ajuda · não |
| Cuidados | CRECI na peça, autorização de imagem (LGPD), preço e dados confirmados, direitos de música |

## Registro de mudanças na taxonomia

- 2026-10-31 — Versão inicial.
