# NearbyApp

Nume: Bigeo
Prenume: Simona
Grupa: 341C2

Proiect: aplicatie Android
Arhiva finala : NearbyDemo v final

Resurse utilizate (documentatie):
https://developer.android.com/studio/index.html
https://developers.facebook.com/docs/facebook-login/android
https://developers.google.com/maps/documentation/android-api/start

Etapa 1:
  - Implementare ecran principal (MainActivity) : background, icon
  - Integrare Facebook Login cu ajutorul LoginManager
  - Creare buton Google Maps, implmentare Google Maps cu updateul locatiei in timp real (MapsActivity)
    Sursa utilizata : https://developers.google.com/maps/documentation/android-sdk/map-with-marker
  
Etapa 2:
  - Integrare FireBase 
    Sursa : https://firebase.google.com/docs/android/setup
  - Scrierea datelor utilizatorilor in baza de date, retinerea primei zi de autentificare,
    retinerea datei ultimei autentificari, asignare userId
  - Preluarea constanta a locatiei din aplicatie si scrierea datelor in baza pentru fiecare
    utilizator in parte
  - Incercare creare Chat. Retinerea mesajelor din chat in baza de date. (ChatMessage)

Etapa 3:
  - Conditionarea accesului la facilitatile aplicatiei - utilizatorul nu va avea 
    acces daca nu este logat cu Facebook ( am folosit o variabila bool pentru
    verificarea autentificarii cu Firebase )
  - Update-ul constant al locatiei in fundal (nu este necesara accesarea butonului
    de Google Maps)
    Sursa : https://developer.android.com/training/location/receive-location-updates
  - Afisarea distantei utilizatorului curent fata de ceilalti utilizatori. Acest lucru se obtine
    prin iterarea in baza de date si calcularea distantei intre distanta utilizatorului curent
    si utilizatorii din baza.
    Sursa : https://andrew.hedges.name/experiments/haversine/

