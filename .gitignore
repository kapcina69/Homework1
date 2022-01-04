lista_brojeva = input().split(',')
lista_brojeva=list(map(lambda x: int(x) ,lista_brojeva))

lis = lista_brojeva[:]
lis.sort()
srecni_brojevi = []
nesrecni_brojevi = []

def provera(x):
    lista1 = [int(x)]
    lista2 = [int(x)]

    while len(lista2) == len(lista1):


        s = 0
        for cifra in str(x):
            s += int(cifra) ** 2
        lista1.append(s)

        lista2 = list((set(lista1)))

        x = str(s)
    if lista1[-1] == 1:
        srecni_brojevi.append((lista1[0]))

    else:
        nesrecni_brojevi.append(lista1[0])
        for i in range(len(lista1)):
            print(end='')
            #print(lista1[i],end="")
def ispis(x):
    lista1 = [int(x)]
    lista2 = [int(x)]

    while len(lista2) == len(lista1):


        s = 0
        for cifra in str(x):
            s += int(cifra) ** 2
        lista1.append(s)

        lista2 = list((set(lista1)))

        x = str(s)

    print(*[lista1[i] for i in range(len(lista1))], sep=' ')

if lis[0] < 0:
    print(end="")


else:
    print(end="")
    for i in range(len(lista_brojeva)):

        provera(lista_brojeva[i])

    for i in range(len(nesrecni_brojevi)):
        ispis(nesrecni_brojevi[i])
        #print('')

    print('SRECNI BROJEVI:', srecni_brojevi,end='')
