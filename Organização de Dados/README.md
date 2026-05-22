# Organização de Dados

## Conjunto de dados: “Alunos da Turma”

### Conjunto base

Turma composta pelos alunos:

* Ana
* Bruno
* Carla
* Diego
* Elisa

---

# 1. Representação em Lista

A lista é a forma mais simples de organizar dados.
Os elementos ficam em sequência.

```txt
[ Ana, Bruno, Carla, Diego, Elisa ]
```

### Teoria aplicada

* Estrutura linear
* Ordem sequencial
* Fácil de armazenar e percorrer
* Cada elemento ocupa uma posição

Exemplo:

| Posição | Aluno |
| ------- | ----- |
| 1       | Ana   |
| 2       | Bruno |
| 3       | Carla |
| 4       | Diego |
| 5       | Elisa |

---

# 2. Representação em Grafo

No grafo, os alunos podem ser ligados por relações.
Exemplo: amizade ou trabalho em grupo.

```txt
Ana ─── Bruno
 │        │
Carla ─ Diego
   \
    Elisa
```

### Teoria aplicada

* Cada aluno é um **nó (vértice)**
* As conexões são **arestas**
* Utilizado para representar relações
* Muito usado em redes sociais, rotas e sistemas de recomendação. Porque claramente tudo hoje precisa virar algoritmo observando seres humanos.

Exemplo de conexões:

* Ana ↔ Bruno
* Ana ↔ Carla
* Bruno ↔ Diego
* Carla ↔ Elisa

---

# 3. Representação Hierárquica

Na hierarquia, existe relação de níveis.

```txt
Turma
├── Grupo 1
│   ├── Ana
│   └── Bruno
├── Grupo 2
│   ├── Carla
│   └── Diego
└── Representante
    └── Elisa
```

### Teoria aplicada

* Estrutura em árvore
* Existe um elemento principal (raiz)
* Os demais ficam subordinados em níveis
* Muito usado em:

  * organogramas
  * pastas do computador
  * bancos de dados
  * estruturas administrativas

---

# Conclusão

O mesmo conjunto de dados pode ser representado de diferentes maneiras dependendo da necessidade:

* **Lista** → organização simples e sequencial
* **Grafo** → representação de relações/conexões
* **Hierarquia** → organização por níveis e dependência
