# BANNER
Cette commande, écrit en Pascal (Turbo Pascal ou Free Pascal), permet d'afficher une bannière. Cette commande est un équivalent de la commande UNIX.

<h3>Syntaxe</h3>

<b>BANNER</b> <i>message</i> [/OUTPUT:<i>format</i>] [/FILE:<i>fichier</i>] [/CHAR:<i>valeur</i>] [/FONT:<i>name</i>] 

<h3>Paramètres</h3>

<table>
  <tr>
    <th>Nom</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><i>message</i></td>
    <td>Ce paramètre permet d'indiquer le message à afficher.</td>
  </tr>
  <tr>
    <td><b>/CHAR:</b><i>valeur</i></td>
    <td>Ce paramètre permet d'indiquer un caractère ou une valeur entre 0 et 255. La valeur par défaut est #.</td>
  </tr>
  <tr>
    <td><b>/FILE:</b><i>fichier</i></td>
    <td>Ce paramètre permet d'indiquer le nom du fichier de sortie à la place de l'écran.</td>
  </tr>
  <tr>
    <td><b>/FONT:</b><i>nom</i></td>
    <td>Ce paramètre permet d'indiquer le nom de la police de caractères : DEFAULT, COMPUTER, SCRIPT,...</td>
  </tr>
  <tr>
    <td><b>/OUTPUT:BASH</b></td>
    <td>Ce paramètre permet d'indiquer que le message est en code source BASH.</td>
  </tr>
  <tr>
    <td><b>/OUTPUT:C</b></td>
    <td>Ce paramètre permet d'indiquer que le message est en code source C.</td>
  </tr>
  <tr>
    <td><b>/OUTPUT:PASCAL</b></td>
    <td>Ce paramètre permet d'indiquer que le message est en code source Pascal.</td>
  </tr>
</table>  

<h3>Exemples</h3>

L'exemple suivant permet d'afficher Bonjour :
<pre>
<b>BANNER</b> Bonjour
</pre>
on obtiendra le résultat suivant :

![image](https://github.com/gladir/BANNER/assets/11842176/22abaf87-4c46-4059-80e6-072ad8f7ea7b)

L'exemple suivant permet d'afficher gladir avec la police de caractères script :
<pre>
<b>BANNER</b> gladir /char:219 /font:script
</pre>

on obtiendra le résultat suivant :

![banner-example-1](https://github.com/gladir/BANNER/assets/11842176/0480b809-b3b4-4400-93c6-610777cb6889)

