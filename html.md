
## **entête du document - head**

## **Le titre**

  
Le titre de votre page, 
  

## **Les scripts**

Les scripts sont de petits programmes en JavaScript ou en VBScript
On distingue deux moyens d'inclure des scripts :  

 - Les scripts externes.   
 - Les scripts internes.

  
**Les scripts externes**  

< script  type="text/javascript"  src="chemin/du/fichier/javascript.js">  
  
  
**Les scripts internes**  

< script  type="text/javascript">  
function maFonction()  
{  
/* du code ici */  
}  
  
  

## **Les styles**

Les feuilles de style en cascade ou CSS (Cascading Style Sheets) s'utilisent pour mettre en page notre code HTML.  
  
**Les styles externes**  
  
< link  rel="stylesheet" type="text/css"  href="chemin/du/fichier.css">  
  
Import avec du code CSS  
< style type="text/css">  
@import url("chemin/du/fichier.css");  
  
  
**Les styles internes**  

< style  type="text/css">  
body  
{  
background-color : #fff;  
}  
  
## **Les meta**

  
On peut différencier deux grandes familles de balises meta :  
**name**  
Touchent toutes les informations concernant le document, l'auteur, le site, les outils utilisés, etc.  
**http-equiv**  
Concernent les meta qui communiquent avec le navigateur.  
**content-type**  
Cette meta est la plus importante et la seule obligatoire pour passer la validation W3C.  

< meta  http-equiv="content-type"  content="text/ html;  charset=utf-8">

## **Le DOCTYPE**

  Il sert d'une part à déclarer quel "langage", "grammaire", ou norme on applique à notre page.

## **Les commentaires**

Ils sont délimités par  < !--  et  -->  et peuvent être multilignes.

## Block-level Elements

A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).
< address>< article>< aside>< blockquote>< canvas>< dd>< div>< dl>< dt>< fieldset>< figcaption>< figure>< footer>< form>< h1>-< h6>< header><hr>< li>< main>< nav>< noscript>< ol>< p>< pre>< section>< table>< tfoot>< ul>< video>

## Inline Elements

An inline element does not start on a new line and only takes up as much width as necessary.
< a>< abbr>< acronym>< b>< bdo>< big>< br>< button>< cite>< code>< dfn>< em>< i>< img>< input>< kbd>< label>< map>< object>< output>< q>< samp>< script>< select>< small>< span>< strong>< sub>< sup>< textarea>< time>< tt>< var>

## Listes des balises

