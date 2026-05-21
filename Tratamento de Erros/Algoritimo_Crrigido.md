# Algoritmos Corrigidos e Refatorados
---
## Algoritmo 1 — Verificação de Número Par

```txt
INICIO

Leia numero

SE numero % 2 = 0 ENTAO
    Escreva "Número Par"
SENAO
    Escreva "Número Ímpar"
FIMSE

FIM
````

### Justificativa Técnica

Foi utilizada a operação módulo (%) para identificar corretamente se o número é divisível por 2.

---

## Algoritmo 2 — Cálculo da Média

```txt
INICIO

Leia nota1
Leia nota2

media = (nota1 + nota2) / 2

Escreva "Média:", media

FIM
```

### Justificativa Técnica

Os parênteses foram adicionados para garantir a ordem correta das operações matemáticas.

---

## Algoritmo 3 — Estrutura de Repetição

```txt
INICIO

contador = 0

ENQUANTO contador < 10 FACA
    Escreva contador
    contador = contador + 1
FIMENQUANTO

FIM
```

### Justificativa Técnica

Foi corrigido o loop infinito adicionando o incremento da variável de controle.

---

## Algoritmo 4 — Validação de Entrada

```txt
INICIO

Leia idade

SE idade >= 18 ENTAO
    Escreva "Maior de idade"
SENAO
    Escreva "Menor de idade"
FIMSE

FIM
```

### Justificativa Técnica

A estrutura condicional foi organizada para melhorar clareza e legibilidade.