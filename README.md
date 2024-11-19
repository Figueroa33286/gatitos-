<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Razas de Gatos</title>
    <style>

         .h1 {
            font-family: 'Pacifico', cursive; /* Fuente personalizada */
            color: #ff6347; /* Tomate */
            text-align: center;
            font-size: 48px;
            margin-top: 50px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3); /* Sombra elegante */
        }


  
        
        body {
            background-color: #8df169; /* Fondo verde pastel */
            font-family:'Pacifico', cursive;
            color:#ff6347;
            margin: 0;
            padding: 0;
        }
        

        header, footer {
            text-align: center;
            padding: 10px;
            background-color: #A8D5A2; /* Color del encabezado y pie de página */
            border: 1px solid #e1e1e1; /* Borde */
        }
        img {
            width: 500px;
            height: 200px;
            margin: auto;
            cursor: pointer;
            border-radius: 10px;
            transition: transform 0.3s ease; /* Efecto de suavidad al pasar el cursor */
        }

        img:hover {
            transform: scale(2.03); /* Zoom ligero al pasar el cursor */
        }

         /* Estilo para el modal */
         .modal {
        display: none;
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(230, 214, 214, 0.8);
        justify-content: center;
        align-items: center;
        z-index: 1000;
    }


    .modal img {
        max-width: 90%;
        max-height: 90%;
        border-radius: 10px;
    }

    .modal:target {
        display: flex;
    }

    .modal a {
        position: absolute;
        top: 50px;
        right: 50px;
        color: white;
        text-decoration: none;
        font-size: 24px;
        background: rgba(0, 0, 0, 0.7);
        padding: 5px 10px;
        border-radius: 5px;
    }

        nav {
            margin: 10px 0;
            text-align: center;
            background-color: #fff;
        }
        nav a {
            line-height: 30px;
            margin: 0 15px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        h1 {
            color: #555;
        }
        .raza {
            margin: 20px;
            padding: 15px;
            background-color: #FFF;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border: 1px solid #ddd;
        }
        .raza img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            border: 2px solid #ddd;
        }
        ul {
            list-style-type: square;
            padding-left: 20px;
        }

        /* Estilo del acordeón */
        input[type="checkbox"] {
            display: none;
        }

        label {
            background-color: #f1f1f1;
            color: #444;
            cursor: pointer;
            padding: 10px;
            width: 100%;
            border: none;
            text-align: left;
            font-size: 18px;
            margin: 5px 0;
            display: block;
            border-radius: 5px;
        }

        label:hover {
            background-color: #3d93e4;
        }

        .accordion-content {
            padding: 10px;
            display: none;
            overflow: hidden;
            background-color: #f9f9f9;
        }

        input[type="checkbox"]:checked + label + .accordion-content {
            display: block;
        }

        /* Media queries para hacer la web responsive */
        @media (max-width: 768px) {
            nav a {
                display: block;
                margin: 10px 0;
            }
            .raza {
                margin: 10px;
                padding: 10px;
            }
            .raza img {
                max-width: 100%;
            }

    /* Estilo general para las imágenes pequeñas */
    .accordion-content img {
        width: 200px;
        height: auto;
        margin: 10px 0;
        border-radius: 10px;
        cursor: pointer;
        transition: transform 0.3s ease;
    }

    .accordion-content img:hover {
        transform: scale(1.05);
    }
   
    
        }
    </style>
</head>

