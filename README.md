# veterinaria
Aquesta codi serveix per ajudar un centre d’adopció a gestionar els animals, els adoptants i les sol·licituds d’adopció. Està feta amb Kotlin, utilitzant l’arquitectura MVVM i Jetpack Compose per a la interfície gràfica. Les dades es guarden en fitxers JSON.

----Actors del sistema----
Treballador del centre d’adopció
Adoptant (client)
Administrador

------Escenaris d’ús-------
1. Registrar un nou animal
Què fa l’usuari: El treballador rep un nou animal i el vol registrar.
Acció: Omple un formulari amb nom, edat i tipus (gos/gat) i desa la informació.
Resultat esperat: L’animal apareix a la llista d’animals disponibles i queda registrat correctament.

2. Crear una sol·licitud d’adopció
Què fa l’usuari: Un adoptant s’interessa per un animal disponible.
Acció: Cerca l’animal a la llista, el selecciona i crea una sol·licitud.
Resultat esperat: La sol·licitud queda registrada i l’animal passa a estat d’adoptat.

3. Actualitzar l’estat d’un animal
Què fa l’usuari: El treballador vol indicar que un animal ha estat adoptat o reservat.
Acció: Entra a la fitxa de l’animal i canvia l’estat (disponible/adoptat/reservat).
Resultat esperat: La informació s’actualitza correctament al sistema.

-----Funcionalitats mínimes-----

Afegir animals nous.
Veure la llista d’animals disponibles.
Registrar animals adoptats.
Crear sol·licituds d’adopció.
Guardar i carregar dades en un fitxer JSON.


------Estructura de carpetes-------
/model
/repository
/viewmodel
/ui
/resources
/utils
README.md
