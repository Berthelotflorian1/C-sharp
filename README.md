# C-sharp

Il s'agit d'une première API créée avec C#.

Explication des dossiers : 

Context -> ApplicationDbContext.cs ;
Cette page contient la class "ApplicationDbContext" qui hérite de "DbContext"
Cela permet d'utiliser une base de données (SqlServer en l'occurrence) 
C'est également à cet endroit que sont créées les tables de la BDD (Sales et Customers)


Sales.cs et Customers.cs ;
Il s'agit de la création des class Sales et Customers avec leur attribut "Id", "Name" et "Description"

SalesController et CustomersController ;
Ces pages servent à indiquer l'attribut [ApiController] qui indique que le code est une API qui utilise des requetes HTTP.
Les attributs {HttpGet] et [HttpPost] servent à récupérer ou envoyer des informations avec des requêtes Http.

J'ai compris le fonctionnement de l'API, son utilité et une partie de sa création, mais je n'ai pas réussi à la faire fonctionner correctement.
La connexion à la BDD s'effectue correctement.
