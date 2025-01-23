# Principios de Accesibilidad Web

_Una serie de guías y reglas a alto nivel para afrontar la accesibilidad web._

* [Lo perfecto es enemigo de lo bueno](#lo-perfecto-es-enemigo-de-lo-bueno)
* [Por defecto o nada](#por-defecto-o-nada)
* [La paridad es primordial](#la-paridad-es-primordial)
* [Diseña para la implementación](#diseña-para-la-implementación)
* [La estructura es lo primero](#la-estructura-es-lo-primero)
* [Usa tus palabras](#usa-tus-palabras)
* [Las herramientas no son identidades](#las-herramientas-no-son-identidades)
* [Menos es menos](#menos-es-menos)
* [Que te paguen](#que-te-paguen)
* [Enseña a pescar, no des pescado](#enseña-a-pescar-no-des-pescado)
* [No vale presumir](#no-vale-presumir)
* [Que se pudra el mal](#que-se-pudra-el-mal)

## Lo perfecto es enemigo de lo bueno

Nada es ni puede ser 100% accesible. La persona que afirme que su propuesta es completamente accesible está mintiendo, no entiende de accesibilidad o las dos cosas. Normalmente las dos. Está bien completar un trabajo que no es accesible del todo, siempre que sea _más_ accesible. Haz lo que puedas dentro de las condiciones dadas. Si las condiciones no son razonables, cuestiónalas primero. Puede que no tengas la confianza en ser la mejor persona disponible para trabajar en accesibilidad. Pero _estás disponible_. No dejes ese trabajo para otros superhéroes de la accesibilidad que no están (o son inexistentes).

## Por defecto o nada

Básicamente, la accesibilidad no funciona como un plugin, un add-on o una subscripción. Si una interfaz ofrece una opción para _habilitar_ la accesibilidad, esa interfaz no es accesible. ¿Un botón con bajo contraste para activar el modo de alto contraste? No. El software para superponer una capa de accesibilidad no funciona y no puede funcionar. Añadir _cosas accesibles_ sobre _cosas no accesibles_ no aborda las necesidades que deben abordarse. Las prestaciones que ofrecen esos intrusos como tercera parte son irrelevantes. Lucha contra la ideología de la accesibilidad _a posteriori_ a toda costa. Un Producto Mínimo y Viable (MVP) sin accesibilidad ni es mínimo ni es viable.

## La paridad es primordial

La idea no es crear una experiencia mejor, ni siquiera una buena experiencia. Se busca asegurar una experiencia _comparable_ entre diferentes personas. Las interfaces no deberían ser un reto para algunos y no para otros, pero algunas interfaces van a ser complejas por necesidad y habrá contenido que será inherentemente incomprensible. No puedes elegir quién está interesado en -o puede sobrellevar- qué cosas. Si se comparte una imagen con un chiste, el texto alternativo no debería revelar la broma o explicar por qué es graciosa. Debería _contar el mismo chiste, pero de forma alternativa_. La gracia será ofensiva para algunos y otros no la entenderán. Esas son limitaciones de la _inclusividad_, no de la accesibilidad.

## Diseña para la implementación

Dicen que la forma debería adecuarse a la función. Pero la mayoría de las organizaciones diseñan primero y desarrollan después. La fase de diseño consiste en ideas puramente gráficas y deja demasiadas preguntas sin respuesta para la implementación. En consecuencia, se anima a los programadores a dar prioridad a aproximaciones visuales por encima de la usabilidad. Las interfaces que usan el ratón para arrastrar elementos deben ser operativas también a través del teclado. Eso significa que debe haber botones. Esos botones deben aparecer en lo que se llama _diseño_. Como un profesional de la accesibilidad, debes contribuir cuanto antes y a nivel conceptual. Porque la forma debe adecuarse a la función y la función debe ser accesible.

## La estructura es lo primero

Una interfaz mal estructurada puede técnicamente pasar los requisitos WCAG. Una interfaz intuitiva y bien estructurada puede tener algunos errores específicos de WCAG. Pero lo más seguro es que esta última sea una interfaz más accesible para la mayoría. Las herramientas automatizadas de accesibilidad son muy buenas localizando estos errores específicos. Aunque pueden ser útiles para diagnosticar problemas, debes plantearte un enfoque integral y completo. ¿Qué confunde o agobia a la gente? ¿Dónde tropezarán? No pierdas tiempo solucionando criterios específicos cuando puede que necesites replantearte la estructura básica.

## Usa tus palabras

Una parte considerable de la accesibilidad web consiste en proporcionar etiquetas de texto. Botones, enlaces y campos de texto deben estar etiquetados. Los títulos de las páginas y los encabezados son también etiquetas. Los mensajes de estado son críticos para etiquetar el estado. Incluir una etiqueta puede ser suficiente para contentar a las herramientas de prueba de accesibilidad, pero las _palabras_ de la etiqueta son las que marcan la diferencia. Una buena redacción no se puede automatizar. La Inteligencia Artificial no puede adivinar tu intención. Desarrolla tus habilidades de escritura y edición o incluye a escritores y editores en tu proceso.

## Las herramientas no son identidades

La discapacidad no es más uniforme que la capacidad. Diferentes usuarios de lectores de pantalla usan diferentes programas de lectura de pantalla de forma diferente, por diferentes razones, en diferentes circunstancias, para satisfacer diferentes necesidades y preferencias. Y eso si es que usan un lector de pantalla. No hay una persona concreta que pueda ejemplificar un lector de pantalla y su comportamiento. No hay un usuario de lector de pantalla que represente a todos los usuarios de lectores de pantalla. Así que no diseñes para usuarios de lectores de pantalla (o cualquier otro grupo homogéneo ficticio). Diseña para dar soporte a las capacidades del software lector de pantalla. Las personas no se pueden -y no se deben- cuantificar, pero las entradas y las salidas si pueden serlo y lo son.

## Menos es menos

El lema _menos es más_ es incorrecto. Menos es solo menos y eso es bueno. Mucha de la ingeniería de interfaces se hace porque otros lo han hecho o para probar que se puede hacer. Déjalo. Mientras más hacemos, y mientras más complejo se vuelve el resultado, más fácil es equivocarse. Y no solamente porque se producirán más errores y fallos discretos; más importante aún, porque luchamos contra la comprensión. La mayoría de los componentes, en la mayoría de los casos, deberían ser solo contenido. El contenido en raras ocasiones debería esconderse con un botón. Convertir los encabezados, párrafos y listas en una interfaz accesible con el tabulador no es una mejora. Es un deterioro con alardeos.

## Que te paguen

No dejes que exploten tu entusiasmo por la accesibilidad. Como cualquier otro trabajo, cuanta más gente lo haga de forma gratuita, menos se valorará. Las tareas de accesibilidad no son un extra opcional, un hobby o un acto de generosidad. Es una parte fundamental en el diseño de una interfaz sólida. Si te pagan por trabajar y trabajas en accesibilidad, debería estar definido como parte de tu puesto. El trabajo en accesibilidad debe remunerarse y recompensarse como cualquier otro trabajo. Cuando la _"accesibilidad es trabajo de todos"_, normalmente no es trabajo de nadie. Ten cuidado con esa retórica. 

## Enseña a pescar, no des pescado

El diseño de productos e interfaces accesibles comienza con el diseño de la organización y las comunidades que las proporcionan. Puedes producir trabajo accesible hoy, pero, ¿quién lo hará mañana? ¿Quién o qué lo _deshará_ mañana? Un diseño accesible puede significar crear un equipo de frontend consistente en programadores expertos en frontend. Puede significar reemplazar un sistema de control de contenido (CMS) que impida unos resultados accesibles. Puede significar dar instrucciones al equipo editorial sobre cómo estructurar el contenido. Si estás solucionando la inaccesibilidad por tu cuenta, solamente tú, tu impacto se desvanecerá pronto.

## No vale presumir

Las compañías tienden a priorizar que _parezca_ que están centrándose en la accesibilidad más que hacer algo en sí. Contratan a profesionales de la accesibilidad y no les dan los recursos necesarios. Contratan estudios con participantes con discapacidades y rechazan interpretar sus comentarios. Pagan por auditorías y no implementan sus recomendaciones. Te dicen que el contraste de colores debe examinarse, pero los colores de su marca son sagrados y no se cambian. Si realmente quieres marcar la diferencia, pide hechos en lugar de actuaciones de cara a la galería.

## Que se pudra el mal

Vas a tener oportunidades para trabajar en productos que son inherentemente explotadores y adictivos, que comercian con odio y desinformación o que simplemente hacen el mundo un lugar peor. Ese tipo de productos, y las empresas psicóticas que los engendran, son extremadamente resistentes al cambio, sin importar lo que te digan. No te conviertas en un mártir intentando redimir lo irredimible. No hagas tuyo su fracaso. Protege tu reputación y tu salud mental. Hay mucha inaccesibilidad en el mundo. Da prioridad a trabajar con gente que escucha, en el tipo de productos que merecen existir.
