# INFORMACION PERSONAL

## *Sergio* Andres *Rozo* Pulido

**20 años**

Graduado del colegio Agustiniano Norte

### parrafo 1
Estudiante de la Escuela Colombiana de Ingenieria, 7mo semestre, actualmente cursando las materias de RECO, AUPN, LSOD, EGI4 y CVDS. Tambien e estudiado ingles en el Colombo Americano. 

### parrafo 2
En mi circulo familiar vivo con mis padres, mi hermano menor y como mascota cuento con un pequeño gato.

Ingenieria de sistemas

## Gustos
+ videojuegos
+ viajes
+ peliculas
+ comer
+ salir

## Cosas que no me gustan
1. Madrugar
2. Calor
3. Multitudes
4. Covid

[ejemplo link](https://www.youtube.com/watch?v=HIcSWuKMwOw)

## Ejemplo codigo
```
def main() -> None:
    """
    proceso principal que analiza si teniendo una lista de numeros, uno de ellos es divisible por el siguiente.
    :return: nada.
    """
    # print(digite los numeros a evaluar)
    numeros = input().split(" ")
    lista_sumas = list()
    i = 0
    suma = int()
    while i < len(numeros):
        if i < len(numeros) - 1:
            if int(numeros[i]) % int(numeros[i + 1]) != 0:
                lista_sumas.append(numeros[i])
        elif i == len(numeros) - 1:
            if int(numeros[i]) % int(numeros[-i]) != 0: # no esta claro, aqui la idea era el ultimo por el primero osea la pos 0.
                lista_sumas.append(numeros[i])
        i += 1
    for num in range(len(lista_sumas)):
        suma += int(lista_sumas[num])
    # print(El total es:)
    print(suma)

main()
```

## ejemplo imagen

![imagen](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQBYPU0cUZnHVLrg-1xyMvK7g3cinQ-6dCet_h9Zg_Cifn6YLEEinSKtJc9rCOSKEUMx0U&usqp=CAU)




