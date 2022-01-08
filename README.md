<h1>Compilation</h1>

<p>make</p>

<h1>Suppression des fichiers générés</h1>

<p>make clean</p>

<h1>Lancement du programme</h1>

<p>bash script.sh # ou bien</p>

<p>./script # Si vous avez un Permission denied ---> (sudo chmod u+x script.sh)</p>

<h1>Exécution sequentiel du programme sans le script</h1>

<h2>pour générer pseudo-aléatoirement de texte</h2>
<p>./genere-texte 50000 3 > texte3.txt</p> 
<h2>pour générer pseudo-aléatoirement de mots</h2>
<p>./genere-mots 10 5 25 3 > mots3.txt</p> 
<h2>Recherche Aho-corasick avec la matrice de transition</h2>
<p>./ac-matrice mots3.txt texte3.txt > res-ac-matrice</p>
<h2>Recherche Aho-corasick avec la table de hachage</h2>
<p>./ac-hachage mots3.txt texte3.txt > res-ac-hachage</p>

<h1>Comparaison entre les deux structures de données utilisées</h1>
<img src="./cmp.png">
