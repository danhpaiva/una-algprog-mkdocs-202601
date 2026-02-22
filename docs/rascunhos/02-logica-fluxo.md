Com certeza! Como seu mentor, vou refinar as soluções. Escrever em **Portugol** é o passo ideal antes de pularmos para linguagens como Python ou Java, pois foca 100% na **lógica** e 0% em sintaxe complexa.

Aqui estão os algoritmos estruturados para você testar diretamente no editor:

---

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