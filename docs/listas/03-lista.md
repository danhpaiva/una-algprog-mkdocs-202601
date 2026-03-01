# 🚀 Missão: O Poder dos Dados e Operadores

Excelente! Você já aprendeu que variáveis são os recipientes da nossa lógica e que os operadores são as ferramentas que transformam dados brutos em informação útil. No desenvolvimento sênior, **código limpo e cálculos precisos separam os amadores dos profissionais.**

Agora, vamos consolidar esse conhecimento transformando esses conceitos em código real no seu portfólio.

---

## 🛠️ O Algoritmo da Entrega: Versão 3.0

Siga estes passos para documentar sua evolução em **Variáveis e Operadores Matemáticos**:

### 1. Codificar com Precisão

Resolva a lista de exercícios abaixo utilizando o **Portugol Studio** ou qualquer editor de texto (como VS Code). Lembre-se de comentar seu código explicando o que cada variável armazena.

### 2. Organizar o Repositório

No seu GitHub, crie um novo repositório (ou uma pasta dentro do anterior) com o nome:
`una-algprog-lista03`

### 3. Documentação (O Diferencial)

No seu `README.md`, explique brevemente a importância de escolher o **tipo de dado correto** (Inteiro vs. Real) para evitar erros de arredondamento em sistemas financeiros ou científicos.

---

## 📝 Lista de Exercícios de Fixação

Abaixo, os desafios para testar sua lógica matemática:

??? abstract "Exercício 1: O Fechamento do Caixa"
**Contexto:** Um pequeno mercado precisa automatizar o caixa.
**Tarefa:** Crie um algoritmo que leia o nome de um produto, o seu preço unitário e a quantidade comprada. Calcule o valor total e exiba uma frase: `"O produto [nome] custou total de R$ [valor_total]"`.

??? abstract "Exercício 2: Conversor de Temperatura (Fahrenheit)"
**Contexto:** Você está trabalhando em um software para uma estação meteorológica americana.
**Tarefa:** Leia uma temperatura em graus **Celsius** e converta para **Fahrenheit**.
**Fórmula:** $F = (C \cdot 1.8) + 32$

??? abstract "Exercício 3: Média Ponderada"
**Contexto:** Uma faculdade utiliza pesos diferentes para as provas: Prova A (peso 4) e Prova B (peso 6).
**Tarefa:** Leia as duas notas do aluno e calcule a média ponderada.
**Dica:** $Média = \frac{(NotaA \cdot 4) + (NotaB \cdot 6)}{10}$

??? abstract "Exercício 4: O Consumo do Automóvel"
**Contexto:** Um app de caronas precisa calcular o gasto de combustível.
**Tarefa:** Leia a distância total percorrida (km) e o total de combustível gasto (litros). Calcule e exiba o consumo médio do carro (km/l).

??? abstract "Exercício 5: Cálculo de Desconto Profissional"
**Contexto:** Um e-commerce quer aplicar descontos em feriados.
**Tarefa:** Leia o valor original de um produto e o percentual de desconto (ex: 15). O programa deve calcular o valor do desconto em reais e o novo preço final com o desconto aplicado.

---

## 📂 Estrutura Sugerida do Repositório

Mantenha o padrão profissional que o mercado exige:

```text
una-algprog-lista03/
├── README.md
└── algoritmos/
    ├── 01_fechamento_caixa.por
    ├── 02_conversor_temp.por
    ├── 03_media_ponderada.por
    ├── 04_consumo_carro.por
    └── 05_calculo_desconto.por

```

---

## ⚠️ Checklist de Qualidade

!!! check "Critérios de Aceite"
- [ ] As variáveis possuem nomes significativos (ex: `preco_final` em vez de `pf`)?
- [ ] O algoritmo do Exercício 2 usa o tipo **Real** para as temperaturas?
- [ ] A precedência matemática (parênteses) foi aplicada corretamente no cálculo da média e do desconto?
- [ ] O `README.md` contém seu nome e uma breve descrição da lista?

---

!!! info "Dica de Sênior"
Tente prever erros de entrada! 
Por exemplo, o que acontece se o usuário digitar uma letra onde deveria ser um número? 
No Portugol ainda não tratamos isso, mas já comece a pensar como um **QA (Quality Assurance)**.