**<!– … –>**	Définit un commentaire<br>
**< !DOCTYPE>**	Définit le type du document<br>
**< a>**	 Définit un lien<br>
**< abbr>**	Définit une abréviation<br>
**< address>**	Définit une adresse<br>
**< area>**	Définit une zone à l’intérieur d’une image<br>
**< article>** NOUVEAU	Définit un article<br>
**< aside>** NOUVEAU	Définit une partie latérale au contenu<br>
**< audio>** NOUVEAU	Définit un fichier audio<br>
**< b>**	Texte en gras<br>
**< base>**	Définit une URL de base pour tous les liens de la page<br>
**< bdo>**	Définit la direction du texte<br>
**< blockquote>**	Définit une longue citation<br>
**< body>**	Définit le corps de la page<br>
**< br>**	Saut de ligne<br>
**< button>**	Définit un bouton cliquable<br>
**< canvas>** NOUVEAU	Définit un graphique<br>
**< caption>**	Légende du tableau<br>
**< cite>**	Définit une citation<br>
**< code>**	Mise en forme d’un texte en code informatique<br>
**< col>**	Définit une colonne d’un tableau<br>
**< colgroup>**	Définit un groupe de colonne pour un tableau<br>
**< command>** NOUVEAU	Définit un bouton de commande<br>
**< datalist>** NOUVEAU	Définit une liste d’options<br>
**< dd>**	Définition d’un terme<br>
**< del>**	Définit un texte supprimé<br>
**< details>** NOUVEAU	Définit les détails d’un élément<br>
**< dfn>**	Définition<br>
**< div>**	Définit un calque ou une section<br>
**< dl>**	Liste de définition<br>
**< dt>**	Définition d’un terme<br>
**< em>**	Mise en exergue d’un texte – italique<br>
**< embed>** NOUVEAU	Définit un contenu extérieur (audio, vidéo …)<br>
**< fieldset>**	Regroupe plusieurs éléments d’un formulaire<br>
**< figcaption>** NOUVEAU	Légende d’un groupe d’élément multimédia<br>
**< figure>** NOUVEAU	Définit un groupe d’élément multimédia<br>
**< footer>** NOUVEAU	Définit le bas d’un section ou d’une page<br>
**< form>**	Définit un formulaire<br>
**< h1> to < h6>**	Définit un titre par degré importance de 1 à 6<br>
**< head>**	Définit l’en-tête d’un document<br>
**< header>** NOUVEAU	Définit le haut d’une section ou d’une page<br>
**< hgroup>**  NOUVEAU	Regroupe les informations du haut d’une page ou section<br>
**< hr>**	Barre horizontale<br>
**< html>**	Définit un document html<br>
**< i>**	Texte en italique<br>
**< iframe>**	Introduit un page html dans une frame<br>
**< img>**	Définit une image<br>
**< input>**	Définit un champ<br>
**< ins>**	Définit un texte insérer<br>
**< keygen>** NOUVEAU	Générateur de clé pour un formulaire<br>
**< kbd>**	Raccourcis ou touche du clavier<br>
**< label>**	Légende d’un groupe d’élément de formulaire<br>
**< legend>**	Titre d’un groupe d’élément d’un formulaire<br>
**< li>** 	Élément d’une liste<br>
**< link>**	Définit les relations entre les documents<br>
**< map>**	Définit une carte<br>
**< mark>**  NOUVEAU	Mise en valeur d’un mot ou d’un texte – Texte marqué<br>
**< math>** NOUVEAU	Définit une formule mathématique<br>
**< menu>**	Définit un menu en liste<br>
**< meta>**	Définit des informations relatives au document<br>
**< meter>** NOUVEAU	Définit une unité de mesure<br>
**< nav>** NOUVEAU	Définit un groupe de liens de navigation<br>
**< noscript>**	Définit une alternative au script non supporté<br>
**< object>**	Définit un objet du contenu extérieur multimédia<br>
**< ol>**	Définit une liste ordonné<br>
**< optgroup>**	Regroupe d’une liste d »option dans un formulaire<br>
**< option>**	Option d’une liste dans un formulaire<br>
**< output>**  NOUVEAU	Définit un type de sortie<br>
**< p>**	Définit un paragraphe<br>
**< param>**	Définit les paramètres d’un objet<br>
**< pre>**	Texte pré-formaté<br>
**< progress>** NOUVEAU	Définit une progression<br>
**< q>**	Définit une courte citation<br>
**< rp>**  NOUVEAU	Annotation ruby si le script n’est pas supporté<br>
**< rt>** NOUVEAU	Annotation ruby d’explication<br>
**< ruby>** NOUVEAU	Définit une annotation en ruby<br>
**< samp>**	Définit un échantillon de code<br>
**< script>**	Définit un script<br>
**< section>**  NOUVEAU	Définit une section<br>
**< select>**	Définit une liste sélectionnable<br>
**< small>**	Minimise l’importance d’un texte<br>
**< source>** NOUVEAU	Définit la source d’un contenu multimédia<br>
**< span>**	Définit une section de type inline<br>
**< strong>**	Mise en exergue d’un texte – Texte en Gras<br>
**< style>**	Définit un style CSS<br>
**< sub>**	Mise en indice d’un texte<br>
**< summary>** NOUVEAU	Définit l’en-tête des détails d’un document ou section<br>
**< sup>**	Mise en exposant d’un texte<br>
**< svg>** NOUVEAU	Définit une image vectorielle<br>
**< table>**	Définit un tableau<br>
**< tbody>**	Définit le corps d’un tableau<br>
**< td>**	Définit une cellule d’un tableau<br>
**< textarea>**	Définit une zone de texte<br>
**< tfoot>**	Définit le bas d’un tableau<br>
**< th>**	Définit une cellule d’en-tête d’un tableau<br>
**< thead>**	Définit le haut d’un tableau<br>
**< time>** NOUVEAU	Définit une unité de temps<br>
**< title>**	Définit le titre d’un document<br>
**< tr>**	Définit une ligne de tableau<br>
**< track>** NOUVEAU	Définit une unité de temps pour les éléments < audio> et < video>.<br>
**< ul>**	Définit une liste non-ordonné<br>
**< var>**	Définit une variable<br>
**< video>** NOUVEAU	Définit une vidéo<br>
**< wbr>** NOUVEAU	Définit un possible retour à la ligne<br>
