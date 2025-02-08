# TPC1 - Somador Condicional de Números num Arquivo

Realizado a 2025-02-08

## Autor 

Rodrigo Oliveira Fernandes - A104175


![Captura de ecrã 2024-09-26 201150](https://github.com/user-attachments/assets/9464b39a-cbc8-49dc-af0c-fbd804c439c9)

## Resumo

Este script em Python lê um arquivo de texto e soma os números encontrados nele, respeitando comandos especiais "On" e "Off" para ativar ou desativar a soma. O resultado final e os valores intermediários são gravados em um arquivo `resultado.txt`.

- Soma todos os números encontrados no arquivo, respeitando comandos de ativação/desativação.
- Escreve a soma acumulada até cada caractere `=` e o resultado final no arquivo `resultado.txt`.
- Gera mensagens de erro caso o arquivo não seja encontrado.

O arquivo de entrada pode conter números misturados com texto, além dos comandos:

- **On**: Ativa a soma.
- **Off**: Desativa a soma.
- **=**: Indica um ponto intermediário onde a soma acumulada é registrada.

**Exemplo de arquivo de entrada:**

```
On 10 20 Off 30 On 40 = 50
```

**Saída esperada no **``**:**

```
Soma até '=': 50
Soma final: 90
```

## Teste e Resultado
[Ficheiro de Teste](https://github.com/RodrigoOFernandes/PL2025-A104175/blob/main/TPC1/tester.txt)
[Resultado](https://github.com/RodrigoOFernandes/PL2025-A104175/blob/main/TPC1/resultado.txt)

