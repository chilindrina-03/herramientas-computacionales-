# herramientas-computacionales-
ejercicicios de clase 


	* Primer trabajo de Herramientas Computacionales

numero1=int(input("ingresa primer numero"))
numero2=int(input("ingresa segundo numero"))
resultado=numero1 + numero2
print("el resultado es ", resultado)


numero1=eval(input("nota primer parcial"))
resultado1parcial=numero1*25/100
numero2=eval(input("nota segundo parcial"))
resultado2parcial=numero2*25/100              
resultadodosparciales=resultado1parcial+resultado2parcial
print("el resultado es ", resultadodosparciales)
numero3=eval(input("nota taller"))            
resultadonotadeltaller=numero3*20/100
print("el resultado es",resultadonotadeltaller)
numero4=eval(input(" nota de proyecto"))
resultadonotaproyecto=numero4*30/100
print("el resultado es", resultadonotaproyecto)
resultado=resultadodosparciales+resultadonotadeltaller+resultadonotaproyecto
print("el resultado final de la asignatura es",resultado)
