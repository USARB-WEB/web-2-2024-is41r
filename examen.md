# Evaluare periodica

De creat un modul CRUD, conform variantei si de implementat functionalul descris mai jos. Toate endpoint-urile trebuie sa comunice in format JSON.


1. Creați un repositoriu privat ``ex27012025`` și deschideți acces pentru ``sergiuchilat`` (2p)
2. Creați o entitate(conform variantei) (2p)
3. Creati un ednpoint care va fi accesibil cu metoda GET si va returna lista tuturor entitatilor (2p)

Ex: GET /products va returna
```
[
   {
    "id": 1,
    "name: "Product 1"
    }
]
```
4. Creati un ednpoint care va fi accesibil cu metoda GET si va returna o entitate dupa id-ul indicat (2p)

Ex: GET /products/1 va returna
```
{
  "id": 1,
  "name: "Product 1"
}
```
5. Creati un ednpoint care va fi accesibil cu metoda POST si va permite adaugarea unei entitati (3p)

Ex: POST /products va primi
```
{
  "id": 1,
  "name: "Product 1"
}
```
si va returna "Succes" daca produsul a fost adaugat si "Error" daca produsul nu a fost adaugat.

6. Creati un ednpoint care va fi accesibil cu metoda PUT si va permite modificarea unei entitati cu un ID indicat (3p)

Ex: PUT /products/1 va primi
```
{
  "name: "Product 1 modificat"
}
```
si va returna "Succes" daca produsul a fost modificat si "Error" daca produsul nu a fost modificat.

7. Creati un ednpoint care va fi accesibil cu metoda DELETE si va sterge o entitate dupa id-ul indicat (2p)

Ex: DELETE /products/1 va returna
```
{}
```
daca produsul a fost sters si "Error" daca produsul nu aputut fi sters

8. Toate endpoint-urile trebuie sa returneze status code corect, in dependenta de situatie: (2 p)
- Cod 200 in caz ca operatia a fost executata cu succes
- Cod 404 in cazul in care informatia solicitata nu exista
- Cod 500 in cazul in care a aparut o eroare
9. Executați codul, faceți screenshoot-uri pe care le încărcați în repozitoriu, în mapa ``screens`` (1p)
10. Trebuie de facut cite un commit pentru fiecare însărcinare (1p)



Variante:
1. Car: name, engineType, maxSpeed
2. Bus: number, color, maxPlaces
3. Rabbit: name, age, type
4. Train: routeName, maxPassengers, color
5. Employee: idnp, name, salary
6. PC: brand, ramSize, price
7. Phone: brand, color, price
8. Bank Account: number, totalMoney, ownerName [5-CM]
9. Student: name, group, averageMark [1-BA]
10. Company: name, website, totalEmployees
11. Store: name, address, totalProducts [10-TA]
12. Monitor(screen): brand, resolution [8-PN]
13. Teacher: name, school, experience(in years)[3-CA]
14. Fish: species, weight, age(years) [9-RR]
15. POS terminal: number, storeName, casInForDay
16. Pupil: name, class, averageMark
17. User: email. password, phone [4-CA]
18. Product: name, price, weight
19. Butterfly: type, color, age(in days)


Barem de notare:
```
Nota     Puncte
10       19-20
 9       16-18
 8       13-15
 7       10-12
 6        8-9
 5        6-7
 4        4-5
 3          3
 2          2
 1          1
```
