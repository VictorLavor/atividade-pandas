# atividade-pandas

Projeto: Exemplos de Variáveis em Python

📝 Informações Iniciais

Nome: Victor Matheus de LavorTurma: Turma 34

📚 Descrição

Este projeto apresenta exemplos práticos e explicações sobre o conceito de variáveis em Python. O objetivo é demonstrar como as variáveis funcionam, abordando tipagem dinâmica, tipos de dados primitivos e conversões.

🖋️ Conteúdo Abordado

1. Conceito de Variáveis

Em Python, as variáveis são referências a objetos na memória, funcionando como etiquetas. A linguagem trata tudo como objeto, facilitando a manipulação de dados.

Exemplo:

x = 1
y = 0.1324

print("x vale", x)
print("y vale", y)

2. Tipagem Dinâmica

Python é dinamicamente tipado, o que significa que o tipo da variável é definido automaticamente pelo valor atribuído.

Exemplo:

x = "Data "
y = "Science"
print(x + y)

3. Vantagens e Desvantagens

Vantagens:

Flexibilidade na codificação

Código mais legível

Facilidade para iniciantes

Desvantagens:

Possibilidade de erros em tempo de execução

Desempenho levemente inferior comparado às linguagens estaticamente tipadas

4. Exemplos por Tipo de Dados

Inteiros:

x = 2.861
a = int(4.5 + 3.8)
print(a)  # Saída: 8

Float:

a = float(22/5)
b = 3.01e23
print(a)  # Saída: 4.4
print(b)  # Saída: 3.01e+23

Booleano:

x = 1
y = 0
print(bool(x))  # True
print(bool(y))  # False

NoneType:

valor = None
if valor:
    print("Tem valor!")
else:
    print("É None ou falso.")

String:

nome = "Victor"
idade = "36"
print("Nome: %s, Idade: %s" % (nome, idade))
print("Meu nome em caixa alta:", nome.upper())

5. Conversões de Tipos

Conversões entre tipos podem ser feitas explicitamente para evitar erros.

Exemplo:

a = float(22/5)
b = int(4.5)
c = round(3.9)
print(a, b, c)  # Saída: 4.4 4 4

🚀 Como Executar

Instale o Python (versão 3.8 ou superior).

Copie o código-fonte para um arquivo exemplos_variaveis.py.

No terminal, execute o comando:

python exemplos_variaveis.py

📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para detalhes.
