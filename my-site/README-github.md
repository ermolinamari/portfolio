# Maria Ermolina — AI Visual Director
## GitHub Pages setup & file structure

### Folder structure

```
/ (root)
├── index.html
├── robots.txt
├── sitemap.xml
└── images/
    ├── catalogue/
    │   ├── catalogue-white-lace-dress-front-01.jpg
    │   ├── catalogue-white-lace-dress-side-01.jpg
    │   ├── catalogue-white-lace-dress-back-01.jpg
    │   ├── catalogue-white-lace-dress-detail-01.jpg
    │   ├── catalogue-blue-silk-blouse-front-01.jpg
    │   ├── catalogue-blue-silk-blouse-back-01.jpg
    │   ├── catalogue-blue-silk-blouse-detail-01.jpg
    │   ├── catalogue-lace-blouse-cream-front-01.jpg
    │   ├── catalogue-lace-blouse-cream-back-01.jpg
    │   ├── catalogue-blue-silk-trousers-front-01.jpg
    │   ├── catalogue-blue-silk-trousers-back-01.jpg
    │   ├── catalogue-kids-blue-linen-dress-front-01.jpg
    │   ├── catalogue-kids-blue-linen-dress-back-01.jpg
    │   └── catalogue-kids-blue-linen-dress-side-01.jpg
    │
    ├── product/
    │   ├── product-white-lace-dress-front-01.jpg
    │   ├── product-white-lace-dress-back-01.jpg
    │   ├── product-lace-blouse-cream-front-01.jpg
    │   ├── product-lace-blouse-cream-back-01.jpg
    │   ├── product-blue-blouse-kolibri-front-01.jpg
    │   ├── product-blue-blouse-kolibri-back-01.jpg
    │   ├── product-blue-silk-top-front-01.jpg
    │   ├── product-blue-silk-top-back-01.jpg
    │   ├── product-blue-silk-top-detail-01.jpg
    │   ├── product-white-shorts-orange-trim-front-01.jpg
    │   └── product-white-shorts-orange-trim-back-01.jpg
    │
    └── campaign/
        ├── campaign-studio-portrait-hero.jpg          ← HERO image
        ├── campaign-ocean-black-sand-ladder-01.jpg
        ├── campaign-ocean-black-sand-portrait-02.jpg
        ├── campaign-ocean-black-sand-side-03.jpg
        ├── campaign-garden-cream-blouse-back-01.jpg
        ├── campaign-garden-cream-blouse-portrait-02.jpg
        ├── campaign-garden-cream-blouse-front-03.jpg
        ├── campaign-cote-dazur-lobster-dress-01.jpg
        ├── campaign-coastal-chess-cliffs-01.jpg
        ├── campaign-noir-editorial-ballet-01.jpg
        ├── campaign-paris-orange-blouse-front-01.jpg
        ├── campaign-paris-orange-blouse-back-02.jpg
        ├── campaign-amsterdam-green-pullover-01.jpg
        ├── campaign-lemon-print-editorial-01.jpg
        ├── campaign-green-editorial-collage-01.jpg
        ├── campaign-kids-blue-sky-ribbons-01.jpg
        └── campaign-kids-linen-portrait-01.jpg
```

### What each current file maps to

**Hero**
campaign-studio-portrait-hero.jpg → hf_20260518_191533_...png (girl in white lace, grey bg)

