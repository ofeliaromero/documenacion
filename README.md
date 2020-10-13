# documenacion
documentación de los servicios APIs
FORMAT: 1A
# Encuestas
Encuestas es una API que permite a los clientes ver encuestas y votar en ellas.
# Group Preguntas
## Colección de preguntas [/preguntas]
### Lista todas las preguntas [GET]
+ Response 200 (application/json)
        [
            {
                "pregunta": "¿Cuál es tu lenguaje de programación favorito?",
                "publicado_en": "2014-11-11T08:40:51.620Z",
                "url": "/preguntas/1",
                "opciones": [
                    {
                        "opcion": "Go",
                        "url": "/preguntas/1/opciones/1",
                        "votos": 2048
                    }, {
                        "opcion": "PHP",
                        "url": "/preguntas/1/opciones/2",
                        "votos": 1024
                    }, {
                        "opcion": "Python",
                        "url": "/preguntas/1/opciones/3",
                        "votos": 512
                    }, {
                        "opcion": "Ruby",
                        "url": "/preguntas/1/opciones/4",
                        "votos": 256
                    }
                ]
            }
        ]
