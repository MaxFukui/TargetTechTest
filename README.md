# TargetTechTest

## Respostas

### 1

```
91
```

### 2

> Código (Feito em Python)

```
def isFibonacci(number):
    n1, n2 = 0, 1 
    sequence = [n1, n2]
    next_num = 0
    isNumberFibonacci = False
    while next_num <= number: 
        if (next_num == number): isNumberFibonacci=True
        next_num = n1+n2
        n1 = n2
        n2 = next_num
        sequence.append(next_num)
    mensagem =  str( number ) + " é fibonnaci" if isNumberFibonacci else str(number)+" não é fibonacci"
    print(sequence[:-1])
    print(mensagem)
```

> Saida

```
>>> isFibonacci(65)
[0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55]
65 não é fibonacci
>>> isFibonacci(21)
[0, 1, 1, 2, 3, 5, 8, 13, 21]
21 é fibonnaci
```

### 3

```
# Respostas A) 9
# Respostas B) 128
# Respostas C) 49
# Respostas D) 100
# Respostas E) 13
# Respostas F) 200

```

### 4

Para responder essa pergunta, gostaria de deixar evidente a formulação dela:

> Quando eles se **cruzarem** na rodovia, **qual** estará mais próximo a cidade de Ribeirão Preto?  

Reposta:

> SE AMBOS se cruzaram, Ambos estão no mesmo ponto da estrada, pois eles se encontraram. **Logo, eles possuem a mesma proximidade em relação a Ribeirão preto!**

  
### 5 

> Código (desenvolvido em Python)

```
def reverteString(texto):
    reversedTexto = "";
    for i in  texto[::-1]:
        reversedTexto += i
    return reversedTexto
reverteString("Lorem ipsum")
```

> Saída

```
>>> reverteString("Lorem ipsum")
'muspi meroL'
```