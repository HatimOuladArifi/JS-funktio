JavaScriptillä funktio add, joka laskee yhteen lukuja. Funktion on toimittava seuraavasti:
add(4, 6); // Palauttaa 10.
add(4)(6); // Palauttaa 10.
// Mitä palauttaa seuraava kutsu?
// doubleAdder(3, 4)
function doubleAdder(x, y) {
return add(x)(y) + add(x, y);
}
