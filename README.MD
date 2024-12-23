<h3>Compte rendu</h3>

<body> Nous allons développer un service Web SOAP qui permet :

Conversion de devise : Convertir un montant de l'euro en dirhams marocains (DH).
Consultation d’un compte : Récupérer les informations d’un compte spécifique.
Consultation d’une liste de comptes : Retourner une liste contenant les soldes de plusieurs comptes.
<img src="Captures/Capture_1.png">

Pour déployer le Web Service SOAP avec JAX-WS, les dépendances suivantes sont ajoutées dans le fichier pom.xml

<img src="Captures/Capture_2.png">

Nous allons déployer le Web Service SOAP en utilisant un simple serveur JAX-WS :

1.Implémenter le Web Service avec l'annotation @WebService pour définir les méthodes.

2.Utiliser la classe Endpoint pour publier le service sur une URL locale.

3.Accéder au fichier WSDL généré automatiquement pour permettre l'interaction avec le service via des clients SOAP.

<img src="Captures/Capture_3.png">

Le navigateur affichera le fichier WSDL en format XML, décrivant les opérations, les types de données et l'emplacement du service.

<img src="Captures/Capture_4.png">

Nous allons tester les opérations d’un Web Service SOAP avec SoapUI(Convert,getCompte,ListComptes)

<img src="Captures/Capture_5.png">
<img src="Captures/Capture_6.png">
<img src="Captures/Capture_7.png">
