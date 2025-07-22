# 📱 meus-estudos-ios

Meu guia de aprendizado iOS com Swift e SwiftUI — Da base ao app real!  
Este repositório faz parte da minha jornada como desenvolvedor iOS júnior.  
🧠 Estudando Swift do zero com foco em prática e compreensão, do jeito que faz sentido pra mim.

---

## 🚀 Objetivo

- Desenvolver uma base sólida com Swift e SwiftUI  
- Compartilhar desafios, códigos e aprendizados por dia  
- Criar projetos reais no futuro

---

## 📆 Cronograma de Estudos

---

### 🧭 Dia 1 – Variáveis, Constantes, Strings e Números

#### 🧠 Conceitos

A — **Variável**: em Swift a gente usa `var`, que é um valor que pode mudar  
B — **Constante**: em Swift a gente usa `let`, que é um valor que não pode mudar  
C — **String**: em Swift são textos entre aspas  
D — **Números inteiros**: em Swift usamos `Int`  
E — **Números decimais**: usamos `Double`

#### 👨🏽‍💻 Na prática

```swift
var nome = "Valdemar"
print(nome)

Esse valor você pode mudar — tu és livre!

var nome = "Paulo"
var nome = "Bruna"

💡 Por que começamos variáveis com letra minúscula tipo nome?
É o famoso camelCase. Não é obrigatório, mas é uma boa prática.

let nome = "Valdemar"
print(nome)

O uso de let ou var depende de ti: se o valor não vai mudar, usa let.

var idade = 28
let altura = 1.75

var cidade: String = "São Paulo"
var ano: Int = 2025

print(cidade)

🧪 Desafios para praticar
Crie uma variável com seu nome e imprima na tela:

var nome = "Valdemar"
print(nome)

Crie uma constante com o nome do seu país:

let pais = "Angola"
print(pais)

Some dois números:
var numero1 = 10
var numero2 = 20
var resultado = numero1 + numero2

print(resultado)

🧭 Dia 2 – Booleans e Interpolação de Strings
🧠 Conceitos
Bool representa verdadeiro ou falso: true / false

if, else controlam o fluxo do código

Interpolação de strings: inserir variáveis dentro de uma string com \()

👨🏽‍💻 Exemplos

let souEstudante = true

if souEstudante {
    print("Bem-vindo de volta à aula!")
} else {
    print("Você precisa se matricular.")
}


let nome = "Valdemar"
let idade = 27
print("Meu nome é \(nome) e tenho \(idade) anos.")

💡 Desafios

let temEmprego = false

if temEmprego {
    print("Parabéns pelo trabalho!")
} else {
    print("Envie seu currículo!")
}


var nome = "Valdemar"
var cidade = "Benguela"

print("Meu nome é \(nome) e sou de \(cidade)")


🧭 Dia 3 – Arrays, Dicionários, Conjuntos e Enums
🧠 Conceitos
Array: lista de itens

let listaDeCompras = ["Arroz", "Feijão", "Leite", "Leite"]
print(listaDeCompras[0]) // Arroz


let contatos = ["João": "99999-9999", "Maria": "88888-8888"]
print(contatos["Maria"]!) // 88888-8888


let figurinhas: Set = ["Pikachu", "Charizard", "Mewtwo", "Pikachu"]
print(figurinhas.count) // 3


🔧 Métodos úteis:
.append() – Adiciona no final da lista

.remove(at:) – Remove algo pela posição

.contains() – Verifica se existe

.count – Conta quantos tem

Enumeração

enum Direcao {
    case norte, sul, leste, oeste
}
let minhaDirecao = Direcao.sul

🧭 Dia 4 – Tipos Explícitos

var idade: Int = 30
var nome: String = "Valdemar"
var peso: Double = 70.5

🧑🏽‍💻 Sobre mim
Sou Valdemar Hoque, desenvolvedor iOS em formação no iOS Lab – Apple Authorized Training Center.
Estou aprendendo Swift e SwiftUI com foco em criar projetos reais e úteis.

🔗 Me segue lá: github.com/valdemarhoque



