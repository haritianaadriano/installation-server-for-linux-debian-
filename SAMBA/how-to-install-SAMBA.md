<h3>Definition</h3>
<p>Samba est un logiciel d'interopérabilité qui implémente le protocole propriétaire SMB/CIFS
de Microsoft Windows dans les ordinateurs tournant sous le sustéme d'exploitation Unix et ses
dérivés de maniére à partager des imprimantes et des fichiers dans un reseau informatique.</p>

<h3>Installation</h3>
<img src="installationsamba.PNG">

<h3>Etape d'utilisation</h3>
<ul>
    <li>ceer un dossier => mkdir dossier</li>
    <li>changer le droit du dossier => chmod 777 dossier {pour tout acces au dossier}</li>
    <li>ajouter un utilisateur => adduser nom</li>
    <li>taper maintenant => smbpasswd -a exemple {pour les problemes de si non compatibilite}
</ul>

<p>Modifions maintenant la configuration</p>

<h3>configuration1</h3>
<img src="configurationsamba.PNG">

<h3>configuration2</h3>
<img src="SAMBAconfig.PNG">

<h3>lancer le serveur</h3>
<p>taper la commande suivante => etc/init.d/samba restart</p>