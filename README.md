<!doctype html>
   <html>
  <head>
    <title>Sadun</title>
  </head>   
    
  <body>         
      <form>
          <center>
          <h1></h1>
      <button type="button">Klik Aku</button>
          </center>
      </form>
 
      <script>
      let btn = document.getElementsByTagName('button')[0];
      let h1 = document.getElementsByTagName('h1')[0];
          
        btn.addEventListener('click', function(){
            setTimeout(function(){
                h1.innerHTML = "Halo ira sayang :D";
            }, 100);
            setTimeout(function(){
               h1.innerHTML = " Aku pengen pukul kamu :D";
            }, 1500);
            setTimeout(function(){
               h1.innerHTML = " aku nonjok kamu sampai bunyi ngik yah :)";
            }, 3000);
        });
      </script>
  </body>
</html>
