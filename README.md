# icon-assylum

A categorised collection of **4,103 icons and logos** (SVG, plus one PNG), sorted into 38 folders so they are easy to find.

## Structure

| Folder | Files |
|---|---|
| `aerospace-industrial` | 8 |
| `ai` | 144 |
| `browsers` | 51 |
| `browsers-extensions` | 1 |
| `cloud-hosting` | 138 |
| `communication-social` | 171 |
| `company-logos-simple-icons` | 221 |
| `creative-design` | 13 |
| `databases` | 67 |
| `dev-tools` | 353 |
| `devops-infrastructure` | 236 |
| `ecommerce-retail` | 20 |
| `education` | 13 |
| `email` | 57 |
| `file-formats` | 11 |
| `finance-payments` | 72 |
| `gaming` | 183 |
| `google` | 52 |
| `hardware-electronics` | 75 |
| `health-fitness` | 8 |
| `kawaii-art` | 37 |
| `logistics` | 2 |
| `media-management` | 246 |
| `microsoft` | 53 |
| `misc` | 219 |
| `monitoring-analytics` | 128 |
| `music-audio` | 82 |
| `operating-systems` | 78 |
| `productivity-office` | 352 |
| `pvy` | 240 |
| `remote-access` | 14 |
| `security-auth` | 163 |
| `smart-home-iot` | 168 |
| `storage-backup-files` | 155 |
| `streaming-video` | 57 |
| `telecom` | 16 |
| `voip-telephony` | 10 |
| `vpn-networking` | 189 |

- Icons keep their original file names. `-dark` and `-light` variants sit next to the base icon, and wordmark versions sit in the same folder as their base icon.
- `company-logos-simple-icons/` holds single-colour brand logos (filled with each brand's colour) grouped by industry: `telecom`, `tech`, `finance`, `media`, `social`, and so on.
- `misc/` holds icons that did not fit a clear category.
- `index.json` and `index.csv` list every icon with its name, category, variant, format and path. Use them to build a search page or to look up an icon quickly.

## Usage

Link an icon directly through the jsDelivr CDN:

```html
<img src="https://cdn.jsdelivr.net/gh/AbedLabLabee/icon-assylum/telecom/verizon.svg" width="48" alt="Verizon">
```

Pattern: `https://cdn.jsdelivr.net/gh/AbedLabLabee/icon-assylum/<category>/<name>.svg`

Or look an icon up in `index.json`:

```json
{"name": "verizon", "category": "telecom", "variant": "default", "format": "svg", "path": "telecom/verizon.svg"}
```

## Sources and licences

- Most icons come from [Dashboard Icons](https://github.com/homarr-labs/dashboard-icons) (homarr-labs). Check that project's licence before reuse.
- `company-logos-simple-icons/` is built from [Simple Icons](https://simpleicons.org) (CC0), with a few full-colour logos from [SVG Logos](https://github.com/gilbarbara/logos) and one Orange logo supplied by the repo owner.
- **Trademarks:** all logos are the property of their owners. An open licence on the file does not give you the right to use a brand's logo in any way you like. Follow each brand's usage guidelines, especially for commercial use.
