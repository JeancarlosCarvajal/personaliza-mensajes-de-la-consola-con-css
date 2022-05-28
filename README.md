# personaliza-mensajes-de-la-consola-con-estilos
Personaliza Mensajes de la Consola con estilos


    <script>

        // Función aplica sólo a Cadenas de Texto (String)
        function console_log(datos){
            // Creamos los estilos del Console log personalizado
            var estilos = 'font-size: 25px; background: #03a9f4; color: white; font-weight: bold; padding: 5px 15px;';
            // Agregamos los datos y el css al console log
            console.log('%c' + datos, estilos);
        }

        // Probando nuestro Console log personalizado
        console_log('HOLA MUNDO');

    </script>
