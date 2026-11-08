# JWT pitfalls

Toujours verifier `alg` cote serveur (liste blanche), l'`aud`, l'`iss` et l'`exp`.
Pas de donnees sensibles dans le payload: il est seulement signe, pas chiffre.