<body>
    <header>
        <h1 class="h1">Gatos</h1>
    </header>
   
        </style>
    </head>
    
        
    
        
    
   
    
    
    <main>
        <section id="razas" class="raza">
            <h2 style="font-family: 'Pacifico', cursive; color: #ff6347; text-align: center; font-size: 36px; text-transform: uppercase; letter-spacing: 3px; text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.3); transition: transform 0.3s ease; cursor: pointer;" 
            onmouseover="this.style.transform='scale(1.1)'" 
            onmouseout="this.style.transform='scale(1)'">
            Razas de Gatos
        </h2>

            <!-- Acordeón de razas con solo HTML y CSS -->
            <input type="checkbox" id="persa">
            <label for="persa">Persa</label>
           <div class="accordion-content">
               <a href="#persa-modal">
                   <img src="images/Persa.jpg" alt="Gato Persa">
               </a>
               <p>El gato Persa es conocido por su pelaje largo y su carácter tranquilo. Son gatos muy cariñosos y sociables.</p>
               <ul>
                   <li><strong>Origen:</strong> Persia</li>
                   <li><strong>Esperanza de vida:</strong> 12-17 años</li>
                   <li><strong>Peso:</strong> 3-5kg</li>
               </ul>
           </div>
           

           <input type="checkbox" id="siames">
           <label for="siames">Siames</label>
          <div class="accordion-content">
              <a href="#siames-modal">
                  <img src="images/Siames.jpg" alt="Gato Siamés">
              </a>
              <p>El Siamés es conocido por su elegancia, sus ojos azules y su naturaleza comunicativa.</p>
              <ul>
                <li><strong>Origen:</strong> Tailandia</li>
                <li><strong>Esperanza de vida:</strong> 15-20 años</li>
                <li><strong>Peso:</strong> 2.5-5.5 kg</li>
            </ul>
                
          </div>
          


           

            
       
            
            <input type="checkbox" id="maine-coon">
 <label for="maine-coon">Maine Coon</label>
<div class="accordion-content">
    <a href="#maine-coon-modal">
        <img src="images/MaineCoon.jpg" alt="Gato Maine Coon">
    </a>
    <p>El Maine Coon es una de las razas más grandes, con un pelaje grueso y una naturaleza amigable.</p>
    <ul>
        <li><strong>Origen:</strong> Estados Unidos</li>
        <li><strong>Esperanza de vida:</strong> 10-13 años</li>
        <li><strong>Peso:</strong> 5.9-8.2 kg</li>
    </ul>
</div>



<input type="checkbox" id="bengali">
<label for="bengali">Bengali</label>
<div class="accordion-content">
   <a href="#bengali-modal">
       <img src="images/Bengali.jpg" alt="Gato Bengali">
   </a>
   <p>El Bengalí es famoso por su pelaje con patrones similares a los de un leopardo, y su energía incansable.</p>
   <ul>
       <li><strong>Origen:</strong> Estados Unidos</li>
       <li><strong>Esperanza de vida:</strong> 12-16 años</li>
       <li><strong>Peso:</strong> 3.6-6.8 kg</li>
   </ul>
</div>

