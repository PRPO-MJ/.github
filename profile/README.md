# PRPO-MJ

## Organizacija za projekt pri predmetu PRPO

[📄 Dokumentacija (PDF)](PRPO.pdf)

Popravek: 
  - Nastavitve ciljev ima tudi dodajanje in brisanje ur čez
  - Nadzorna plošča servira / vrača React in MCP (nanjo se poveže kot recimo v VSCode - poglej kako dela in če lahko tudi direktno preko ChatGPTja kličeš ta server, drugače dodaj še to opcijo v nadzorno ploščo)
  - PAZI da vsaka mikrostoritev v bazi lahko gleda / spreminja samo svoje podatke, drugače mora iti preko druge mikrostoritve, ki je lastnica

Previdni bodite pri deljenju mikrostoritev (MS). Iz sheme zgleda, da so smiselno razdeljene po domenah in vse uporabljajo isto DB, pri čemer morate biti pozorni, da ima vsaka MS svojo DB shemo.
Frontend je tudi lahko MS.
