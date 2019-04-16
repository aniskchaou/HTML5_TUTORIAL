
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

**<!– … –>**	Définit un commentaire
**< !DOCTYPE>**	Définit le type du document
**< a>**	 Définit un lien
**< abbr>**	Définit une abréviation
**< address>**	Définit une adresse
**< area>**	Définit une zone à l’intérieur d’une image
**< article>** NOUVEAU	Définit un article
**< aside>** NOUVEAU	Définit une partie latérale au contenu
**< audio>** NOUVEAU	Définit un fichier audio
**< b>**	Texte en gras
**< base>**	Définit une URL de base pour tous les liens de la page
**< bdo>**	Définit la direction du texte
**< blockquote>**	Définit une longue citation
**< body>**	Définit le corps de la page
**< br>**	Saut de ligne
**< button>**	Définit un bouton cliquable
**< canvas>** NOUVEAU	Définit un graphique
**< caption>**	Légende du tableau
**< cite>**	Définit une citation
**< code>**	Mise en forme d’un texte en code informatique
**< col>**	Définit une colonne d’un tableau
**< colgroup>**	Définit un groupe de colonne pour un tableau
**< command>** NOUVEAU	Définit un bouton de commande
**< datalist>** NOUVEAU	Définit une liste d’options
**< dd>**	Définition d’un terme
**< del>**	Définit un texte supprimé
**< details>** NOUVEAU	Définit les détails d’un élément
**< dfn>**	Définition
**< div>**	Définit un calque ou une section
**< dl>**	Liste de définition
**< dt>**	Définition d’un terme
**< em>**	Mise en exergue d’un texte – italique
**< embed>** NOUVEAU	Définit un contenu extérieur (audio, vidéo …)
**< fieldset>**	Regroupe plusieurs éléments d’un formulaire
**< figcaption>** NOUVEAU	Légende d’un groupe d’élément multimédia
**< figure>** NOUVEAU	Définit un groupe d’élément multimédia
**< footer>** NOUVEAU	Définit le bas d’un section ou d’une page
**< form>**	Définit un formulaire
**< h1> to < h6>**	Définit un titre par degré importance de 1 à 6
**< head>**	Définit l’en-tête d’un document
**< header>** NOUVEAU	Définit le haut d’une section ou d’une page
**< hgroup>**  NOUVEAU	Regroupe les informations du haut d’une page ou section
**< hr>**	Barre horizontale
**< html>**	Définit un document html
**< i>**	Texte en italique
**< iframe>**	Introduit un page html dans une frame
**< img>**	Définit une image
**< input>**	Définit un champ
**< ins>**	Définit un texte insérer
**< keygen>** NOUVEAU	Générateur de clé pour un formulaire
**< kbd>**	Raccourcis ou touche du clavier
**< label>**	Légende d’un groupe d’élément de formulaire
**< legend>**	Titre d’un groupe d’élément d’un formulaire
**< li>** 	Élément d’une liste
**< link>**	Définit les relations entre les documents
**< map>**	Définit une carte
**< mark>**  NOUVEAU	Mise en valeur d’un mot ou d’un texte – Texte marqué
**< math>** NOUVEAU	Définit une formule mathématique
**< menu>**	Définit un menu en liste
**< meta>**	Définit des informations relatives au document
**< meter>** NOUVEAU	Définit une unité de mesure
**< nav>** NOUVEAU	Définit un groupe de liens de navigation
**< noscript>**	Définit une alternative au script non supporté
**< object>**	Définit un objet du contenu extérieur multimédia
**< ol>**	Définit une liste ordonné
**< optgroup>**	Regroupe d’une liste d »option dans un formulaire
**< option>**	Option d’une liste dans un formulaire
**< output>**  NOUVEAU	Définit un type de sortie
**< p>**	Définit un paragraphe
**< param>**	Définit les paramètres d’un objet
**< pre>**	Texte pré-formaté
**< progress>** NOUVEAU	Définit une progression
**< q>**	Définit une courte citation
**< rp>**  NOUVEAU	Annotation ruby si le script n’est pas supporté
**< rt>** NOUVEAU	Annotation ruby d’explication
**< ruby>** NOUVEAU	Définit une annotation en ruby
**< samp>**	Définit un échantillon de code
**< script>**	Définit un script
**< section>**  NOUVEAU	Définit une section
**< select>**	Définit une liste sélectionnable
**< small>**	Minimise l’importance d’un texte
**< source>** NOUVEAU	Définit la source d’un contenu multimédia
**< span>**	Définit une section de type inline
**< strong>**	Mise en exergue d’un texte – Texte en Gras
**< style>**	Définit un style CSS
**< sub>**	Mise en indice d’un texte
**< summary>** NOUVEAU	Définit l’en-tête des détails d’un document ou section
**< sup>**	Mise en exposant d’un texte
**< svg>** NOUVEAU	Définit une image vectorielle
**< table>**	Définit un tableau
**< tbody>**	Définit le corps d’un tableau
**< td>**	Définit une cellule d’un tableau
**< textarea>**	Définit une zone de texte
**< tfoot>**	Définit le bas d’un tableau
**< th>**	Définit une cellule d’en-tête d’un tableau
**< thead>**	Définit le haut d’un tableau
**< time>** NOUVEAU	Définit une unité de temps
**< title>**	Définit le titre d’un document
**< tr>**	Définit une ligne de tableau
**< track>** NOUVEAU	Définit une unité de temps pour les éléments < audio> et < video>.
**< ul>**	Définit une liste non-ordonné
**< var>**	Définit une variable
**< video>** NOUVEAU	Définit une vidéo
**< wbr>** NOUVEAU	Définit un possible retour à la ligne
