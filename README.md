# CoronaLabSion
Dépôt des projets réalisés durant la crise du Covid19

Sous l'impulsion de Grégoire Largey et Lucas Monachon, le FabLab Sion et TheArk se sont alliés afin de lancer un appel aux makers de Sion et région afin de fournir du matériel à l'Hôpital de Sion dans un premier temps. Deux modèles ont été retenu et il s'agira d'imprimer des montures pour un test à large échelle au sein de l'hôpital.

Pour toutes questions, vous pouvez contacter le FabLab Sion.

# Situation de la pandémie
Situation mondiale: https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6

Situation en Suisse: [COVID-19_Situation_epidemiologique_en_Suisse.pdf](COVID-19_Situation_epidemiologique_en_Suisse.pdf)

# Visières faciales

## Modèle NewShield Classic et NewShield Shark
Testée par Lucas Monachon, ce modèle a la particularité qu'aucun trou n'est nécessaire pour accrocher la feuille plastique sur la monture. Un système ingénieux de clip à dents tient la feuille. Design développé par Julien Delnatte (CTO de http://mango.io), Marc Demange, Guillaume Raineri et Mathieu Saulenc. https://newshield.org

- Licence: https://creativecommons.org/licenses/by-nc-nd/2.0/fr/

- Monture
	- fichier stl (unité: mm): [newshieldsupport-org-notext.stl](newshieldsupport-org-notext.stl)
	- modèle 3D :
	
		<img src="Prototype2.png" width="500" />

- Visière
	- Template pour la visière : [Template-shield-EUROPE-4hole.pdf](Template-shield-EUROPE-4hole.pdf)
	- Cette visière doit être découpée dans une feuille A4 transparente de 0.15mm d'épaisseur, au maximum dans du 0.18mm.
	- Les découpes peuvent être faites selon le template ci-dessus (pas besoin de faire les trous pour ce prototype).
	- Si la matière est du PVC, les découpes doivent être faites manuellement. Si la matière est du PET, les découpes peuvent être faites au laser.
	- Ces visières vont tout simplement venir ce cliper dans la monture tel que montré sur l'image suivante.
	
		<img src="details.png" width="300" />

- Impression de la monture
	- Matière: PLA ou PETG
	- Quantité utilisée: environ 20g 
	- Précision: 0.39mm est suffisant
	- Infill: 0% ou 10% pas plus.
	- Temps d'impression: environ 1h30 (sur une Zortrax M200)
	- Quantité de matière: environ 
	
- Assemblage
	- Si besoin, perforer la feuille là où il y a des trous dans la monture pour sécuriser la feuille si elle venait à tomber. 
	- Les boucles ne sont pas utilisées car non-nécessaire. A la place, l'élastique (de type élastique-boutonnière https://www.aboutdefil.com/images/pages/elastique-boutonniere.jpg) vient se crocher directement sur la monture afin qu'elle s'adapte à toutes les têtes.

		<img src="Assembled_frame.png" width="300" />

## Modèle 3DVerkstan
Testée par Grégoire Largey, ce modèle est fait pour être utilisée avec une feuille trouée au moyen d'une perforatrice 2 trous ISO 838 qui est commune dans toute l'Europe. Design développé par https://3dverkstan.se/protective-visor/.

- Licence: https://creativecommons.org/licenses/by-sa/3.0/deed.fr

- Monture
	- fichier stl (unité: mm): [Visor_frame_EUROPE_80mm_4hole_v1.stl](Visor_frame_EUROPE_80mm_4hole_v1.stl)
	- modèle 3D pour l'europe :
	
		<img src="visor_frame_iso838_a6.jpg" width="300" />	
  
- Visière
	- Template pour perforer la feuille A4 : [Template-shield-EUROPE-4hole.pdf](Template-shield-EUROPE-4hole.pdf)
	
		- Cette visière doit être découpée dans une feuille A4 transparente de 0.15mm d'épaisseur, au maximum dans du 0.18mm.
	
		- Si la matière est du PVC, faire les trous à l'aide d'une perforatrice standard :

			1. Réglez votre perforatrice sur la position d'une feuille A6, en tirant sur la barre de guidage jusqu'à ce qu'elle indique "A6".
			2. Faites un test de perforation sur un morceau de papier, puis mesurez la distance entre les trous et chaque bord et assurez-vous que la perforation est symétrique.
			3. Faites une perforation sur un côté du côté long de la feuille A4

				<img src="hole-punch-v1.jpg" width="300" />

			4. Retournez la feuille A4 autour de son axe court, et faites une perforation sur le côté opposé, de façon à obtenir 4 trous sur le même bord.
		
		- Si la matière est du PET, la feuille peut être découpée au moyen d'une découpeuse laser selon le template ci-dessus.

- Impression de la monture
	- Matière: PLA
	- Quantité utilisée: environ 11-12g 
	- Precision: 0.2mm est suffisant
	- Infill: 15% est suffisant (Veillez à ne pas trop remplir pour garder la souplesse)
	- Temps d'impression: environ 1h (sur une Prusa i3 Mk3s)

- Assemblage du tout

	<img src="europe-iso838-2.jpg" width="300" />
	

## Modèle "Minimalist"
- Un test de ce modèle (https://hackaday.io/project/170481-laser-cut-medical-shield) sera réalisé au FabLab de Renens. C'est une visière conçue par Konrad Klepacki et Mateusz Dyrda et qui présente l'avantage d'être produite uniquement par découpage de feuilles de PETG de 0.5 mm d'épaisseur.

# Informations sur les matières
- Le PLA ou le PETG plus idéalement semblent être des matières adéquates pour la production des montures imprimées en 3D.
- Le PVC ou le PET plus idéalement peuvent convenir pour les visières qui pourraient être désinfectées mais finalement consommées rapidement.

Ce document fait état de plusieurs type de désinfectant et permet d'avoir une vue sur ce qui peut aller suivant la matière de la monture désinfectée. https://faceshield.us/wp-content/uploads/2020/04/Sanitizing_Instructions.pdf

# Paramètres d'impression
**Attention aux quelques soucis de qualité d'impression, ces montures doivent rester un minimum confortables. Les paramètres d'impression jouent un rôle très important à ce niveau. Cette vidéo explique très bien les paramètres de base auxquels faire attention : [https://youtu.be/-7cbijYlGj4](https://youtu.be/-7cbijYlGj4)**

