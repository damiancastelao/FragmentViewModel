# Fragment con ViewModel


---

A tener en cuenta:

- Creamos un paquete para la UI (interface de usuario)
- En este paquete tenemos el ViewModel y los fragments de la interface
- Cada fragment tiene su propio layout
- En el layout de la activity necesitamos un elemento (en este ejemplo FrameLayout) para alojar el layout del fragment
- El FrameLayout es un elemento que me permite contener otras Views también, aqui solo se utiliza para contener al fragmnet
- En este ejemplo el frameLayout acupa toda la Activity
- La Activity principal tiene un layout diferente si ponemos el dispositivo apaisado. En este layout, el FrameLayou comparte layout con un textView

