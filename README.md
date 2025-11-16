Simulator de economie – Gestionarea unei companii

Functionalitati principale si modul de implementare

Crearea unei companii cu departamente – realizata prin clase separate (Company si Department), unde Company contine o lista de departamente (compozitie).

Stabilirea bugetului pentru departamente – implementat prin clasa nested Budget din interiorul clasei Department.

Angajarea angajatilor – se face prin mostenire; clasele Engineer si Manager mostenesc din Employee, iar Company gestioneaza angajatii prin metode si operatori supraincarcati.

Concedierea angajatilor – implementata cu operatorul -= in clasa Company pentru eliminarea angajatilor dupa ID.

Afisarea angajatilor si a departamentelor – realizata prin functii membre si prin supraincarcarea operatorului << unde este necesar.

Calcularea cheltuielilor cu salariile – Company parcurge toti angajatii si aduna salariile folosind clasa Money.

Crearea si afisarea produselor – se foloseste clasa template Product<T> pentru a putea crea produse cu orice tip de valoare.

Gestionarea resurselor generice – realizata cu un template ResourcePool<T>, care poate stoca si administra diferite tipuri de resurse.

Supraincarcarea operatorilor (Money) – operatorii +, -, == si << permit manipularea sumelor de bani intr-un mod simplu.

Angajare si concediere prin operatori – operatorii += si -= din Company usureaza gestionarea angajatilor.


Actualizarea salariilor angajatilor – poti creste sau scadea salariile individuale sau pe departamente.

Transferul angajatilor intre departamente – mutarea unui angajat dintr-un departament in altul.

Raport lunar al cheltuielilor – afisarea cheltuielilor totale, pe departamente si pe angajati.

Cautarea angajatilor dupa nume sau ID – permite gasirea rapida a unui angajat.

Numar total de angajati si statistici pe departamente – afiseaza cati angajati sunt in fiecare departament.

Listarea produselor si a valorilor acestora – permite vizualizarea rapida a produselor companiei.