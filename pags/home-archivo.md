---
layout: portada-archivo
title: Archivo Histórico JVA
---
<!-- Carousel -->
    <div class="demo_wrapper">
      <div class="demo_block">
      <ul id="demo1">
        <li><a href="#slide1"><img src="{{ site.baseurl }}/img/img-carousel/foto-2-carrousel.jpg" alt="TOR tri 04 - Torneo Triagón - 108" ></a></li>
        <li><a href="#slide2"><img src="{{ site.baseurl }}/img/img-carousel/foto-carrousel7.jpg"  alt="PH-AP ver 71 - Phalène Quinta Vergara - 49"></a></li>
        <li><a href="#slide3"><img src="{{ site.baseurl }}/img/img-carousel/foto-carrousel-8.jpg" alt="EX bie 10 - IV Bienal de Diseño - Chile se diseña (faenas escuela) - 10"></a></li>
      </ul>
      </div>
    </div>    
    <script>
      $(function() {
        var demo1 = $("#demo1").slippry({
          transition: 'fade',
          useCSS: true,
          speed: 1000,
          pause: 3000,
          auto: true,
          preload: 'visible'
        });

        $('.stop').click(function () {
          demo1.stopAuto();
        });

        $('.start').click(function () {
          demo1.startAuto();
        });

        $('.prev').click(function () {
          demo1.goToPrevSlide();
          return false;
        });
        $('.next').click(function () {
          demo1.goToNextSlide();
          return false;
        });
        $('.reset').click(function () {
          demo1.destroySlider();
          return false;
        });
        $('.reload').click(function () {
          demo1.reloadSlider();
          return false;
        });
        $('.init').click(function () {
          demo1 = $("#demo1").slippry();
          return false;
        });
      });
    </script>

<!--      CONTENIDO CENTRAL     -->


<div class='col-lg-12 col-md-12'>
    <div class='wrap'>
        <div class='division-seccion'>
          <h3><i class="icn icn-noticias icn-lg "></i> Noticias</h3>
        </div>

        <div class='fila bloque-enlace'> <!-- Noticia destacada -->

            <div class='col-lg-12 col-md-12 col-sm-12  margen-superior'>
                <div class='col-lg-5'>
                    <img class= 'destacada-archivo' src='{{ site.baseurl }}/img/img-archivo/foto-noticia1.jpg'>          
                    <div class='indice-fecha fondo-negro-claro'>
                      <div class='linea-vert-fecha fondo-blanco'></div>
                      <div class='contenedor-fecha'>
                          <p class='fecha-destacado centrada'> 22 <br/></p>
                          <p class='fecha-destacado centrada'>abr</p>
                      </div>
                    </div>
                </div>       
            </div>

            <div class='col-lg-6 col-lg-offset-0'> 
                <div class='col-lg-9'>
                    <h6 class='gris-oscuro margen-superior'>Valparaíso antiguo</h6>
                    <h2 class='rojo-claro fina'>Un retrato de la vida en los cerros</h2>
                </div>

                <div class='col-lg-10'>
                    <p class='xs gris-oscuro fina'>Los griegos no conocieron la fotografía, pero de haberlo hecho,tal vez la hubiesen llamado la “escritura de la luz”. Eso es lo que exactamente hacen estas y acaso todas las fotografías y por ello en esta Escuela somos afortunados, pues durante muchos años-décadas- tuvimos a alguien dedicado, en preocupación y pasión,a escribirnos con la luz.</br>  Don Juan Hernández dedicó su escritura de la luz a escribirnosa nosotros, a este pueblo poético, en sus quehaceres y aconteceres. Es decir, en su tiempo y lugar. Su tiempo que era y sigue siendo el juego en los vientos efímeros de la palabra de la poesía, y su lugar que fue y sigue siendo, esencialmente, los obrares leves de los oficios en Valparaíso y en las arenas.</p></br> 
                </div>
                        
                <div class='margen-icn-mas'>
                    <a href='noticia-dest.html'><i class='icn icn-mas icono-mas icn-lg rojo-claro'></i></a>
                </div>  
            </div>
        </div> <!-- fin noticia destacada -->
    </div> <!-- fin wrap -->
</div>


<p> <!-- fin fila --></p>

<!-- Inicio noticias varias -->

