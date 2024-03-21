# 💻 Codando com python pela primeira vez 🥰

◉ Tipos em Python 

| Tipos |   -   | 
|-------|-----|
|Texto|Str|
|Numérico|Int,float,complex|
|Mapa|Dict
|Coleção|Set,frozenset|
|Booleano| Bool|
|Binário| Bytes, bytearray, memoryview|
Sequência| List, tuple, range|



# ✲  Convertendo Tipos 🎮

print (int(1.0))
print (int("10"))
print (float("10.10"))

valor = 10
valor_str = str(valor)
print(type(valor))
print(type(valor_str))


print(100/2)
print(100//2)

# Função Input 


nome = input("Informe o seu nome: ")
idade = input("Ïnforme a sua idade: ")

print(nome,idade)
print(nome,idade,end="...\n")
print(nome,idade,sep="#")



## informacoes extras sobre input

# input(prompt)
#Se o argumento prompt estiver presente, escreve na saída padrão sem uma nova linha ao final. A função então lê uma linha da fonte de entrada, converte a mesma para uma string (removendo o caractere de nova linha ao final), e devolve isso. Quando o final do arquivo (EOF / end-of-file) é encontrado, um erro EOFError é levantado. Exemplo:

#>>>
#s = input('--> ')  
#--> Monty Python's Flying Circus
#s  
#"Monty Python's Flying Circus"
#Se o módulo readline foi carregado, então input() usará ele para prover edição de linhas elaboradas e funcionalidades de histórico.

#Levanta um evento de auditoria builtins.input com argumento prompt.

#Levanta um evento de auditoria builtins.input/result com argumento result.


# Constantes ⌨️

nome = 'Bia'
idade = '27'

nome = 'Gilberto'

print(nome, idade)

limit_saque_diario = 1000

STATES = ["SP", "RJ", "SC", "RS"]

print(STATES)


# Variáveis 🖥️

age, name = (27, 'Bia')
print(f'Meu nome é {name} e eu tenho {age} ano(s) de idade ')