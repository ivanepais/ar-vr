# ar-vr

AR: 
	
	Superpone información digital (como imágenes, videos, sonidos y otros datos) al entorno físico real del usuario en tiempo real. 

	A diferencia de la realidad virtual (VR), que crea un entorno completamente virtual, la realidad aumentada enriquece el mundo real con elementos virtuales, mejorando la percepción y la interacción del usuario con su entorno.


AV: 
	
	La Realidad Aumentada por Visualización integra elementos digitales en el entorno real del usuario, mejorando la percepción de la realidad mediante la superposición de información visual. 

	Esta categoría específica de realidad aumentada se centra en proporcionar información adicional y relevante directamente en el campo de visión del usuario, facilitando una interacción más rica y contextualizada con el entorno.


VR: 
	
	Crea entornos completamente digitales en los que los usuarios pueden sumergirse e interactuar.

	Estos entornos simulan la presencia física en lugares reales o imaginarios, proporcionando una experiencia inmersiva que puede ser visual, auditiva e incluso táctil.


MR: 
	
	Tecnología que combina elementos de la realidad aumentada (AR) y la realidad virtual (VR), creando entornos donde los objetos digitales y físicos coexisten e interactúan en tiempo real. 

	A diferencia de la AR, que solo superpone información digital al mundo real, o la VR, que sumerge al usuario en un entorno completamente virtual, la MR permite una interacción más dinámica y bidireccional entre ambos mundos.



....


|| AR
	
	Conceptos Tecnológicos
	
	Conceptos Teóricos

	Interacción Humano-Computadora (HCI)

	Continuum de Realidad-Virtualidad	
	Percepción y Cognición en AR

	Sensores y cámaras

	Motores de gráficos (Unity, Unreal Engine)

    Herramientas y SDKs (ARCore, ARKit, Vuforia)	

    C#, JavaScript

    Unity y Unreal Engine

    Modelado 3D básico (Blender, Autodesk Maya)

    Diseño de interfaces y experiencia de usuario (UX/UI)

    SDKs como ARCore y ARKit
	
	Implementación de objetos 3D y animaciones

	Técnicas de rastreo de movimiento y posición

    Registro preciso de objetos virtuales en el mundo real

    Interacción gestual y por voz
    
    Integración de retroalimentación háptica

    Mejora del rendimiento y latencia



|| AR

	Es una tecnología que superpone información digital (como imágenes, videos, sonidos y otros datos) al entorno físico real del usuario en tiempo real. 

	A diferencia de la realidad virtual (VR), que crea un entorno completamente virtual, la realidad aumentada enriquece el mundo real con elementos virtuales, mejorando la percepción y la interacción del usuario con su entorno.


	Componentes:	

		Hardware:

			Dispositivos de visualización: 	

				Gafas AR, teléfonos inteligentes y tabletas.		


			Cámaras y sensores:

				Capturan el entorno real y ayudan a integrar los elementos virtuales.
			

			Procesadores: 

				Necesarios para ejecutar el software de AR y procesar la información en tiempo real.


		Software:

		    Aplicaciones y plataformas AR: 	

		    	Programas que permiten crear, visualizar e interactuar con contenido aumentado.
		    

		    Algoritmos de reconocimiento y rastreo:

		    	Detectan y siguen objetos en el entorno real para superponer correctamente los elementos virtuales.


	Tipos de Realidad Aumentada:

		1. Basada en marcadores:

			Utiliza imágenes predefinidas (marcadores) que, cuando son detectadas por la cámara, desencadenan la aparición de contenido virtual.


		2. Sin marcadores (basada en la ubicación): 

			Utiliza la ubicación del usuario obtenida a través de GPS, brújulas y otros sensores para mostrar contenido relevante según la posición geográfica.


		3. Proyección: 

			Proyecta luz artificial en superficies reales y permite la interacción con la proyección.


		4. Superposición: 

			Reemplaza parcialmente la vista real con una vista aumentada, como las aplicaciones de maquillaje virtual.


	Usos: 	

		Juegos y entretenimiento: 

			Juegos que combinan elementos virtuales con el mundo real.


		Educación: 

			Material didáctico interactivo que permite a los estudiantes visualizar conceptos complejos.


		Medicina: 

			Herramientas de visualización para cirugía y entrenamiento médico.


		Comercio: 

			Pruebas virtuales de productos, como ropa o muebles, en el entorno del usuario.


		Industria y mantenimiento:

			Instrucciones superpuestas en equipos para asistencia en reparaciones y ensamblajes.


	Ejemplo: 

		Pokémon GO: 

			Un juego móvil que permite a los jugadores capturar criaturas virtuales en el mundo real.


		Google Lens: 

			Una herramienta que usa la cámara del smartphone para identificar objetos, traducir textos, y proporcionar información relevante sobre lo que se enfoca.


		Snapchat Lenses: 

			Filtros de realidad aumentada que modifican la apariencia del usuario o su entorno en tiempo real.