<div class='fila'>
    <div class="col-lg-12">

        <div class='col-sm-2'>
            <div class='cont-noticia-previa'>

                <img class='foto-interior-pub' src='{{ site.baseurl }}/img/img-archivo/seminario-dis.jpg'>                
                <div class='titulo-noticia-prev'>
                    <a href='#'><span class="rojo-claro">“De la hipótesis al Diseño: Aproximaciones, casos y obras”<p class='subtitulo'>El objetivo del seminario es dar lugar a la exposición e intercambio de ideas referidas al diseño, creando una instancia [...] </p></span></a>
                </div>
            </div>
        </div>

        <div class='col-sm-2'>
            <div class='cont-noticia-previa'>
               
                <img class='foto-interior-pub' src='{{ site.baseurl }}/img/img-archivo/concurso-vergel.jpg'> 

                <div class='titulo-noticia-prev'>
                    <a href='#'><span class="rojo-claro">Convocatoria Concurso de Ideas y Relatos: Vergel 439 <p class='subtitulo'>Producto del trágico siniestro que afectó a la ciudad de Valparaíso el pasado 12 de abril de 2014, el académico Luis Álvarez Aránguiz,[...]</p></span></a>
                </div>
            </div>
        </div>

        <div class='col-sm-2'>
            <div class='cont-noticia-previa'>

                <img class='foto-interior-pub' src='{{ site.baseurl }}/img/img-archivo/Ojos-Gato-2014.png'>                
                <div class='titulo-noticia-prev'>
                    <a href='#'><span class="rojo-claro">Presentación Libro "Los Ojos del Gato" Memorial de Edison Simons <p class='subtitulo'>Se llevó a cabo en la Escuela la inauguración de la exposición de grabados del poeta panameño Edison Simons, y el lanzamiento del libro[...]</p></span></a>
                </div>
            </div>
        </div> 

        <div class='col-sm-2'>
            <div class='cont-noticia-previa'>
                
                <img class='foto-interior-pub' src='{{ site.baseurl }}/img/img-archivo/inauguracion-expo.jpg'>

                <div class='titulo-noticia-prev'>
                    <a href='#'><span class="rojo-claro">Exposición Travesía Magallanes 2013 en Museo Marítimo Nacional <p class='subtitulo'>En el contexto de la celebración del 99° aniversario del Museo Marítimo Nacional, esta mañana se inauguró la exposición Travesía Magallanes 2013,[...]</p></span></a>
                </div>
            </div>
        </div>

        <div class='col-sm-2'>
          <h6 class='negro-claro altas chica'>más noticias</h6>
            <div class='cont-noticia-previa'>
                <div class='cont-icono-fecha margen-lista '>
                    <i class='icn icn-noticias icn-md rojo-claro'></i>
                    <span class='gris-oscuro datos-publicacion'>viernes 16 de Mayo de 2014</span>
                </div>
                <div class='titulo-noticia-prev'>
                    <a href='#'><p class='subtitulo rojo-claro'>Proyectos de la e[ad] seleccionados por Fondo “Ideas y Manos para Valparaíso”</p></a>
                </div>
                
                <div class='cont-icono-fecha margen-lista'>
                    <i class='icn icn-noticias icn-md rojo-claro'></i>
                    <span class="gris-oscuro datos-publicacion">lunes 5 de mayo de 2014</span>
                </div>
                <div class='titulo-noticia-prev'>
                    <a href='#'><p class='subtitulo rojo-claro margen-lista'>Concursos de Innovación y Emprendimiento: postulaciones hasta el 11 de mayo</p></a>
                </div>               
            </div>
        </div>
   </div> <!-- fin col-lg-12 -->
</div>


<p> <!-- fin fila --></p>

<!-- fin de Noticia destacada -->

<!--  Inicio Álbumes destacados -->


