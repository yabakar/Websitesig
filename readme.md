# Créer une application cartographique Web

---

** Etape 1 : **
Jeux de données : https://www.donneesquebec.ca/recherche/dataset/?sort=metadata_created+desc&organization=ville-de-quebec&res_format=GeoJSON

Télécharger et intégrer au projets les fichiers GeoJSON suivants :
* vdq-arrondissement.geojson.json : https://www.donneesquebec.ca/recherche/dataset/5ddf584d-b73d-4cd7-b203-28c3b5364d66/resource/5c5671d1-802f-4fa4-8c18-ebd3ce3d373b/download/vdq-arrondissement.geojson
* vdq-cheminfer.geojson.json : https://www.donneesquebec.ca/recherche/dataset/f60a3d1c-b797-4a67-861a-c06234551566/resource/e21709ff-7799-45bc-b6be-0f752fea0fe4/download/vdq-cheminfer.geojson
* vdq-hydrocourseauxsurface.geojson.json : https://www.donneesquebec.ca/recherche/dataset/5d725484-a008-4c53-a0be-33798b69518d/resource/6212d1e9-5568-4877-b5a8-6d5f43fb54a2/download/vdq-hydrocourseauxsurface.geojson
---

** Etape 2 : **

Renommer les fichiers téléchargés ainsi :
* vdq-arrondissement.geojson.json --> arrondissement.js
* vdq-cheminfer.geojson.json --> cheminfer.js
* vdq-hydrocourseauxsurface.geojson.json --> hydro.js
---

** Etape 3 : **
Initialiser le contenu des fichiers JSON dans des variables (arroundJSON, cheminFerJSON, hydroJSON) :

exemple pour le fichier hydro.js :
```javascript
let hydroJSON = {...}
```