|| AR: Conceptos Tecnológicos
	

	Captura y Sensores: 

		Cámaras: 

			Las cámaras de los dispositivos AR capturan el entorno real. 

			Esta información visual es fundamental para la superposición de elementos virtuales en el mundo real.


		Sensores:

		    Acelerómetros: 

		    	Miden la aceleración del dispositivo, ayudando a determinar su movimiento y orientación.


		    Giroscopios: 

		    	Detectan la rotación del dispositivo, crucial para mantener la estabilidad de los objetos virtuales en el entorno.


		    GPS: 

		    	Proporciona información de ubicación geográfica, esencial para aplicaciones AR basadas en la ubicación.


		    Brújula digital:

		    	Determina la dirección en la que apunta el dispositivo.


	Procesamiento de Imágenes y Reconocimiento de Patrones:

		Algoritmos de Visión por Computadora:

		    Detección de características: 

		    	Identifica puntos de interés en la imagen capturada, como esquinas y bordes, que pueden ser rastreados para superponer objetos virtuales.


		    Reconocimiento de objetos: 

		    	Identifica y categoriza objetos dentro del entorno real para interactuar con ellos o superponer información relevante.


		    Mapeo y Localización Simultáneos (SLAM):


		    	Técnica que construye un mapa del entorno mientras localiza la posición del dispositivo en ese mapa. 

		    	Esto es fundamental para aplicaciones AR móviles que necesitan seguir el entorno en tiempo real.


	Rastreo y Registro:

		Rastreo:

		    Rastreo de movimiento:

		    	Monitorea el movimiento del dispositivo para ajustar la posición de los objetos virtuales en consecuencia.


		    Rastreo de marcadores:

		    	Utiliza marcadores visuales (como códigos QR o imágenes específicas) para determinar la posición y orientación del dispositivo respecto a esos puntos de referencia.


		Registro:

		    Registro de contexto:

		    	Alinea objetos virtuales con el entorno real de manera precisa y coherente, asegurando que los elementos virtuales se mantengan en la misma posición relativa al mundo real.	    


	Renderización

		Gráficos 3D:

		    Los motores de renderización 3D generan imágenes virtuales que se superponen al entorno real. 

		    Estos motores deben manejar la iluminación, sombras y perspectiva para que los objetos virtuales se integren de manera convincente con el mundo real.


	Interfaz de Usuario (UI) e Interacción:

		Interfaces Naturales:

		    Permiten a los usuarios interactuar con los elementos virtuales de manera intuitiva, utilizando gestos, voz y otros métodos de entrada natural.


		Interfaces Táctiles:

		    En dispositivos móviles, las pantallas táctiles permiten a los usuarios manipular objetos virtuales directamente.


	Plataformas y Herramientas de Desarrollo

		Kits de Desarrollo de Software (SDKs):

		    ARKit (Apple):

		    	Proporciona herramientas para desarrollar aplicaciones AR para dispositivos iOS.


		    ARCore (Google):

		    	Plataforma para desarrollar aplicaciones AR en dispositivos Android.
		    

		    Vuforia: 

		    	SDK multiplataforma para desarrollar aplicaciones AR en diversos dispositivos.


		Motores de Juego:

		    Unity: 

		    	Un motor de juego popular que ofrece soporte para AR, permitiendo a los desarrolladores crear experiencias inmersivas.


		    Unreal Engine: 

		    	Otro motor de juego que proporciona herramientas robustas para el desarrollo de aplicaciones AR.


	Redes y Conectividad

		Redes de baja latencia:

		    La conectividad rápida y estable es crucial para muchas aplicaciones AR, especialmente aquellas que requieren colaboración en tiempo real o acceso a datos en la nube.


	Inteligencia Artificial y Aprendizaje Automático

		IA y Machine Learning:

		    Mejoran el reconocimiento de objetos y la comprensión del entorno, permitiendo una interacción más natural y precisa con el usuario. 



