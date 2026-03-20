# References for *Careproctus argosgeorgiae* sp. nov. – Poster (2026)

This repository hosts the Zootaxa-style formatted reference list used in a scientific poster presented at the conference **“Topics of Fish Systematics”** (Zoological Institute RAS, Saint Petersburg, March 18–20, 2026), dedicated to the 150th anniversary of Lev S. Berg (https://www.zin.ru/conferences/Berg_2026/index_e.html).

The references support the following publication:

**Villarroel-Perez, M.L., Chernova, N.V., Weston, J.J.N., Vukasin, V. & Shcherbich, Z. (2026).**  
*A new species of Careproctus (Cottoidei: Liparidae) from the Falkland Plateau, southwestern Atlantic, with COI-based phylogenetic analysis.*  
Zootaxa, **5777**(3), 453–470.  
https://doi.org/10.11646/zootaxa.5777.3.3

---

##  Online Access (QR-linked)

The complete reference list is available via GitHub Pages:

 **https://martinglhf.github.io/careproctus-argosgeorgiae-references-poster/**

This URL is encoded as a QR code on the poster to avoid cluttering printed space and to allow attendees to view the full reference list on their mobile devices.

---

##  Repository Contents

| File                      | Purpose                                                     |
|---------------------------|-------------------------------------------------------------|
| `index.html`              | HTML page displaying all formatted references               |
| `generate_qr.R`           | R script used to generate the QR code                      |
| `qr_references_poster.png`| High-resolution QR code used in the poster                 |
| `README.md`               | Documentation and reproducibility information              |

---

## 🔧 Reproducing the QR Code in R

To regenerate the QR code:

```r
source("generate_qr.R")
```

This will produce the file:

```
qr_references_poster.png
```

in your working directory.

The file is generated in high resolution (800×800 px), suitable for A1-size posters.

---

##  Software Environment (Reproducibility)

QR code generation was performed under the following system configuration:

- **R version:** R version 4.1.3 (2022-03-10)
- **OS:** Windows 10 x64 (build 19045)
- **RStudio version:** 2024.4.2.764
- **Package:** qrencoder (CRAN version)

To obtain these values on your own system, you can run:

```r
R.version.string
Sys.info()
RStudio.Version()$version
```

---

##  License

No explicit license has been added.  
Default GitHub terms apply (view allowed; reuse not granted).

A Creative Commons license (such as **CC BY 4.0**) may be added later if reuse and attribution are desired.

---

## 📬 Contact / Citation

For formal citation, please cite the original Zootaxa publication once released.

For questions, suggestions, or improvements, feel free to open an **Issue** or submit a **Pull Request** in this repository.
