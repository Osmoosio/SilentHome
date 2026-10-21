# 🏠 Hiljainen koti (Silent Home)

Selaimessa pyörivä mikrofonilla ohjattava hiljaisuuspeli. Pysy hiljaa: kun hiljaisuutta on kestänyt tarpeeksi kauan, pöydälle lentää välipala (oletuksena suklaakeksi, vaihdettavissa asetuksista terveellisempään). Seuraava välipala tulee kaksinkertaisen ajan kohdalla jne. Jos meuhkaat liian kauan, pöytä kaatuu ja kohteet putoavat.

## Ominaisuudet

- Mikrofonin äänenvoimakkuuden mittari ja säädettävä raja (kynnys)
- Säädettävä nopeus ja rajat asetuksissa (⚙)
- Taustamusiikki ja äänet, mykistys (🔊)
- Vaalea/tumma teema (seuraa järjestelmän asetusta)
- "Jatka ilman mikkiä" -tila, jos mikrofonia ei saada käyttöön
- Mobiiliystävällinen (safe-area-tuki)

## Teknologia

Yksi tiedosto, ei riippuvuuksia ja ei build-vaihetta:

- HTML + CSS + vanilla JavaScript
- Canvas 2D -piirto
- Web Audio API (äänet, musiikki, mikrofonin analyysi)

## Käyttö

1. Avaa `index.html` selaimessa tai julkaise se esim. GitHub Pagesilla.
2. Salli mikrofoni, kun selain kysyy.
3. Paina **Aloita** ja pysy hiljaa.

Vinkkejä:

- Mikrofoni vaatii turvallisen yhteyden: käytä `https://`-osoitetta tai `localhost`. Paikallisesti esim. `python3 -m http.server` ja avaa `http://localhost:8000`.
- Jos peli on avattu sovelluksen sisällä (esim. viestisovelluksen selain), avaa linkki suoraan Safarissa tai Chromessa.

## Tiedostot

| Tiedosto | Kuvaus |
| --- | --- |
| `index.html` | Koko peli (markup, tyylit ja logiikka) |
