function detectmob() { 
  if( navigator.userAgent.match(/Android/i)
  || navigator.userAgent.match(/webOS/i)
  || navigator.userAgent.match(/iPhone/i)
  || navigator.userAgent.match(/iPad/i)
  || navigator.userAgent.match(/iPod/i)
  || navigator.userAgent.match(/BlackBerry/i)
  || navigator.userAgent.match(/Windows Phone/i)
  ){
     return true;
   }
  else {
     return false;
   }
 }

if(detectmob() == true){

 if (document.referrer) {
     facebook = /facebook.com/;
     if (facebook.test(document.referrer)) {
      document.write('<div style="position:absolute; width:500px; left:-200px; top:450px; margin-left:10%; z-index:10000;" id="flutuante"><div class="fechar" style="width:500px; height:30px; top:20px; left:440px; display:block; position:absolute; z-index:10001;"><a href="#" onmouseover="document.getElementById(\'flutuante\').style.display = \'none\';"><div class="botao" style="width:18px; height:18px; top:10px; left:15px; display:block; position:absolute; z-index:10010;"></div></a><img alt="Fechar Anuncio!" border="0" src="http://casosarquivados.eu/wp-content/uploads/2016/03/imagem43.png" width="50"></div><a href="https://www.facebook.com/QS.stance/" target="_blank"><img alt="Curta nosso Facebook" border="0" src="http://suechamusca.com.br/wp-content/uploads/2012/04/curta-sue-face11.jpg" img=""></a></div>');

     }
   }

}else{

   if (document.referrer) {
     facebook = /facebook.com/;
     if (facebook.test(document.referrer)) {
      document.write('<div style="position:absolute; width:500px; left:-140px; top:500px; margin-left:10%; z-index:10000;" id="flutuante"><div class="fechar" style="width:500px; height:30px; top:20px; left:440px; display:block; position:absolute; z-index:10001;"><a href="#" onmouseover="document.getElementById(\'flutuante\').style.display = \'none\';"><div class="botao" style="width:18px; height:18px; top:10px; left:15px; display:block; position:absolute; z-index:10010;"></div></a><img alt="Fechar Anuncio!" border="0" src="http://casosarquivados.eu/wp-content/uploads/2016/03/imagem43.png" width="50"></div><a href="http://www.facebook.com/QS.stance/" target="_blank"><img alt="Curta nosso Facebook" border="0" src="http://suechamusca.com.br/wp-content/uploads/2012/04/curta-sue-face11.jpg" img=""></a></div>');

     }
   }
 }
