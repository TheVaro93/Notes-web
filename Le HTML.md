**A ne pas oublier** :  
les balises fermantes et ouvrantes (<> et </>)  
une balise auto fermante = une balise qui n'a pas de balise de fermeture  
enlever les points dans les balises qui sont là pour les empêcher de devenir fonctionnelles et qu'elles deviennent invisibles
fermer chaque parenthèse et les guillemets  

Les balises HTML :  <>  
Titres : de <.h1> (le plus grand) à <h6.> (le plus petit) 
Centrer du texte: <Center.>  
Intégrer un lien :<a href="https://fr.wikipedia.org/wiki/Hatsune_Miku".>  
Intégrer une image : <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.meme-arsenal.com%2Fmemes%2F7c3fa2146c74a6ecf638663f28aa4d1b.jpg&f=1&nofb=1&ipt=8b7226a29f5f72f07930d3f7400140a8b91da9ceb38d1732316a97bf585516f9" alt="Drink my vegetable juice" srcset="".>  (alt sert a donner une description de l'image et srcset de mettre une taille à l'image par exemple 300x300)  
Saut de ligne : <p.>  
Séparation de la page (crée une lgne horizontale) : <hr.> (balise auto fermante)  
Italique : <i.>  
Aliger un texte à droite/ gauche : <p style="text-align: right/left;".>  
Mettre un police d'écriture (ici monospace) :<p.style="font-family: monospace"> (enlever le point et mettre un espace à la place)  
Créer un menu déroulant (non clicable il faudra joindre du css avec pour le rendre fonctionnel sinon ca ressemblera à ca  
Accueil   Services   Produits   Contact  
              │  
              ├── Service 1  
              ├── Service 2  
              └── Service 3 )
              
><nav>
    <ul class="menu">
        <li><a href="#">Accueil</a></li>
        <li>
            <a href="#">Services</a>
            <ul class="sous-menu">
                <li><a href="#">Service 1</a></li>
                <li><a href="#">Service 2</a></li>
                <li><a href="#">Service 3</a></li>
            </ul>
        </li>
        <li>
            <a href="#">Produits</a>
            <ul class="sous-menu">
                <li><a href="#">Produit 1</a></li>
                <li><a href="#">Produit 2</a></li>
            </ul>
        </li>
        <li><a href="#">Contact</a></li>
    </ul> </nav>  

(<ul>) signifie liste non ordonnnée, sert a créer une liste sans ordre numérique  
<li.> signifie listem list, il définit un élément dans une liste et doit toujours se trouver dans une balise <ol> ou <ul>  
<class.> donne un nom  pour styliser avec du css ou javascript  
<ol.> liste à puces numérotées  





















