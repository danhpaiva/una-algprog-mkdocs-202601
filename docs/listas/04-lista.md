# 🚀 Missão: A Arte da Decisão (Estruturas Condicionais)

Dominar o `if/else` é o que permite criar sistemas de segurança, filtros de crédito e inteligências artificiais. No nível sênior, **evitamos condições aninhadas desnecessárias (o famoso "código espaguete")** e focamos em uma lógica clara e direta.

---

## 🛠️ O Algoritmo da Entrega: Versão 4.0

Siga estes passos para documentar sua evolução em **Estruturas de Controle**:

### 1. Codificar com Lógica

Resolva a lista abaixo. O foco aqui não é apenas o cálculo, mas **qual caminho o código deve seguir** dependendo da entrada do usuário.

### 2. Organizar o Repositório

No seu GitHub, crie a pasta:
`una-algprog-lista04`

### 3. Documentação (O Diferencial)

No seu `README.md`, descreva o que é um **Operador Lógico** (E, OU, NÃO) e como eles ajudam a criar condições mais complexas em um único `if`.

---

## 📝 Lista de Exercícios de Fixação: Estruturas Condicionais

??? abstract "Exercício 1: Validador de Maioridade"
**Contexto:** Um site de jogos precisa restringir o acesso de menores de idade.
**Tarefa:** Leia o ano de nascimento do usuário e o ano atual. Calcule a idade. Se a idade for maior ou igual a 18, exiba `"Acesso Permitido"`. Caso contrário, exiba `"Acesso Negado: Usuário menor de idade"`.

??? abstract "Exercício 2: O Radar de Velocidade"
**Contexto:** A prefeitura quer automatizar as multas em uma avenida de 80km/h.
**Tarefa:** Leia a velocidade de um carro. Se a velocidade for superior a 80, calcule a multa (R$ 7,00 por cada km acima do limite) e exiba o valor. Se estiver no limite, exiba `"Boa viagem!"`.

??? abstract "Exercício 3: Sistema de Aprovação Escolar"
**Contexto:** Uma escola precisa decidir se o aluno passou de ano.
**Tarefa:** Leia duas notas e calcule a média simples.
- Se a média for 7.0 ou superior: `"Aprovado"`.
- Se a média estiver entre 5.0 e 6.9: `"Recuperação"`.
- Se a média for menor que 5.0: `"Reprovado"`.

??? abstract "Exercício 4: Par ou Ímpar?"
**Contexto:** Um jogo de sorteio precisa identificar a natureza do número.
**Tarefa:** Leia um número inteiro e informe se ele é **PAR** ou **ÍMPAR**.
**Dica:** Utilize o operador de resto da divisão `%`. Se `numero % 2 == 0`, ele é par.

??? abstract "Exercício 5: Analisador de Triângulos"
**Contexto:** Um software de engenharia precisa classificar estruturas.
**Tarefa:** Leia três valores (lados de um triângulo). Primeiro, verifique se eles podem formar um triângulo (a soma de dois lados deve ser sempre maior que o terceiro). Se sim, classifique em:
- **Equilátero:** Todos os lados iguais.
- **Isósceles:** Dois lados iguais.
- **Escaleno:** Todos os lados diferentes.

---

## 📂 Estrutura Sugerida do Repositório

```text
una-algprog-lista04/
├── README.md
└── algoritmos/
    ├── 01_validador_idade.por
    ├── 02_radar_velocidade.por
    ├── 03_sistema_notas.por
    ├── 04_par_impar.por
    └── 05_classificador_triangulos.por

```

---

## ⚠️ Checklist de Qualidade

!!! check "Critérios de Aceite"
- [ ] Você utilizou o `senao se` (else if) para evitar múltiplos `if` soltos no Exercício 3 e 5?
- [ ] As mensagens de saída são claras e amigáveis para o usuário?
- [ ] No Exercício 5, você validou a existência do triângulo antes de classificá-lo? (Isso se chama **Fail Fast** e é uma prática sênior).
- [ ] O código está indentado corretamente (organizado visualmente)?

---

!!! info "Dica de Sênior"
Cuidado com o "código redundante". Se você já testou se um número é maior que 10 em um `if`, você não precisa testar se ele é menor ou igual a 10 no `else` — o computador já sabe disso por exclusão! Economize processamento e neurônios.

**Gostaria que eu resolvesse um desses exercícios passo a passo com você para explicar a lógica do Portugol?**