
# Fitxa tècnica: Creació i gestió d'un repositori a GitHub
 
## Objectiu
 
Aprendre a crear un repositori a GitHub, gestionar versions amb Git i sincronitzar els canvis amb un repositori remot.
 
## Materials
 
- Ordinador amb connexió a Internet
- Visual Studio Code
- Git instal·lat
- Compte de GitHub
 
## Procediment
 
1. Accedir a GitHub i iniciar sessió.
2. Crear un nou repositori.
3. Obrir Visual Studio Code.
4. Crear una carpeta per al projecte.
5. Inicialitzar el repositori local amb:
 
```bash
git init
```
 
6. Crear el fitxer `fitxa-tecnica.md`.
7. Afegir el fitxer al control de versions:
 
```bash
git add fitxa-tecnica.md
```
 
8. Crear un commit:
 
```bash
git commit -m "Crea estructura de fitxa tècnica"
```
 
9. Connectar el repositori local amb GitHub.
10. Pujar els canvis:
 
```bash
git push origin main
```
 
## Comprovacions
 
- [ ] El repositori s'ha creat correctament.
- [ ] Git detecta els canvis amb `git status`.
- [ ] El commit apareix a l'historial amb `git log`.
- [ ] Els fitxers s'han sincronitzat amb GitHub.
 
## Incidències i solucions
 
| Incidència | Solució |
|---|---|
| Git no reconeix la comanda | Instal·lar Git i reiniciar el terminal |
| Error d'autenticació amb GitHub | Revisar les credencials o el token d'accés |
| No es pot fer `git push` | Comprovar que l'URL del repositori remot és correcta |
| Els canvis no apareixen | Executar `git status` i afegir els fitxers amb `git add` |
 
## Recursos
 
- [ttps://docs.github.com/]
 
## Imatge
 
![Logo GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark)