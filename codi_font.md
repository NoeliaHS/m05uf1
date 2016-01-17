###__1.2.CODI FONT, CODI OBJECTE I CODI EXCUTABLE: MÀQUINES VIRTUALS.__

<p>Un programa es farà creant un arxiu, on inclourem un seguit d'instruccions. 
 Aquestes hauran de seguir unes pautes determinades.<p>

<p> Aquest arxius que contenen les instruccions, s'anomenen __codi font__. 
 Pot tenir diferents nivells, alts (aprop del llenguatge humà) i baixos 
 (codi de les màquines).<p>
 
 <p>Actualment, es tendeix a utilitzar llenguatges de nivell alt. Amb aixó, 
 sorgeix un problema, i es que, hem de traduir aquest nivell alt, de llenguatge 
 humà a codi màquina (nivell baix).<p>
 
 <p>Aquest procès, se l'anomena:<p>
 
 __COMPILACIÓ__
 
 <p>Què és la traducció del codi font dels fitxers del programa en fitxers de format binari: __CODI OBJECTE__. 
 Aquest codi, no es pot executar.<p>
 
 <p>Per tant, necessitem el __CODI EXECUTABLE__, que és la traducció completa a codi màquina, 
 que es dur a terme per l'enllaçador. Què és  interpretat directament per l'enllaçador.<p>
 
 <p>__L'enllaçador__ insereix al codi objece funcions de les llibreries necessàries. 
 <p>Una __llibreria__ és una col·lecció de codi predefinit que facilita la tasca de 
 programador a l'hora de codificar un programa.<p>
 
![codi](http://ioc.xtec.cat/materials/FP/Materials/2252_DAM/DAM_2252_M05/web/html/WebContent/u1/media/ic10m05u1_01.png)
 
####__1.2.1.MÀQUINA VIRTUAL.__
<p>Facilita el desenvolupament de compiladors.<p>
<p>_Dues fases_<p>
<p>1. La primera parteix del codi font a un llenguatge intermedi obtenint un programa equivalent amb un
menor nivell d'abstracció que l'original i que no pot ser directament executat.<p>
<p>2. La segona fase tradueix el llenguatge intermedi a un llenguatge comprensible per la màquina.<p>
<p>_Objectius_<p>
<p<El codi de la primera fase, el codi intermedi, sigui comú per a qualsevol processador, i que 
el codi generat en la segona fase sigui l'específic per a cada processador.<p>
<p>__La màquina virtual Java__<p>
<p><abbr title="Màquina virtual Java">JVM</abbr> és l'entorn on s'executen els programes Java.<p>
<p>1. Executable en una plataforma específica, que interpeta i executa instruccions expressades en codi bytes.<p>
<p>2. Actua com un poc entre el codi de bytes a executar i el sistema. Així, es l'encarregat d'executar l'aplicació, 
de convertir el codi de bytes a codi natiu de la plataforma física.<p>
<p>3. Possibilita la portabilitat de l'aplicació a diferents plataformes.<p>



 
 
 
 
 

 
 

 
 
 
 


