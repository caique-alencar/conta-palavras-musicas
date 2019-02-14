<h1> Contador de palavras repetidas em músicas </h1>

Os códigos <code>contagem_musicas_portugues.ipynb</code> e <code>contagem_musicas_ingles.ipynb</code> contam quantas palavras uma única música tem. Há diferença no código de um idioma para o outro por conta de as estruturas do HTML das páginas serem diferentes.
  
O código <code>contagem_musicas_csv.ipynb</code> conta quantas vezes cada palavra se repetiu em uma lista de músicas no arquivo <code>musicas.csv</code> e gera o CSV <code>palavras_repetidas_musicas.csv</code>.

Ao executar o programa, <code>contagem_musicas_csv.ipynb</code> e <code>musicas.csv</code> devem estar no mesmo diretório.

<b>Observações</b>:
<ul>
  <li>Usei o site do Vagalume para escrever o código e a raspagem só funciona com esse site</li>
  <li>Para adicionar letras de músicas à planilha <code>musicas.csv</code>, usar links do Vagalume</li>
  <li>O código exige que, antes, sejam instaladas as bibliotecas <code>BeautifulSoup4</code> e <code>Requests</code></li>
<ul>
