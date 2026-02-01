# ddya
# Prueba técnica – Semana 1

Este repositorio contiene la solución de la prueba técnica correspondiente a la semana 1.

ejercicio 1.
## Diagrama de flujo
![Diagrama de flujo](_Diagrama%20de%20flujo.png)
## Codigo
def fibonacci(entero):
    if entero<0:
        return False
    a=0
    b=1 
    while a<entero:
        c=a+b
        a=b 
        b=c 
    if a==entero:
        return True
    else:
        return False

def enteros(entero):
    if entero > 0:
        print("el numero es positivo")
    elif entero < 0:
        print("el numero es negativo")
    else:
        print("el numero es 0")

def main():
    entero = int(input("ingrese un numero"))
    
    signo=enteros(entero)
    print("el numero es" signo)
main()
    
