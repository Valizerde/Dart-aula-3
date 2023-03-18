# Dart-aula-3

void main() {
  int idade = 18;
  
  if (idade >= 18) { //se
    print("Pode entrar na baladinha");
  } else { //senão
    print("Infelizmente precisa ter ao menos 18 para entrar");
  }
  
  print(1 == 2); //verrificar se é exatamente igual: false
  print(1 < 2);  //true
  print(1 <= 2); //true pois é menor OU igual
  print(2 < 2);  //false
  print(2 <= 2); //true
  print(3 > 4);  //false
  print(2 >= 1); //true
  print(3 != 4); //true
  
 
  /*
   * Pensando em um sistema de notas, onde o aluno aprova com nota >= 6,
   * mas se não tirar isso, realiza uma DP a qual ele precisa tirar ao 
   * menos 7 para passar!
   * O aluno só pode fazer a DP se a nota for >= 3.5
   * */
  
  double nota = 6;
  double dp = 8;
  
  if (nota >= 6) {
    print("Aprovado mizeravi!");
  } else if(nota >= 3.5 && dp >= 7) {
    print("Aprovado com a nota da DP!");
  } else if (nota >= 3.5) {
    print("reprovado com DP!");
  } else {
    print("Reprovado!");
  }
  
  
  bool fumante = false;
  if (fumante) {
    print("O cara fuma!");
  } else {
    print("O cara não fuma!");
  }
  
  //ternário
  // (condição booleana) ? <Valor se verdadeiro> : <valor se falso>
  
  print(fumante ? "Fuma muito!" : "Não fuma!");
  
}