<div class='col-lg-12'>
    <div class='wrap'>
        <div class='division-seccion'>
            <h3><i class="icn icn-estrella-l icn-lg "></i> Álbumes destacados</h3>
        </div>
        <div class='fila'>

            <div class='col-lg-12 margen-superior'>

                <div class='col-lg-2 col-md-4- col-sm-6 col-xs-12 fondo-gris-claro altura-destacados margen-destacados'>
                    <img class='altura-foto-interior margen-superior' src='{{ site.baseurl }}/img/img-archivo/foto-album-1.jpg'></br>
                    <div class='cuadro-icono fondo-negro-claro'><i class= 'icn icn-acto icn-lg blanco col-lg-offset-3'></i> </div>

                    <h6 class='rojo-claro fina texto-cuadro-des'>Montaje y Exposición:</br>4ta Bienal Chile se Diseña</h6> <h6 class="datos-publicacion col-lg-12">Publicado día lunes 21 de Abril 2014.</h6>

                    <p class='xs negro-claro fina texto-cuadro-des margen-etiquetas '>Entre el 26 de noviembre y el 12 de diciembre de 2010 se realizó la 4ª Bienal de Diseño que marcó la refundación de las bienales de esta disciplina luego de 14 años de ausencia.</p> 

                    <p class="categorias-publicacion margen-superior-s">[ Diseño ] [ Actividades ]</p>  

                    <div class='margen-icn-mas'>
                      <a href='noticia-dest.html'><i class='icn icn-mas rojo-claro'></i></a>
                    </div>        
                </div>

                <div class='col-lg-2 col-md-4- col-sm-6 col-xs-12 fondo-gris-claro altura-destacados margen-destacados'>
                    <img class='altura-foto-interior margen-superior' src='{{ site.baseurl }}/img/img-archivo/foto-album-2.jpg'>
                    <div class='cuadro-icono fondo-negro-claro'><i class='icn icn-imagen icn-lg blanco col-lg-offset-3'></i></div> 

                    <h6 class='rojo-claro fina texto-cuadro-des'>Valparaíso Antiguo:</br>Capturas de Juan Hernández</h6> <h6 class="datos-publicacion col-lg-12">Publicado día miércoles 23 de Abril 2014.</h6>

                    <p class='xs negro-claro fina texto-cuadro-des margen-etiquetas'>Imágenes de la ciudad entre 1960 y 1980, que da cuenta de rasgos esenciales de la identidad original del puerto y su patrimonio,bajo el registro histórico de Juan Hernández, ex fotógrafo de la escuela.</p> 

                    <p class="categorias-publicacion margen-superior">[ Catastro ]</p>  

                    <div class='margen-icn-mas'>
                        <a href='noticia-dest.html'><i class='icn icn-mas rojo-claro'></i></a>
                    </div>        
                </div>

                <div class='col-lg-2 col-md-4- col-sm-6 col-xs-12 fondo-gris-claro altura-destacados margen-destacados'>
                    <img class='altura-foto-interior margen-superior' src='{{ site.baseurl }}/img/img-archivo/foto-album-3.jpg'>
                    <div class='cuadro-icono fondo-negro-claro'><i class='icn icn-travesia icn-lg blanco col-lg-offset-3'></i></div>

                    <h6 class='rojo-claro fina texto-cuadro-des'>Travesía Caldera:</br>Habitáculos para el desierto</h6><h6 class="datos-publicacion col-lg-12 ">Publicado día jueves 24 de Abril 2014.</h6>

                    <p class='xs negro-claro fina texto-cuadro-des margen-etiquetas'>Travesía al norte del país, realizada por alumnos de taller de Diseño Industrial y el profesor Ricardo Lang el año 1987.</p> 

                    <p class="categorias-publicacion margen-superior">[ Travesía ] [ Diseño Industrial ]</p>    
                        
                    <div class='margen-icn-mas'>
                        <a href='noticia-dest.html'><i class='icn icn-mas rojo-claro'></i></a>
                    </div> 
                </div>

                <div class='col-lg-2 col-md-4- col-sm-6 col-xs-12 fondo-gris-claro altura-destacados margen-destacados'>
                    <img class='altura-foto-interior margen-superior' src='{{ site.baseurl }}/img/img-archivo/travesia-tarabuco.jpg'>
                    <div class='cuadro-icono fondo-negro-claro'><i class='icn icn-travesia icn-lg blanco col-lg-offset-3'></i></div>

                    <h6 class='rojo-claro fina texto-cuadro-des'>Travesía Tarabuco:</br>Taller 2º año Diseño Industrial</h6><h6 class="datos-publicacion col-lg-12">Publicado día jueves 24 de Abril 2014.</h6>

                    <p class='xs negro-claro fina texto-cuadro-des margen-etiquetas'> Travesía realizada a Bolivia por el Taller de 2º año Diseño Industrial junto al profesor Juan Carlos Jeldes y su ayudante Daniela Salgado</p> 

                    <p class="categorias-publicacion margen-superior">[ Travesía ] [ Diseño Industrial ]</p>    
                        
                    <div class='margen-icn-mas'>
                        <a href='noticia-dest.html'><i class='icn icn-mas rojo-claro'></i></a>
                    </div> 
                </div>
            </div> <!-- fin col-lg-12 -->
        </div> <!-- fin fila -->
    </div> <!-- fin wrap -->
</div>


<p> <!-- fin col-lg-12 --></p>

<!-- fin álbumes destacados -->


<p></p>

<!-- inicio publicaciones recientes -->


<p></p>

