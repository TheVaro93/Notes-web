**A ne pas oublier:**  
les acolades (d'ouverture et de fermeture) {}  
(une partie des notes sont des codes générés par ia)  
Menu déroulant (relié avec le html)  

><style>
    /* Réinitialisation des marges et padding */
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    /* Style du menu principal */
    .menu {
        list-style: none;
        background-color: #333;
        display: flex; /* Affiche les éléments en ligne */
    }

    .menu > li {
        position: relative; /* Permet de positionner les sous-menus */
    }

    .menu > li > a {
        color: white;
        text-decoration: none;
        padding: 15px 20px;
        display: block; /* Permet de cliquer sur toute la surface */
    }

    /* Style au survol des éléments du menu principal */
    .menu > li > a:hover {
        background-color: #555;
    }

    /* Style des sous-menus */
    .sous-menu {
        list-style: none;
        position: absolute; /* Positionne le sous-menu par rapport au parent */
        top: 100%; /* Place le sous-menu juste en dessous */
        left: 0;
        background-color: #444;
        width: 200px;
        display: none; /* Cache le sous-menu par défaut */
    }

    .sous-menu > li > a {
        color: white;
        text-decoration: none;
        padding: 10px 15px;
        display: block;
    }

    /* Style au survol des éléments des sous-menus */
    .sous-menu > li > a:hover {
        background-color: #666;
    }

    /* Affiche le sous-menu au survol de l'élément parent */
    .menu > li:hover > .sous-menu {
        display: block; /* Affiche le sous-menu */
    }
</style>
