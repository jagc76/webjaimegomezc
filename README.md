<! DOCTYPE html >
< html  lang = " es " >
< cabeza >
    < meta  charset = " UTF-8 " >
    < meta  name = " viewport " content = " ancho = ancho del dispositivo, escala inicial = 1.0 " >
    <! - nombre de la pagina ->
    < título > Jaime Gómez Cañar </ título >
    <! - favicon es un icono o imagen que se inserta para personalizar 
        la pagina ->
    < link  rel = " icono de acceso directo " href = " faviconjaime.png " type = " image / x-icon " >
    <! - se crea un subprograma en css estilos para llamar a funciones 
        o arreglos ->
        < link  rel = " stylesheet " href = " https://use.fontawesome.com/c8c717c6e2.css " >
    < link  rel = " stylesheet " href = " estilos.css " >
    <! - se pega el linck de open sans obtenido de google fonts
    https://fonts.google.com/specimen/Open+Sans?query=open+sans&sidebar.open&selection.family=Open+Sans:ital,wght@0,300;0,400;0,600;0,800;1,800#standard-styles-->
    < link  href = " https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;0,800;1,800&display=swap " rel = " stylesheet " >
</ cabeza >
< cuerpo >
   < encabezado >
       <! - dentro del header se usa nav con un elemento a href con una 
        almohadilla para que no valla a ningun lado para los titulos 
        de inicio de pagina ->
       < nav >
           < Un  href = " # " > Inicio </ a >
           < Un  href = " # titulo1 " > Nuestro producto </ a >
           < Un  href = " # titulo2 " > Portafolios </ a >
           < Un  href = " # titulo3 " > que dicen Nuestros Clientes </ a >
           < Un  href = " # titulo4 " > Servicios </ a >
           < Un  href = " # titulo de final " > Contactos </ a >
       </ nav >
       <! - con sección clase "textos-header" se colocan los titulos y 
        subtitulos ->
       < section  class = " textos-header " >
           < h1 > Proyecta tu imagen </ h1 >
           < h2 > Con una pagina web potente </ h2 >
       </ sección >
       <! - con un dib de clase "ola" ola se hace el efecto de hola, en estilo 
        tenemos una altura de altura, desbordamiento por desbordamiento. un segundo estilo
        con altura-altura 100% y ancho-ancho 100%. un tercer estilo con
        stroke-trazo ninguno y fill-relleno de este codigo esta el color 
        que se le desea poner, se encuentra este codigo en este enlace: 
        https://smooth.ie/blogs/news/svg-wavey-transitions-between-sections-->
       < div  class = " wave " style = " height: 150px; overflow: hidden; " > < svg  viewBox = " 0 0 500 150 " preserveAspectRatio = " none "
              estilo = " altura: 100%; ancho: 100%; " >
              < ruta  d = " M0.00,49.98 C206.26,223.52 274.54,49.83 500.00,49.98 L500.00,150.00 L0.00,150.00 Z "
              style = " stroke: none; fill: #fff; " > </ path >
            </ svg > </ div >
   </ header >
   <! - se crea un main y con section se va generando la sección ->
   < principal >
       < section  class = " contenedor sobre-nosotros " >
        < Un  nombre = " titulo1 " > < h2  clase =" titulo " > Nuestro producto </ h2 > </ a >
           <! - se crea un dib class contendor-sobre-nosotros para contener 
            la imagen con una clase "imagen-acerca de nosotros" y tambien contiene 
            un div clase "contenido-textos" ->
           < div  class = " contenedor-sobre-nosotros " >
               < img  src = " programacionpresentacion.jpeg " alt = "" class = " imagen-about-us " >
               < div  class = " contenido-textos " >
                   <! - dentro del div tenemos un h3 donde pondresmos un span 
                    y lleva un numero para darle un estilo al texto ->
                   < h3 > < span > 1 </ span > Mi experiencia en la Policía Nacional </ h3 >
                   <! - elemento p que contiene un loren ->
                   < p > Técnico profesional en policía judicial, Técnico profesional en Servicio de policía,
                    Diplomado en Seguridad Policial, Diplomado en Gerencia Integral, Seminario
                    actualización institucional para el efectivo rendimiento Policial, Seminario Programa
                    de Protección a Víctimas y Testigos de la ley de Justicia y Paz, Seminario Sobre
                    Derecho Internacional Humanitario, Seminario en Proyecto de Vida, mi último
                    desempeño fue como Subcomandante de la estación de policía, también Labore en el
                    Valle como Comandante de Subestaciones de Policía, Comandante de Grupo de
                    Reacción de Dagua en la Vía al Mar, Comandante de CAI en Buenaventura, en la
                    Metropolitana de Medellín me desempeñe como Comandante de patrulla de
                    Vigilancia y patrulla de reacción motorizada en el Grupo CORAM, labore en
                    patrulla operativa en la SIJIN de Medellín. < Br >
                    Experiencia en manejo de Grupos de trabajo y personal durante 22 años de servicio
                    en la Policía Nacional.
                    </ p >
                   <! - se copia el h3 ypy se le cambia en el span el numero
                    1 por el 2 ->
                   < h3 > < span > 2 </ span > Mi nueva proyección profesional </ h3 >
                   < p > Estudiante de Tecnología de ADSI en el SENA CAB con proyección profesional en
                    la elaboración de productos para la web en responsive, asi como otras soluciones
                    tecnologicas en diferentes ambitos de la Industria. < param  name = "" value = "" >  </ p >
               </ div >
           </ div >
       </ sección >
       <! - se crea una sección con identificador de portafolio ->
       < section  class = " portafolio " >
           <! - se crea un div contenedor ->
           < div  class = " contenedor " >
               <! - se crea el titulo portafolio ->
               < Un  nombre = " titulo2 " > < h2  clase =" titulo " > Portafolios </ h2 > </ a >
               <! - se crea un div cass "galeria-port" ->
               < div  class = " galeria-port " >
                   <! - se crea un div class "imagen-port" ->
                   < div  class = " imagen-port " >
                       < img  src = " programacionresponsive.jpeg " alt = "" >
                       <! - dentro va otro div clase "hover-galeria" con su 
                        img de nombre dedo.png que sera el icono de señalar ->
                       < div  class = " hover-galeria " >
                           < img  src = " dedo.png " alt = "" >
                           <! - dentro llevara un p con un texto ->
                           < p > Nuestro trabajo </ p >
                       </ div >
                   </ div >
                   < div  class = " imagen-port " >
                       < img  src = " programacionresponsive1.jpg " alt = "" >
                       <! - dentro va otro div clase "hover-galeria" con su 
                       img de nombre dedo.png que sera el icono de señalar ->
                       < div  class = " hover-galeria " >
                           < img  src = " dedo.png " alt = "" >
                           <! - dentro llevara un p con un texto ->
                           < p > Nuestro trabajo </ p >
                       </ div >
                    </ div >
                    < div  class = " imagen-port " >
                        < img  src = " programacionresponsive2.jpg " alt = "" >
                        <! - dentro va otro div clase "hover-galeria" con su 
                         img de nombre dedo.png que sera el icono de señalar ->
                        < div  class = " hover-galeria " >
                            < img  src = " dedo.png " alt = "" >
                            <! - dentro llevara un p con un texto ->
                            < p > Nuestro trabajo </ p >
                        </ div >
                    </ div >
                    < div  class = " imagen-port " >
                        < img  src = " programacionresponsive3.jpeg " alt = "" >
                        <! - dentro va otro div clase "hover-galeria" con su 
                         img de nombre dedo.png que sera el icono de señalar ->
                        < div  class = " hover-galeria " >
                            < img  src = " dedo.png " alt = "" >
                            <! - dentro llevara un p con un texto ->
                            < p > Nuestro trabajo </ p >
                        </ div >
                    </ div >
                    < div  class = " imagen-port " >
                        < img  src = " programacion1.jpg " alt = "" >
                        <! - dentro va otro div clase "hover-galeria" con su 
                         img de nombre dedo.png que sera el icono de señalar ->
                        < div  class = " hover-galeria " >
                            < img  src = " dedo.png " alt = "" >
                            <! - dentro llevara un p con un texto ->
                            < p > Nuestro trabajo </ p >
                        </ div >
                    </ div >
                    < div  class = " imagen-port " >
                        < img  src = " programacion2.jpg " alt = "" >
                        <! - dentro va otro div clase "hover-galeria" con su 
                         img de nombre dedo.png que sera el icono de señalar ->
                        < div  class = " hover-galeria " >
                            < img  src = " dedo.png " alt = "" >
                            <! - dentro llevara un p con un texto ->
                            < p > Nuestro trabajo </ p >
                        </ div >
                    </ div >
                    < div  class = " imagen-port " >
                        < img  src = " programacion3.jpg " alt = "" >
                        <! - dentro va otro div clase "hover-galeria" con su 
                         img de nombre dedo.png que sera el icono de señalar ->
                        < div  class = " hover-galeria " >
                            < img  src = " dedo.png " alt = "" >
                            <! - dentro llevara un p con un texto ->
                            < p > Nuestro trabajo </ p >
                        </ div >
                    </ div >
                    < div  class = " imagen-port " >
                        < img  src = " programacion4.jpg " alt = "" >
                        <! - dentro va otro div clase "hover-galeria" con su 
                         img de nombre dedo.png que sera el icono de señalar ->
                        < div  class = " hover-galeria " >
                            < img  src = " dedo.png " alt = "" >
                            <! - dentro llevara un p con un texto ->
                            < p > Nuestro trabajo </ p >
                        </ div >
                    </ div >
                </ div >
           </ div >
       </ sección >
       <! - se crea un div class llamado clientes contenedor ->
       < section  class = " clientes contenedor " >
            <! - se coloca un titulo ->
            < Un  nombre = " titulo3 " > < h2  clase =" titulo " > que dicen Nuestros Clientes </ h2 > </ a >
            <! - se crea un div cards porque es el que lleva todo ->
               < div  class = " cards " >
                    <! - se crea un div que se llama card y llevara 
                      una imagen y otro div clase "contenido-texto-card"
                     con un h4 Nombre y un p lorem10 ->
                    < div  class = " tarjeta " >
                        < img  src = " clientealegre.png " alt = "" >
                            < div  class = " contenido-texto-card " >
                            <! - el nombre es de la persona que esta testificando
                             acerca de nosotros .-->
                                < h4 > Sector Privado </ h4 >
                                    < p > Desarrollo de soluciones que dejan satisfechos a clientes del
                                    sector privado </ p >
                            </ div >
                    </ div >
                    <! - se copia y pega el div class "tarjeta" anterior ->
                    < div  class = " tarjeta " >
                        < img  src = " alcaldia.jpg " alt = "" >
                            < div  class = " contenido-texto-card " >
                                < h4 > Sector Públicos </ h4 >
                                    < p > Desarrollo de software, aplicaciones y sitios en diferentes entidades
                                    publicas que ayudan en el mejor rendimiento de los empleados públicos haciendolos 
                                    mas eficicientes en sus labores.  </ p >
                            </ div >
                    </ div >
                </ div >
       </ sección >
       <! - se crea otra sección clase "about-services" para
        nuestros servicios ->
        < section  class = " about-services " >
            <! - se coloca un contenedor ->
            < div  class = " contenedor " >
                < Un  nombre = " titulo4 " > < h2  clase =" titulo " > Nuestros Servicios </ h2 > </ a >
                <! - se crea un div de la clase "servicio-cont" ->
                < div  class = " servicio-cont " >
                    <! - se crea dentro de otro div clase "servicio-ind"
                    el cual contiene una img., un h3 con el 
                    Nombre y un p con un lorem10 ->
                    < div  class = " servicio-ind " >
                        < img  src = " sistematizacion.jpg " alt = "" >
                        < h3 > Software para la Industria </ h3 >
                        < p > Desarrollode Software para la Industria en todas sus madalidades volviendo mas
                        productiva la empresa y por ende mas competitiva para un mercado que cada dia crece
                        y exige un mejor y más eficiente empleo de los recursos a menor costo y con una mayor
                         producción para satisfacer las necesidades mundiales. </ p >
                    </ div >
                    <! - se copia y se pegan los div class 
                    "servicio-int" las veces necesarias para
                    colocar los servicios. se agregan las
                    imagenes alucivas al servicio .-->
                    < div  class = " servicio-ind " >
                        < img  src = " sistematizacion1.jpg " alt = "" >
                        < h3 > Desarrollo Web </ h3 >
                        < p > Desarrollo de soluciones web que hacerquen a la empresa a la globalización,
                        por medio de Herramientas web que haran mas competitiva a la empresa y le daran 
                        presencia en la web con tan solo un clic desde cualquier parte del mundo, 
                        necesitamos vender los productos o prestar servicios sin presencia física del que 
                        oferta como del demanda, es un paso fundamental para modernizar la empresa. </ p >
                    </ div >
                    < div  class = " servicio-ind " >
                        < img  src = " Bigdata.jpg " alt = "" >
                        < h3 > Herramientas Big Data </ h3 >
                        < p > Desarrollo de herramientas que facilitan al usuario tener un programa potente
                        que acerque a su empresa a un eficiente aprovechamiento de las tecnologías de Big 
                        Datos que lo lleven a alcanzar el exito. . </ p >
                    </ div >
                </ div >
            </ div >
        </ sección >
   </ main >
   <! - se crea un pie de página que contenga la última parte del código ->
   < pie de página >
       < div  class = " contenedor-footer " >
           <! - dentro de un contenedor-pie de página se crea una clase div
            content-foo para almacenar un h4 y un p con un numero ->
           < div  class = " content-foo " >
               < h4 > Teléfono </ h4 >
               < p > < i  class = " fa fa-whatsapp " aria-hidden = " true " > </ i > 3192429987 </ p >
           </ div >
           < div  class = " content-foo " >
               < h4 > Correo electrónico </ h4 >
               < p > jgomez0685@misena.edu.co </ p >
            </ div >
           < div  class = " content-foo " >
               < h4 > Ubicación </ h4 >
               < p > Calle 19 # 16-02 </ p >
            </ div >
       </ div >
       < Un  nombre = " titulo de final " > < h2 > & copy; Jagc | Jaime Gómez Cañar </ h2 > </ a >
   </ pie de página >
</ cuerpo >
</ html >
