<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kultur cafe</title>
    <!--Navn giv din side. Det er står oppe i fanen på din pc-->
  <link rel="stylesheet" href="style.css">
  <!--Husk altid at linke din css fil ellers virker den ikke:) -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Anton&family=Comfortaa:wght@300&display=swap" rel="stylesheet">
<link rel="icon" type="image/x-icon" href="5775761.png">
<link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
  />
</head>

<!--for at få animationer skal man bruge dette link og en class som kan finde inde på animation.css-->
<body>
  <a href="index.html">
    <button class="logo">
        <img class="logo" src="Kopi af logo-oskar.png" alt="Logo">
    </button>
</a>
    <Div class="knap">
      <a href="KulturCafe-Oskar">Hjem</a> 
      <a href="KulturCafe-Oskar-bestil-bord"> Bord bestilling</a>
      <a href="KulturCafe-Oskar-Lej-cafeen"> Lej Oskar</a>
      <a href="KulturCafe-Oskar-kontakt-os"> Kontakt</a>
        <!--a href er der hvor du vil have en kanp hvor du føres til en af dine egne sider. Der hvor der nu står hjem er det er står på kappen.-->
    </Div>
 <hr>
 <!--hr er en horizontal linje man kan lave. Der skal også bruges css til det. Det punkt hedder også hr-->
   <div class="parallax"></div>
   <div class="overskrift"><h1 class="animate__animated animate__zoomIn">Kulturcafe <br> Oskar</h1></div>
   
   
   <div class="omlinje"><hr></div>

<div class="omost"><h1>Tæt på musikken</h1></div>
  <div class="omos"><h3>
  Kulturcafé Oskar er et spillested med levende musik for levende mennesker.
  Hvert år afholdes mellem 26 og 30 koncerter, der spænder meget bredt stilmæssigt. Der er intime koncerter med en eller to musikere på scenen, rockkoncerter og danseaftener med god popmusik.
  Fælles for det hele er et nøje udvalgt program med erfarne og anerkendte kunstnere præsenteret i et topprofessionelt setup med virkelig god lyd og lys.
  <br><br>På Kulturcafé Oskar kommer man tæt på musikken og musikken kommer tæt på publikum. Derfor vil mange gerne spille på Oskar og mange gæster kommer igen og igen på grund af den helt særlige stemning.
  Sideløbende med musikken indgår Oskar i samarbejde med andre foreninger, der bruger stedet til fx ungdomsarrangementer (Søby UngdomsProjekt), teater og danseskole.
  </div>
 
  <div class="omost"><h1>Foreningen bag</h1></div>
 <div class="omos"><h3>Kulturcafé Oskar drives af en kreds af frivillige ildsjæle med en fælles passion for levende musik og glæden ved at have et aktivt spillested i Søby.
  Oskar er en nonprofit forening på ca. 40 medlemmer med en bestyrelse, samt en række andre udvalg / arbejdsgrupper.
  Det lokale erhvervsliv, Søby Kommune samt forskellige organisationer og fonde støtter projektet økonomisk på flotteste vis. Sammen med billetindtægterne og barsalget er det foreningens økonomiske grundlag.
  </h3></div>
 
  
<div class="tætbillede"><img src="Kopi af stemning3.jpeg" alt="tæt på"></div> 

<div class="omos2"><hr></div>


<div class="program"><h2>Kommende artister</h2></div>

<div class="program1"> <h2>24. september 2023 <br>DAS MÄDCHEN <br><br>PRIS 285 / STARTER KL 19 / ÅBNER KL 20 / STÅENDE KONCERT</h2></div>

<div class="program2"><h2>15. OKTOBER 2023 <br>CHRISTIAN ANDERSEN BAND <br><br> PRIS 250 / STARTER KL 20 / ÅBNER KL 19 / NYHED</h2></div>

<div class="program3"><h2> 29. OKTOBER 2023 <br>SANNE BENTSEN SOLO – Support Emily <br><br>PRIS 200 / STARTER KL 19.30 / ÅBNER KL 18 / NYHED</h2></div>

<div class="programhr"><hr></div>

<div class="billede2"><img src="Kopi af christianandersen.jpg" alt=""></div>

<div class="chandersen"><h2>Christian Andersen</h2></div>



<!-- Tekstfelt, der altid er synligt -->
<div id="visibleText">
  <p>Christian Andersen har en karakteristisk, stærk vokal, en intens guitarstil, og ikke mindst et fantastisk band! Christian Andersen er derfor med god grund ét af Danmarks travleste live-navne.

    44-årige Christian Andersen, døbt Christan Højbjerg Andersen, begyndte at spille guitar da han var 12 år gammel i Rødekro i Sønderjylland.
  
    Allerede som teenager spillede han på barer og spillesteder i forskellige bands og begyndte desuden allerede hér at skrive sange. <br> <br>

    Som 16-årig blev Aarhus hans nye hjemby, og byens levende musikliv og jamsessions blev rammen om hans tidlige ungdom. I en alder af blot 22 startede han sit eget Christian Andersen Band, som udgav det anmelderroste debutalbum ‘My Love For The Blues’ i 2002.
    
    Som ung dyrkede Christian Andersen de store amerikanske bluesguitarister og soulsangere intenst.
    
    Christian har dog altid haft en erkendelse af, at den musik han er så forelsket i stammer fra en tid længe før han blev født, og fra et sted langt fra Rødekro.
    
    Dén erkendelse, samt en nysgerrighed på andre genrer, og hvad der foregår musikalsk i den tid vi lever i, har betydet at Christian Andersen altid har søgt sin egen stil og lyd.</p>
