# Challenge
## FTP - Authentification

>1. Ouvrir le fichier dans wireshark.
>2. Appliquer un filtre : "TCP".
>3.Clique droit sur une des lignes puis sur cliquer "suivre" puis "flux TCP"
>5. Le mot de passe se situe sur la 5è ligne 

## Telnet - Authentification


>1. Ouvrir le fichier dans wireshark.
>2. Appliquer un filtre : "Telnet".
>3. Clique droit sur la ligne ou il est écrit [Malformed packet] puis sur cliquer "suivre" puis "flux TCP"
>4. Le mot de passe est les caractéres en face du mot "Password:"

## Ethernet - Trame
 >1. Convertir le texte codé en hexadécimal en texte qui peut être lu par des humains en utilisant un site dédié à cela.
 >2. Repérer le texte codé en base64, on peut facilement le réperer car il se termine par " == "
 >3. Decoder le texte en base 64 et on obtient le mot de passe

## Authentification Twitter
>1. Ouvrir le fichier correspondant au challenge  dans wireshark.
>2. Clique droit sur la ligne puis sur cliquer "suivre" puis "flux TCP"
>3. Sur la ligne authorization, on a les informations sur le mot de passe donc il faut decoder la chaine de caractère qui est codé en base64
4. Le mot de passe est la chaîne de caractère qui se situe après ":"

## Bluetooth - Fichier inconnu
>1. Ouvrir le fichier correspondant au challenge  dans wireshark.
>2. Dans les onglets de wireshark, on clique sur "Wireless" et on choisit "Equipement Bluetooth"
>3. Dans la fenêtre qui s'ouvre, on concatène l'adresse MAC et le modèle du telephone après avoir mis l'adresse MAC en majuscule
>4. On convertir les caractère concatenés dans le site sha1.fr et on obtient le mot de passe.
 