<div class='col-lg-12'>
    <div class='wrap'>
        <div class='division-seccion'>
            <h3><i class="icn icn-etiqueta icn-lg "></i> Publicaciones recientes</h3>
        </div>
        <div class='fila'>
      
            <div class='col-lg-12 margen-superior'>
                
                    <div class='col-lg-2 col-md-4- col-sm-6 col-xs-12 fondo-gris-claro margen-destacados margen-cuadros'>
                        <img class='foto-interior-pub margen-superior' src='{{ site.baseurl }}/img/img-archivo/marimenuco-travesia.jpg'>
                        <div class='cuadro-icono fondo-negro-claro'><i class='icn icn-imagen icn-lg blanco col-lg-offset-3'></i></div></br>
                        
                        <h6 class='rojo-claro fina texto-cuadro-des'>Travesía Marimenuco 2012</h6> 
                        <h6 class="datos-publicacion col-lg-21 col-lg-offset-2">Publicado día viernes 25 de Abril 2014.</h6> 
                        
                        <p class='xs negro-claro fina texto-cuadro-des margen-etiquetas'>Obra realizada anteriormente por estudiantes y docentes de Tercer Año de Arquitectura donde  se construyó una ruca para que los lugareños pudiesen celebrar su Wetripantu o año nuevo mapuche.</p>
                        <p class="categorias-publicacion margen-superior">[ Travesías ] [ Diseño Industrial ]</p>    
                        
                        <div class='margen-icn-mas'>
                            <a href='noticia-dest.html'><i class='icn icn-mas rojo-claro'></i></a>
                        </div>        
                    </div>
                    
                    <div class='col-lg-2 col-md-4- col-sm-6 col-xs-12 fondo-gris-claro margen-destacados margen-cuadros'>
                        <img class='foto-interior-pub margen-superior' src='{{ site.baseurl }}/img/img-archivo/foto-pub-2.jpg'>
                        <div class='cuadro-icono fondo-negro-claro'><i class='icn icn-parlante-l icn-lg blanco col-lg-offset-3'></i></div>
                        
                        <h6 class='rojo-claro fina texto-cuadro-des'>Taller de Amereida</h6> 
                        <h6 class="datos-publicacion col-lg-21 col-lg-offset-2">Publicado día miércoles 30 de Abril 2014.</h6>
                        
                        <p class='xs negro-claro fina texto-cuadro-des margen-etiquetas'>El Taller de Amereida es la instancia en que se reúne prácticamente la totalidad del cuerpo de la Escuela. es decir, estudiantes y profesores, a construir y debatir precisamente ese ser cuerpo.</p> 
                        <p class="categorias-publicacion margen-superior">[ Actividades ] [Taller de Amereida ]</p>    
                        
                        <div class='margen-icn-mas'>
                            <a href='noticia-dest.html'><i class='icn icn-mas rojo-claro'></i></a>
                        </div>        
                    </div>
                    
                    <div class='col-lg-2 col-md-4- col-sm-6 col-xs-12 fondo-gris-claro margen-destacados margen-cuadros'>
                        <img class='foto-interior-pub margen-superior' src='{{ site.baseurl }}/img/img-archivo/foto-pub-3.jpg'>
                        <div class='cuadro-icono fondo-negro-claro'><i class='icn icn-ojo-l icn-lg blanco col-lg-offset-3'></i></div>
                        
                        <h6 class='rojo-claro fina texto-cuadro-des'>Phalène de Horcones</h6>
                        <h6 class="datos-publicacion col-lg-21 col-lg-offset-2">Publicado día miércoles 30 de Abril 2014.</h6> 
                        
                        <p class='xs negro-claro fina texto-cuadro-des margen-etiquetas'> Registro audiovisual de la Phalène de Horcones realizada el año 1964. Su registro en video a través del canal de la escuela en Vimeo tiene una duración de 12 minutos con 9 segundos.</p> 
                        <p class="categorias-publicacion margen-superior">[ Actos poéticos ]</p>    
                        
                        <div class='margen-icn-mas'>
                            <a href='noticia-dest.html'><i class='icn icn-mas rojo-claro'></i></a>
                        </div> 
                    </div>
                    
                    <div class='col-lg-2 col-md-4- col-sm-6 col-xs-12 fondo-gris-claro margen-destacados margen-cuadros'>
                        <img class='foto-interior-pub margen-superior' src='{{ site.baseurl }}/img/img-archivo/pizarron20años-documentos.jpg'>
                        <div class='cuadro-icono fondo-negro-claro'><i class='icn icn-documento-l icn-lg blanco col-lg-offset-3'></i></div>
                        
                        <h6 class='rojo-claro fina texto-cuadro-des'>Exposición 20 años </h6>
                        <h6 class="datos-publicacion col-lg-21 col-lg-offset-2">Publicado día miércoles 30 de Abril 2014.</h6> 
                        
                        <p class='xs negro-claro fina texto-cuadro-des margen-etiquetas'>Muestra realizada en el Museo Nacional de Bellas Artes, Santiago, Chile; consta de pizarrones de 1,5 x 1,5 mt. escritos y dibujados a tiza blanca. Se digitalizaron negativos fotográficos de 6 x 6 mm. </p> 
                        <p class="categorias-publicacion margen-superior">[Exposiciones]</p>    
                        
                        <div class='margen-icn-mas'>
                            <a href='noticia-dest.html'><i class='icn icn-mas rojo-claro'></i></a>
                        </div> 
                    </div>
                </div> <!-- fin col-lg-12--> 
            </div> <!-- fin fila -->
        </div>   <!-- fin wrap -->
    </div>