**Catalogue**
catalogue-white-lace-dress-front-01.jpg  → ms_a_plat_assol_bel_01.jpg
catalogue-white-lace-dress-side-01.jpg   → ms_a_plat_assol_bel_02.jpg
catalogue-white-lace-dress-back-01.jpg   → ms_a_plat_assol_bel_07.jpg
catalogue-white-lace-dress-detail-01.jpg → ms_a_plat_assol_bel_05 (detail crop)
catalogue-blue-silk-blouse-front-01.jpg  → ms_a_bluza_kolibri_blue_02.jpg
catalogue-blue-silk-blouse-back-01.jpg   → ms_a_bluza_kolibri_blue_03.jpg
catalogue-blue-silk-blouse-detail-01.jpg → ms_a_bluza_kolibri_blue_05.jpg
catalogue-lace-blouse-cream-front-01.jpg → ms_a_bluza_kruzhevo_bel_04__1_.jpg
catalogue-lace-blouse-cream-back-01.jpg  → ms_a_bluza_kruzhevo_bel_02.jpg
catalogue-blue-silk-trousers-front-01.jpg → ms_a_bruki_silk_blue_01.jpg
catalogue-blue-silk-trousers-back-01.jpg  → ms_a_bruki_silk_blue_02.jpg
catalogue-kids-blue-linen-dress-front-01.jpg → lien_blue_1.jpg
catalogue-kids-blue-linen-dress-side-01.jpg  → lien_blue_3.jpg
catalogue-kids-blue-linen-dress-back-01.jpg  → lien_blue_6___копия.jpg

**Product**
product-white-lace-dress-front-01.jpg       → us_a_plat_assol_bel_01.png
product-white-lace-dress-back-01.jpg        → us_a_plat_assol_bel_02.png
product-lace-blouse-cream-front-01.jpg      → us_a_bluza_kruzhevo_bel_03.jpg
product-lace-blouse-cream-back-01.jpg       → us_a_bluza_kruzhevo_bel_04.jpg
product-blue-blouse-kolibri-front-01.jpg    → us_a_bluza_kolibri_blue_01.jpg
product-blue-blouse-kolibri-back-01.jpg     → us_a_bluza_kolibri_blue_02.jpg
product-blue-silk-top-front-01.jpg          → us_a_top_silk_blue_07__1_.jpg
product-blue-silk-top-back-01.jpg           → us_a_top_silk_blue_08.jpg
product-blue-silk-top-detail-01.jpg         → us_a_top_silk_blue_11.jpg
product-white-shorts-orange-trim-front-01.jpg → us_a_short_bel-orange-_01.jpg
product-white-shorts-orange-trim-back-01.jpg  → us_a_short_bel-orange-_02.jpg

**Campaign**
campaign-ocean-black-sand-ladder-01.jpg    → 8ec90d0e3527b25e47...jpg
campaign-ocean-black-sand-portrait-02.jpg  → a2483fd192ddc0c633...jpg
campaign-ocean-black-sand-side-03.jpg      → b2b7169a6dea44ef67...jpg
campaign-garden-cream-blouse-back-01.jpg   → ms_a_bluza_kruzhevo_bel_02.jpg
campaign-garden-cream-blouse-portrait-02.jpg → ms_a_bluza_kruzhevo_bel_03.jpg
campaign-garden-cream-blouse-front-03.jpg  → ms_a_bluza_kruzhevo_bel_04__1_.jpg
campaign-cote-dazur-lobster-dress-01.jpg   → hf_20260611_180400...png
campaign-coastal-chess-cliffs-01.jpg       → b2b7169a6dea44ef67...jpg
campaign-noir-editorial-ballet-01.jpg      → hf_20260310_112159...png
campaign-paris-orange-blouse-front-01.jpg  → ms_a_bluza_silk_orange_01__3_.jpg
campaign-amsterdam-green-pullover-01.jpg   → d96e2b041765d7fe3e...png
campaign-lemon-print-editorial-01.jpg      → f3e085f55baaab6236...jpg
campaign-green-editorial-collage-01.jpg    → big_ban__3____копия.jpg
campaign-kids-blue-sky-ribbons-01.jpg      → e7c7860d24d4bdfc6e...png
campaign-kids-linen-portrait-01.jpg        → lien_blue_1.jpg

### How to deploy to GitHub Pages
1. Create repo: github.com/new — name it `mariaermolina.github.io`
2. Upload index.html + images/ folder
3. Go to Settings → Pages → Source: main branch / root
4. Site live at: https://mariaermolina.github.io

### To add new images later
1. Rename file using the naming system above
2. Place in the correct images/ subfolder
3. Add one line to the DATA object in index.html under the right category:
   {src:'images/catalogue/catalogue-NEW-NAME-01.jpg', alt:'description for Google', label:'Display Name · View'}
