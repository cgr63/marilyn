<!DOCTYPE html>

<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <title>Marilyn Monroe</title>
    
    <meta name="author" content="Author" />
    <meta name="description" content="Website description" />
    <link rel="stylesheet" href="styles.css" />
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
     <style>


  @keyframes shake {
    0% { transform: translateX(0); }
    25% { transform: translateX(-2px); }
    50% { transform: translateX(2px); }
    75% { transform: translateX(-2px); }
    100% { transform: translateX(0); }
  }

  .marilyn-image:hover {
    animation: shake 0.3s ease-in-out;
  }

    
.image-container {
  position: relative;
  width: 300px;
  display: inline-block;
  margin: 20px;
  border: 4px solid gray;}

.image-container img {
  display: block;
  width: 100%;
  height: auto;
  transition: transform 0.3s ease;}

.overlay {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba(255, 255, 255, 0.5); 
  opacity: 0;
  transition: opacity 0.3s ease; 
  display: flex;
  justify-content: center;
  align-items: center;}


.overlay .text {
  color: black;
  font-size: 1.5em;
  font-family: 'Montserrat', sans-serif;
  text-align: center;}

.image-container:hover img {
  transform: scale(1.1);}

.image-container:hover .overlay {
  opacity: 1; }

      
  .trail { position: absolute;
          width: 10px;
          height: 10px;
          background-color: rgb(108, 30, 30);
          border-radius: 50%;
          pointer-events: none; }

          img {transition: transform 0.3s ease;}



   </style>
  </head>
  
  <body>
    <header>
      <h1 style="color: black; font-family: 'Great Vibes', Cursive;">
        "Imperfection is beauty, madness is genius, and it's better 
        to be absolutely ridiculous than absolutely boring."</h1>
        <p style="text-align: center;">
          <img class="marilyn-image" src="images/marilyn.png" alt="Marilyn Monroe" width="100" height="100">  
          <img class="marilyn-image" src="images/marilyn.png" alt="Marilyn Monroe" width="100" height="100">  
          <img class="marilyn-image" src="images/marilyn.png" alt="Marilyn Monroe" width="100" height="100">  
          <img class="marilyn-image" src="images/marilyn.png" alt="Marilyn Monroe" width="100" height="100">  
          <img class="marilyn-image" src="images/marilyn.png" alt="Marilyn Monroe" width="100" height="100">  
          <img class="marilyn-image" src="images/marilyn.png" alt="Marilyn Monroe" width="100" height="100">  
        </p>
        
      
      
    </header>
    <div style="margin-bottom: 200px;"></div>


    <main>
      <h2 style= "text-align: center; color: gray; font-family: 'Great Vibes', cursive;"
    >Marilyn Monroe</h2>
      <p>
 
        Marilyn Monroe was an iconic actress, model, and cultural symbol who believed that 
        beauty lies in madness and the joy of being unapologetically unique. She embodied the allure of imperfection and boldness by embracing her true self!
      </p>
      <div style="margin-bottom: 50px;"></div>
      <h2 style= "text-align: center; color: gray; font-family: 'Great Vibes', cursive;">
        June 1, 1926-August 5, 1962</h2>  <p>
        
Marilyn Monroe, born Norma Jeane Mortenson, transformed herself from a 
troubled young woman into one of the most iconic and glamorous figures 
in Hollywood history. She created her public persona as a blonde bombshell by 
captivating the world with her beauty and charm. Meanwhile, she constantly privately battled the abuse of her career, lifestyle, drugs and meantal health.
Her death at the young age of 36 left her legacy as a symbol of both the 
dsire and tragedy of fame... 

Find more about her by watching her movie 
 <a href="https://en.wikipedia.org/wiki/Blonde_(2022_film)" 
 target="_blank" >Blonde</a>
