auteur : Darkangel
blog : raspberry.etoilecraft.com
mail : roch@blondiaux.com

                                  Yuri installe micro/windows

Pré-requis :								  

1) brancher votre micro
2) installer framework .Net ici : http://download.microsoft.com/download/1/6/7/167F0D79-9317-48AE-AEDB-17120579F8E2/NDP451-KB2858728-x86-x64-AllOS-ENU.exe	  
3) installer les drivers si nécessaire : Microsoft SAPI

Config :

- Ne pas dézipper dans un chemin contenant des espaces (ou trop long)

- changer l'adresse du site dans tout les fichier macros et index.html et yuri.php , yuri.html

Usage :

- Lancer WSRMicro.cmd 
- Parlez a yuri !

Changer  la voie :

Télécharger les voie sur le net

Installer les voix Voix_Hortense_FR et Voix_Viginie_FR
Lancer l'executable: %windir%\SysWOW64\speech\SpeechUX\sapi.cpl
Choisir la voie qui vous convient le mieux

Liste des Fichiers:

- WSRKinect.cmd => Le C# qui charge/écoute les grammaire (WSRMacro.exe sans Kinect)
- WSRNode.cmd => Le NodeJS qui lance un serveur HTTP
- /bin => executables appelés par NodeJS
- /macros => grammaire XML de Speech
- /plugin => dossier vide mais obligatoire

Changer le nom :

Ouvrir /yuri/macros/nom_fichier.XML

Puis changer les lignes suivantes :
      <example>Yuri/nom raconte une blague! </example>
      <tag>out.action=new Object(); </tag>
      <one-of>
      <item>Yuri/nom blague</item>
      <item>blague</item>
	  <item>Yuri/nom fait nous rigoler</item>

Ajouter/changer des commandes :
      
	  Copier un fichier puis changer les questions 
	  Puis editer yuri.php  et ajouter ceci a la fin :
	  
	      //action 
    case 'GET_COM':
        $response = 'reponse a la question '
    break;
	      
		  renplacer le COM par autre chose sur les 2 fichiers
		  
		  
		  
