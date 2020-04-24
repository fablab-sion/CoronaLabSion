# CoronaLabSion
Dépôt des projets réalisés durant la crise du Covid19

Sous l'impulsion de Grégoire Largey et Lucas Monachon, le FabLab Sion et TheArk se sont alliés afin de lancer un appel aux makers de Sion et région afin de fournir du matériel à l'Hôpital de Sion dans un premier temps. Deux modèles ont été retenu et il s'agira d'imprimer des montures pour un test à large échelle au sein de l'hôpital.

Pour toutes questions, vous pouvez contacter le FabLab Sion.

# Situation de la pandémie
Situation mondiale: https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6

Situation en Suisse: [COVID-19_Situation_epidemiologique_en_Suisse.pdf](COVID-19_Situation_epidemiologique_en_Suisse.pdf)

# Visières faciales

## Modèle NewShield Shark
Testée par Lucas Monachon, ce modèle a la particularité qu'aucun trou n'est nécessaire pour accrocher la feuille plastique sur la monture. Un système ingénieux de clip à dents tient la feuille. Design développé par Julien Delnatte (CTO de http://mango.io), Marc Demange, Guillaume Raineri et Mathieu Saulenc. https://newshield.org

- Licence: https://creativecommons.org/licenses/by-nc-nd/2.0/fr/

- Fichier stl de la monture (unité: mm): [newshield-shark-notext.stl](newshield-shark-notext.stl)

- Visière
	- Pour la visière, utiliser une feuille A4 transparente de 0.2mm d'épaisseur, éventuellement de 0.15mm.
	- Ces visières vont tout simplement venir ce cliper dans la monture.

- Impression de la monture
	- Matière: PLA
	- Quantité utilisée: environ 20g 
	- Précision: 0.39mm est suffisant (sur une Zortrax M200)
	- Infill: 0% ou 10% pas plus.
	- Temps d'impression: environ 1h30 (sur une Zortrax M200)
	
- Assemblage
	- voir notice : [notice-newshield-shark-livret.pdf](notice-newshield-shark-livret.pdf)

## Modèle 3DVerkstan
Testée par Grégoire Largey, ce modèle est fait pour être utilisée avec une feuille trouée au moyen d'une perforatrice 2 trous ISO 838 qui est commune dans toute l'Europe. Design développé par https://3dverkstan.se/protective-visor/.

- Licence: https://creativecommons.org/licenses/by-sa/3.0/deed.fr

- Monture
	- fichier stl (unité: mm): [Visor_frame_EUROPE_80mm_4hole_v1-Batch_test-single.stl](Visor_frame_EUROPE_80mm_4hole_v1-Batch_test-single.stl)	
  
- Visière
	- Template pour perforer la feuille A4 : [Template-shield-EUROPE-4hole.pdf](Template-shield-EUROPE-4hole.pdf)
	
		- Cette visière doit être découpée dans une feuille A4 transparente de 0.15mm d'épaisseur, au maximum dans du 0.18mm.
	
		- Si la matière est du PVC, faire les trous à l'aide d'une perforatrice standard :

			1. Réglez votre perforatrice sur la position d'une feuille A6, en tirant sur la barre de guidage jusqu'à ce qu'elle indique "A6".
			2. Faites un test de perforation sur un morceau de papier, puis mesurez la distance entre les trous et chaque bord et assurez-vous que la perforation est symétrique.
			3. Faites une perforation sur un côté du côté long de la feuille A4

			4. Retournez la feuille A4 autour de son axe court, et faites une perforation sur le côté opposé, de façon à obtenir 4 trous sur le même bord.
		
		- Si la matière est du PET, la feuille peut être découpée au moyen d'une découpeuse laser selon le template ci-dessus.

- Impression de la monture:
	- Matière: PLA
	- Quantité utilisée: environ 11-12g 
	- Precision: 0.2mm est suffisant (sur une Prusa i3 Mk3s)
	- Infill: 15% est suffisant (Veillez à ne pas trop remplir pour garder la souplesse)
	- Temps d'impression: environ 1h (sur une Prusa i3 Mk3s)

- Assemblage du tout: La feuille vient se cliper sur les ergots.
	

## Modèle "Minimalist"
- Un test de ce modèle (https://hackaday.io/project/170481-laser-cut-medical-shield) sera réalisé au FabLab de Renens. C'est une visière conçue par Konrad Klepacki et Mateusz Dyrda et qui présente l'avantage d'être produite uniquement par découpage de feuilles de PETG de 0.5 mm d'épaisseur.

# Informations sur les matières
- Le PLA ou le PETG plus idéalement semblent être des matières adéquates pour la production des montures imprimées en 3D.
- Le PVC ou le PET plus idéalement peuvent convenir pour les visières qui pourraient être désinfectées mais finalement consommées rapidement.

Ce document fait état de plusieurs type de désinfectant et permet d'avoir une vue sur ce qui peut aller suivant la matière de la monture désinfectée. https://faceshield.us/wp-content/uploads/2020/04/Sanitizing_Instructions.pdf

# Paramètres d'impression
Attention aux quelques soucis de qualité d'impression, ces montures doivent rester un minimum confortables. Les paramètres d'impression jouent un rôle très important à ce niveau. Cette vidéo explique très bien les paramètres de base auxquels faire attention : [https://youtu.be/-7cbijYlGj4](https://youtu.be/-7cbijYlGj4)

