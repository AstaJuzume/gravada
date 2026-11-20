# Suvenyrų valdymo demonstracinis prototipas (Power Apps Canvas stilius)

## Kaip naudoti
Įkelkite `index.html` į GitHub Pages repozitorijos šaknį ir įjunkite GitHub Pages iš pagrindinės šakos.

Atidarykite svetainę HTTPS adresu, kad QR kodai turėtų tiesioginę produkto kortelės nuorodą. Vietinėje HTML peržiūroje QR kodai naudoja produkto SKU.

## Demonstruojami etapai
I: produktai, užsakymai, gamybos būsenos ir kiekiai, likučiai, perdavimas, atsekamumas.
II: savikaina, bendros išlaidos, filtruotos ataskaitos, PDF katalogų atsisiuntimas, QR, užduotys.

## Duomenys ir architektūra
Tai interaktyvus naršyklinis prototipas su localStorage. Duomenys saugomi atskirai kiekvienoje naršyklėje ir nėra bendrinami. Nėra Microsoft 365, Power Apps, SharePoint, Power Automate ar realios autentifikacijos integracijų. Rolės demonstruoja sąsajos ir veiksmų prieigos apribojimus, tačiau tai nėra tikra serverio saugos kontrolė.

## Demonstravimo seka
Užsakymas -> Gamyba -> Likučiai -> Perdavimo registravimas -> Judėjimo istorija -> Ataskaitos.

## QR ir PDF
QR skenavimas per kamerą veikia palaikomose naršyklėse saugioje HTTPS aplinkoje; kitur veikia rankinis produkto kodo įvedimas. PDF katalogas sukuriamas vietoje ir atsisiunčiamas.