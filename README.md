# Lietuvos teisė (git)

Lietuvos Respublikos teisės aktų suvestinės redakcijos kaip git istorija.

- Vienas failas = vienas teisės aktas (Markdown).
- Vienas commit = viena suvestinė redakcija.
- Commit data = data, nuo kurios redakcija galioja.
- Commit autorius = institucija, priėmusi keičiantį teisės aktą (pvz., Lietuvos Respublikos Seimas).
- Commit žinutėje nurodyti keičiantys aktai, jų paskelbimo duomenys ir nuorodos į e-tar.lt.

Naudinga: `git log -p konstitucija.md`, `git blame kodeksai/darbo-kodeksas.md`,
`git diff 'main@{2020-01-01}' -- konstitucija.md` (arba `git log --until=2020-01-01`).

**Tai neoficiali kopija.** Oficialūs tekstai skelbiami Teisės aktų registre: https://www.e-tar.lt

---

Lithuanian legislation as a git history: one file per act, one commit per consolidated version,
dated by entry into force and authored by the adopting institution. Unofficial; source: e-tar.lt.
