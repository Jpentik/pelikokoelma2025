# Pelikokoelma

- Käyttäjä pystyy luomaan tunnuksen ja kirjautumaan sisään sovellukseen. (Tehty)
- Käyttäjä pystyy lisäämään, muokkaamaan ja poistamaan pelejä. (Lisäys tehty)
- Käyttäjä näkee sovellukseen lisätyt pelit. (Tehty)
- Käyttäjä pystyy etsimään pelejä hakusanalla.
- Sovelluksessa on käyttäjäsivut, jotka näyttävät jokaisesta käyttäjästä tilastoja ja käyttäjän lisäämät pelit.
- Käyttäjä pystyy valitsemaan pelille yhden tai useamman lisätiedon/luokittelun (esim. pelikonsoli, kunto, tuotekoodi, fyysinen/digitaalinen, halutaan ostaa/myydä)
- Käyttäjä pystyy lähettämään viestejä toisille käyttäjille.
- Käyttäjä pystyy lukemaan saamansa viestit ja vastaamaan viesteihin.
- Käyttäjä voi lisätä toissijaisena tietokohteena kuvia omiin tai toisten peleihin

Asennus- ja käyttöohjeet 21.9.2025

- Juurihakemistossa virtuaaliympäristön luonti:
`python3 -m venv venv`
- Virtuaaliympäristön käynnistys:
`source venv/bin/activate`
- Flask-kirjaston asennus:
`pip install flask`
- Tietokannan alustus:
`sqlite3 database.db < schema.sql`
- Sovelluksen käynnistys:
`flask run`
- Sovelluksen sulkeminen:
`Control+C`
- Virtuaaliympäristöstä poistuminen:
`deactivate`

Sovelluksen toiminnot:
- Kirjautumissivu:
`http://127.0.0.1:5000/`
- Rekisteröitymissivu:
`http://127.0.0.1:5000/register` 