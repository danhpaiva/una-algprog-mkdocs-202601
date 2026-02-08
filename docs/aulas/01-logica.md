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

Todo programa segue esse fluxo:

-   **Entrada (Input):** dados recebidos\
-   **Processamento:** regras aplicadas\
-   **Saída (Output):** resultado produzido

**Exemplo:**

  Etapa           Exemplo
  --------------- ----------------------
  Entrada         Nota do aluno
  Processamento   Verificar se ≥ 60
  Saída           Aprovado / Reprovado

!!! tip "Mentalidade de Programador" Sempre pergunte: - O que entra? - O
que acontece? - O que deve sair?

------------------------------------------------------------------------

## 🧩 Os Pilares do Pensamento Computacional

=== "1. Decomposição" Dividir um problema complexo em partes menores e
mais gerenciáveis.

=== "2. Reconhecimento de Padrões" Identificar similaridades entre
problemas já resolvidos.

=== "3. Abstração" Focar apenas nos detalhes importantes e ignorar o que
é irrelevante.

=== "4. Algoritmos" Criar o passo a passo definitivo (a receita) para
resolver o problema.

------------------------------------------------------------------------

## 🧠 Pensamento Algorítmico Incremental

Construa algoritmos passo a passo:

1.  Resolver manualmente
2.  Escrever em linguagem natural
3.  Transformar em pseudocódigo
4.  Testar com exemplos
5.  Melhorar

------------------------------------------------------------------------

## 🔎 Teste de Mesa (Simulação)

Antes de executar, simule o algoritmo manualmente.

  idade   Resultado
  ------- -----------
  10      Negado
  18      Permitido
  30      Permitido

------------------------------------------------------------------------

## 🤖 Desafio Prático: O Algoritmo do "Mestre Cuca"

**Humano:** "Frite um ovo."

**Computador (Algoritmo):** 1. Pegue a frigideira. 2. Coloque no fogão.
3. Acenda o fogo. 4. Adicione óleo. 5. Se o óleo estiver quente → quebre
o ovo. 6. Senão → espere e repita.

!!! question "Reflexão" - E se não houver óleo? - E se o fogo estiver
alto demais? - E se o ovo estiver estragado?

------------------------------------------------------------------------

## 🛠️ Experimentando com Pseudocódigo

    Algoritmo "Verificador_de_Idade"
    Var
       idade: inteiro
    Inicio
       Escreva("Digite sua idade: ")
       Leia(idade)
       
       Se (idade >= 18) entao
          Escreva("Acesso permitido")
       Senao
          Escreva("Acesso negado")
       FimSe
    FimAlgoritmo

------------------------------------------------------------------------

## ⚠️ Erros Comuns de Lógica

-   Loop infinito
-   Condição invertida
-   Esquecer entrada de dados
-   Não tratar casos extremos
-   Pensar como humano, não como máquina

------------------------------------------------------------------------

## 📝 Atividades

### Exercício 1 --- Travessia do Fazendeiro

Escreva o algoritmo para atravessar:

-   Lobo
-   Cabra
-   Couve

Sem que um coma o outro.

------------------------------------------------------------------------

### Exercício 2 --- Semáforo

Crie um algoritmo:

-   Verde → atravessar\
-   Amarelo → esperar\
-   Vermelho → parar

------------------------------------------------------------------------

### Exercício 3 --- Par ou Ímpar

Entrada: número inteiro\
Saída: "Par" ou "Ímpar"

------------------------------------------------------------------------

### Exercício 4 --- Soma até N

Entrada: número N\
Saída: soma de 1 até N

Exemplo: N=5 → 15

------------------------------------------------------------------------

## 💻 Onde isso aparece na programação?

-   `if` → decisões\
-   `while` → repetição\
-   Variáveis → memória\
-   Funções → decomposição\
-   Classes → abstração

------------------------------------------------------------------------

## 🧠 Desafio Final

**Instrução:** "Arrume seu quarto"

Liste os passos extremamente detalhados como um algoritmo.

------------------------------------------------------------------------

!!! tip "Próxima Aula" Variáveis e Tipos de Dados
