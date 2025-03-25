print("olá mundo")


[Uplotry:
    # Solicita a temperatura do usuário
    temperatura = float(input("Digite a sua temperatura: "))  # Usando float para permitir números decimais

    # Classifica a pessoa em criança, adulto ou idoso
    if temperatura <= 15:
        print("Frio")
    elif temperatura <= 25:
        print("Agradável")
    elif temperatura >= 45:
        print("Como tu tá vivo ainda?")
    else: 
        print("Quente")
        print("Cuidados devido ao calor.")



except ValueError:
    print("Por favor, insira um número válido para a temperatura. Ex: 10")
ading 2ds.py…]()



[Upnota = int(input('digite um numero: ')) 
if (nota <=2):
    print('F')
elif (nota >=3 ):
    print('D')
elif (nota >=6):
    print('C')
elif (nota >=7):
    print('B')
elif (nota >=10):
    print('A')
import random
quer_continuiar = True
contador = 1



while(quer_continuiar):
    n1 = random.randint(1,100)
    n2 = random.randint(1,100)
    print(f"Q{contador}:{n1}+{n2}")
    resp = int(input("R:")) 
    if(resp == n1+n2):
        acertos+=1
        print("resposta correta")
    else:
        erros+=1
        print("resposta incorreta")



contador = contador+1   
print(contador)  
continuar = input("Quer continuar? [1]Sim [2]Nao")
if(continuar == 2):
    quer_continuiar = False

print("FIM!")
print("acertos: {acertos}")
print("erros: {erros}")         loading 90.PY…]()




[Uploadingimport random
quer_continuiar = True
contador = 1
while(quer_continuiar):
    n1 = random.randint(1,100)
    n2 = random.randint(1,100)
    print(f"Q{contador}:{n1}+{n2}")
    resp = int(input("R:")) 
    if(resp == n1+n2):
        acertos+=1
        print("resposta correta")
    else:
        erros+=1
        print("resposta incorreta")

contador = contador+1   
print(contador)  
continuar = input("Quer continuar? [1]Sim [2]Nao")
if(continuar == 2):
    quer_continuiar = False

print("FIM!")
print("acertos: {acertos}")
print("erros: {erros}")         
nota = int(input('digite um numero: ')) 
if (nota <=2):
    print('F')
elif (nota >=3 ):
    print('D')
elif (nota >=6):
    print('C')
elif (nota >=7):
    print('B')
elif (nota >=10):
    print('A') aula 999.py…]()

dias = (int(input("dias da semana:")))
dia1 = 2
if dias == 2:
  print ('segunda-feira')
elif dias == 3:
      print ('terça-feira')
elif dias == 4:
        print ('quarta-feira')
elif dias == 5:
      print ('quinta-feira')
elif dias == 6:
      print ('sexta-feira')
elif dias == 7:
        print ('sabado')
elif dias == 1:
      print ('domingo')
else:
   print("dia da semana invalido")

count = 0
while count <=9     :
    print("PAR")
    count+=2    


# Solicita o número do usuário
numero = int(input("Digite um numero: "))

par = 2
par = 4
par = 5
par = 8
par = 10

impar = 1
impar = 3 
impar = 6
impar = 7
impar = 9


if par: print ("par")

elif impar:
    print("impar")

else:
   print("número invalido")

# Solicita o número do usuário
numero = int(input("Digite um numero: "))

#  Verifica se e positivo
if numero >=0 :
    print("e positivo")
else:
    print ("número invalido")



a = int(input('digite um numero: '))
b = int(input('digite um numero: '))
c = int(input('digite um numero: '))
if(a > b,c ):
    print("é maior")

elif (b > a,c):
    print("é maior")

elif(c > b,a):
    print("é maior")

else:
    print("números iguais por favor faça denovo")


nota = int(input('digite um numero: ')) #10
if (nota >= 7 and nota <=10 ):
    print('Aprovado')
elif (nota>=10):
    print('nota invalida')
else:
    print('Reprovado')

count = 0
while count <=4:
    print("A")
    count+=1    
contador=0
while contador >2:
    print("olá mundo")
    contador +=1


nota = int(input('Digite um número: '))

if nota >= 10:
    print('A')
elif nota >= 7:
    print('B')
elif nota >= 6:
    print('C')
elif nota >= 3:
    print('D')
else:
    print('F')


a = int(input('Digite um número: '))
b = int(input('Digite um número: '))
c = int(input('Digite um número: '))

if a > b and a > c:
    print(f"O maior número é {a}")
elif b > a and b > c:
    print(f"O maior número é {b}")
elif c > a and c > b:
    print(f"O maior número é {c}")
else:
    print("Os números são iguais, tente novamente.")

[Uploadi# Solicita o número do usuário
numero = int(input("Digite um número: "))

# Verifica se o número é par ou ímpar
if numero % 2 == 0:
    print("par")
else:
    print("ímpar")
ng teste2.py…]()

nota = int(input('Digite um número: '))

if nota >= 10:
    print('A')
elif nota >= 7:
    print('B')
elif nota >= 6:
    print('C')
elif nota >= 3:
    print('D')
else:
    print('F')


