- 👋 Hi, I’m @JulioAnalist
- 👀 I’m interested in  Aprender e Publicar meus projetos     
- 🌱 I’m currently learning  HTML5, CSS , JS, SQL, bootstrap, PHP, Python
- 💞️ I’m looking to collaborate on  Todas as ferramentas estudadas
- 📫 How to reach me  Email Julioti06@gmail.com ou whatsapp +5511977750389

<!---
Pedro joga N jogos de basquete por temporada. Para saber como está ele está progredindo, ele mantém
registro de todos os as pontuações feitas por jogo. Após cada jogo ele anota no novo valor e confere se o
mesmo é maior ou menor que seu melhor e pior desempenho. Dada uma lista string = “pontuação1 pontuação2
pontuação3 etc..”, escreva uma função que ao recebê-la irá comparar os valores um a um e irá retornar um
vetor com o número de vezes que ele bateu seu recorde de maior número de pontos e quando fez seu pior
jogo. 
--->

let vetorResultado = []
const jogos = function(pontuação) {

vetorResultado.push(pontuação)

let MaiorResultado = Math.max.apply(Math, vetorResultado)
let MenorResultado = Math.min.apply(Math, vetorResultado)

console.log(`O maior Resultado ${MaiorResultado}` )
console.log(`O Menor Resultado ${MenorResultado}` )

}


// jogo 1
jogos(20)

// jogo 2

jogos(10)

// jogo 3
jogos(30)
