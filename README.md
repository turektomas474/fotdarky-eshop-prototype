# Fotodárkový e-shop: prototyp v1

## 1. Účel projektu

Prototyp e-shopu zaměřeného na fotodárky. Projekt slouží jako výchozí verze pro další vývoj skutečného obchodního systému s backendem a relační databází.

## 2. Součásti aplikace

| Soubor            | Účel                                |
| ----------------- | ----------------------------------- |
| `mini-eshop.html` | Zákaznická část e-shopu             |
| `admin.html`      | Administrace obchodu                |
| `warehouse.html`  | Rozhraní skladového hospodářství    |
| `common.css`      | Sdílené styly                       |
| `store.js`        | JavaScriptová logika a práce s daty |
| `README.md`       | Dokumentace projektu                |

## 3. Výchozí technologie

* HTML
* CSS
* JavaScript
* localStorage pro lokální ukládání dat a simulaci sdíleného stavu

## 4. Architektonická omezení

Tato verze je prototyp, nikoli produkční obchodní systém.

* Aplikace zatím nemá ověřený produkční backend.
* PostgreSQL zatím není součástí systému.
* localStorage není náhradou za centrální databázi sdílenou mezi zařízeními.
* Produkční přihlášení, oprávnění, bezpečnost a zpracování plateb nejsou v této dokumentaci potvrzeny jako implementované funkce.

## 5. Výchozí verze

* GitHub repository: `fotdarky-eshop-prototype`
* Verze: `prototype-v1`
* Výchozí větev: `main`

## 6. Plán dalšího vývoje

1. Ověřit současné funkce a integrační tok.
2. Navrhnout datový model pro fotodárkový e-shop.
3. Vytvořit PostgreSQL databázi.
4. Implementovat backend v Node.js a Express.
5. Připojit zákaznickou část, administraci a sklad ke společnému API.
6. Doplnit autentizaci, oprávnění, správu fotografií a bezpečnost.
7. Nasadit systém na server a provést integrační testy.

## 7. Pravidlo vývoje

Původní prototyp slouží jako referenční verze. Změny architektury budou probíhat postupně, s ověřováním jednotlivých funkcí a zachováním možnosti návratu k výchozímu stavu.
