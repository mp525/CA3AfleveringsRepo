## CA3AfleveringsRepo for Mathias Frank Parking(cph-mp525) gruppe 7 klasse E

På forsiden af mit projekt, ligger en beskrivelse af hver funktion på siden og hvilke krav de hver opfylder.
- Link til frontend: http://ca3mp525frontend.surge.sh/
- Link til backend: https://mparking.dk/CA3Backend/

- Link til gruppens startkode backend: https://github.com/mp525/StartcodeGrp7Backend
- Link til gruppens startkode frontend: https://github.com/mp525/StartcodeGrp7Frontend

- Link til Mathias's CA3 backend: https://github.com/mp525/ca3backend
- Link til Mathias's CA3 frontend: https://github.com/mp525/ca3frontend

På backend har jeg tilføjet flere endpoints, som frontenden kunne tilgå.
### Tilføjede endpoints: 
- /api/info/user/cats : (GET) Dette endpoint henter alle brugerens katte ud af databasen.
- /api/info/admin/cats : (GET) Gør det samme bare med adminstratoren.
- /api/info/admin/allCats : (GET) Dette endpoint henter alle katte i databasen.
- /api/info/breeds : (GET) Dette endpoint kalder på et eksternt api, der henter alle katteracer og returnerer dem til dette endpoint.
- /api/info/user : (POST) Dette endpoint tager imod den kat man sender med i requestet, og tilføjer den kat til brugeren der kalder endpointet.
- /api/info/admin : (POST) Gør det samme bare med adminstratoren.
- /api/info/admin/{id} : (DELETE) Dette endpoint tager imod et id og sletter katten med det id nede i databasen.
- /api/default : (GET) Dette endpoint henter et katte-fact og en tilfældig person fra et eksternt api og returnerer dem i et samlet DTO objekt til endpointet.
