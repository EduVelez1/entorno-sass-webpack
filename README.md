# entorno-sass-webpack

<h1>utils:</h1> no contiene estilos reales , solo mecanismos Sass que ayudan a definir estilos en otros directorios (a veces llamados "ayudantes"). Esto incluye cosas como variables globales, funciones y mixins. Cada una de estas categorías debe colocarse en su propio archivo parcial con el nombre apropiado, como se ve arriba.

<h1>vendors:</h1> contiene las hojas de estilo de terceros que utiliza un proyecto. Por ejemplo, si quisiéramos usar Bootstrap junto con nuestro propio Sass personalizado en un proyecto, descargaríamos la hoja de estilo de Bootstrap y la colocaríamos aquí.

<h1>base:</h1> contiene texto repetitivo utilizado en todo un sitio. Esto incluye estilos tipográficos para todo el proyecto y hojas de estilo que restablecen o normalizan universalmente el CSS predeterminado.

<h1>layout:</h1> contiene estilos para diferentes aspectos del diseño estructural del sitio (piense en áreas como barras de navegación, encabezados, pies de página, etc.)

<h1>components:</h1> son como diseños "mini". Los estilos para piezas pequeñas y reutilizables del sitio deben residir aquí (piense en botones, formularios, imágenes de perfil, etc.)

<h1>pages:</h1> es donde residen los estilos específicos de página. Por ejemplo, si un proyecto contenía varias reglas de estilo que solo se usan en la página "Contáctenos" , vivirían aquí en un archivo _contact.scss , como se ve arriba.

<h1>themes:</h1> se utiliza siempre que un sitio tiene varios temas. Por ejemplo, el proyecto de ejemplo anterior incluye temas de administración y predeterminados. Por lo tanto, podemos suponer que este sitio de ejemplo tiene un estilo completamente diferente para los administradores registrados. Tal vez para presentar y acomodar mejor las funciones adicionales que tiene un administrador. Algunos sitios web también ofrecen un "modo nocturno", donde el fondo del sitio es más oscuro con texto de color más claro para facilitar la lectura en entornos con poca luz. Una opción como esta también estaría representada en su propio archivo de tema.
