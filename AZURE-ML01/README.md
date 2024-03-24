## Hello world no azure-machine-learning

Seguindo a dinâmica proposta: 
- [x] 1. Crie um novo repositório no github com um nome a sua preferência
- [x] 2. Crie um modelo de previsão com seus devidos pontos de extremidade configurados
- [x] 3. Escreva o passo a passo desse processo em um readme.md de como você chegou nessa etapa
- [x] 4. Salve nesse repositório o readme.md e o arquivo .json de pontos de extremidade
- [x] 5. Compartilhe conosco o link desse repositório através do botão 'entregar projeto'

Obs.: O passo 3 relata escrever o passo a passo desse processo, mas literalmente segui o tutorial do azure: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html, com a diferença que troquei alguns nomes apenas para melhor absorção do conteúdo.

No passo 4 não ficou claro qual é o arquivo .json do endpoint seria, se swagger, se request para o teste ou a response do teste ou mesmo outra coisa, por isso coloquei os três primeiros (uma vez que o mesmo já não existe, acredito não ter riscos de segurança no compartilhamento).
![image](https://github.com/JRGCast/learning-azure-machine-learning/assets/69092560/fab35e88-14b1-4758-a49b-e7066cb28ff3)

Tive alguns percalços no caminho pois queria explorar além do tutorial.

A primeira tentativa 'fora' do tutorial foi deployar o modelo sem anteceder os passos anteriores, bem como com outro nome.

Infelizmente o azure troubleshooting não me deu detalhes de onde aconteceu o erro, é bem chato porque na página fala 'FAILED' e aponta para a página de logs, relatando que haverá detalhamento, porém a página de logs não possui qualquer informação.

Daí troquei o nome do endpoint e deu certo.

