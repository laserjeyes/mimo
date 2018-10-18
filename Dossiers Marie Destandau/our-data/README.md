# traitement des données

## exports (depuis Idesia)
01_idesia/keywords.xml : export MIMO 

01_idesia/hs.xml : export HS

## xml nettoyé (et enrichi des alignements 01_idesia/MIMOwikipedia.csv)
###02_cleaned/keywords.xml
pour mettre à jour, lancer 02_cleaned/clean_xml_mimo.py
###02_cleaned/hs.xml
pour mettre à jour, lancer 02_cleaned/clean_xml_hs.py

## skos
(pour appliquer une xslt, utiliser Oxygen par exemple)

###03_cleaned/keywords_skos.xml 
pour mettre à jour, appliquer la xslt 03_cleaned/keywords.xsl sur le fichier  02_cleaned/keywords.xml 

###03_cleaned/hs_skos.xml
pour mettre à jour, appliquer la xslt 03_cleaned/hs.xsl sur le fichier  02_cleaned/hs.xml
