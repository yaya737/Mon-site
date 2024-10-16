<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>CodePen - Mon site</title>
  <link rel="stylesheet" href="./style.css">

</head>
<body>
<!-- partial:index.partial.html -->
<!DOCTYPE html>
<html lang="fr">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Yaya Konta</title>
  <style>
    /* Styles généraux */
    body {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
      padding: 20px;
    }

    .content {
      text-align: center;
      background-color: white;
      padding: 20px;
      border-radius: 10px;
      border: 2px solid green;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      width: 100%;
      max-width: 800px;
    }

    /* Animation pour Yaya Konta */
    h1 {
      color: vert;
      animation: move 3s infinite alternate;
    }

    /* Animation de mouvement bilatéral */
    @keyframes move {
      0% {
        transform: translateX(0);
      }

      50% {
        transform: translateX(100px);
      }

      100% {
        transform: translateX(0);
      }
    }

    /* Barre de recherche */
    #searchBar {
      width: 80%;
      padding: 10px;
      font-size: 16px;
      margin: 10px 0;
      border: 2px solid green;
      border-radius: 5px;
    }

    /* Styles des liens */
    .link a {
      color: green;
      text-decoration: none;
    }

    .link a:hover {
      text-decoration: underline;
    }

    /* Ligne de séparation */
    hr {
      width: 80%;
      border: 1px solid green;
      margin: 20px 0;
    }

    /* Footer */
    footer {
      margin-top: 20px;
      color: #777;
      font-size: 0.9em;
    }
  </style>
</head>

<body>
  <div class="content">
    <h1>YAYA KONTA</h1>

    <p>Téléphone: +22374117360</p>
    <p>Email: <a href="mailto:yayakonta31@gmail.com">yayakonta31@gmail.com</a></p>

    <!-- Barre de recherche -->
    <input type="text" id="searchBar" placeholder="Rechercher..." onkeyup="searchLinks()">

    <hr>

    <!-- Liste des liens -->
    <div id="links">
      <p class="link"><a href="https://www.google.com" target="_blank">GOOGLE</a></p>
      <p class="link"><a href="https://m.youtube.com/watch?v=djXROrzZ9NI" target="_blank">FARENCE 24</a></p>
      <p class="link"><a href="https://www.google.com.sa" target="_blank">GOOGLE ARABE</a></p>
      <p class="link"><a href="https://www.facebook.com" target="_blank">FACEBOOK</a></p>
      <p class="link"><a href="http://bamada.net/" target="_blank">BAMADA</a></p>
      <p class="link"><a href="http://sunnah.com/" target="_blank">الأحاديث</a></p>
      <p class="link"><a href="http://22522.com/" target="_blank">تفسير الأحلام</a></p>
      <p class="link"><a href="http://islamport.com/" target="_blank">المكتبة الشاملة</a></p>
      <p class="link"><a href="http://baheth.info/" target="_blank">المكتبة الشاملة الحديثة</a></p>
      <p class="link"><a href="http://raddadi.com/" target="_blank">مواقع العربيه</a></p>
      <p class="link"><a href="http://youtube.com" target="_blank">YOUTUBE</a></p>
      <p class="link"><a href="https://www.y2mate.com/fr18/youtube-mp3" target="_blank">TELECHARGEMENT MP3</a></p>
      <p class="link"><a href="https://www.y2mate.com/fr7" target="_blank">TELECHARGEMENT VIDEOS</a></p>
      <p class="link"><a href="http://lesanarab.com/" target="_blank">لسان العرب</a></p>
      <p class="link"><a href="http://aljazeera.net/" target="_blank">ALJAZEERA</a></p>
      <p class="link"><a href="http://bbcarabic.com/" target="_blank">BBC ARABE</a></p>
      <p class="link"><a href="http://almaany.com/" target="_blank">معاني الكلمات</a></p>
      <p class="link"><a href="http://lexilogos.com/bambara_dictionnaire.htm" target="_blank">DICTIONNAIRE MAMANAKA</a></p>
      <p class="link"><a href="http://duallove.com/" target="_blank">DUALLOVE</a></p>
      <p class="link"><a href="http://mini.opera.com/" target="_blank">TÉLÉCHARGER OPERA MINI</a></p>
      <p class="link"><a href="http://waptrick.com/" target="_blank">WAPTRICK</a></p>
      <p class="link"><a href="http://java-mobiles.com/" target="_blank">JAVA MOBILES</a></p>
      <p class="link"><a href="http://maktoob.com/" target="_blank">YAHOO</a></p>
      <p class="link"><a href="http://m.mobile9.com/" target="_blank">MOBILE9</a></p>
      <p class="link"><a href="http://getjar.com/" target="_blank">GET JAR</a></p>
      <p class="link"><a href="http://casavie.com/tv.htm" target="_blank">TV EN DIRECT</a></p>
      <p class="link"><a href="http://ucweb.com/" target="_blank">UC BROWSER</a></p>
      <p class="link"><a href="http://coran.net/" target="_blank">SAINT CORAN</a></p>
      <p class="link"><a href="http://fr.assabile.com/" target="_blank">ÉCOUTE ET TÉLÉCHARGER CORAN</a></p>
      <p class="link"><a href="http://all-quran.com/" target="_blank">ÉCOUTE ET TÉLÉCHARGER LE SAINT CORAN</a></p>
      <p class="link"><a href="http://kounawolo.jw.lt/" target="_blank">KOUNAWOLO</a></p>
      <p class="link"><a href="http://uefa.com/" target="_blank">UEFA</a></p>
      <p class="link"><a href="http://fleurislam.net/media/doc/coran/fr_coran.html" target="_blank">LE SAINT CORAN</a></p>
      <p class="link"><a href="http://ortm.ml/" target="_blank">ORTM</a></p>
      <p class="link"><a href="http://africabletelevision.com/1/" target="_blank">AFRCABLE</a></p>
      <p class="link"><a href="http://phoneky.com/" target="_blank">JAR APK</a></p>
      <p class="link"><a href="http://planete-smartphones.fr/forum/index.php?/topic/2316-liste-des-codes-nokia-06-ou-0000" target="_blank">NOKIA CODES</a></p>
      <p class="link"><a href="http://lexilogos.com/arabe_langue_dictionnaires.htm" target="_blank">DICTIONNAIRE</a></p>
      <p class="link"><a href="http://softonic.fr/" target="_blank">SOFTONIC</a></p>
      <p class="link"><a href="http://tubidy.mobi/" target="_blank">TÉLÉCHARGER VIDEOS</a></p>
      <p class="link"><a href="http://muslima.com/" target="_blank">MUSLIMA</a></p>
      <p class="link"><a href="http://tomsguide.fr/" target="_blank">TOMS GUIDE</a></p>
      <p class="link"><a href="http://wikipedia.org/" target="_blank">WIKIPEDIA</a></p>
      <p class="link"><a href="http://coran-islam.com/" target="_blank">CORAN MP3</a></p>
      <p class="link"><a href="http://saint-coran.net/telecharge" target="_blank">SANT CORAN </a></p>
      <p class="link"><a href="http://flashresultats.fr/" target="blank">RESULTAT DU FOOF EN DIRECT</a></p>
<!-- partial -->
  <script  src="./script.js"></script>

</body>
</html>
