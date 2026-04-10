# Cod reducere MediaWorld — fetch automat de pe shopilo.it

Modul Python pentru fetch automat de **coduri de reducere MediaWorld** de pe [shopilo.it](https://shopilo.it/magazin/mediaworld.it). Returneaza **cupoane MediaWorld** active in format JSON, gata de integrat intr-un bot Telegram, extensie de browser sau orice alt tool.

**Pagina live:** [shopilo-it.github.io/codice-sconto-mediaworld](https://shopilo-it.github.io/codice-sconto-mediaworld/)

![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue) ![License MIT](https://img.shields.io/badge/license-MIT-green)

## Instalare

```bash
pip install requests beautifulsoup4
git clone https://github.com/shopilo-it/codice-sconto-mediaworld
cd codice-sconto-mediaworld
python fetch.py
```

## Output exemplu

```json
[
  {
    "store": "MediaWorld",
    "code": "SHOPILO10",
    "discount": "10%",
    "description": "10% di sconto su elettronica e elettrodomestici",
    "expires": "2026-10-10",
    "source": "https://shopilo.it/magazin/mediaworld.it"
  }
]
```

## Cupoane MediaWorld disponibile

| Reducere | Descriere | Sursa |
|----------|-----------|-------|
| 10% | 10% di sconto su elettronica e elettrodomestici | [shopilo.it](https://shopilo.it/magazin/mediaworld.it) |

Codurile active: **[shopilo.it/magazin/mediaworld.it](https://shopilo.it/magazin/mediaworld.it)**

## Intrebari frecvente

### Cum folosesc un cod de reducere MediaWorld?
Copiaza codul din tabelul de mai sus sau de pe [shopilo.it](https://shopilo.it/magazin/mediaworld.it), adauga produsele in cos pe MediaWorld, si introdu codul la checkout in campul dedicat.

### Cat timp sunt valabile cupoanele MediaWorld?
Fiecare cupon are data de expirare afisata in coloana "Expira". Scriptul fetch.py returneaza doar cupoanele active la momentul rularii.

### Unde gasesc cele mai noi voucher-uri MediaWorld?
Pagina [shopilo.it/magazin/mediaworld.it](https://shopilo.it/magazin/mediaworld.it) este actualizata zilnic cu cele mai noi cod reducere MediaWorld, voucher MediaWorld si cupon promotional MediaWorld.

### Codul nu functioneaza. Ce fac?
Verifica data de expirare si conditiile (valoare minima cos, produse eligibile). Unele coduri sunt valabile doar in aplicatia mobila sau pentru prima comanda.

## Despre MediaWorld

MediaWorld este unul dintre magazinele online populare. Gasesti pe [shopilo.it](https://shopilo.it/magazin/mediaworld.it) cele mai bune cod reducere MediaWorld, cupoane MediaWorld verificate si voucher MediaWorld active, actualizate zilnic.

## Instalare npm

```bash
npm install codice-sconto-mediaworld
```

```javascript
const { fetchCoupons } = require('codice-sconto-mediaworld');
fetchCoupons().then(data => console.log(data));
```

## Licenta

MIT — date sursa de pe [shopilo.it](https://shopilo.it)
