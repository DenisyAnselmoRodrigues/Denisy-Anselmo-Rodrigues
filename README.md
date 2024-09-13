# Denisy-Anselmo-Rodrigues!
![](link)
A palavra **limão** deve ser destacada.
> Escrito por Alura Start
> let palavras = 
palavra = “Caminhante”;
let palavras = ["Caminhante", "Caminho", "Caminha"];
palavra = “Caminhante”;
> let palavras = ["Caminhante", "Caminho", "Caminha"];

let palavra = random(palavras);
function setup() {
  createCanvas(400, 400);
  
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  let palavra = random(palavras);
}
function draw() {
  
  let maximo = width;
  let minimo = 0;
  //mouseX, 0, width ==> 0, palavra.length
  let quantidade = map(mouseX, 0, width, 1, palavra.length);
  //console.log(quantidade);
  let parcial = palavra.substring(0,quantidade);
  text(parcial,200,200);
}
let palavra;

function setup() {
  createCanvas(400, 400);
  
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  let palavra = random(palavras);
}
let palavra;

function setup() {
  createCanvas(400, 400);
  
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  palavra = random(palavras);
}
let palavra;

function setup() {
  createCanvas(400, 400);
  
  
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  
  palavra = random(palavras);
}

function inicializaCores() {
  
  background("white");
  fill("black");
  textSize(64);
  textAlign(CENTER, CENTER);
}

function draw() {
  
  inicializaCores();

  let maximo = width;
  let minimo = 0;
  // mouseX, 0, width ==> 0, palavra.length
  
  let quantidade = map(mouseX, 0, width, 1, palavra.length);
  //console.log(quantidade);
  let parcial = palavra.substring(0, quantidade);
  text(parcial, 200, 200);
  
}
let nacionalidade = “Brasil”;

function dadosPessoais(){
    let idade = 14;
}
function digaOi() {
    let mensagem = "Olá, estudante!";
    console.log(mensagem);
}
let saldoBancario = 1000;  

function realizarCompra(valor) {
    saldoBancario -= valor;
}

realizarCompra(200);
console.log(saldoBancario);  // Resultado: 800
function setup() {
  createCanvas(400, 400);

  let palavras = ["Caminhante", "Caminho", "Caminha"];

  palavra = random(palavras);
}
let palavra;

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();

  let palavras = ["Caminhante", "Caminho", "Caminha"];
  palavra = random(palavras);
}
let palavra;

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();

  let palavras = ["Caminhante", "Caminho", "Caminha"];
  palavra = random(palavras);
}

function palavraAleatoria(){

}
let palavra;

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}
let palavra;

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}

function palavraAleatoria(){
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  palavra = random(palavras);
}
function draw() {

  inicializaCores();

  // ... parte restante do código
}
function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}
let palavra;

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}

function palavraAleatoria(){
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  palavra = random(palavras);
}
function palavraAleatoria(){
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  return random(palavras);
}
let palavra;

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
}

function palavraAleatoria() {
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  return random(palavras);
}

function inicializaCores() {
  background("white");
  fill("black");
  textSize(64);
  textAlign(CENTER, CENTER);
}

function draw() {
  inicializaCores();

  let maximo = width;
  let minimo = 0;
  // mouseX, 0, width ==> 0, palavra.length

  let quantidade = map(mouseX, 0, width, 1, palavra.length);
  //console.log(quantidade);
  let parcial = palavra.substring(0, quantidade);
  text(parcial, 200, 200);
}
function dizerOla(paraQuem) {
    console.log("Olá, " + paraQuem + "!");
}

dizerOla("Alice");
dizerOla("Bob");
dizerOla("Charlie");
function calculaAreaDoRetangulo(altura, largura) {
    let area = altura * largura;
    return area;
}
function calculaAreaDoRetangulo(largura, altura) {
    let area = largura * altura;
    console.log("A área do retângulo é: " + area);
}

calculaAreaDoRetangulo(5, 8);
calculaAreaDoRetangulo(10, 3);
calculaAreaDoRetangulo(7, 7);
function facaCompras(livroA, livroB) {

  let soma = livroA + livroB;
  console.log("A soma dos preços dos livros é: R$ " + soma + ",00");
}

facaCompras(50, 50);
facaCompras(72, 28); 
