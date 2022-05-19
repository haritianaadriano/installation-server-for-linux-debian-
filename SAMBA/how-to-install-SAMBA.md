<h3>Definition</h3>
<p>Samba est un logiciel d'interoperabilite qui implemente le protocole proprietaire SMB/CIFS de Microsoft Windows dans les ordinateurs tournant sous le systeme d'exploitation Unix de maniere à partager des imprimantes et des fichiers dans un reseau informatique.</p>

<h3>installation de SAMBA</h3>
<img src="/img/installationsamba.PNG">

<h3>configuration SAMBA</h3>
<img src="/img/configurationsamba.PNG>

<h3>Etape de configuration</h3>
<p>Tout ce qui suit se fait en mode Super Utilisateur</p>

<h3>les etapes</h3>
<ul>
    <li>creer un dossier dans le home => ecrire mkdir nom_du_dossier</li>
    <li>changer le droit d'utilistation du fichier => chmod 777 nom_du_dossier</li>
    <li>creer un nouvelle utilisateur => useradd nom_d'utilisateur</li>
    <li>modifions la config du server => nano /etc/samba/smb.conf</li>
</ul>

<p>exemple</p>
<img src="/img/SAMBAconfig.PNG">

<p>Puis configurer votre machine locale => entrer dans le panneau de configuration puis modifier votre connexion network, et entrer en ethernet et taper l'adress du server</p>