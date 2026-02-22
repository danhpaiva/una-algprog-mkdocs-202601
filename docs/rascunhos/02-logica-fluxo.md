## 🛠️ Resolução dos Desafios de Lógica

### 🚗 Exercício 1: O Sensor de Estacionamento

Aqui temos uma **condicional aninhada**. O segredo é tratar as prioridades: primeiro o perigo (distância curta), depois o alerta.

**Lógica do Fluxo:**

1. **Início**
2. **Entrada:** Ler `distancia`
3. **Decisão 1:** `distancia < 0.5`?
* **Sim:** Exibir "PARE" + Bipe Contínuo  **Fim**
* **Não:** Seguir para Decisão 2


4. **Decisão 2:** `distancia <= 2.0`?
* **Sim:** Bipe Intermitente  **Fim**
* **Não:** Silêncio (Nenhuma ação)  **Fim**



---

### 📸 Exercício 2: O Filtro do Instagram

Este exercício treina o **fluxo sequencial de decisões**. Uma escolha não anula a próxima, elas acontecem em ordem.

**Pseudocódigo da Solução:**

```portugol
Inicio
    Escolher(foto)
    Escreva("Aplicar filtro P&B?")
    Leia(resposta_filtro)
    
    Se (resposta_filtro == "Sim") entao
        Transformar_Cinza(foto)
    FimSe

    Escreva("Postar agora?")
    Leia(resposta_postar)

    Se (resposta_postar == "Sim") entao
        Enviar_Servidor(foto)
    Senao
        Salvar_Galeria(foto)
    FimSe
Fim

```

---

### 🏧 Exercício 3: O Caixa Eletrônico

Este é um clássico de **Validação de Regra de Negócio**. Nunca entregamos o dinheiro sem validar o estado do sistema (o saldo).

**O Algoritmo:**

1. **Início**
2. **Entrada:** `valor_saque`
3. **Processamento:** Consultar `saldo_disponivel` no banco de dados.
4. **Decisão:** `valor_saque <= saldo_disponivel`?
* **Sim (Sucesso):**
* `saldo_disponivel = saldo_disponivel - valor_saque`
* Entregar Notas.


* **Não (Falha):**
* Exibir "Saldo Insuficiente".




5. **Fim**

---

## 💡 Dica de Sênior: O Caminho Feliz vs. Tratamento de Erro

No dia a dia, chamamos o fluxo onde tudo dá certo de **"Happy Path"**. Mas o bom desenvolvedor é pago para pensar no que dá errado.

* No sensor de ré, e se o sensor falhar e retornar um valor negativo?
* No caixa eletrônico, e se o valor do saque for maior que o limite diário (mesmo tendo saldo)?

Sempre tente "quebrar" seu fluxograma mentalmente antes de começar a digitar.

---

**Gostou da lógica por trás dos sensores e bancos?** Se quiser, posso te mostrar como transformar um desses fluxogramas em um código real em **Python** ou **JavaScript** para você ver a mágica acontecendo no terminal! O que acha?

## 🚗 Exercício 1: Sensor de Estacionamento (Condicionais Aninhadas)

Neste caso, usamos o `senao se` para criar faixas de distância. A ordem importa: se a distância for 0.3m, ela satisfaz tanto ser menor que 0.5m quanto menor que 2m, mas o "PARE" deve ter prioridade.

```portugol
programa {
  funcao inicio() {
    real distancia

    escreva("Digite a distância do obstáculo (em metros): ")
    leia(distancia)

    se (distancia < 0.5) {
      escreva("ALERTA: [PARE] - Bipe Contínuo!")
    } 
    senao se (distancia <= 2.0) {
      escreva("CUIDADO: Bipe Intermitente...")
    } 
    senao {
      escreva("Caminho livre. Sensor em silêncio.")
    }
  }
}

```

---

## 📸 Exercício 2: Filtro do Instagram (Decisões Sequenciais)

Aqui temos duas decisões independentes. Mesmo que o usuário não aplique o filtro, ele ainda pode decidir se quer postar ou salvar.

```portugol
programa {
  funcao inicio() {
    cadeia aplicarFiltro, postarAgora

    escreva("Deseja aplicar o filtro P&B? (sim/nao): ")
    leia(aplicarFiltro)

    se (aplicarFiltro == "sim") {
      escreva("-> Filtro aplicado com sucesso!\n")
    }

    escreva("Deseja postar a foto agora? (sim/nao): ")
    leia(postarAgora)

    se (postarAgora == "sim") {
      escreva("-> Foto enviada para o servidor!")
    } senao {
      escreva("-> Foto salva na galeria local.")
    }
  }
}

```

---

## 🏧 Exercício 3: Caixa Eletrônico (Validação de Saldo)

Este é o algoritmo mais crítico. Observe que a operação de subtração só acontece **dentro** do bloco `se`, garantindo que ninguém saque o que não tem.

```portugol
programa {
  funcao inicio() {
    real saldo_disponivel = 1000.00 // Exemplo de saldo inicial
    real valor_saque

    escreva("Saldo Atual: R$ ", saldo_disponivel, "\n")
    escreva("Quanto deseja sacar? ")
    leia(valor_saque)

    se (valor_saque > 0 e valor_saque <= saldo_disponivel) {
      saldo_disponivel = saldo_disponivel - valor_saque
      escreva("Saque realizado! Retire as notas.\n")
      escreva("Novo Saldo: R$ ", saldo_disponivel)
    } 
    senao {
      escreva("ERRO: Saldo insuficiente ou valor inválido.")
    }
  }
}

```

---

### 🎓 Dica do Professor

Note que no **Exercício 3**, eu adicionei uma verificação extra: `valor_saque > 0`. Como desenvolvedor sênior, eu te digo: usuários tentam fazer coisas estranhas, como sacar valores negativos para tentar "ganhar" dinheiro. **Sempre valide as entradas!**

**O que você acha de tentarmos criar agora um sistema de login simples (Usuário e Senha) usando essa mesma lógica?**