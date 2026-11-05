Atividade em aula de programação para dispositivos móveis- Jetpack Compose

1. O que é entrada em um sistema computacional? Dê dois exemplos.
  R: Entrada em um sistema computacional é qualquer dado, instrução ou informação que é enviado para o computador para ser processado. Ex: Mouse, Teclado
   
2. Qual é a diferença entre processamento e saída?
  R: A diferença essencial entre processamento e saída está na etapa do ciclo de dados: o processamento é o trabalho interno de transformação, enquanto a saída é o resultado final entregue ao usuário.

3. Por que o valor digitado em um TextField é inicialmente tratado como texto?
  R: porque as teclas pressionadas no teclado geram caracteres, e o componente foi projetado para aceitar qualquer tipo de caractere universalmente, seja uma letra, um número ou um símbolo.

4. Qual é a finalidade de remember e mutableStateOf?
   R: Cria um estado que o Compose consegue "observar". Quando o valor dentro dele mud
   
5. O que é um evento? Cite os eventos utilizados nesta aplicação.
    R: um evento é uma ação ou acontecimento gerado pelo usuário ao qual a aplicação pode reagir. Ex: onValueChange, onClick
   
6. O que significa recomposição no Jetpack Compose?
    R: Recomposição é o processo em que o Jetpack Compose executa novamente as funções de interface para atualizar a tela com novos dados.
    
7. Qual é a responsabilidade da MainActivity neste projeto?
    R: a MainActivity tem a responsabilidade de ser a porta de entrada da aplicação no Android e o ponto de partida que inicializa e ancora a interface do usuário.
    
8. Qual é a responsabilidade de CalculadoraDescontoScreen?
    R:  CalculadoraDescontoScreen tem a responsabilidade exclusiva de gerenciar e desenhar a interface do usuário (UI) da tela da calculadora de descontos.
    
9. Por que calcularPrecoComDesconto foi colocada em outro arquivo?
    R: A função calcularPrecoComDesconto foi colocada em outro arquivo para aplicar o princípio de Separação de Responsabilidades
     
10. Qual é a vantagem de uma função de regra de negócio não depender do Compose?
    R: A principal vantagem de uma função de regra de negócio não depender do Compose é o desacoplamento total da lógica em relação à interface gráfica, o que torna o núcleo do seu aplicativo independente de tecnologias de visualização
