```markdown
# 🧠 Aula 01: O Pensamento Computacional

Bem-vindos à base de tudo! Antes de digitarmos uma única linha de código, precisamos aprender a "ensinar" uma máquina a pensar. Spoiler: máquinas são muito rápidas, mas incrivelmente literais (e um pouco burras).

---

## 🧐 O que é Lógica de Programação?

A lógica de programação é a organização coerente de uma sequência de passos para atingir um objetivo. No ensino superior, não queremos apenas que você decore comandos, mas que desenvolva a habilidade de **decompor problemas complexos**.

!!! quote "Pensamento do Dia"
    "Programar não é sobre o que você sabe; é sobre o que você consegue descobrir." — Chris Pine

---

## 🧩 Os Pilares do Pensamento Computacional

Para resolver qualquer problema na nossa área, usamos quatro pilares:

=== "1. Decomposição"
    Dividir um problema complexo em partes menores e mais gerenciáveis.
    *Exemplo: Para fazer um café, você precisa moer o grão, esquentar a água, filtrar, etc.*

=== "2. Reconhecimento de Padrões"
    Identificar similaridades entre problemas já resolvidos.
    *Exemplo: O processo de validar um CPF é muito parecido com o de validar um CNPJ.*

=== "3. Abstração"
    Focar apenas nos detalhes importantes e ignorar o que é irrelevante.
    *Exemplo: Para um GPS, não importa a cor do seu carro, apenas a sua coordenada.*

=== "4. Algoritmos"
    Criar o passo a passo definitivo (a receita) para resolver o problema.

---

## 🤖 Desafio Prático: O Algoritmo do "Mestre Cuca"

Vamos analisar como um computador interpretaria uma instrução simples.

!!! example "Instrução Humana vs. Instrução Computacional"
    **Humano:** "Frite um ovo."
    
    **Computador (Algoritmo):**
    1. Pegue a frigideira no armário.
    2. Coloque a frigideira no fogão.
    3. Acenda o fogo.
    4. Adicione uma colher de óleo.
    5. **Se** o óleo estiver quente:
        * Quebre o ovo na frigideira.
    6. **Senão**:
        * Espere 30 segundos e volte ao passo 5.



---

## 🛠️ Experimentando com Pseudocódigo

Abaixo está um exemplo de como estruturamos essa lógica usando uma linguagem "quase humana" (Portugol):

~~~portugol
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

---

## ⚠️ Erros Comuns de Lógica

!!! danger "Cuidado com o Loop Infinito"
Um erro clássico é esquecer de dar uma condição de parada para o computador.
*Exemplo: "Ande para frente enquanto não bater na parede", mas você está em um campo aberto.*

---

## 📝 Atividade de Fixação

??? abstract "Exercício: O Desafio da Travessia"
Um fazendeiro precisa levar um lobo, uma cabra e um maço de couve para o outro lado do rio. 
Ele tem um barco que só permite levar ele e mais um item.

```
**Regras:**
- Se o lobo ficar sozinho com a cabra, ele a come.
- Se a cabra ficar sozinha com a couve, ela a come.

**Tarefa:** Escreva no seu caderno o passo a passo (algoritmo) para atravessar todos em segurança.

```

---

!!! tip "Próximos Passos"
Na próxima aula, transformaremos essa lógica em **Variáveis e Tipos de Dados**. Não esqueça de revisar este material!

```