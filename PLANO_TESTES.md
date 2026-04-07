# Revisao_Calculadora
teste001: Executar programa pela IDE
entrada: execução do sistema
retorno_esperado: execução para que se possa continuar analise pelo terminal
resultado: Ocorreu fora do esperado. Programa declara erro no caso 2, por falta de do sinal de subtração entre as variaveis.

TESTE POS RESOLUÇÃO DO PRIMEIRO PROBLEMA===

teste001:Testes com valores fora do escolha caso (valores invalidos).
entrada: 5 | a | 1,2
resultado_esperado: Mensagem de erro com orientação.
resultado:Após digitar numero fora do escolha caso o codigo ainda pede para inserir primeiro e segundo valor, so apos isso mostra uma mensagem pouco esclarecedora. Quando a entrada é uma letra o codigo quebra sem avisos, o mesmo ocorre com numeros com virgula.

teste002:Teste com soma.
entrada:0/0 | 1/1  | 1,3/4,2
retorno_esperado:Realizar a soma exata e sem erros com valores que tem virgula.
resultado: ocorreu como o esperado.

teste003:Testes com subtração apos correção do teste001 
entrada:2/1 | 6/7  | 6,2/3,2 |
resultado_esperado:exibir resultado da subtração sem erros e caso houver, orientar usuario.
resultado:Ocorreu como o esperado.

teste004:Teste com multiplicação.
entrada: 2,3/2 | 2/2 | 0/2
resultado_esperado:Exibir resultado da multiplicação sem erros.
resultado:Ocorreu de acordo com o esperado.

teste005:Teste com divisão.
entrada:2/2 | 2,2/3 | 2/0|
resultado_esperado:Exibir valor da divisão e mostrar erro esclarecedor para o usuario ao dividir por zero.
resultado:Ocorreu como esperado.