|| AR: Conceptos Teóricos

	Interacción Humano-Computadora (HCI)

		La realidad aumentada es una subdisciplina de la interacción humano-computadora (HCI) que se centra en cómo los humanos interactúan con sistemas computacionales aumentados.

		Los principios de HCI en AR incluyen:

	    Usabilidad: 

	    	Evaluación de qué tan fácil y eficiente es para los usuarios interactuar con los sistemas AR.


	    Ergonomía: 

	    	Diseño de interfaces AR que minimicen la fatiga y maximicen el confort del usuario.


	    Feedback: 

	    	Provisión de respuestas inmediatas y claras a las acciones del usuario en el entorno AR.	


	Realidad Mixta (MR):

		La realidad aumentada se sitúa en el espectro de la realidad mixta, que abarca desde la realidad virtual (VR) hasta la realidad aumentada.

		Este espectro se describe en el 'Continuum de Realidad-Virtualidad' de Paul Milgram, que clasifica las tecnologías de inmersión basadas en cuánto mezclan el mundo real con el virtual:

	    Realidad Virtual (VR):

	    	Entornos completamente virtuales sin elementos del mundo real.


	    Realidad Aumentada (AR):

	    	Entornos del mundo real enriquecidos con elementos virtuales.
	    

	    Realidad Aumentada por Visualización (AV): 

	    	El mundo virtual se enriquece con elementos del mundo real.


	Teoría de la Percepción y Cognición

		La AR se basa en principios de percepción y cognición humana para crear experiencias inmersivas y naturales, incluye:

	    Percepción Espacial: 

	    	Cómo los usuarios perciben y entienden la ubicación y el movimiento de objetos en el espacio.


	    Atención Selectiva: 

	    	Cómo los elementos aumentados pueden atraer y dirigir la atención del usuario sin sobrecargarlo.


	    Procesamiento Multisensorial:

	    	Integración de información visual, auditiva y táctil para proporcionar una experiencia coherente.


	Registro y Rastreo:

		El registro en AR se refiere al proceso de alinear correctamente los objetos virtuales con el entorno real. 

		Es crucial para mantener la coherencia y la percepción de realidad, incluye:

	    Registro Espacial: 

	    	Alineación precisa de objetos virtuales en el espacio físico.


	    Registro Temporal: 

	    	Sincronización de movimientos y cambios en el entorno real y virtual.

		El rastreo implica monitorear la posición y orientación del dispositivo o del usuario para asegurar que los objetos virtuales se mantengan en la ubicación correcta.


	Superposición de Información

		La superposición se refiere a cómo se añaden elementos virtuales al entorno real.

		Hay diferentes niveles de superposición:

	    Superposición Aditiva:

	    	Añade elementos virtuales al entorno real sin modificarlo.


	    Superposición Sustractiva: 

	    	Elimina o modifica elementos del entorno real mediante efectos visuales.


	Interacción e Interfaz de Usuario

		La teoría de la interacción en AR se centra en cómo los usuarios manipulan y controlan los objetos aumentados:

	    Interacción Tangible: 

	    	Uso de gestos físicos para interactuar con objetos virtuales.


	    Interacción Gestual: 

	    	Uso de gestos con las manos para controlar y manipular los elementos aumentados.


	    Interacción por Voz: 

	    	Uso de comandos de voz para controlar el sistema AR


	Inteligencia Artificial y Contexto

		La AR se beneficia enormemente de la inteligencia artificial (IA) para comprender y responder al contexto del usuario:

	    Reconocimiento de Contexto:

	    	Identificación del entorno y situación del usuario para proporcionar información relevante.


	    Adaptabilidad: 

	    	Ajuste del contenido aumentado basado en las acciones y necesidades del usuario.

	
	Ética y Privacidad

		Las aplicaciones de AR también plantean importantes consideraciones éticas y de privacidad:

	    Privacidad de Datos: 

	    	Manejo seguro de la información capturada por los dispositivos AR.


	    Uso Ético: 

	    	Consideraciones sobre cómo se utilizan las tecnologías AR y el impacto en la sociedad.	


	Teoría de la Información

		La AR también se basa en teorías de la información para optimizar la transmisión y presentación de datos:

		Redundancia y Ruido: 

			Minimización del ruido (información no relevante) y optimización de la señal (información relevante) en la superposición de datos.


	Modelo de Realidad Aumentada

		Un modelo teórico de AR debe integrar los siguientes componentes:

	    Captura del Entorno Real:

	    	Sensores y cámaras que capturan el mundo físico.


	    Procesamiento de Datos:

	    	Algoritmos que analizan y procesan la información del entorno.


	    Generación de Contenido Virtual: 

	    	Creación de objetos y datos virtuales que se superponen al entorno real.


	    Interfaz de Usuario: 

	    	Métodos de interacción que permiten al usuario manipular el contenido aumentado.



