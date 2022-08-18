# Lógica de  programação

##### Lógica de programação é a organização coesa de uma sequência de instruções voltadas à resolução de um problema, ou à criação de um software ou aplicação. Cada linguagem tem suas próprias particularidades, como sua sintaxe, seus tipos de dados e sua orientação, mas a lógica por trás de todas é a mesma.

![Tela de computador com texto preto sobre fundo branco  Descrição gerada automaticamente](https://lh5.googleusercontent.com/ZrB4I025xzt4YpmiaWFdA3EtURfUEGKg0UH_C6Cy2rN8JAW4p1g9DpvP1NwfGYyCJAzed58ulSgtO9hrt8SoJiQlzrk2FkwPjIZVbTXKLVm2TvR4G38KpfkNUzjDqjOPIPohe03QQ40O6ag)



##### A lógica de programação é importante porque é ela quem nos dá as ferramentas necessárias para executar o processo mais básico no desenvolvimento de alguma aplicação: a criação de seu **algoritmo**.

## **Algoritmo**

##### De acordo com o dicionário, é um processo de cálculo que, por meio de **uma sequência finita** de operações, aplicada a um número finito de dados, **leva à resolução de problemas**.

![Forma  Descrição gerada automaticamente](https://lh4.googleusercontent.com/omRPgMz_jpEH8a8qaPzqU8C6R30QcZkhJR6ZUHckfiDUD-FICmRKikHcy_5ieTht2g4nAAom9cK7wnrB-YVXrGJkGoQF4m3yFS0-ANODPju7_gbtqGm-JYkrESc2AbCgNkIhX4zYVssCdOU)



##### Vamos tomar como exemplo o café que tomamos de manhã.

##### Quando perguntam como tomamos nosso café, a maioria de nós responde que, ao acordarmos, preparamos o café com auxílio de uma cafeteira elétrica, colocamos ele em uma caneca e o tomamos. Mas, ao destrinchar este processo, somos capazes de estipular uma sequência de passos que nos levaram ao ato final de beber este café. 

Esta sequência pode ser:

1. Ao acordar, levanto da cama;
2. Após levantar da cama, desço as escadas;
3. Após descer as escadas, entro na cozinha;
4. Após entrar na cozinha, pego o pó de café no armário;
5. Após pegar o pó de café, o coloco dentro da cafeteira;
6. Após colocar o pó na cafeteira, jogo água no compartimento específico;
7. Após inserir todos os ingredientes na máquina, aperto o botão de ligar;
8. Quando o café está pronto, pego a garrafa;
9. Após pegar a garrafa, despeje o café dentro de uma caneca;
10. Após colocar o café na caneca, bebo o café.

**Um algoritmo deve ser:**

| Completo            | Todas as ações precisam ser descritas e devem ser únicas.    |
| ------------------- | ------------------------------------------------------------ |
| **Sem redundância** | **Um conjunto de instruções só pode ter uma única forma de ser interpretada.** |
| **Determinístico**  | **Se as instruções forem executadas, o resultado esperado será sempre atingido.** |
| **Finito**          | **As instruções precisam terminar após um número limitado de passos.** |

Podemos dividir um algoritmo em três fases fundamentais: **entrada, processamento e saída**.

**Entrada** recebe as informações necessárias para iniciar nosso algoritmo;
**Processamento** são os procedimentos utilizados para chegar ao resultado final.
**Saída** é o resultado esperado da fase de processamento, dados já processados. 

| Formas mais conhecidas de representação          |
| ------------------------------------------------ |
| Descrição narrativa                              |
| Fluxograma                                       |
| Pseudocódigo (Linguagem estruturada ou Portugol) |

  **FLUXOGRAMA**

Um fluxograma é a representação gráfica de um procedimento, problema ou sistema, cujas etapas ou módulos são ilustrados de forma encadeada por meio de símbolos geométricos interconectados.

![image-20220818185340804](C:\Users\LENOVO\AppData\Roaming\Typora\typora-user-images\image-20220818185340804.png)

![Tabela  Descrição gerada automaticamente](https://lh5.googleusercontent.com/fbOmheUHqOoid7gXvupdxY79i9hhfPXJe5vl0yOZQfgieYIAtFJc0S0X9sXK8kTdeCa7TghAoU3zr_JU96h4u-gX4u_da-hWbMnX5_gEvaB4pc9eK0pDDiJ4gRWdqL3FZkGXWc8vzG0feaA)

#### **Algoritmo troca de lâmpada** 

![img](https://lh6.googleusercontent.com/4SI-lmm-GPohvUP22EcZBvnV1LNh_MDqd83TTPCvXasIXgUgDpDN1_C7-cmGOc8EdfH-BoxLTxB1IGl5rMvYtBBfiNZbKhk2A0CmcBFHGtRu8TaTTpsrVXhZ_VUsI_qSeZvQFiB5dmQkiN0)

#### **Pseudocódigo**

É rico em detalhes, como a definição dos tipos das variáveis usadas no algoritmo. 

![Tela de celular com texto preto sobre fundo branco  Descrição gerada automaticamente](https://lh6.googleusercontent.com/9fHPTo9kwvUnSN8pOVZRaj3ed-cJh3nXJPN5S2rWbxKb5-j4IkON5ffoIZjU5M2h6V1EC_Dp3ADX8y_1H1aWb24RQr7Yu78aWi9ec9F2ODOJ4qOKntPJC73yt7AUsyyQdtcGpP4UT_Ufegc)

#### **Pseudocódigo**

![Tabela  Descrição gerada automaticamente](https://lh4.googleusercontent.com/Rpc79vsBqEl0VMSjdp8FyLveTf32hwSRBDGxJZl3WGkjBo1YLK_nSen_L_OLjlTKx5YMi0lkvI4tVoJBWO9U5-ydjSn3mBjMY9lp2J_EZMdV_rP40OJJqyznb83bnTyPqnKkzc0QkCEPqVk)

#### Exemplo: 

Cálculo da média de um aluno: 
Algoritmo Calculo_Media
Var Nota1, Nota2, MEDIA: real; Início Leia Nota1, Nota2;
MEDIA ← (Nota1 + Nota2) / 2; 
Se MEDIA >= 7 então Escreva “Aprovado”; Senão 
Escreva “Reprovado”; Fim_se 
Fim Exemplo: - Cálculo da média de um aluno: 
Algoritmo Calculo_Media
Var Nota1, Nota2, MEDIA: real; Início Leia Nota1, Nota2;
MEDIA ← (Nota1 + Nota2) / 2; 
Se MEDIA >= 7 então Escreva “Aprovado”; Senão 
Escreva “Reprovado”; Fim_se 
Fim 

![Uma imagem contendo Tabela  Descrição gerada automaticamente](https://lh4.googleusercontent.com/HY_YP5U4GhRNwS5O4lhTd4wTp3h87KKQGU3sqVPzJ101ty79gb0yzxqfUsDTxDm4WGgAdMPCbzfl8yaoIm8sRq-TK0P3cy7cxl3E-xPB9FIWJXySlcZx97Wq6C6a6C-wvHpgKyuqI_iK8_M)



#### **Atividade em Grupo**

1- Faça um algoritmo que mostre o passo a passo para passear com seu animal de estimação.
2- Faça um algoritmo que mostre o passo a passo para trocar uma lâmpada. 
3- Faça um algoritmo que mostre o passo a passo para lavar um copo.
4- Faça um algoritmo que mostre o passo a passo para postar uma foto em uma rede social
5- Faça um algoritmo que mostre o passo a passo para acessar um computador.
6- Faça um algoritmo que mostre o passo a passo para fazer um bolo.
