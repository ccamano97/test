Paper 2:
libro: 1988
refinar que signiifica que algo este bien disenado --> tienen una caracteristica principal: tiene **pistas** del funcionamiento/uso

3 tipos de visibilidad:
1. pistas del **funcionamiento**: el ejemplo de las puertas, no tenian un indicador/pis. el que y como se opera 
2. **feedback**: el telefono y la luz roja del telefono on hold, las teclas del telefono
3.  **mapeo** entre lo que yo quiero hacer y lo que puedo hacer. ejemplo: las diapositivas, el proyector con 1 boton (no es visible ir para atras y adelante)

**affordance** o prestaciones, (de los materiales)  
estacion de tren (vidrio: si se peude romper, se rompe, si se peude rayar se raya), una comunidad tiene una idea de como interactuar con un material 
affordance:  dependiendo de que esta hecho algo, interactuamos de forma distinta

CELULAR: abusa de la idea de affordance. los primeors iphones usaba esqueumorfismo, la idea es dise;ar objetos que muestran materiales de la vida real (notas: hoja n5 con renglones, dibujar: fondo de pizarra, youtube: una tele, microfono: un microfno de fondo) la gente aprendio, ya no hace falta

modelo conceptual: tijera, una idea mental de como funciona el dispositivo . se predice como se va a comportar, una tijera, malo: reloj digital (mal dise;o necesito manual, error no se que pasa)


bien disenado: sigue las "metricas" mencionadas

**en nuestra disciplina:** 
- ejemplo: lavarropas con muchas opciones, pero solo se usa 1, proyectos de sistemas de voz para maquinas expendedoras fallaron por el mercado (software con muchas opciones, despues el usuario solo usa 1 -> hacer proyectos cortos para probar rapido)
- feedback: cortinas y luz  en el aula, visibilidad: horrible // 
- nombres en software tienen que ser declarativos: puedo ver la funcion y entiendo que hace segun el nombre

vamos a definir un concepto de software bien dise;ado, queremos llegar a lo que menciona el libro (llegar al dise;o natural: lo veo y ya se como se usa)


----
PRACTICA
definir numeros naturales: axiomas 
cloneNmaed: clona un nuevo objeto basado en self con el nombre self name, 'I' (la , concatena el string)

yo intento
![[Pasted image 20230824205213.png]]

colaboradores no inicializados: devuelven **nil**

II next anObsolteIII <_ objeto obsoleto
inspeccionar el II, borrar el next y poner nil
	como son numeros naturales, no tiene sentido que el 1 sepa que es una resta, no hacemos nada y small talk ya sabe, tampoco tiene sentido el previous al 1


(usar ifs es malo... por algun motivo que vamos a ver, agrega complejidad )
resta sin if:
en vez de alguien retarme a mi, yo restarme a el

- a NaturalNumber
^ a naturalNumber restateA: self.


restateA: aNaturalNumber
^aNaturalNumber previos self previous.

y ahora el I es el caso base,  (evita usar el previous del I) y 
restateA: a naturalNumber
^aNaturalNumber previous


implementar multiplicacion y division
