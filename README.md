# Gerador de Tabela de Multiplicação

Este projeto é um script em Python que gera e exibe a tabela de multiplicação para um número fornecido pelo usuário.

## Objetivo

O objetivo deste projeto é criar um script que solicite ao usuário um número e exiba a tabela de multiplicação desse número, mostrando os resultados de multiplicar o número de 1 a 10.

## Código

O código funciona da seguinte maneira:
1. Solicita ao usuário um número inteiro.
2. Utiliza um loop `for` para iterar de 1 a 10 e calcula o produto do número fornecido pelo usuário com cada valor de 1 a 10.
3. Exibe a tabela de multiplicação formatada.

```python
# leitura do número
numero = int(input("Digite um número para gerar a tabela de multiplicação: "))

# loop para gerar a tabela de multiplicação
for i in range(1, 11):
    print(f"{numero} x {i} = {numero * i}")
Como Executar
1. Certifique-se de ter o Python instalado em seu sistema.

2. Salve o código acima em um arquivo chamado tabela_multiplicacao.py.

3. Execute o código usando o seguinte comando:
python tabela_multiplicacao.py
4. Insira um número quando solicitado e veja a tabela de multiplicação correspondente.

Contribuição
Sinta-se à vontade para fazer sugestões ou melhorias. Se encontrar um problema ou tiver uma ideia para aprimorar o projeto, por favor, abra uma issue ou envie um pull request.

Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.
