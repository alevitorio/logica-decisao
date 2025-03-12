# Tomada de Decisão com Python

Bem-vindo! 🚀 Aqui vamos explorar como tomar decisões em código usando Python, de forma clara, objetiva e, claro, com um toque descontraído! 😎

---

## 🎯 O que é tomada de decisão?
A tomada de decisão em um programa é quando o código escolhe entre diferentes caminhos com base em condições lógicas. Em Python, usamos estruturas como `if`, `elif` e `else` para isso.

---

## 🔀 Fluxograma da Decisão

Aqui está um exemplo visual de como funciona a tomada de decisão:

```plaintext
   👀 Entrada de dados  
          ⬇️
    🤔 Verifica condição?
    /     \  
  Sim     Não
  |        |
  🔄 Executa A  ➡️ Executa B  
```

---

## 📝 Exemplo prático: Classificação de Idade

Vamos criar um programa que classifica uma pessoa com base na idade:

```python
idade = int(input("Digite sua idade: "))

if idade < 12:
    print("🍼 Você é uma criança!")
elif idade < 18:
    print("🎓 Você é um adolescente!")
elif idade < 60:
    print("💼 Você é um adulto!")
else:
    print("🏆 Você é um idoso experiente!")
```

---

## ⚡ Exemplo com Multiplas Condições
E se quisermos verificar várias condições ao mesmo tempo? Podemos usar operadores lógicos (`and`, `or`, `not`).

Exemplo: Um programa que verifica se um número está dentro de um intervalo:

```python
numero = int(input("Digite um número: "))

if numero >= 10 and numero <= 50:
    print("✅ O número está entre 10 e 50.")
else:
    print("❌ O número está fora do intervalo.")
```

---

## 🏆 Conclusão
Tomar decisões em Python é essencial para tornar seus programas inteligentes e dinâmicos. Com `if`, `elif`, `else` e operadores lógicos, você pode criar lógicas cada vez mais poderosas! 🚀

Agora é sua vez! Teste esses exemplos e crie suas próprias decisões! 💡