....


|| AV
	

	

....


|| VR

	Interacción Humano-Computadora (HCI) en VR

	Inmersión y presencia
	
	Percepción y cognición en entornos virtuales

	Sensores y controladores de movimiento
	
	Sistemas de retroalimentación háptica

	Unity, Unreal Engine

	SteamVR, Oculus SDK, OpenXR

	C#, C++

	Unity y Unreal Engine

	Técnicas de rastreo de movimiento y posición en VR

    Sistemas de posicionamiento absoluto y relativo	

    Interacción mediante controladores de movimiento y gestos

    Integración de comandos de voz y retroalimentación háptica

    Rendimiento y latencia

    Mareo por movimiento (motion sickness)



|| VR

	Tecnología que crea entornos completamente digitales en los que los usuarios pueden sumergirse e interactuar. 

	Estos entornos simulan la presencia física en lugares reales o imaginarios, proporcionando una experiencia inmersiva que puede ser visual, auditiva e incluso táctil


	Componentes:

		Hardware:

		    Cascos o gafas VR:

		    	Dispositivos que se colocan en la cabeza del usuario y contienen pantallas frente a los ojos para mostrar el entorno virtual.

		    	Ejemplos como Oculus, PlayStation VR.


		    Controladores: 

		    	Dispositivos de mano que permiten al usuario interactuar con el entorno virtual, rastrean los movimientos y pueden tener botones, joysticks y sensores táctiles.


		    Sensores y cámaras: 

		    	Utilizados para rastrear la posición y movimientos del usuario en el espacio, proporcionando datos para ajustar la perspectiva del entorno virtual en tiempo real.


		    Computadoras y consolas:

		    	Equipos que procesan el contenido VR y generan los gráficos en 3D.		


		Software:

		    Motores de juego y gráficos: 

		    	Plataformas como Unity y Unreal Engine que se utilizan para desarrollar experiencias y entornos VR.


		    Aplicaciones y experiencias VR:

		    	Programas específicos que proporcionan contenido y actividades dentro de la realidad virtual, desde juegos hasta simulaciones educativas y de entrenamiento.


	Conceptos Tecnológicos Claves:

		Inmersión: 

			La inmersión se refiere al grado en que la VR puede hacer que el usuario se sienta presente en el entorno virtual. 

			Esto se logra a través de gráficos detallados, audio espacial y, a veces, retroalimentación háptica (táctil).


		Interacción

		    La interacción en VR permite a los usuarios manipular objetos y navegar por el entorno virtual usando controladores, gestos, o incluso comandos de voz.


		Campo de Visión (FOV)

		    El campo de visión es el ángulo de la escena virtual que se muestra al usuario. 

		    Un FOV amplio contribuye a una mayor sensación de inmersión.


		Rastreo y Seguimiento

		    Los sistemas de VR rastrean los movimientos de la cabeza y, a veces, del cuerpo completo del usuario para ajustar la vista del entorno virtual en tiempo real, asegurando que los cambios en perspectiva sean naturales y precisos.


		Latencia

		    La latencia es el retraso entre los movimientos del usuario y la actualización del entorno virtual. 

		    Baja latencia es crucial para evitar mareos y proporcionar una experiencia fluida.


	Usos: 	

		Juegos y Entretenimiento:

		    Videojuegos inmersivos que permiten a los jugadores vivir experiencias intensas y detalladas.


		Educación y Entrenamiento:

		    Simulaciones que permiten a los estudiantes y profesionales practicar habilidades en entornos seguros y controlados, como entrenamientos médicos o simuladores de vuelo.


		Arquitectura e Ingeniería:

		    Visualización de diseños en 3D antes de la construcción, permitiendo la inspección y modificación en un entorno virtual.


		Medicina:

		    Terapias de exposición para tratar fobias y trastornos de estrés postraumático, así como entrenamiento quirúrgico.


		Viajes Virtuales:

		    Explorar lugares y entornos lejanos o inaccesibles sin salir de casa.


	Desafíos:	

		Mareo y Fatiga Visual:

			Algunas personas pueden experimentar mareos y molestias debido a la latencia o desajustes visuales.


		Accesibilidad y Usabilidad:

			La tecnología puede no ser accesible para todas las personas, especialmente aquellas con discapacidades físicas.	



