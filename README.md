## 1. Creació carpeta
He creat la carpeta `dunder_mifflin_xml` al **Escritorio** i l'he obert amb **Visual Studio Code**
<img width="512" height="288" alt="basededatos1" src="https://github.com/user-attachments/assets/4aa4c6ad-a342-4a69-92a3-f328cb3b32c8" />

---

## 2. Fitxers creats i codi inicial
He creat 2 fitxers, tot i que després he creat un més per poder fer la resolució d'errors:
**`dunder.dtd`** → Defineix regles (ordre, elements obligatoris, atributs)
**`dunder.xml`** → Document XML correcte amb mínim 3 elements per entitat
<img width="512" height="288" alt="basededatos2" src="https://github.com/user-attachments/assets/73a88447-e546-41d6-b5b2-f93ae79c2066" />
<img width="512" height="288" alt="basededatos3" src="https://github.com/user-attachments/assets/6878e0b6-f942-4808-833b-a2309b7f370c" />
<img width="512" height="288" alt="basededatos4" src="https://github.com/user-attachments/assets/e476a2d8-f7c7-4e28-9d53-8a0df1d7820f" />

---

## 3. Errors intencionals (dunder_errors.xml)
**He forçat 3 errors deliberats** per demostrar la validació:

**Errors detectats:**
**`productes` abans `comandes`** → *Orden incorrecte segons DTD*
**`<producte>` sense `<preu>`** → *Element obligatori absent*
**`tipus="urgente"`** → *Atribut no declarat al DTD*
<img width="512" height="288" alt="basededatos5" src="https://github.com/user-attachments/assets/4ec7538f-ad03-4372-be12-30aade48f6f3" />

---

## 4. Document corregit (0 errors)

**Correcció aplicada:**
1. Intercanviat ordre: `comandes` → `productes`
2. Afegit `<preu>1.20</preu>` al producte P002  
3. Eliminat atribut `tipus="urgente"`
<img width="512" height="288" alt="basededatos6" src="https://github.com/user-attachments/assets/a9f4bc2c-77af-4e56-acef-915e2454f4ac" />

