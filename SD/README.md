# System Design Laboratories

**Student:** Oprea Alexandru  
**Group:** InfA241  
**Language:** English

## Laboratory work

| Laboratory | Solution | Contents |
| --- | --- | --- |
| Lab 1 — Initial Product Definition | [Open Lab 1](./lab-1/README.md) | Product research, stakeholders/actors, scope, five user stories, and C4 System Context. |
| Lab 2 — Quality and Capacity Estimates | [Open Lab 2](./lab-2/README.md) | Measurable quality targets, three-scale steady/burst RPS, researched instrument count, reproducible record sizes, storage, and bottleneck hypotheses. |

Future laboratories will be linked when their assignments and solutions exist; empty or placeholder solutions are not presented as completed work.

## Course sources and submission arrangement

- [Course material repository — read only](https://github.com/AlexOp27-z/system-design-labs/tree/main).
- [Presentation rules](https://github.com/AlexOp27-z/system-design-labs/blob/main/PRESENTATION-RULES.md) and [Romanian version](https://github.com/AlexOp27-z/system-design-labs/blob/main/PRESENTATION-RULES-ro.md).
- Solutions are published in this **personal public repository**, following the student's reported agreement with the teacher to use individual repositories. This is the agreed exception to the written fork instruction; the remaining content, language, structure, evidence, and presentation rules still apply.
- All student work is inside `SD/`. The course material repository is not modified.

## Screenshot upload checklist

The written solutions include source URLs, research decisions, and image references. **Research evidence remains incomplete until the corresponding real screenshots are uploaded, or the allowed live demonstration is given.** No screenshots have been fabricated or described as already supplied.

Use PNG files with the **exact lowercase filenames** below. The Markdown references are already written, so uploading the files is enough to make them appear in the laboratory pages; no text replacement is required.

| Destination folder | Filename | What to capture | Public source |
| --- | --- | --- | --- |
| `SD/lab-1/assets/` | `google-finance-overview.png` | Market overview, recognisable source title, and URL. | [Google Finance](https://www.google.com/finance/) |
| `SD/lab-1/assets/` | `google-finance-watchlist.png` | The official description of following securities or creating watchlists. No sign-in is necessary. | [Google help](https://support.google.com/websearch/answer/7579076?hl=en) |
| `SD/lab-1/assets/` | `tradingview-filters.png` | The Filters section, showing exchange/sector criteria; use the public documentation, not an account or trading session. | [TradingView screener guide](https://www.tradingview.com/support/solutions/43000718866-tradingview-stock-screener-trade-smarter-not-harder/) |
| `SD/lab-2/assets/` | `stock-definition.png` | The explanation distinguishing common and preferred stocks. | [Investor.gov](https://www.investor.gov/introduction-investing/investing-basics/investment-products/stocks) |
| `SD/lab-2/assets/` | `nasdaq-directory.png` | The file header and several instrument rows, with the source URL visible. The estimate's snapshot date/counts are documented in Lab 2. | [Nasdaq-listed directory](https://www.nasdaqtrader.com/dynamic/SymDir/nasdaqlisted.txt) |
| `SD/lab-2/assets/` | `nasdaq-fields.png` | Nasdaq-Listed Securities definitions, especially Test Issue and File Creation Time. | [Nasdaq directory definitions](https://www.nasdaqtrader.com/Trader.aspx?id=SymbolDirDefs) |

### Upload steps on GitHub

1. Take your own readable captures of the public source sections. Include the browser URL and, where practical, your system date. Do not include passwords, account balances, personal data, or unrelated tabs. Do not alter source numbers or dates.
2. Save/export each image as PNG using its exact filename above. Renaming a JPEG extension to `.png` is not a format conversion.
3. Open [Lab 1 assets](./lab-1/assets/) in **this** repository, choose **Add file → Upload files**, and upload the three Lab 1 PNGs. Commit to `main`, for example with `Add Lab 1 research screenshots`.
4. Repeat in [Lab 2 assets](./lab-2/assets/) for its three PNGs, with `Add Lab 2 research screenshots`.
5. Reopen each laboratory README and verify that all three images render and the text in them is readable. Do not upload an extra enclosing `SD` or `assets` directory inside the existing assets folder.

The empty `.gitkeep` files only make the destination folders available before the images are added. They are not evidence and can remain there. Live sources can change: a later capture is evidence of the page when captured, not proof of the exact earlier snapshot count.

## Presentation readiness

Present Lab 1 before Lab 2, with at most two laboratories per session. Upload the written work and evidence **before** the presentation. Be ready to explain the scope choices, why delayed data is not zero, how the six RPS rows and burst were calculated, why user traffic is not provider traffic, and why gross history ingestion differs from retained storage.

These are design documents and estimates. They do not claim a working application, completed performance tests, or guaranteed grading outcomes.
