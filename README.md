# 📱 meus-estudos-ios

Meu guia de aprendizado iOS com Swift e SwiftUI — Da base ao app real!  
Este repositório é parte da minha jornada como desenvolvedor iOS júnior.

🧠 Estudando Swift do zero com foco em prática e compreensão, do jeito que faz sentido pra mim.

---

## 🚀 Objetivo

- Desenvolver uma base sólida com Swift e SwiftUI
- Compartilhar desafios, códigos e aprendizados por dia
- Criar projetos reais no futuro

---

## 📆 Cronograma de Estudos

### 🧭 Dia 1 – Variáveis, Constantes, Strings e Números

```swift
var nome = "Valdemar"
print(nome)

let pais = "Angola"
print(pais)

var idade = 28
let altura = 1.75
```

---

### 🧭 Dia 2 – Booleanos e Interpolação de Strings

```swift
let souEstudante = true

if souEstudante {
    print("Bem-vindo de volta à aula!")
} else {
    print("Você precisa se matricular.")
}

let nome = "Valdemar"
let idade = 27
print("Meu nome é \(nome) e tenho \(idade) anos.")
```

---

### 🧭 Dia 3 – Arrays, Dicionários, Sets e Enums

```swift
let frutas = ["Banana", "Maçã", "Abacaxi"]
print(frutas[1])

let pessoa = ["nome": "Valdemar", "cidade": "Belém"]
print(pessoa["nome"]!)

let numeros: Set = [1, 2, 3, 3]
print(numeros.count)

enum Direcao {
    case norte, sul, leste, oeste
}
let minhaDirecao = Direcao.sul
```

---

### 🧭 Dia 4 – Tipos Explícitos

```swift
var idade: Int = 30
var nome: String = "Valdemar"
var peso: Double = 70.5
```

---

### 🧭 Dia 5 – if, switch, operador ternário

```swift
let linguagem = "Swift"

switch linguagem {
case "Swift":
    print("Estamos estudando iOS!")
case "Python":
    print("Ótimo para scripts.")
default:
    print("Linguagem desconhecida.")
}
```

---

### 🧭 Dia 6 – Loops

```swift
let frutas = ["Banana", "Maçã", "Uva"]

for fruta in frutas {
    print("Eu gosto de \(fruta)")
}
```

---

### 🧭 Dia 7 – Funções

```swift
func soma(a: Int, b: Int) -> Int {
    return a + b
}

print(soma(a: 10, b: 5))
```

---

### 🧭 Dia 8 – Parâmetros padrão

```swift
func saudacao(nome: String = "Amigo") {
    print("Olá, \(nome)!")
}

saudacao()
saudacao(nome: "Valdemar")
```

---

## 🧑🏽‍💻 Sobre mim

Sou Valdemar Hoque, desenvolvedor iOS em formação no iOS Lab – Apple Authorized Training Center. Estou aprendendo Swift e SwiftUI com foco em criar projetos reais e úteis.  
🔗 [Meu GitHub](https://github.com/valdemarhoque)
