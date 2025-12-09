# PRUEBA_RA2
# __Ejercico 1__
## **1A PREGUNTA**
El h1 no esta centrado porque el elemento esta alineado hacia la izquierda, en el flexbox.

Lo que se debe cambiar aqui es que en el .site header, hay que añadir el flex-direcion: column; para poder centrar el texto.
Ademas tambien añadiria en el h1, el class, .site header h1

## **1B PREGUNTA**
Una de las soluciones seria usando el flex-direction: column; en el .site header como ya se hizo en la pregunta 1.
SOLUCION 1:
.site-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.site-header h1 {
  text-align: center;
  flex: 1;
}

SOLUCION 2:
.site-header {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  align-items: center;
}
.site-header h1 {
  grid-column: 2; /* la columna del centro */
  text-align: center;
}


## **1C PREGUNTA**
.site-header {
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: auto 30px auto;
  justify-items: center;      /* Centra horizontalmente */
}

.site-header h1 {
  grid-row: 1;
}

.site-header .main-nav {
  grid-row: 3;
}


## **1D PREGUNTA**
.site-header {
  background-color: #f5f5f5;
  padding: 20px;
  border-bottom: 1px solid #ccc;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

## __Ejercicio 2__
[EJERCICIO 2 COMPLETO](https://dariomggg.github.io/EJ2/)


