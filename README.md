# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Cotizador.jsx= 

lineas de 6 a 12= defino las variables 

lineas de 18 a 8= creo una funcion que devuelve los 2 fetch para los 2 json

lineas de 30 a 53= creo la funcion cotizarPoliza que obtiene a traves de un find la opcion de propiedad y ubicacion selecionada, si ambas estan disponibles realiza el calculo de su valor, le pasa a setPrecioEstimado el resultado, crea un objeto con los detalles de la operacion y muestra un boton para guardar en el historial

lineas de 56 a 60 creo una funcion que guarda en el localStorage

lineas de 63 a 118: devuelve todo el contenido html de la pagina.

lineas de 113 a 115: al hacer click en el boton que dice guardar En Historial se guarda la informacion en el localStorage



Historial.jsx: 

lineas de 14 a 17: creo una funcion que borra todos los datos del localstorage

lineas de 19 a 41: si el contenido del array del historial es mayor a 0 se crea el contenido html del historial, sino muestra un mensaje que dice: No hay historial disponible.

lineas de 36 a 42: agrego 1 boton para borrar el historial al hacerle click, y un NavLink para volver a la pagina principal 