<input type="checkbox" id="siberiano">
<label for="siberiano">Siberiano</label>
<div class="accordion-content">
   <a href="#siberiano-modal">
       <img src="images/Siberiano.jpg" alt="Gato Siberiano">
   </a>
   <p>El gato Siberiano es robusto, con un pelaje espeso, y es muy amigable y juguetón.</p>
                <ul>
                    <li><strong>Origen:</strong> Rusia</li>
                    <li><strong>Esperanza de vida:</strong> 12-15 años</li>
                    <li><strong>Peso:</strong> 4-8 kg</li>
                </ul>
            </div>

            <input type="checkbox" id="ragdoll">
            <label for="ragdoll">Ragdoll</label>
            <div class="accordion-content">
               <a href="#ragdoll-modal">
                   <img src="images/Ragdoll.jpg" alt="Gato ragdoll">
               </a>
               <p>El Ragdoll es un gato relajado y extremadamente sociable, con un pelaje suave y semi-largo.</p>
               <ul>
                   <li><strong>Origen:</strong> Estados Unidos</li>
                   <li><strong>Esperanza de vida:</strong> 12-17 años</li>
                   <li><strong>Peso:</strong> 4-9 kg</li>
               </ul>
           </div>
       
           <input type="checkbox" id="esfinge">
           <label for="esfinge">Esfinge</label>
           <div class="accordion-content">
              <a href="#esfinge-modal">
                  <img src="images/Esfinge.jpg" alt="Gato esfinge">
              </a>
              <p>El Esfinge es un gato sin pelo, conocido por su apariencia única y su carácter afectuoso.</p>
            <ul>
                <li><strong>Origen:</strong> Canadá</li>
                <li><strong>Esperanza de vida:</strong> 8-14 años</li>
                <li><strong>Peso:</strong> 3.5-7 kg</li>
            </ul>
          </div>
         
          <input type="checkbox" id="birmano">
          <label for="birmano">Birmano</label>
          <div class="accordion-content">
             <a href="#birmano-modal">
                 <img src="images/Birmano.jpg" alt="Gato birmano">
             </a>
             <p>El Birmano es un gato con un hermoso pelaje semi-largo, conocido por su naturaleza calmada y afectuosa.</p>
             <ul>
                 <li><strong>Origen:</strong> Birmania</li>
                 <li><strong>Esperanza de vida:</strong> 12-16 años</li>
                 <li><strong>Peso:</strong> 3.5-6 kg</li>
             </ul>
         </div>
        
         <input type="checkbox" id="british-shorthair">
         <label for="british-shorthair">British-Shorthair</label>
         <div class="accordion-content">
            <a href="#british-shorthair-modal">
                <img src="images/BritishSorthair.jpg" alt="Gato british-shorthair">
            </a>
            <p>El British Shorthair es un gato de cuerpo robusto, con un pelaje corto y denso, y una personalidad tranquila.</p>
            <ul>
                <li><strong>Origen:</strong> Reino Unido</li>
                <li><strong>Esperanza de vida:</strong> 12-20 años</li>
                <li><strong>Peso:</strong> 4-8 kg</li>
            </ul>
        </div>

        <input type="checkbox" id="exoticodepelocorto">
        <label for="exoticodepelocorto">Exotico De Pelo Corto</label>
        <div class="accordion-content">
           <a href="#exoticodepelocorto-modal">
               <img src="images/ExoticoDePeloCorto.jpg" alt="Gato exoticodepelocorto">
           </a>
           <p>El Exótico de Pelo Corto es similar al Persa, pero con un pelaje más corto. Es una raza tranquila y afectuosa.</p>
           <ul>
               <li><strong>Origen:</strong>Estados Unidos</li>
               <li><strong>Esperanza de vida:</strong> 12-15 años</li>
               <li><strong>Peso:</strong> 3.5 6kg</li>
           </ul>
       </div>

       <input type="checkbox" id="abisinio">
       <label for="abisinio">Abisinio</label>
       <div class="accordion-content">
          <a href="#abisinio-modal">
              <img src="images/Abisinio.jpg" alt="Gato abisinio">
          </a>
          <p>El Abisinio es una raza activa y curiosa, con un pelaje corto y un temperamento vivaz.</p>
                <ul>
                    <li><strong>Origen:</strong>Etiopía</li>
                    <li><strong>Esperanza de vida:</strong> 9-15 años</li>
                    <li><strong>Peso:</strong> 2.7-4.5 kg</li>
                </ul>
            </div>

            <input type="checkbox" id="scottish-fold">
            <label for="scottish-fold">Scottish Fold</label>
            <div class="accordion-content">
               <a href="#scottishfold-modal">
                   <img src="images/ScottishFold.jpg" alt="Gato scottish-fold">
               </a>
               <p>El Scottish Fold es conocido por sus orejas dobladas hacia adelante, lo que le da una apariencia única.</p>
                <ul>
                    <li><strong>Origen:</strong> Escocia</li>
                    <li><strong>Esperanza de vida:</strong> 11 a 14 años</li>
                    <li><strong>Peso:</strong>  2.7-6 kg</li>
                </ul>
            </div>
     
            <input type="checkbox" id="chartreux">
            <label for="chartreux">Chartreux</label>
            <div class="accordion-content">
               <a href="#chartreux-modal">
                   <img src="images/Chartreux.jpg" alt="Gato Chartreux">
               </a>
               <p>El Chartreux es una raza francesa de gatos, conocida por su pelaje gris azulado y su comportamiento cariñoso .</p>
               <ul>
                   <li><strong>Origen:</strong>  Francia</li>
                   <li><strong>Esperanza de vida:</strong> 12-15 años</li>
                   <li><strong>Peso:</strong> 3,5-7 kg</li>
               </ul>
           </div>

           <input type="checkbox" id="burmes">
           <label for="burmes">Burmes</label>
           <div class="accordion-content">
              <a href="#burmes-modal">
                  <img src="images/gato-burmes.jpg" alt="Gato Burmes">
              </a>
              <p>El Burmés es una raza de origen Myanmar (Birmania), conocida por su pelaje marron claro y su comportamiento cariñoso.</p>
              <ul>
                  <li><strong>Origen:</strong>  Birmania</li>
                  <li><strong>Esperanza de vida:</strong> 12-17 años</li>
                  <li><strong>Peso:</strong> 3,5-7 kg</li>
              </ul>
          </div>



