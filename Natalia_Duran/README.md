# LABORATORIO

## Nombre

_Natalia Durán Vivas_

### Carnet 

2148825


### Edad

19 años


### Carrera

Ingeniería de sistemas


### Semestre

7

### Plan de estudios

* PIMB
* PIMO
* POOB 
* TPRO 
* MBDA 
* CVDS

### Fragmento de código

```
public void insertar(int a){
	if (esVacio()) {
		nodoArbol nuevo = new nodoArbol();
		nuevo.dato = a;
		nuevo.hd = new abb();
		nuevo.hi = new abb();
		raiz = nuevo;
	}
	else {
		if (a > raiz.dato) (raiz.hd).insertar(a);
		if (a < raiz.dato) (raiz.hi).insertar(a);       
  }
}
```
### Imágenes de Learn Git Branching

* [Main](https://github.com/nduran06/Laboratorio/blob/master/2.png) 
* [Remote](https://github.com/nduran06/Laboratorio/blob/master/3.png) 
* [Finalizado](https://github.com/nduran06/Laboratorio/blob/master/1.png) 
