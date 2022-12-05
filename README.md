# Realtime reflections - Unity

Link del proyecto de unity: https://drive.google.com/file/d/1_6nFnQEAGE7CFKIfCYTFiIQjNHmPdFoZ/view

El proyecto se trata de desarrollar una escena en la cual un objeto refleje la totalidad del entorno en su superficie, este objeto va a ser una esfera y va a reflejar una escena en un pasillo futurista obtenida a partir del asset corridor de Unity. Para generar la superficie que refleja el entorno se creó un objeto de unity y se le agregó un material con las propiedades Metallic y Smoothness al máximo. Para generar posteriormente el efecto de reflexión se utilizaron reflection probes de Unity, el elemento reflection probe se centra en el objeto que va a reflejar el entorno y se define el alcance del efecto. Para agregar el efecto de reflexión en tiempo real es necesario modificar el tipo del lightning probe de baked a realtime y el refresh mode a every frame. Para probar que la configuración fue correcta se agregan cubos de colores diferentes alrededor de la esfera para evidenciar el cambio en la reflexión  

Para ejecutar el proyecto ir al link de drive, descargar el zip, descomprimir, abrir la carpeta del proyecto en el editor de Unity y ejecutar con el boton de play, ahi se muestra en la ventana de game la escena desarrollada con las relfexiones.

![image](https://user-images.githubusercontent.com/60159763/205742213-61fa6176-a09f-4d5f-846c-7f27ba86319d.png)
