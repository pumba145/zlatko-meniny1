# Všetko najlepšie k meninám – moje zlatko ❤️

Romantická stránka k meninám s animovanými srdiečkami.

## Ako to spustiť

### Možnosť 1 – Lokálne
Otvor súbor `index.html` v prehliadači (dvojklik).

### Možnosť 2 – GitHub Pages (odporúčané)

1. Vytvor nový repozitár na GitHub-e (napr. `meniny-zlatko`)
2. Nahraj do neho všetky súbory z tohto priečinka:
   - `index.html`
   - `romantic_heart.jpg`
   - `README.md`
3. Choď do **Settings → Pages**
4. Ako Source vyber **Deploy from a branch** → branch `main` → folder `/ (root)`
5. Po chvíli bude stránka dostupná na:
   `https://tvoje-meno.github.io/meniny-zlatko/`

## Čo obsahuje
- Animované plávajúce srdiečka v pozadí
- Romantický text
- Foto srdiečka
- Podpis Daniel

Vytvorené s láskou.

## QR kód

V priečinku je súbor `qr-kod-meniny.png`.

**Dôležité:** QR kód momentálne ukazuje na ukážkovú adresu:
`https://tvoje-meno.github.io/meniny-zlatko/`

Po tom, čo si stránku nahráš na GitHub Pages, vygeneruj si nový QR kód s **tvojou skutočnou adresou**.

### Ako si vygenerovať vlastný QR kód (najjednoduchšie):

1. Choď na stránku: https://qr-code-generator.com alebo https://www.qr-code-styling.com
2. Vlož svoju skutočnú GitHub Pages adresu
3. Uprav farby (odporúčam ružovú / bordo)
4. Stiahni PNG

Alebo v termináli (ak máš Python):
```bash
pip install qrcode[pil]
python -c "
import qrcode
qr = qrcode.make('https://TVOJE-MENO.github.io/meniny-zlatko/')
qr.save('moj-qr.png')
"
```
