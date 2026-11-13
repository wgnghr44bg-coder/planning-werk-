# Planning Werk

Rooster voor een 5-ploegendienst: 2 vroeg, 2 laat, 2 nacht, 4 vrij.

De site is afgeschermd met een wachtwoord: `index.html` bevat alleen een versleutelde versie van de planning (AES-GCM, sleutel afgeleid van het wachtwoord met PBKDF2). Zonder wachtwoord is de inhoud niet te lezen.
