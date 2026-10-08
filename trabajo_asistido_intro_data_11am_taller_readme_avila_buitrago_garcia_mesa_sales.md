# Aleksandr Kogan...

<div align="right">
  
##  ...y la intervención de Cambridge Analytica<br>en las elecciones presidenciales de 2016 en EEUU
  
</div>

## *Introducción*
El caso de ***Aleksandr Kogan*** y ***Cambrige Analytica*** representa uno de los casos más criticos en la historia de la ciencia de datos moderna, la seguridad digital y la gobernanza de datos. Todo comenzo como un proyecto de investigación en psicología computacional y termino convirtiendose en una de las mayores filtraciones de datos en la historia de las redes sociales y en una herramienta de control social masiva utilizada en las elecciones presidenciales de Estados Unidos en 2016.

Este caso demuestra como la mineria de datos sin control y modelado psicográfico puede modelar la opinión pública e influir en los procesos democráticos sin el consentimiento de los usuarios.

## *Contexto Histórico* 

En los años **2014 a 2016** en el escenario politico y digital ocurria lo siguente:
- **El auge del *Big Data* en redes sociales:** En 2014, plataformas como Facebook tenian políticas de privacidad debibles y APIs abiertas que permitían a los desarrolladores externos acceder a grandes volumenes de datos de los usuarios.
- **El escenario politico en 2016:** La disputa electoral en EE.UU. entre Donald Trump y Hillary Clinton fue el escenario ideal para probar nuevas estrategias de publicidad altamente segmentadas.

## *¿Por qué fue un evento tan influyente?*
>[!IMPORTANT]
>Este caso fue hito en el mundo de la tecnología, la política y en el manejo de datos.

1. **Privacidad Digital:** Cambió la forma en que los usuarios, gobiernos y empresas perciben el valor y la vulnerabilidad de la información personal en internet.
2. **Tranformación en las regulaciones:** Fue un catalizador que aceleró la aprobación y aplicación de leyes estrictas de protección de datos a nivel mundial.
3. **Redifinió las campañas electorales:** Demostró que las elecciones en el auge de las redes sociales ya no solo dependen de los medios tradicionales (TV o radio), sino mediante el uso de algoritmos de segmentación y análisis masivo de datos.
4. **Marco precedentes para los gigantes tecnologicos:** Obligó a empresas como Facebook (Meta) a enfrentar investigaciones gubernamentales, pagar multas multimillonarias y reestructurar el acceso de terceros a sus plataformas.

### *Estructura del documento*

Para explicar en detalle este proyecto en ciencia de datos el documento tiene las siguentes secciones:
<details>
<summary>Haga click para desplegar</summary>
  
1. **Recolección de datos:** Detalle sobre el método de recopilación de Aleksandr Kogan y las herramientas utilizadas.
2. **Procesamiento de datos:** Estrategia de analisis aplicada por Cambridge Analytica.
3. **Implicaciones éticas y conclusiones:** Reflexión sobre la responsabilidad en Ciencia de Datos y el impacto en la gobernanza de datos actual.
   
</details>

- ## El papel de Kogan: ¿Quién es en esta historia?

  - Entre 2012 y 2016, coincidiendo con la transición de las redes sociales a los dispositivos móviles, hubo un gran auge de aplicativos y sitios web que contenían *Tests de personalidad*. En este contexto, entre el año 2013 y 2014, Kogan creo una encuesta titulada ***"This is your digital life"***, que, según sus declaraciones, tenía la única finalidad de estudiar fenómenos comportamentales para avanzar en su campo de investigación: la psicología.
  
  - A través de esta encuesta, que fue respondida por unos 270.000 usuarios, Kogan no solo obtuvo los perfiles psicológicos de quienes la respondieron, sino que, por medio de los permisos que pedía su aplicativo y debido a una ***falla en la construcción de la API de Facebook***, pudo capturar información completa de los perfiles de Facebook de todas las personas en la lista de amigos de cada usuario que interactuó con la encuesta, lo que hizo que el número de datos filtrados creciera de forma exponencial.

   > ### ¡ IMPORTANTE !
   > 
   > Kogan logro obtener no solo caracterizaciones básicas sino **DATOS DE INTERACCIONES** de hasta **81 MILLONES DE PERSONAS**, que     como veremos a continuación, pueden reflejar incluso con mayor precisión el perfil psicológico de un usuario que las propias encuestas respondidas.
   >
   > En la base de datos que recopiló Kogan se encontraban datos desde los capturados "más evidentes", como los ***Likes*** y los ***comentarios***, hasta los menos controlables y ni siquiera visibles para los usuarios, como las preferencias de contenido de cada uno con base en los ***tipos de perfiles con los que más interactuaban***.
   >
   
   - Tras su recopilación, considerada ***ilegítima*** porque contenía datos de personas que no interactuaron con la encuesta y que por ende no habían aceptado los términos y condiciones, Kogan vendió la base a la compañía inglesa Cambridge Analytica.
   - Finalmente, al momento de dar declaraciones, Kogan argumentó que todos los involucrados pretendían usarlo como un ***chivo expiatorio***, puesto que, dejando de lado la corrección moral del asunto, debe tenerse en cuenta que:
     
       - La responsabilidad de la protección de los datos de los usuarios depende de la plataforma que los almacena (en este caso Facebook). Así pues, "sin importar la intención del investigador", fue Facebook quien permitió que la información de los usuarios que no habían consentido se filtrara gracias la arquitectura de su software.
       - La práctica de comprar, vender y hacer transferencias con bases de datos (incluso de personas) está totalmente protegida por la ley y es extremadamente común en el mundo de las redes sociales.
         
    - Así pues, Aleksandr Kogan traslada toda la responsabilidad de los hechos a las dos grandes empresas involucradas, quienes almacenaron los datos de manera deficiente y los trataron con un objetivo coercitivo respectivamente.
 
### y entonces... ¿Qué hizo Kogan con los datos?

Lo importante del trabajo de Kogan no fue la recopilación de los datos si no poder construir **perfiles psicometricos** de los usuarios a partir de estos, con información como likes, género, ubicación, edad, entre otros.... Esto para poder inferir características de la personallidad a partir de su comportamiento en las redes.

Uno de los datos más importantes fueron los likes, porque estos permiten ver los patrones de lo que le gusta al usuario. 

Este tipo de datos se usaron para estimar lo que el llama los cinco grandes rasgos de la personalidad del modelo ***OCEAN***:

**O -> Openness:** o apertura
**C -> Conscientiousness:** La responsabilidad
**E -> Extraversion:** extraversión
**A -> Agreeableness:** amabilidad.
**N -> Neuroticism:** ell neuroticismo.

Podemos resumir el proceso en :

**Los datos extraídos de Facebook** -> **Patrones de comportamiento** -> **Perfíl psicométrico**

Más adelante los datos fueron transferidos de GSR a SCL, la empresa vinculada a **Cambridge Analytica**, que usó esos datos junto con otras fuentes de información para segmentar audiencias políticas.

>[!IMPORTANT]
> Kogan estuvo involucrado en la **recopilación de datos** y el **desarrollo de modelos psicométricos**.
> El uso de estos datos para la segmentación política correspondió a Cambridge Analytica.
  

  
    

