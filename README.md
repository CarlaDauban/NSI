<html lang="fr"> 
  <head>
    <title>courspage1.html</title>
 <style>
 
body {
  background-color: rgb(191, 170, 170);
}

h1 {
  color: black;
  text-align: center;
  font-family: Fantasy;
  border-style: solid;
  border-radius: 15px;
}

h2 {
  font-family: sans-serif;
  font-size: 20px;
}

h3 {
  font-family: sans-serif;
  font-size: 15px;
}

p {
  font-family: sans-serif;
  font-size: 15px;
}

p1 {
  font-family: sans-serif;
  background-color: lightgrey;
}

p2 {
  font-family: sans-serif;
  border-style: groove;
}

table {
    font-family: sans-serif;
    border-collapse: collapse;
}

td, th {
    border: 1px solid black;
}
  
</style>
  <head/>
    
    <body>
      <h2>1°) Base d’un système de numération</h2>
      <p>La base d’un système de numération est le nombre de chiffres différents qu’utilise ce système de numération.<p/>
      
      <h3>1.1°) Système décimal</h3>
      <p>C’est le système le plus couramment utilisé. Il est dit de base 10, il comprend donc 10 symboles ou chiffres : <p1>0, 1, 2, 3, 4, 5, 6, 7, 8, 9</p1>.<br/>Ex : N = (2756)<sup>10</sup><br/>L’indice 10 indique que le nombre écrit entre les parenthèses est en base 10. On peut écrire ce nombre sous la forme d’un polynôme :<br/><p1>N = 2.10<sup>3</sup> +7.10<sup>2</sup> + 5.10<sup>1</sup> + 6.10<sup>0</sup><br/>N = 2000 + 700 + 50 + 6<br/>N = 2756</p1><br/>Le polynôme est constitué de plusieurs monômes. Dans chaque monôme, on trouve un chiffre du nombre N qui est multiplié par une puissance de la base avec pour exposant le rang du chiffre de N.</p>
      
      <h3>1.2°) Système binaire</h3>
      <p>Les minuscules interrupteurs électroniques des microprocesseurs (c’est le « cerveau » d’un ordinateur)
ne connaissent que 2 états, ouvert ou fermé, représentés par <p1>0 ou 1</p1>. Le langage interne des microprocesseurs est donc basé sur le système binaire.<br/>Avec ces 2 états, le système binaire permet des circuits très efficaces et peu coûteux.<br/>Toutes les informations traitées par un microprocesseur doivent donc être converties en binaire.<br/>Ce système de base 2 comprend 2 symboles qui sont les chiffres 0 et 1<br/>Chacun d’eux est appelé aussi bit (contraction de Binary Digit) ou élément binaire.<br/>Ex : N = (1 0110)<sub>2</sub> = <p1>%10110 = 1.2<sup>4</sup> + 0.2<sup>3</sup> + 1.2<sup>2</sup> + 1.2<sup>1</sup> + 0.2<sup>0</sup></p1></p>

		<h3>1.3°) Système hexadécimal</h3>
        <p>Le code binaire est si éloigné de la pensée humaine que les utilisateurs ont dû imaginer un moyen plus rapide pour représenter des nombres binaires.</br>Ce système de base 16 comprend 16 symboles qui sont les chiffres et symboles suivant <p1>0,1,2,3,4,5,6,7,8,9, A, B, C, D, E, F</p1><br/>Ex : N = (56A)<sub>16</sub> = <p1>$56A = 5.16<sup>2</sup> + 6.16<sup>1</sup> + 10.16<sup>0</sup><p1/>

		<h3>1.4°) Tableau récapitulatif</h3>
        <table>
        <tr>
        	<th>SYSTEME</th>
        	<th>BASE</th>
        	<th>SYMBOLES</th>
       	 	<th>POIDS</th>
        </tr>
        <tr>
           <td>Binaire</td>
           <td>2</td>
           <td>0, 1</td>
           <td>2<sup>n</sup>...2<sup>2</sup>2<sup>1</sup>2<sup>0</sup></td>
         </tr>
         <tr>
         	<td>Décimal</td>
            <td>10</td>
            <td>0, 1, 2, 3, 4, 5, 6, 7, 8, 9</td> 
            <td>10<sup>n</sup> ... 10<sup>2</sup> 10<sup>1</sup> 10<sup>0</sup></td>
         </tr>
         <tr>
         <td>Hexadécimal</td>
         <td>16</td>
         <td>0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F</td> 
         <td>16<sup>n</sup> ... 16<sup>2</sup> 16<sup>1</sup> 16<sup>0</sup></td>
        
        </table>
        

  </body>
</html>
