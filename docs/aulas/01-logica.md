# 🧠 Aula 01: O Pensamento Computacional

Bem-vindos à base de tudo! Antes de digitarmos uma única linha de
código, precisamos aprender a "ensinar" uma máquina a pensar. Spoiler:
máquinas são muito rápidas, mas incrivelmente literais (e um pouco
burras).

------------------------------------------------------------------------

## 🧐 O que é Lógica de Programação?

A lógica de programação é a organização coerente de uma sequência de
passos para atingir um objetivo. No ensino superior, não queremos apenas
que você decore comandos, mas que desenvolva a habilidade de **decompor
problemas complexos**.

!!! quote "Pensamento do Dia" "Programar não é sobre o que você sabe; é
sobre o que você consegue descobrir." --- Chris Pine

------------------------------------------------------------------------

## 🔄 Entrada → Processamento → Saída (IPO)

=== "Entrada" Dados recebidos pelo programa.

=== "Processamento" Regras e decisões aplicadas.

=== "Saída" Resultado final produzido.

!!! example "Exemplo Prático" Entrada: Nota do aluno\
Processamento: Verificar se ≥ 60\
Saída: Aprovado / Reprovado

!!! tip "Mentalidade de Programador" Sempre pergunte: - O que entra? - O
que acontece? - O que deve sair?

------------------------------------------------------------------------

## 🧩 Os Pilares do Pensamento Computacional

=== "1. Decomposição" Dividir um problema complexo em partes menores e
mais gerenciáveis.\
*Exemplo: Fazer café → moer, esquentar água, filtrar.*

=== "2. Reconhecimento de Padrões" Identificar similaridades entre
problemas já resolvidos.\
*Exemplo: Validar CPF é parecido com validar CNPJ.*

=== "3. Abstração" Focar apenas no que importa.\
*Exemplo: GPS precisa da localização, não da cor do carro.*

=== "4. Algoritmos" Criar o passo a passo definitivo (a receita).

------------------------------------------------------------------------

## 🤖 Desafio Prático: O Algoritmo do "Mestre Cuca"

!!! example "Instrução Humana vs. Instrução Computacional" **Humano:**
"Frite um ovo."

    **Computador (Algoritmo):**
    1. Pegue a frigideira no armário.
    2. Coloque a frigideira no fogão.
    3. Acenda o fogo.
    4. Adicione uma colher de óleo.
    5. **Se** o óleo estiver quente:
        - Quebre o ovo na frigideira.
    6. **Senão**:
        - Espere 30 segundos e volte ao passo 5.

!!! question "Reflexão Computacional" - E se não houver óleo? - E se o
fogo estiver alto demais? - E se o ovo estiver estragado?

------------------------------------------------------------------------

## 🧠 Pensamento Algorítmico Incremental

1.  Resolver manualmente\
2.  Escrever em linguagem natural\
3.  Transformar em pseudocódigo\
4.  Testar com exemplos\
5.  Melhorar

!!! tip "Dica de Ouro" Bons programadores escrevem **algoritmos antes do
código**.

------------------------------------------------------------------------

## 🔎 Teste de Mesa (Simulação)

Simule o algoritmo manualmente antes de executar.

  idade   Resultado
  ------- -----------
  10      Negado
  18      Permitido
  30      Permitido

------------------------------------------------------------------------

## 🛠️ Experimentando com Pseudocódigo

``` portugol
Algoritmo "Verificador_de_Idade"
Var
   idade: inteiro
Inicio
   Escreva("Digite sua idade: ")
   Leia(idade)
   
   Se (idade >= 18) entao
      Escreva("Acesso permitido: Você é maior de idade.")
   Senao
      Escreva("Acesso negado: Conteúdo restrito.")
   FimSe
FimAlgoritmo
```

------------------------------------------------------------------------

## ⚠️ Erros Comuns de Lógica

!!! danger "Cuidado com o Loop Infinito" Esquecer condição de parada faz
o programa travar.

Outros erros comuns: - Condição invertida\
- Variável não inicializada\
- Esquecer entrada de dados\
- Não tratar casos extremos\
- Pensar como humano, não como máquina

------------------------------------------------------------------------

## 📝 Atividade de Fixação

??? abstract "Exercício 1 --- Travessia do Fazendeiro" Um fazendeiro
precisa levar um lobo, uma cabra e uma couve para o outro lado do rio.

    **Regras:**
    - Lobo + Cabra → cabra é comida  
    - Cabra + Couve → couve é comida  

    **Tarefa:** Escreva o algoritmo completo da travessia.

??? abstract "Exercício 2 --- Semáforo" Crie um algoritmo:

    - Verde → atravessar  
    - Amarelo → esperar  
    - Vermelho → parar  

??? abstract "Exercício 3 --- Par ou Ímpar" Entrada: número inteiro\
Saída: "Par" ou "Ímpar"

??? abstract "Exercício 4 --- Soma até N" Entrada: número N\
Saída: soma de 1 até N

    Exemplo: N = 5 → 15

------------------------------------------------------------------------

## 💻 Onde isso aparece na programação?

=== "Decisão" `if`, `else`, `switch`

=== "Repetição" `while`, `for`

=== "Memória" Variáveis

=== "Organização" Funções e Métodos

=== "Abstração" Classes e Objetos

------------------------------------------------------------------------

## 🧠 Desafio Final

!!! example "Pense como um computador" **Instrução:** "Arrume seu
quarto"

    Liste passos extremamente detalhados como um algoritmo.

------------------------------------------------------------------------

!!! tip "Próxima Aula" Na próxima aula veremos **Variáveis e Tipos de
Dados**.
