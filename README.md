# EstructuraDeDatos-1
Programación de Estructuras de Datos 1 en lenguaje de programación de C++
CONTENIDO DEL REPOSITORIO:

IMPLEMENTACIÓN DE LISTAS
- Listas Simples.

OPERACIONESS MISCELANEAS

// Direccion del nodo cuyo dato es el referenciado
NodoS* dirDato(int)
		
//Direccion del nodo anterior al nodo cuyo valor sea el referenciado
NodoS* dirAnteriorDato(int) 
		
// Direccion del nodo anterior del nodo de la direccion referenciada
NodoS* dirAnterior(NodoS*) 
		
// Direccion del ultimo nodo
NodoS* dirUltimo() 
		
TDA DE LA LISTA

// dato primero de la lista
int primero() 
		
// dato ultimo de la lista		
int ultimo() 

// retornar el dato en la posicion de referencia		
int datoPos(int) 
		
 // retorna verdadero si la lista esta vacia		
bool esVacia()
		
// retorna verdadero si un valor existe en la lista		
bool existe(int) 

OPERACIONES DE AGREGAR

void agregarInicio(int) // agrega un nodo al inicio
void agregarAlFinal(int) // agrega al final
bool agregarAntesDe(int, int) // agrega un nodo antes de un indice
bool agregarDespuesDe(int, int) // agrega despues de un indice
bool agregarPosicion(int, int)

OPERACIONES DE BORRAR

bool borrar(int) // eliminar el nodo cuyo valor sea el entero de entrada
bool borrarLista() // vacia toda la lista
bool borrarPos(int) // eliminar el nodo que se ubica en la posicion de referencia

OPERACIONES DE DESPLEGAR / LISTAR
void desplegar()

OPERACIONES DE ORDENAMIENTO
void ordenarAscendente() // ordena ascendente

void eleminarValoresRepetidosConsecutivos()
void eliminarValoresRepetidosNoConsecutivos()
    
- Listas Doble Lineal.

TDA DE LA LISTA:
  	int primero()
	int ultimo()
	int datoPos(int)
	bool esVacia()
	bool existe(int)
	
AGREGAR:
	void agregarInicio(int)
	void agregarAlFinal(int)
	void agregarAntesDe(int, int)
	void agregarDespuesDe(int, int)
	bool agregarPosicion(int, int)
	
BORRADO:
	bool borrar(int) // eliminar el nodo cuyo valor sea el entero de entrada
	bool borrarLista() // vacia toda la lista
	bool borrarPos(int) // eliminar el nodo que se ubica en la posicion de referencia

LISTAR:
	void desplegar()

ORDENAMIENTO:
	void ordenarAscendente() // ordena ascendente

	void eleminarValoresRepetidosConsecutivos()
	void eliminarValoresRepetidosNoConsecutivos()

	NodoD* obtenerPosicionCardinal(int)
	int obtenerMayor()
	void eliminarPosicionCardinal(int)
  
- Listas Doble Circular.

TDA DE LA LISTA:
  	int primero()
	int ultimo()
	int datoPos(int)
	bool esVacia()
	bool existe(int)

AGREGAR:
	void agregarInicio(int)
	void agregarAlFinal(int)
	void agregarAntesDe(int, int)
	void agregarDespuesDe(int, int)
	bool agregarPosicion(int, int)

BORRADO:
	bool borrar(int) // eliminar el nodo cuyo valor sea el entero de entrada
	bool borrarLista() // vacia toda la lista
	bool borrarPos(int) // eliminar el nodo que se ubica en la posicion de referencia

LISTAR / DESPLEGAR
	void desplegar()

OPERACIONES DE ORDENAMIENTO:
	void ordenarAscendente() // ordena ascendente

	// eliminar valores repetidos
	void eleminarValoresRepetidosConsecutivos()
	void eliminarValoresRepetidosNoConsecutivos()

	void agregarNodoCadaDosNodosConsecutivos()
	float obtenerPromedio()
	void eliminarValoresEnNodosPares()
