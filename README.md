# calcularora-de-nivel
nível de XP do Herói 
// Cria uma variável para armazenar o nome e a quantidade de experiência (XP) de um herói
var nome = "André";
var xp = 6400;

// Cria uma variável para armazenar o nível do herói
var nivel;

// Utiliza uma estrutura de decisão para determinar o nível do herói de acordo com o XP
if (xp < 1000) {
  nivel = "Ferro";
} else if (xp >= 1000 && xp <= 2000) {
  nivel = "Bronze";
} else if (xp >= 2001 && xp <= 5000) {
  nivel = "Prata";
} else if (xp >= 6001 && xp <= 7000) {
  nivel = "Ouro";
} else if (xp >= 7001 && xp <= 8000) {
  nivel = "Platina";
} else if (xp >= 8001 && xp <= 9000) {
  nivel = "Ascendente";
} else if (xp >= 9001 && xp <= 10000) {
  nivel = "Imortal";
} else if (xp >= 10001) {
  nivel = "Radiante";
}

// Exibe uma mensagem com o nome e o nível do herói
console.log("O Herói de nome " + nome + " está no nível de " + nivel);
    
