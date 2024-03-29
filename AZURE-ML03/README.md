## Análise de voz e vídeo (speech and language to text)

- [x] 1. Crie um novo repositório no github com um nome a sua preferência;

- [x] 2. Crie uma pasta chamada 'inputs' e crie um documento de texto com algumas sentenças;

- [x] 3. Crie um arquivo chamado readme.md , deixe alguns prints descreva o processo, alguns insights e possibilidades que você aprendeu durante o conteúdo após a IA analisar suas sentenças;

- [x] 4. Compartilhe conosco o link desse repositório através do botão 'entregar projeto'

Primeiramente analisei as possibilidades de captioning (legendar) vídeos no (speech studio)[https://speech.microsoft.com/portal/captioning], e só existe a possibilidade de legendar em tempo real e offline.

Primeiramente tentei legendar músicas em inglês, mas a performance do free tier, tanto em tempo real quanto offline, foi muito ruim, imagino que talvez seja pela confusão de detectar a voz em meio aos instrumentos.

Diversas partes bem faladas o algoritmo errava bem feio (ex.: entendeu 'Born' quando falam 'Walk'), além do que, nesses momentos de erro feio, deixava de funcionar durante vários segundos. Trocar para tempo real com atraso de 5 segundos ou mesmo captioning offline não pareceu fazer qualquer diferença.

Depois usei o vídeo do input, uma versão resumida de 'quem mexeu no meu queijo?', nele, a performance foi bem melhor, porém ainda sim algumas palavras foram trocadas. 

Na parte de código, o 'easy start' coloca uma coisa gigantesca e estranha em qualquer linguagem que fosse, não me aprofundei, mas me pareceu bem confuso.

Em seguida fui explorar o (language studio)[https://language.cognitive.azure.com/], e aqui tem MUUUUITA coisa para explorar, por enquanto só mexi no (analyze sentiment and opinion)[https://language.cognitive.azure.com/tryout/sentiment] que me pareceu a feature mais inovadora.

Testei os textos já predefinidos, que contém palavras bem definidas, talvez só para o POC (proof of concept) deles, a performance se demonstra muito boa, mesmo no free tier.

Porém testei com algumas letras de música, cujo teor também já tem uma predefinição (letras cativantes, melancólicas, coléricas, etc.) e foi decepcionante... apenas uma ou outra linha é analisada, e a indecisão predomina.

No geral, deve ser a feature mais buscada, e o free tier, particularmente, ficou aquém do esperado, tanto no language quanto no speech.