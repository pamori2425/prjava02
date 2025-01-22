git clone https://github.com/dacomo2021daw2/prjava02.git  
git remote -v  
git remote rm origin  
git remote add origin https://github.com/pamori2425/prjava02.git  
git branch branca00  
git checkout branca00  
git log --oneline  
git log main..branca00  
git merge branca00  
git log --oneline  
git push origin main  
git branch -r (per comprobar que només main ha estar pujada)  
git branch branca01  
git checkout branca01  
geany Prjava02.java  
git add Prjava02.java  
git push origin branca01  
git checkout branca00  
git push origin branca00  

5) A la branca main no veiem els commits fets dins de la branca00 ja que porten el control i l'historial separat.  
6) No ho podem veure per qué estem en una branca diferent i no hem fet un "merge" per unir-les, pel cual es com treballar en "dos fitxers diferents".  
7) Si afegim contingut a la branca main no es reflexarà a la branca00 fins que fem un merge per la mateixa raó que no es reflecteixen els canvis de 00 a main.  
12) Només s'ha actualitzat la branca main perquè el push es fa exclusivament de la branca activa al remot. Si vols que altres branques, com branca00, també estiguin al remot, s'ha de fer un git push de la branca.  
14) Es troba 1 commit ahead of main (està adelantat a main perqué hem fet un commit y push més nou y main encara no ha estat actualitzat).

