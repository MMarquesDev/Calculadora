# Sistema de Cálculo de Salários

Este é um script Python simples que calcula os salários de uma equipe de vendas, composta por Emily, Larissa, Rafael, Milena e a gerente Jéssica, com base nos valores de vendas realizadas por cada vendedor.

## Variáveis de Configuração
- `salario_base`: Valor base do salário para vendedores.
- `salario_gerente`: Valor base do salário para a gerente.
- `vendas_emily`, `vendas_larissa`, `vendas_rafael`, `vendas_milena`: Valores das vendas realizadas por cada vendedor.

## Cálculo do Faturamento Total
O faturamento total é a soma das vendas de todos os vendedores.
```python
faturamento_total = vendas_emily + vendas_larissa + vendas_rafael + vendas_milena
print("Faturamento total = R$", faturamento_total)
```

## Cálculo dos Salários Individuais
Os salários individuais de Emily, Larissa, Rafael e Milena são calculados com base nas comissões sobre as vendas, conforme as seguintes faixas:
- Se as vendas forem menos de 5000, a comissão é de 1%.
- Se as vendas estiverem entre 5000 (inclusive) e 10000 (exclusive), a comissão é de 1,5%.
- Se as vendas forem iguais ou superiores a 10000, a comissão é de 2%.

Os salários são então impressos na tela.

## Cálculo do Salário da Jéssica (Gerente)
O salário da gerente, Jéssica, é calculado com base em uma comissão de 0,5% sobre o faturamento total.

## Cálculo do Total de Salários
O total de salários é a soma dos salários individuais dos vendedores mais o salário da gerente.

## Observações
- As variáveis e fórmulas utilizadas no script podem ser ajustadas conforme necessário.
- Certifique-se de fornecer valores válidos para as vendas de cada vendedor durante a execução do programa.

### Como Usar
1. Execute o script em um ambiente Python.
2. Insira os valores das vendas quando solicitado.
3. O script calculará e imprimirá os salários individuais, o salário da gerente e o total de salários.