</div>


<!-- En knap, der udløser toggleMoreText() funktionen -->
<button class="mere" onclick="toggleMoreText()" id="toggleButton">Vis mere</button>




<!-- Tekstfelt, der skjules som standard -->
<div id="hiddenText" style="display: none">
  <p>
    2010 blev et vendepunkt
    Christian Andersens tredje album, GENLYD, blev det danske gennembrud for den 34-årige sanger, sangskriver og guitarist.
    
    GENLYD høstede 5 hjerter i Politiken, blev “Ugens Album" på P4 og modtog tre Nordic Music Awards-nomineringer.
    
    Christian vandt senere en Nordic Music Award for albummet AWAY (Årets Songwriter Album - 2015)
    
    GENLYD bringer for alvor Christian Andersen på landevejen, og gennem de sidste 25 år har han, både med band og som solo artist, spillet over 1500 koncerter i mere end tyve lande. 
    
    Christian Andersen havde desuden æren af at spille “opvarmning” for sin store helt, BB KING, hele tre gange!
    <br><br>
    Syvende album byder på duet med Holly Monroe
    Op gennem sine tredivere begynder Christian Andersen at fokusere mere intenst på sin sangskrivning. Han tager på flere ture til Nashville for at co-write. Disse ture bliver en stor inspiration for ham og ved en co-write session i netop Nashville bliver sangen BEFORE til.
    
    BEFORE ender som en duet med den engelske verdensstjerne JOSH STEIN, og udkommer på Christian Andersen Bands 2016 album, DEVIL ON HIS WAY.
    
    Alene og akustisk
    Christian udgiver for første gang et helt akustisk soloalbum i 2019 med titlen 1000 K.
    
    “Jeg har altid stræbt efter at lave sange som kan holde til at blive fremført af bare mig selv og en guitar. Alligevel har jeg aldrig udgivet sange på den måde. Det er så på tide nu”, sagde Christian omring udgivelsen.
    
    1000 K blev en succes. Ni nye originale sange, indspillet på den “gammeldags” måde. Alt hvad man hører på dette album, er Christian der synger og spiller akustisk guitar, mens ham tramper med foden. Ingen redigering, ingen overdubs!
    <br><br>
    Albummet gik #1 på den danske Vinyl Top-20 og dér blev den liggende flere uger.
    
    Den efterfølgende akustiske solo turné vandt en Nordic Music Award (Live Prisen 2020).
    
    Tilbage med bandet på kommende album, LOWER YOUR HAND
    Efter at have fokuseret på 1000 K, og turneret intensivt som solo artist gennem 2019, er Christian Andersen nu tilbage med fuldt band.
    
    Det niende album i rækken er klart, og sat til at udkomme 17. september 2023.
    
    For at fange lyden af et “tight” og sammenspillet band, som har rejst Europa tyndt i en tour bus, er albummet indspillet “live i studiet” på analoge bånd. Det har været med til at give albummet en helt særlig umiddelbarhed og autencitet!
    
    LOWER YOUR HAND er mixet af Grammy Award-vindende tekniker, Gene Rodrigues i New York. Russell er en sand mester i analog lyd og har optaget og mixet musik for en lang række
    internationale stjerner. Gene Rodrigues mixede desuden Christian Andersens gennembruds album, GENLYD.</p>
</div>


<script>
// JavaScript-funktionen toggleMoreText
function toggleMoreText() {
    // Find HTML-elementet med id "hiddenText"
    var hiddenTextElement = document.getElementById("hiddenText");

    // Skift display-stilen fra "none" til "block" eller omvendt
    if (hiddenTextElement.style.display === "none" || hiddenTextElement.style.display === "") {
        hiddenTextElement.style.display = "block";
        document.getElementById("toggleButton").textContent = "Vis mindre";
    } else {
        hiddenTextElement.style.display = "none";
        document.getElementById("toggleButton").textContent = "Vis mere";
    }
}
</script>


</body>
<br><br>
<br>

<footer>
  <div class='container'>
  <div class='row'>
      <div class='col-md-12'>
          <ul>
            <li><a href='KulturCafe-Oskar-bestil-bord'>Bord Bestilling</a></li> <br>
            <li><a href='KulturCafe-Oskar-Lej-cafeen'>Lej Oskar</a></li> <br> 
            <li><a href='KulturCafe-Oskar-kontakt-os'>kontakt</a></li> <br>
            <li><a href='KulturCafe-Oskar-cookies'>Cookies</a></li>
               <div class="sted1"><h2>Lokation:</h2></head></div>
               <div class="sted"><h2> Kulturcafé Oskar <br> Kingosvej 5 <br> 4321 Søby  <br> Tlf. xxxxxxx </h2></div>

               <div class="icons">
                <a href="https://www.facebook.com" target="_blank">
                  <button class="facebook">
                      <img height="40vw" src="facebook.png" alt="Åbner Facebook">
                  </button>
              </a>
              
              <a href="https://www.instagram.com/" target="_blank">
                <button class="facebook">
                    <img height="40vw" src="Instagram.png" alt="Åbner twitter">
                </button>
              </a>
              
              <a href="https://about.twitter.com/en/who-we-are/brand-toolkit" target="_blank">
                <button class="facebook">
                    <img height="40vw" src="twitter.png"f alt="">
                </button>
              </a></div>

              <p>&copy; HTX Delta inc and co</p>
          </ul>
      </div>
  </div>
  </div>


  <style>
    .icons a {
        text-decoration: none; /* Fjerner standardlink-udseende */
        display: inline-block; /* Gør ikonerne til inline-blokke */
    }
  </style>
</footer>
</html>
