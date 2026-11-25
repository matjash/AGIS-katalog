# AGIS-katalog

Katalog slojev za vtičnik QGIS [AGIS](https://github.com/matjash/AGIS) (Arheološki GIS): javno dostopni viri za območje Slovenije.

*Layer catalogue for the [AGIS](https://github.com/matjash/AGIS) QGIS plugin: publicly available map sources for Slovenia.*

## Kaj je tukaj

- `agis_katalog.db` – katalog virov (datoteka SQLite). En vir je en sloj ali skupina slojev skupaj s slogom.

Vtičnik AGIS ob zagonu prenese zadnjo različico te datoteke in vire pokaže v zavihku **Naloži sloje** kot **Katalog AGIS**. Brez povezave uporabi zadnjo preneseno različico. Prenos se lahko izklopi v zavihku Nastavitve.

## Posodabljanje kataloga

1. V QGIS pripravite sloj ali skupino (vir, slog, ime).
2. V AGIS ga dodajte z gumbom **+** v **Moji viri**.
3. **⋯ → Izvozi kot katalog…**, izberite vire in shranite kot `agis_katalog.db`.
4. Datoteko objavite v tem repozitoriju (commit). Uporabniki jo dobijo ob naslednjem zagonu QGIS.

V katalog sodijo samo javno dostopni viri. AGIS pred izvozom odstrani gesla in opozori na lokalne datoteke.

## Napake in predlogi

Manjkajoč ali nedelujoč vir prijavite v [Issues vtičnika AGIS](https://github.com/matjash/AGIS/issues).
