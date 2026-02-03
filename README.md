# Exercícios Kotlin


### Exercício. 1 🌡️
```
fun main() {

  var entrada_celsius = 30
    var F = entrada_celsius * 9/5 + 32
    print(F)
```
---
### Exercício. 2 🌡️
```
fun main() {

  var fahrenheit = 77
    var C = (fahrenheit - 32) * 5/9
    print(C)
   
}
```
---
### Exercício. 3 🛢️
```
fun main() {
  
  var raio = 2.0
  var altura = 5.0
  var V =  3.14 * (Math.pow(raio,2.0) * altura)
    print(V)
```
---
### Exercício. 4 ⛽
```
fun main() {
  
  var distancia = 240
  var consumo = 12
  
    var LG = distancia/consumo
    print(LG)
}
```
---
### Exercícios. 5 🧮
```
fun main() {

   val valor_Original = 500.0
   val meses_atraso = 2.0
   val taxa_juros = 2.0
    
   val valor = valor_Original * (1.0 + (taxa_juros / 100.0) * meses_atraso)
   print(valor)
}
```
### Exercício. 6 💱
```
fun main() {
   
    var A = 5
    var B = 10
    
    var troca = A
    A = B
    B = troca
    
    print("A: $A, B: $B")
}
```
###  Exercício. 7 ➕✖️
```
fun main() {
   
    val A = 1
    val B = 2
    val C = 3
    val D = 4
    
    // Adição
    val R12 = A + B
    val R13 = A + C 
    val R14 = A + D
    val R23 = B + C 
    val R24 = B + D 
    val R34 = C + D
    
    //Multiplicação
     val R21 = A * B
     val R31 = A * C 
     val R41 = A * D
     val R32 = B * C 
     val R42 = B * D 
     val R43 = C * D
    
    print("Adições: $A + $B = $R12, $A + $C = $R13, $A + $D = $R14, $B + $C = $R23, $B + $D = $R24, $C + $D = $R34")
    print("Multiplicações: $A * $B = $R21, $A * $C = $R31, $A * $D = $R41, $B * $C = $R32, $B * $D = $R42, $C * $D = $R43")
}
```
### Exercício. 8 📦
```
fun main() {
    
   val comprimento = 4
   val largura = 3
   val altura = 2
    
   val volume = comprimento * largura * altura
    
   print (volume)
}
```
### Exercício. 9 🟪
```
fun main() {
    
   val n1 = 5
    
   val quadrado = n1 * n1
    print(quadrado)
}
```
### Exercício. 10 🔢
```
fun main() {
    
   val n1 = 10 
   val n2 = 5
    
   val diferenca = n1 - n2
   print("$diferenca ($n1 - $n2)")
}
```
### Exercício. 11 💲
```
fun main() {
    
    val dolar = 50
    
   val real = dolar * 5.24
   print(real)
}  
```
### Exercício. 12 💵
```
fun main() {
    
    val real = 100.0
    
   val dolar = real/5.24
   print(dolar)
}  
```
### Exercício. 13 ➕🟪
```
fun main() {
    
   val n1 = 2
   val n2 = 3
   val n3 = 4
    
   val quad1 = n1 * n1
   val quad2 = n2 * n2
   val quad3 = n3 * n3
    
   val soma = quad1 + quad2 + quad3
   print("$soma ($n1² + $n2² + $n3² = $quad1 + $quad2 + $quad3 = $soma)")
}  
```
### Exercício. 14 🟥➕
```
fun main() {
    
   val n1 = 2
   val n2 = 3
   val n3 = 4
    
   val soma = n1 + n2 + n3
   val quadrado = soma * soma
   print("$quadrado (($n1 + $n2 + $n3)² = $soma² = $quadrado)")
} 
```
### Exercício. 15 ➕4️⃣
```
fun main() {
    
  val n1 = 2
  val n2 = 3 
  val n3 = 4 
  val n4 = 5
    
   val produtos = n1 * n3
   val soma = n2 + n4
    
   print("Produto: $produtos($n1 * $n3), Soma: $soma($n2 + $n4) ")
}  
```
### Exercício. 16 📈
```
fun main() {
    
  val salario = 1000.0
  val porcentagem = 10.0
    
   val aumento = salario * (porcentagem/100.0)
   val novo = salario + aumento
    
   print("Novo Salário: $novo, Aumento: $aumento")
}  
```
### Exercício. 17 ⭕
```
fun main() {
    
  val raio = 5.00
  val area = 3.14 * raio * raio
    
   print(area)
}  
```
### Exercício. 19 ✖️➗
```
fun main() {
    
  val n1 = 10
  val n2 = 5
    
   val soma = n1 + n2
   val subtracao = n1 - n2
   val multiplicacao = n1 * n2
   val divisao = n1/n2
    
   println("Adição: $n1 + $n2 = $soma")
   println("Subtração: $n1 - $n2 = $subtracao")
   println("Multiplicação: $n1 * $n2 = $multiplicacao")
   println("Divisão: $n1/$n2 = $divisao")
}  
```
### Exercício. 20 ⭕
```
fun main() {
    
  val distancia = 200.0
  val tempo = 4.0
  
    
    val km  = distancia/tempo
    val velocidade = km/3.6
    print("Velocidade: $velocidade m/s")
}  
```
### Exercício. 21 🙃
```
fun main() {
    
  val base = 2.0
  val expoente = 3.0
    
  val resultado = Math.pow(base,expoente)
  print(resultado)
}  
```
### Exercício. 22 😯
```
fun main() {
    
 val raio = 5.0
    
 val volume = (4.0/3.0) * 3.14 * Math.pow(raio,3.0) 
    print(volume)
}  
```
### Exercício. 23 👣
```
fun main() {
    
 val pes = 10.0
    
 val metros = pes * 0.3048 
    print(metros)
}  
```
### Exercício. 24 🫚
```
fun main() {
    
 val base = 16.0
 val indice = 2.0
    
   val raiz = Math.pow(base,1.0/indice)
   print(raiz)
}   
```
### Exercício. 25 🙊
```
fun main() {
    
 val numero = 5
   
 val sucessor = numero + 1
 val antecessor = numero - 1
    
 print("Sucessor: $sucessor, Antecessor: $antecessor")
} 
```
### Exercício. 26 🟥➗
```
fun main() {
    
 val n1 = 10.0
 val n2 = 2.0
    
 val resultado_divisao = n1/n2
 val resultadoQuadrado = resultado_divisao * resultado_divisao
    
 print(resultadoQuadrado)
}  
```
### Exercício. 27 🧌
```
fun main() {
    
 val n1 = 10.0
 val n2 = 5.0
 val diferenca:Double
    
 if (n1 > n2){
     diferenca = n1 - n2
 }else{
     diferenca = n2 - n1
 }
    
 print(diferenca)
}  
```
### Exercício. 28 ➕➖
```
fun main() {
    
 val numero = -5
    
 if (numero > 0){
     print("Positivo")
 } else if (numero < 0){
     print("Negativo")
 } else {
     print("Neutro")
 }
}  
```
### Exercício. 29 ✅
```
fun main() {
    
     val nota1 = 7.0
     val nota2 = 6.0
     val nota3 = 4.0
     val nota4 = 5.0

     val media = ( nota1 + nota2 + nota3 + nota4)/4
     if (media >= 5){
         print("Média: $media. Aprovado")
     } else {
         print("Média:$media. Reprovado")
     }  
}
```
### Exercício. 30 ✔️
```
fun main() {
    
     val nota1 = 6.0
     val nota2 = 7.0
     val nota3 = 5.0
     val nota4 = 8.0

     val media = ( nota1 + nota2 + nota3 + nota4)/4
     if (media > 7){
         print("Média: $media. Aprovado")
     } else if (media >= 5){ 
         print("Média: $media. Exame")
     } else {
         print("Média:$media. Reprovado")
     }  
}
  
```
### Exercício. 32 🐽
```
ffun main() {
    
    var n1 = 5
    var n2 = 2
    var n3 = 7
    var temp:Int
    
     if (n1> n2){
        temp = n1
        n1 = n2
        n2 = temp
     } else if (n1 > n3){ 
         temp = n1
         n1 = n3
         n3 = temp
     } else if (n2 > n3) {
         temp = n2
         n2 = n3
         n3 = temp
     }else{
         print("Erro")
     }  
     
    print("$n1, $n2, $n3")
}
```
