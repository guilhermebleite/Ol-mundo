# Ol-mundo
primeiro repositório de curso de git e github
 testando media em pycharme
 nota01 = float(input('Digite a primeira nota:'))
nota02 = float(input('Digite a segunda nota:'))
media = (nota01 + nota02)/2
print('Será que você passou')
from time import sleep
print('Estamos calculando suA média')
print('---='*20)
sleep(4)
if 5 <= media <7:
   print ('Infelizmente, você esta de recuperação, sua media foi: {:.2f} '.format(media))
elif media < 5:
     print('Infelizmente, você foi reprovado')
elif media >7:
   print('Parabéns, você passou de ano, sua media foi {:.2f}'.format(media))