....


|| MR
	
	Interacción Humano-Computadora (HCI) en MR

	Continuum de Realidad-Virtualidad
	
	Percepción y cognición en entornos mixtos

	Sensores y cámaras de profundidad
		
	Controladores de movimiento y retroalimentación háptica

	Técnicas de mapeo espacial y reconocimiento de objetos

    Registro preciso de objetos virtuales en el mundo real	

    Interacción gestual y por voz
    
    Integración de retroalimentación háptica



|| MR
	
	La realidad mixta es una tecnología que combina elementos de la realidad aumentada (AR) y la realidad virtual (VR), creando entornos donde los objetos digitales y físicos coexisten e interactúan en tiempo real. 

	A diferencia de la AR, que solo superpone información digital al mundo real, o la VR, que sumerge al usuario en un entorno completamente virtual, la MR permite una interacción más dinámica y bidireccional entre ambos mundos.


	Componentes:

		Hardware: 

			Gafas y cascos MR:

				Dispositivos que permiten ver el entorno real con elementos digitales superpuestos y que interactúan con él.


		    Controladores y sensores:

		    	Herramientas que rastrean el movimiento de las manos y otros objetos físicos, permitiendo una interacción natural con los elementos virtuales.


		    Cámaras y sensores de profundidad: 

		    	Dispositivos que mapean el entorno real en 3D, permitiendo una integración precisa de objetos virtuales.


		Software

		    Motores de gráficos y realidad mixta: 

		    	Plataformas como Unity y Unreal Engine, que proporcionan las herramientas necesarias para desarrollar aplicaciones y experiencias de MR.


		    Sistemas operativos y plataformas: 

		    	Sistemas específicos para MR, como Windows Mixed Reality, que soportan y gestionan el funcionamiento de las aplicaciones de MR.


	Conceptos Tecnológicos Claves: 

		Mapeo y Comprensión del Entorno:

		    Mapeo Espacial: 

		    	Creación de un modelo 3D del entorno real mediante sensores y cámaras, permitiendo a los objetos virtuales interactuar con objetos físicos.


		    Reconocimiento de Objetos y Superficies:

		    	Identificación y seguimiento de objetos y superficies en el entorno real para que los elementos virtuales puedan alinearse y comportarse de manera coherente con ellos.


		Interacción Natural

		    Interacción Gestual: 

		    	Uso de gestos de las manos para manipular objetos virtuales, como mover, rotar o escalar elementos digitales.


		    Reconocimiento de Voz:

		    	Permite el control de elementos virtuales y la ejecución de comandos mediante la voz.


		    Retroalimentación Háptica: 

		    	Uso de dispositivos que proporcionan sensaciones táctiles, mejorando la inmersión y la interacción con objetos virtuales.


		Inmersión e Interacción

		    Persistencia de Objetos Virtuales: 

		    	Los objetos virtuales permanecen en la misma posición y estado incluso cuando el usuario se mueve o cambia su vista.


		    Interacción Físico-Digital: 

		    	Los objetos virtuales pueden responder a las acciones del usuario y las condiciones del entorno real, como la iluminación y la física.	


	Usos: 

		Educación y Entrenamiento

		    Simulaciones interactivas que permiten a los estudiantes practicar habilidades en un entorno seguro, como entrenamiento médico o técnico.

		    Visualización de conceptos complejos mediante modelos 3D que se integran con el entorno real.


		Industria y Manufactura

		    Asistencia en tiempo real para el ensamblaje y reparación de maquinaria, mostrando instrucciones y guías directamente en el campo de visión del trabajador.

		    Diseño y prototipado de productos en 3D, permitiendo a los ingenieros y diseñadores colaborar en un entorno compartido.


		Arquitectura y Construcción

		    Visualización de planos y modelos arquitectónicos en el sitio de construcción, facilitando la inspección y modificación de diseños en tiempo real.

		    Superposición de modelos 3D sobre estructuras existentes para planificar renovaciones y mejoras.


		Entretenimiento y Juegos

		    Experiencias de juego inmersivas donde los elementos virtuales interactúan con el entorno físico del jugador.

		    Producción de contenido multimedia interactivo que combina actores reales con entornos y objetos virtuales.


		Salud y Medicina

		    Visualización de datos médicos, como imágenes de resonancia magnética y tomografías, en el espacio real del paciente para mejorar el diagnóstico y la planificación quirúrgica.

		    Terapias y rehabilitación mediante entornos virtuales que responden a las acciones del paciente.


	Beneficios: 

		Natural: 

			Permite una interacción más intuitiva y natural con elementos virtuales mediante gestos y comandos de voz.
		

		Mayor Productividad:

			Mejora la eficiencia en tareas complejas al proporcionar información y asistencia en tiempo real.
		

		Colaboración Mejorada:

			Facilita la colaboración remota y presencial mediante la superposición de datos y modelos en un entorno compartido.


		Flexibilidad y Adaptabilidad:

			Se puede aplicar en una amplia gama de industrias y situaciones, desde la educación hasta la manufactura.


	Desafíos:	

		Necesidad de Espacios Adaptados: 

			Algunas aplicaciones de MR requieren espacios específicos y bien definidos para funcionar correctamente.


		Problemas de Precisión y Latencia: 

			La exactitud en el mapeo y la sincronización en tiempo real son cruciales y pueden ser un desafío técnico.		


	Promete una mayor integración con otras tecnologías emergentes como la inteligencia artificial, el aprendizaje automático y el Internet de las cosas (IoT).

	La realidad mixta combina lo mejor de la realidad aumentada y la realidad virtual, creando entornos híbridos donde los elementos físicos y digitales coexisten e interactúan de manera fluida y dinámica, ofreciendo vastas posibilidades en diversas áreas de aplicación.





