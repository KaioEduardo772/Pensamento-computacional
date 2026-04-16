  # ***ALGORITMO (pseudocódigo) ControleDeAcessoAlunos***
  
      INÍCIO
      
          // Um array com todos os alunos
          lista_oficial ← ["Ana", "Bruno", "Carlos", "Daniela", "Eduardo"]
      
          // Array de alunos esperando para a entrada
          fila ← ["Kaio", "Aldo", "Sarah", "Thiago"]
      
          // Variável de controle para estrutura de repetição
          indice ← 0
          
          ENQUANTO indice < tamanho(fila) FAÇA
      
              aluno ← fila[indice]
      
              ESCREVA "Verificando aluno: ", aluno
      
              // Verificando se os alunos estão na lista oficial
              SE aluno ESTÁ EM lista_oficial ENTÃO
                  ESCREVA "Entrada permitida para ", aluno
              SENÃO
                  ESCREVA "ERRO: ", aluno, " não está na lista. Entrada negada."
              FIMSE
      
              indice ← indice + 1
      
          FIMENQUANTO
      
      FIM
