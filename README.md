API Testing Project – ReqRes

Šiame projekte atlikau API testavimą naudodamas ReqRes demonstracinę REST API.
Testai sukurti siekiant patikrinti įvairius endpoint’us, jų atsakymus.

Testuojama buvo:
GET užklausos – vartotojų ir resursų gaunami duomenys, pavieniai įrašai.
POST užklausos – vartotojo kūrimas, registracija, prisijungimas.
PUT/PATCH užklausos – vartotojo atnaujinimas.
DELETE užklausa – vartotojo ištrynimas.

Tikrinimai: 
Status code (200, 201, 204, 400, 404).
Response body struktūra ir reikšmės (pvz. id, name, email, token).
Negatyvūs scenarijai („not found“, „missing password“).
Headerių validacija (Content-Type).
Performance – API atsako laikas < 1000 ms.
Regex patikrinimai
Elementų tam tikrų savybių turėjimas.

Naudoti įrankiai:
Postman (rankiniam testavimui ir kolekcijų sudarymui).
Newman / JavaScript testai (automatiniam paleidimui ir validacijoms).

Projekto struktūra:
tests/API Testing Project – ReqRes.json – testų kolekcija.
README.md – projekto aprašymas.
