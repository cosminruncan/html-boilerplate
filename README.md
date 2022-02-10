# html-boilerplate

## Cand se modifica codul, rulati:

`git add .` adaugam toate fisierele in commit

`git commit -m "mesaj commit"` salvam stadiul codului cu mesajul "mesaj commit"

`git push` urcam continutul commitului pe server (origin)

## Daca descarcam prima data codul :

`git clone https://...` creaza o copie repo-ului de pe github

Aceasta copie are tot istoricul de pe github pentru acest repo

Odata clonat, se poate urca normal ca la procesul de mai sus (git `add`,`commit` si `push`)

## Daca lucram pe acelasi proiect pe mai multe device-uri:

Se presupune ca repo-ul a fost clonat pe toate device-urile.

- situatia 1: pe laptop1 s-au modificat fisiere:

Se urca in mod normal pe github cu comenzile de `add`, `commit`, `push`

Pe laptop 2 trebuie sincronizat codul. Se va rula:

`git pull` va aduce in local toate schimbarile de pe github
