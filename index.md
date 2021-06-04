<h2>Student: Denis Chris Isac</h2>

<h3>NOTĂ DE INFORMARE PRIVIND PRELUCRAREA DATELOR CU CARACTER PERSONAL</h3>

<p align="justify"> Vă aducem la cunoștință că Universitatea Tehnică din Cluj-Napoca aplică Regulamentul General al Uniunii Europene nr. 679/2016 privind Protecția Datelor (GDPR). Vă notificăm faptul că datorită temeiului legal aplicabil în România, a cadrului legal și metodologic stabilit pentru organizarea stagiilor de mobilitate Erasmus,  Universitatea Tehnică din Cluj-Napoca procesează următoarele categorii de informații personale care vă aparțin: istoricul dvs. profesional și educațional (CV) pentru etapa de selecție a celor înscriși pentru stagiul de mobilitate,  semnătura olografă, date de contact pentru comunicarea cu comunitatea academică:: nume, prenume, CNP, seria și nr. CI/Pașaport, data și locul nașterii, cetățenia, domiciliul, asigurări de sănătate și sociale, date/conturi bancare, situația medicală, respectiv adresa de email, număr de telefon în vederea îmbunătățirii procesului de comunicare. </p>

<p align="justify">Sunteţi obligat să furnizaţi datele dumneavoastră personale, acestea fiind necesare în scopul participării la procesul de selecție Erasmus și efectuării de mobilități la universitățile partenere. În cazul refuzului sau al nefurnizării acestor date în mod corect și complet, universitatea ar pu tea fi pusă în situația nerespectării reglementărilor legale specifice din domeniul educațional. Datele personale furnizate de către studenți în vederea eligibilității pentru mobilitatea Erasmus sunt păstrate la nivelul instituției conform Nomenclatorului Arhivistic al Universității Tehnice din Cluj-Napoca, dar și în arhivele Erasmus și ale universității partenere din UK unde studentul își va desfășura activitatea academică pe perioada mobilității.  Menționăm că procedura de organizare include obligația instituției de a transmite o parte din aceste informații personale către reprezentanți Erasmus și Birourilor Universității partenere din Marea Britanie, acestea fiind direct implicate în procesul de organizare a stagiului de mobilitate. </p>
 
<p align="justify">Conform Legii nr. 677/2001 și Regulamentului (UE) nr. 679/2016, beneficiaţi de dreptul de acces, de intervenţie asupra datelor cu titlu gratuit, de dreptul de a nu fi supus unei decizii individuale automatizate, inclusiv crearea de profiluri. Totodată, aveţi dreptul să vă opuneţi prelucrării datelor personale care vă privesc, să vă retrageți consimțământul şi să solicitaţi ştergerea datelor fără a contraveni obligațiilor legale ce revin universității. Pentru exercitarea acestor drepturi, vă puteţi adresa cu o cerere scrisă, datată şi semnată la Biroul pentru Cooperare Europeană și Internațională - Biroul ERASMUS +. Conform procedurilor existente, Universitatea Tehnică din Cluj-Napoca oferă posesorului datelor personale, prin intermediul departamentelor de specialitate, informații cu privire la toate datele deținute și, dacă este cazul, șterge datele, corectează datele incorecte. </p>

<p align="justify">Pentru orice asistență cu privire la respectarea drepturilor cu privire la datele cu caracter personal în instituția noastră, vă puteți adresa acestui birou: date.personale@staff.utcluj.ro , telefon +40 264 401 309, web: www.datepersonale.utcluj.ro. La nivel național respectarea drepturilor persoanelor cu privire la datele cu caracter personal este monitorizată de Autoritatea Națională de Supraveghere a Prelucrării Datelor cu Caracter Personal, www.dataprotection.ro.
</p>

<button onclick="findOS()">Which OS do I use?</button>

<p style="color:red;">Apasă butonul de mai jos pentru a naviga la analiza de impact asupra protecției datelor personale:.</p>

<form action="https://didatec-my.sharepoint.com/:w:/r/personal/marcu_il_roxana_utcluj_didatec_ro/_layouts/15/Doc.aspx?sourcedoc=%7B3FEEABF5-AE23-41DF-8C7B-9BAC0327C8D5%7D&file=dpia-template.docx&action=default&mobileredirect=true&DefaultItemOpen=1&ct=1622731579392&wdOrigin=OFFICECOM-WEB.START.OTHER&cid=3e707c61-f3c9-4bfe-b7b5-5ecf2d393718">
    <input type="submit" value="DPIA" />
</form>
<script>
function findOS(){ 
var OSName="Unknown OS";
if (navigator.appVersion.indexOf("Win")!=-1) OSName="Windows";
if (navigator.appVersion.indexOf("Mac")!=-1) OSName="MacOS";
if (navigator.appVersion.indexOf("X11")!=-1) OSName="UNIX";
if (navigator.appVersion.indexOf("Linux")!=-1) OSName="Linux";
alert('Your OS: '+OSName);
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
