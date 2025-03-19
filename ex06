programa {
  funcao inicio() {

    real numero1, numero2, media, aluno=1, i=0
    cadeia desejo

    enquanto(aluno>0){
      escreva("Digite a primeira nota do aluno: ")
      leia(numero1)
      enquanto(numero1<0 ou numero1>10){
        escreva("Digite um número entre 0 e 10!")
        leia(numero1)
      }



      escreva("Digite a segunda nota do aluno: ")
      leia(numero2)
      enquanto(numero2<0 ou numero2>10){
        escreva("Digite um número entre 0 e 10!")
        leia(numero2)
      }


      media = numero1 + numero2 / 2

      se (media > 9.5){
        escreva("Aluno aprovado!\n")
        i++
      } senao {
        escreva("ALUNO REPROVADISSIMO!!!\n")
      }
      escreva("Calcular a média de outro aluno? Sim/Não?")
      leia(desejo)
      se (desejo=="S"){
        aluno=1
      } senao{
        aluno=0
      }
    }
    escreva("Quantidade de alunos aprovados: ", i)
    }
  }
}
