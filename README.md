# Constru-aoDeAlgoritmos

programa {

  inclua biblioteca Util --> u
  funcao prepararCafe() {

    escreva("Passo 1: Colocar a agua para ferver...\n")
     u.aguarde(700)
    escreva("Passo 2: Aguarndando a água ferve...\n")
     u.aguarde(1700)
    escreva("Passo 3: Coloque o café...\n")
     u.aguarde(1700)
    escreva("Passo 4: Coando café...\n")
     u.aguarde(3000)
    escreva("Passo 5: Café pronto! Aproveite\n")
  }

  funcao aguarde(){
    escreva("...\n")
  }

  funcao inicio(){

    inteiro temPoCafe, temAgua, temFogo, temCoador, temBule


    escreva("Voce tem pó de cafe? (1 para sim / 0 para não): ")
    leia(temPoCafe)

     escreva("Voce tem água? (1 para sim / 0 para não): ")
    leia(temAgua)

     escreva("Voce tem Fogao? (1 para sim / 0 para não): ")
    leia(temFogo)

     escreva("Voce tem coador? (1 para sim / 0 para não): ")
    leia(temCoador)

     escreva("Voce tem bule? (1 para sim / 0 para não): ")
    leia(temBule)

    escreva("...\n")

    se(temPoCafe == 1 e temAgua == 1 e temFogo == 1 e temCoador == 1 e temBule == 1)

    {
      prepararCafe()
    } senao {
      escreva("Nao foi possivel fazer cafe pois faltam alguns intens!...\n")
    }

  }
}
