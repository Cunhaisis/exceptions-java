# exceptions-java

Resumo da Aula

Solução 1 (very bad): lógica de validação no progrma principal.
  ° Lógica de validação não delegada à reserva
  
Solução 2 (bad): método retornando string
  ° A semântica da operação é prejudacada
  ° Retornar string não tem nada a ver com a atualização da reserva
  ° E ser a operação tivesse que retornar String ?
  • Ainda não é possível tratar exceções em construtores
  • Ainda não há auxílio do compilador: o programador deve "lembrar" de verificar se houve
  erro
  • A lógica fica estruturada em condicionais aninhadas
  
Solução 3 (good):  Tratamento de exceções  
