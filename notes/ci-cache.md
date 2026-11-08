# CI: cache des dependances

Cle de cache basee sur le hash du lockfile (`hashFiles('**/package-lock.json')`).
Un cache mal cle invalide a chaque run et ne sert a rien.
