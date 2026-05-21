# Mapeamento de Bugs Encontrados
## Algoritmo 1 — Verificação de Número Par
### Problema encontrado
O algoritmo não validava entradas inválidas e não utilizava corretamente a operação de módulo.

### Erro identificado
```txt
SE numero / 2 = 0
````

### Problema técnico

A divisão não determina corretamente se um número é par.

### Correção sugerida

Utilizar:

```txt
SE numero % 2 = 0
```

---

## Algoritmo 2 — Média de Notas

### Problema encontrado

A variável média não estava sendo calculada corretamente.

### Erro identificado

```txt
media = nota1 + nota2 / 2
```

### Problema técnico

A precedência matemática causa resultado incorreto.

### Correção sugerida

```txt
media = (nota1 + nota2) / 2
```

---

## Algoritmo 3 — Estrutura de Repetição

### Problema encontrado

Loop infinito por ausência de atualização da variável de controle.

### Erro identificado

```txt
ENQUANTO contador < 10
```

### Problema técnico

O contador nunca era incrementado.

### Correção sugerida

```txt
contador = contador + 1
```

````

---

# Algoritmo_Corrigido.md

```md
# Algoritmos Corrigidos e Refatorados

---

## Algoritmo 1 — Número Par ou Ímpar

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

Foi utilizada a operação módulo (%) para verificar corretamente o resto da divisão por 2.

---

## Algoritmo 2 — Média de Notas

```txt
INICIO

Leia nota1
Leia nota2

media = (nota1 + nota2) / 2

Escreva media

FIM
```

### Justificativa Técnica

Foram adicionados parênteses para garantir a prioridade correta das operações matemáticas.

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

Foi corrigido o loop infinito adicionando incremento da variável de controle.