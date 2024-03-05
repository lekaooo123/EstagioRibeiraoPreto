# EstagioRibeiraoPreto
1 - No final do processamento, o valor da variável SOMA será 91.

2 -
def fibonacci(n):
    a, b = 0, 1
    while b < n:
        a, b = b, a + b
    if b == n:
        return True
    else:
        return False

numero = int(input("Informe um número: "))

if fibonacci(numero):
    print(f"O número {numero} pertence à sequência de Fibonacci.")
else:
    print(f"O número {numero} não pertence à sequência de Fibonacci.")

3 - 
a) 1, 3, 5, 7, 9 (aumentando de 2 em 2)
b) 2, 4, 8, 16, 32, 64, 128 (dobro do anterior)
c) 0, 1, 4, 9, 16, 25, 36, 49 (Sao eleveados a 2, começando do 0)
d) 4, 16, 36, 64, 100 (Elevados a 2 dos numeros pares, começando do 2)
e) 1, 1, 2, 3, 5, 8, 13 (Fibonacci, sempre é a soma dos 2 anteriores)
f) 2, 10, 12, 16, 17, 18, 19, 20 (Sem padrao, mas seguindo os ultimos incrimentos seria +1)

4- Eu vi em um corte de um filme, nao me lembro o nome do filme, mas era um menino em uma sala de aula>>
Ligue o primeiro interruptor e aguarde alguns minutos antes de desligá-lo. Em seguida, ligue o segundo interruptor e entre na sala. A lâmpada que está acesa estará conectada ao segundo interruptor. A lâmpada que está desligada, mas quente, estará conectada ao primeiro interruptor. E a lâmpada que está desligada e fria estará conectada ao terceiro interruptor.

5 - def inverter_string(string):
    inverted_string = ""
    for i in range(len(string) - 1, -1, -1):
        inverted_string += string[i]
    return inverted_string

entrada = input("Digite uma string: ")
print("String invertida:", inverter_string(entrada))



