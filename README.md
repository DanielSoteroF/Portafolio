<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <div>
        <nav>
            <h3>DANY</h3>
            <ul class="nav">
                <li class="nav-item">
                  <a class="nav-link link-dark" href="#inicio">Inicio</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link link-dark" href="#Sobremi">Sobre Mi</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link link-dark" href="#misproyectos">Proyectos</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link link-dark" href="#Contacto">Contacto</a>
                </li>
              </ul>
        </nav>

        <!--TITULO-->
        <main id="inicio">
          <div class="d-flex justify-content-evenly">
            <section>
              <h1 class="display-1" id="titulo">Desarrollador Frontend</h1>

              <div class="likendin_github">
                  <a href=""><img src="/Imagenes/Likening_logo.png" alt="" width="33px"></a>
                  <a href=""><img src="/Imagenes/Github_logo.png" alt="" width="33px"></a>
              </div>
            </section>

            <aside class="foto_perfil">
              <img class="rounded-circle" src="/Imagenes/Foto_Perfil.jpg" alt="">
            </aside>
          </div>

          <!--SKILLS-->
          <section class="skills">
            <h2>Skills</h2>
            
            <div class="skills_img">
              <img src="/Imagenes/HTML5_logo.png" alt="" width="68px" height="68px" >
              <img src="/Imagenes/CSS3_logo.png" alt="" width="48px" height="68px">
              <img src="/Imagenes/JavaScript-logo.png" alt="" width="58px" height="55px">
            </div>
          </section>

          <!--SOBRE MI-->
          <section class="SobreMi" id="Sobremi">
            <h4>Sobre mi</h4>

            <div class="card text-center" id="card_sobremi" style="width: 70%;">
              <div class="card-body">
                <h5 class="card-title">DANIEL SOTERO</h5>
                <p class="card-text">Estudiante de Computación e Informática en el instituto Cibertec de tercer Ciclo, Apto para tomar decisiones y cumplir objetivos bajo presión. Exigente de la calidad y responsabilidad. Capacidad para trabajar en equipo, proactivo, flexible al cambio manteniendo la disciplina y puntualidad correspondiente al trabajo.</p>
                <img class="position-absolute top-0 start-100 translate-middle" src="/Imagenes/Foto_Perfil.jpg" alt="" width="160px"
              height="160px">
              </div>
            </div>
          </section>

          <!--MIS PROYECTOS-->
          <section class="MisProyectos" id="misproyectos">
            <h4>Mis Proyectos</h4>

            <div class="card mb-3" id="card_misproyectos" style="max-width: 1168px;">
              <div class="row g-0">
                <div class="col-md-6">
                  <a href="">
                    <img id="proyecto1" src="Imagenes/MercadoMusic.png" class="img-fluid" alt="">
                  </a>
                </div>
                <div class="col-md-6">
                  <div class="card-body">
                    <h5 class="card-title">MERCADO MUSIC🎸</h5>
                    <p class="card-text">Una pagina personalizada de proyecto personal para institución CIBERTEC. Hermosa y minimalista.</p>
                    <p class="card-text"><strong>Tecnologías usadas</strong></p>
                    <img src="/Imagenes/HTML5_logo.png" width="44px" height="43px"
                    alt="">
                    <img src="/Imagenes/CSS3_logo.png" width="31px" height="43px" alt="">
                  </div>
                </div>
              </div>
            </div>

            <div class="card mb-3" id="card_misproyectos" style="max-width: 1168px;">
              <div class="row g-0">
                <div class="col-md-6">
                  <div class="card-body">
                    <h5 class="card-title">Fast Food🛒</h5>
                    <p class="card-text">Una pagina personalizada de proyecto personal para institución CIBERTEC. Hermosa y minimalista.</p>
                    <p class="card-text"><strong>Tecnologías usadas</strong></p>
                    <img src="/Imagenes/HTML5_logo.png" width="44px" height="43px"
                    alt="">
                    <img src="/Imagenes/CSS3_logo.png" width="31px" height="43px" alt="">
                    <img src="/Imagenes/JavaScript-logo.png" width="33px">
                  </div>
                </div>

                <div class="col-md-6">
                  <a href="">
                    <img id="proyecto1" src="Imagenes/FastFood.png" class="img-fluid" alt="">
                  </a>
                </div>
              </div>
            </div>
          </section>

          <section class="Contacto" id="Contacto">
            <h4>Contacto</h4>

            <p>
              Si estás interesado en contratarme. ¡Llámame, envíame un correo electrónico o conéctate y chatea conmigo a través de LinkedIn!
            </p>

            <div class="card text-center" id="card_sobremi" style="width: 70%;">
              <div class="card-body">
                 <div class="item_contac">
                  <a href=""><img src="/Imagenes/phone_icon.png" alt="" width="47px" height="50px"></a>
                  <p> +51 902308690</p>
                 </div>

                 <div class="item_contac">
                  <a href=""><img src="/Imagenes/gmail_logo.png" alt="" width="51px" height="40px"></a>
                  <p>danielsoterofarfan1@gmail.com</p>
                 </div>

                 <div class="item_contac">
                  <a href=""><img src="/Imagenes/Github_logo.png" alt="" width="33px" height="37px"></a>
                  <p> daniel-sotero-farf</p>
                 </div>
                
              </div>
            </div>
          </section>
        </main>

        <footer>
          <p>Creado por Daniel Sotero | Derechos de autor reservados</p>
        </footer>
    </div>
</body>
</html>  
