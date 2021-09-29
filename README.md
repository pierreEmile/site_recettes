# site_recettes<!DOCTYPE html>

<html  lang="fr">

    <head>
            <title> recette gateaux  </title>
            <meta charset= "UTF-8">
            <link rel="stylesheet"href="recette.CSS"/>


            
                



            
    </head>



    <body>
        <div class="centre , categorie">

            <p class="categorie" > Recette</p>
        </div>

        <div class="contenu">
            <h1 align="center"> Gateau au chocolat </h1>

            <div class="separateur"></div>


            


            <!--- voici le contenue de ma  page -->
            <div class="centre">

                <p style="color: black" class= "description">  <b>cette recette de gateaux aux chocolat a un grand classique. Elle fera plaisir au plus gourmand:</b>  </p>

            </div>

            <br>
                <a href="https://google.fr"
                target="_blank"> aller sur  Google</a>
            
            
            <br>
            <br>
            <div class= "info">
                <img class="centre info" src="https://img-3.journaldesfemmes.fr/QndQQSXutz_1tYbPPQF6SsUelIM=/750x500/smart/3fab692feaaf4aeda820708bbb11ada6/recipe-jdf/10018954.jpg">

                <table class="info">
                    <tr>
                        <th>Difficulter</th>
                        <th>Preparation</th>
                        <th>cuisson</th>
                        <th>Temps totals</th>

                    </tr>

                    <tr>
                        <td> Facile</td>
                        <td> 10 min</td>
                        <td> 25 min</td>
                        <td>  35 min</td>
                    </tr>

                </table>
                
            </div>
            <div class="colonne1 colonne">

                <p style="color : black"> <h2> Ingredients</h2>  </p>

                <!----- LISTE 
                    LISTE non ordonne: unordered list (ul)
                    LISTE ordonee : ordered list (ol)
                    Element : list item (li)
                -->

                <div class="ingredients">
                    <p> chocolat noir: 200g</p>
                    <p> sucre: 150g</p>
                    <p> beure : 200g</p>
                    <p> oeufs : 4 </p>
                    <p> Farine: 80g</p>

                </div>
           </div>

           <div class="colonne2 colonne">

                <p style="color : black"> <h2> Preparation</h2>  </p>

               
                <table class="preparation">
                    <tr><td><p class="numeros">1</p></td><td class="preparation_etape">faire fondre le chocolat avec du beurre</td></tr>
                    <tr><td><p class="numeros">2</p></td><td class="preparation_etape">melanger le sucre, les oeufs et la farine</td></tr>
                    <tr><td><p class="numeros">3</p></td><td class="preparation_etape">melanger le tout pour faire une patte</td></tr>
                    <tr><td><p class="numeros">4</p></td><td class="preparation_etape">mettre au four</td></tr>

                </table>
            </div>

            <!---- Tables 
                tr : table row (ligne)
                    th : table header (titre)
                
                    td: table data (donnee)
            -->


            <table border="1">
                <tr>
                    <th>Article</th>
                    <th>Prix</th>

                </tr>
                <tr>
                    <td> chocolat noir</td>
                    <td> 750 cfa</td>
                </tr>
                <tr>
                    <td> Beurre</td>
                    <td> 3.5 cfa</td>
                </tr>
                <tr>
                    <td> oeufs </td>
                    <td> 10.1 cfa</td>
                </tr>



        </table>
    </div>

    </body>
</html>
body {
    background-color: #8BA1BB;
    font-family: Arial;
    margin: 0;

}
p.categorie {
    background-color: black;
    color : white; 
    display: inline-block;
    
    margin-top: 0px ;
    padding: 8px 10px;
    margin-bottom: 0;
    font-weight: bold;
    font-size: 16px;
}

div.contenu {

    background-color: white;
    margin: 0px 10% 80px 10%;
    padding: 30px; 
    min-width: 350px;
    box-shadow: 0px 0px 8px 10px  rgba(0, 0, 0,0, 0.1);
}
h1 {
    text-align: center;
    margin-bottom: 12px;
    margin-top: 10px;
}
p.description {
    text-align: center;

    display: inline-block;
    font-size: 14px;
}
div.description {
    text-align: center;
}
.centre {
    text-align: center;
    width: 100%;

}
div.categorie{
    margin-bottom: -20px;
    margin-top: 60px ;
}
div.separateur{
    width: 100px;
    height: 1px;
    background-color: black;
    margin-left: auto;
    margin-right:auto ;
}
div.info {
    position: relative;


}
table.info {
    position: absolute;
    bottom : 0;
    width: 100%;
    color: white;
    background-color: #6C829DC0;
    height: 80px;


}
table.info td {
    text-align: center;
    font-size: 14px;
    vertical-align: top;
}
table.info th {
    vertical-align: bottom;
    padding-bottom: 8px;
}
img.info {
    display: block;
    max-height: 350px;
    object-fit: initial;
}
div.colonne {
    width: 50%;
    margin-top: 20px;

}
div.colonne h2 {
    text-align: center;
    text-transform: uppercase;
    font-size: 15px;
    border-bottom: 5px  solid #6C829DC0;
}
div.colonne1 {
    
    display: inline-block;

    


}
div.colonne2 {
    float:right;
    
    


}
div.ingredients p  {
    text-align: center;
    font-size: 14px;
    border: 1px solid lightgray;
    padding: 8px 0;
    margin-top: 4px;
    margin-bottom: 0;


}
table.preparation  p.numeros {
    background-color: #6C829DC0;
    color: white;
    width: 25px;
    height: 25px;
    text-align: center;
    font-size: 14px;
    font-weight: bold;
    padding-top: 4px;
    box-sizing: border-box;
    border-radius: 50%;
    margin: 0;
}
table.preparation td {

    vertical-align: top;
}
table.preparation td.preparation_etape {
    font-size: 14px;
    padding-left: 10px;
    padding-bottom: 10px;
}
table.preparation tr {
    height: 40px;
}

* {
    overflow: auto;
}
