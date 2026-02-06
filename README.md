Étape 1 — Télécharger Mobexler (OVA) et tracer le téléchargement:

1-Vérification de l'empreinte numérique:

Cette image montre l'utilisation de PowerShell pour calculer le hash SHA256 du fichier Mobexler.ova. C'est une étape de sécurité importante pour vérifier que le fichier téléchargé est intègre et n'a pas été modifié ou corrompu.

<img width="1451" height="281" alt="chifrement 1" src="https://github.com/user-attachments/assets/814865c7-f5c1-465e-812a-6ff649bf8100" />

Étape 2 — Importer l’OVA dans VirtualBox/VMware:

1-on importer la machine mobexler dans virtualbox:

<img width="1860" height="962" alt="machine 2" src="https://github.com/user-attachments/assets/316e55d7-2bb7-4428-85c0-7677673e36ad" />

2-Paramètres Réseau - Adaptateur 1 :

Cette image montre la configuration du premier adaptateur réseau pour la machine virtuelle Mobexler. Il est configuré en mode NAT, ce qui permet à la machine virtuelle d'accéder à Internet en utilisant l'adresse IP de votre ordinateur hôte. Le type d'adaptateur est défini sur "Ethernet over USB".

<img width="970" height="650" alt="adapter 1" src="https://github.com/user-attachments/assets/b2ab7bad-0177-4b8f-af14-5c7b0c43bfce" />

3-Paramètres Réseau - Adaptateur 2 :

Ici, on voit la configuration du deuxième adaptateur réseau. Contrairement au premier, celui-ci est configuré en Réseau privé hôte (Host-only). Ce mode est crucial pour permettre à votre ordinateur de communiquer directement avec la machine virtuelle sans passer par un réseau externe. Note : La case "Câble connecté" n'est pas cochée, ce qui pourrait empêcher la connexion de fonctionner.

<img width="977" height="640" alt="adapter 2" src="https://github.com/user-attachments/assets/35bbe647-c70e-4059-a232-da94857e6e93" />

Étape 3 — Premier démarrage + connexion

1-page login avec le mote de pass:

<img width="1918" height="923" alt="interface 3" src="https://github.com/user-attachments/assets/462462dd-f9f8-454e-aff9-481b706e70fc" />

Étape 4 — Vérifier le réseau

1-les addresses:

<img width="1873" height="613" alt="image" src="https://github.com/user-attachments/assets/a1c4ab71-bf58-4fdd-8f0d-f6dddf054d30" />

2-verifier ip route :

<img width="1515" height="191" alt="route 4" src="https://github.com/user-attachments/assets/3a0678b0-fabd-4919-9543-079653ba8e1f" />

3-ping vers le DNS 8.8.8.8:

<img width="1206" height="323" alt="ping 5" src="https://github.com/user-attachments/assets/f0f9d411-3c69-46a7-adc0-63d22efb1ba9" />

4-ping vers google:

<img width="1670" height="380" alt="google 6" src="https://github.com/user-attachments/assets/d681e2f3-367f-471f-8bcc-8ed74c31d853" />


Étape 5 — Créer le snapshot “CLEAN”

1-snapshot:
<img width="497" height="452" alt="snapshot 7" src="https://github.com/user-attachments/assets/c9d0491e-7c82-4bb4-9f0a-0e380a8a4e41" />

Étape 6 — Préparer la cible Android

1-L'installation de l'indroid google nexus 5:

<img width="1913" height="982" alt="ansdoid 8" src="https://github.com/user-attachments/assets/0da14c07-8e73-4870-8159-a9c935f1c357" />

2-Connecter ADB:

<img width="1017" height="392" alt="image" src="https://github.com/user-attachments/assets/85b96b1d-6981-4b34-b727-dfb68e7a447f" />








