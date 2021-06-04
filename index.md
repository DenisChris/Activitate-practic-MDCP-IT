<h2>Student: Denis Chris Isac</h2>

<h3>NOTĂ DE INFORMARE PRIVIND PRELUCRAREA DATELOR CU CARACTER PERSONAL</h3>
<p align="justify">
Vă aducem la cunoștință că Universitatea Tehnică din Cluj-Napoca aplică Regulamentul General al Uniunii Europene nr. 679/2016 privind Protecția Datelor (GDPR). Pentru orice asistență cu privire la respectarea drepturilor cu privire la datele cu caracter personal în instituția noastră, vă puteți adresa acestui birou: date.personale@staff.utcluj.ro , telefon +40 264 401 309, web: www.datepersonale.utcluj.ro. Vă notificăm faptul că datorită temeiului legal aplicabil în România, a cadrului legal și metodologic stabilit pentru organizarea stagiilor de mobilitate Erasmus,  Universitatea Tehnică din Cluj-Napoca procesează următoarele categorii de informații personale care vă aparțin: istoricul dvs. profesional și educațional (CV) pentru etapa de selecție a celor înscriși pentru această mobilitate,  semnătura olografă, date de contact pentru comunicarea cu comunitatea academică,  data nașterii , contul IBAN, pentru posibile viramente din partea Erasmus pe perioada mobilității. Refuzul furnizării acestor date cu caracter personal duce la anularea eligibilității candidatului pentru ocuparea unei poziții în cadrul mobilității Erasmus din UK. Datele personale furnizate de către studenți în vederea eligibilității pentru mobilitatea Erasmus sunt păstrate la nivelul instituției conform Nomenclatorului Arhivistic al Universității Tehnice din Cluj-Napoca, dar și în arhivele Erasmus și ale universității partenere din UK unde studentul își va desfășura activitatea academică pe perioada mobilității.  Menționăm că procedura de organizare include obligația instituției de a transmite o parte din aceste informații personale către reprezentanți Erasmus și Birourilor Universității partenere din Marea Britanie, acestea fiind direct implicate în procesul de organizare. Conform procedurilor existente, Universitatea Tehnică din Cluj-Napoca oferă posesorului datelor personale, prin intermediul departamentelor de specialitate, informații cu privire la toate datele deținute și, dacă este cazul, șterge datele, corectează datele incorecte. Solicitarea ștergerii datelor din arhivele universității este posibilă după o perioadă de 4 ani de la efectuarea stagiului de mobilitate din Marea Britanie.  La nivel național respectarea drepturilor persoanelor cu privire la datele cu caracter personal este monitorizată de Autoritatea Națională de Supraveghere a Prelucrării Datelor cu Caracter Personal, www.dataprotection.ro.
</p>

<button onclick="findOS()">Which OS do I use?</button>
<script>
function findOS(){ 
var OSName="Unknown OS";
if (navigator.appVersion.indexOf("Win")!=-1) OSName="Windows";
if (navigator.appVersion.indexOf("Mac")!=-1) OSName="MacOS";
if (navigator.appVersion.indexOf("X11")!=-1) OSName="UNIX";
if (navigator.appVersion.indexOf("Linux")!=-1) OSName="Linux";
document.write('Your OS: '+OSName);
}
</script>
<html>
<head>
<script>
function setCookie(cname,cvalue,exdays) {
  var d = new Date();
  d.setTime(d.getTime() + (exdays*24*60*60*1000));
  var expires = "expires=" + d.toGMTString();
  document.cookie = cname + "=" + cvalue + ";" + expires + ";path=/";
}

function getCookie(cname) {
  var name = cname + "=";
  var decodedCookie = decodeURIComponent(document.cookie);
  var ca = decodedCookie.split(';');
  for(var i = 0; i < ca.length; i++) {
    var c = ca[i];
    while (c.charAt(0) == ' ') {
      c = c.substring(1);
    }
    if (c.indexOf(name) == 0) {
      return c.substring(name.length, c.length);
    }
  }
  return "";
}

function checkCookie() {
  var user=getCookie("username");
  if (user != "") {
    alert("Welcome back, " + user + "!");
  } else {
     user = prompt("We have cookies! Please enter your name:","");
     if (user != "" && user != null) {
       setCookie("username", user, 30);
     }
  }
}
</script>
</head>

<body onload="checkCookie()"></body>

</html>
