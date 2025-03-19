- **Código fuente documentado**

> ; SUMA SIMPLE Y MULTIPLICACIÓN
> 
> .begin:	
> 	clra
> 
> 	mva  #5
> 
> 	data Rb, Multiplicador
> 
> 	Multiplicador =3
> 
> ;SUMA Rb +Rc -> Rd:
> 
> 	add Ra
> 
> 	mvd Ra
> 	
> ;loop para tabla del 8 con el numero sumado
> 
> .loop:
> 
> 	add Ra
> 
> 	inc Rb
> 
> 	mvd Ra
> 
> 	jmp .loop



![image](https://github.com/user-attachments/assets/5eb787b3-bd8d-4a33-b414-32b7a30922d4)


- **Breve informe explicando la lógica y el funcionamiento**
El programa funciona sumando dos registros diferentes Ra con 5 y Rb que es una constante de valor 3, posterior mente a la suma se hace un loop con la misma constante de 3, hasta que pase overflow y se reinicie.

- **Demostración en la computadora de 8 bits o en el emulador**

https://github.com/user-attachments/assets/c4b78bb9-5cc8-44ab-bae3-077f7a49d913