<!-- Modal para ampliar la imagen -->
<div id="maine-coon-modal" class="modal">
    <a href="#">&times;</a>
    <img src="images/MaineCoon.jpg" alt="Gato Maine Coon">
</div>
<div id="persa-modal" class="modal">
    <a href="#">&times;</a>
    <img src="images/Persa.jpg" alt="Gato Persa">
</div>

<div id="siames-modal" class="modal">
    <a href="#">&times;</a>
    <img src="images/Siames.jpg" alt="Gato Siames">
</div>

<div id="bengali-modal" class="modal">
    <a href="#">&times;</a>
    <img src="images/Bengali.jpg" alt="Gato Bengali">
</div>

</div>
<div id="siberiano-modal" class="modal">
    <a href="#">&times;</a>
    <img src="images/Siberiano.jpg" alt="Gato Siberiano">
</div>

<div id="ragdoll-modal" class="modal">
    <a href="#">&times;</a>
    <img src="images/Ragdoll.jpg" alt="Gato Ragdoll">
</div>

<div id="esfinge-modal" class="modal">
    <a href="#">&times;</a>
    <img src="images/Esfinge.jpg" alt="Gato Esfinge">
</div>

<div id="birmano-modal" class="modal">
    <a href="#">&times;</a>
    <img src="images/Birmano.jpg" alt="Gato Birmano">
</div>

<div id="british-shorthair-modal" class="modal">
    <a href="#">&times;</a>
    <img src="images/BritishSorthair.jpg" alt="Gato British-Shorthair">
</div>

<div id="exoticodepelocorto-modal" class="modal">
    <a href="#">&times;</a>
    <img src="images/ExoticoDePeloCorto.jpg" alt="Gato Exotico-DePelo-Corto">
</div>

<div id="abisinio-modal" class="modal">
    <a href="#">&times;</a>
    <img src="images/Abisinio.jpg" alt="Gato Abisinio">
</div>

<div id="scottishfold-modal" class="modal">
    <a href="#">&times;</a>
    <img src="images/ScottishFold.jpg" alt="Gato scottishfold">
</div>

<div id="chartreux-modal" class="modal">
    <a href="#">&times;</a>
    <img src="images/Chartreux.jpg" alt="Gato Chartreux">
</div>
              
<div id="burmes-modal" class="modal">
    <a href="#">&times;</a>
    <img src="images/gato-burmes.jpg" alt="Gato Burmes">
</div>
     
            
        <section id="video" class="raza">
            <h2>Video sobre los Gatos</h2>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/wv_dJvjuC04?si=krI2GGIkwhokAtxt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </section>

        <section id="contacto" class="raza">
            <h2>Contacto</h2>
            <form action="#" method="post">
                <label for="nombre">Nombre:</label>
                <input type="text" id="nombre" name="nombre" required>
                <label for="mensaje">Mensaje:</label>
                <textarea id="mensaje" name="mensaje" rows="4" required></textarea>
                <input type="submit" value="Enviar">
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Razas de Gatos</p>
    </footer>

</body>
</html>