released on September 28, 2022--- directed by Andrew Dominik. </p>
      <div style="margin-bottom: 200px;"></div>

      <div class="center-content" style="display: flex; justify-content: space-evenly; 
      align-items: flex-start; text-align: center; gap: 50px;">
        <div style="width: 300px;">
          <h3 style="color:rgb(108, 30, 30); margin-bottom: 20px;"><i>Most Famous Films</i></h3> 
          <ol style="list-style-type: none; padding: 0; margin: 0;">
            <li style="color: white; padding: 10px 0;">Some Like It Hot (1958)</li>
            <li style="color: white; padding: 10px 0;">Gentlemen Prefer Blondes (1953)</li>
            <li style="color: white; padding: 10px 0;">The Seven Year Itch (1955)</li>
          </ol>
        </div>
        
        <div style="width: 300px;">
          <h3 style="color:rgb(108, 30, 30); margin-bottom: 20px;"><i>Biggest Accomplishments</i></h3>
          <ul style="list-style-type: none; padding: 0; margin: 0;">
            <li style="color: white; padding: 10px 0;">Hollywood Icon</li>
            <li style="color: white; padding: 10px 0;">Golden Globe Win</li>
            <li style="color: white; padding: 10px 0;">Cultural Legacies</li>
          </ul>
        </div>
      </div>
      <div style="margin-bottom: 200px;"></div>
      <h3 style="text-align: center; color: gray; font-family: 'Montserrat', sans-serif; margin-bottom: 1px; margin-top: 10px;">Gallery</h3>


      
      .image-container img .image-container img {
        display: block;
        width: 100%;
        height: 400px; /* Enforce uniform height */
        object-fit: cover; /* Ensures the image maintains aspect ratio without distortion */
        transition: transform 0.3s ease;
      }
      

      <div class="gallery-container" style="display: flex; justify-content: center; gap: 20px; margin-top: 50px;">
        <div class="image-container">
          <img src="images/somelikeithot.JPG" alt="Some Like It Hot">
          <div class="overlay">
            <div class="text">The black sequined dress worn by Marilyn in Some Like It Hot was designed by Orry-Kelly. Its daring and form-fitting style was considered quite revealing for the 1950s.</div>
          </div>
        </div>
      
        <div class="image-container">
          <img src="images/gentlemanpreferblondes.jpg" alt="Gentlemen Prefer Blondes">
          <div class="overlay">
            <div class="text">Marilyn's red gown, made by William Travilla, in Gentleman Prefer Blondes emphasized the character's taste for luxury and diamonds.</div>
          </div>
        </div>
      
        <div class="image-container">
          <img src="images/sevenyearitch.JPG" alt="The Seven Year Itch">
          <div class="overlay">
            <div class="text">The white halter dress from The Seven Year Itch, created by William Travilla, became one of the most iconic costumes in cinematic history.</div>
          </div>
        </div>
      </div>
      

      
      
    </main>

    <footer>
      <div style="margin-bottom: 10px;">
        <p style="background-color: transparent; color: white;">
          Not associated with Marilyn Monroe Productions®
        </p>
      </div>
    </footer>
    <script>
      document.addEventListener('mousemove', function(e) {
        let trail = document.createElement('div');
        trail.classList.add('trail');
        document.body.appendChild(trail);
    
        trail.style.left = e.pageX + 'px';
        trail.style.top = e.pageY + 'px';
    
        setTimeout(function() {
          trail.remove();
        }, 1300); 
      });
    </script>
    
  
    <style>
       body {background-color: black; 
        background-image: 
          url('images/static.jpg'), 
          repeating-linear-gradient(0deg, rgba(255, 255, 255, 0.8) 200px, transparent 200px); 
        background-size: 300px 300px, 100%; 
        background-blend-mode: normal, multiply; 
        background-position: center;
        font-family: 'Montserrat', sans-serif;
        color: black;
        padding: 20px;
}

h1, p {padding: 20px;
    text-align: center;
    background-color: rgba(255, 255, 255, 0.787);
    border-radius: 8px;
    max-width: 700px;  
    margin: 20px auto;}

h1 {color: black;}

p {color: black;
    padding: 15px;}

