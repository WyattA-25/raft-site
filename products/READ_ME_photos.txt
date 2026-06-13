HOW TO ADD YOUR PRODUCT PHOTOS
==============================

Each product has its own folder here. Drop a photo named  main.jpg  into the
matching folder and it appears on the site automatically — no code changes
needed. Until then, a clean "PHOTO COMING SOON" placeholder shows in its place.

Folder  ->  Product
-------------------------------------------
7-pin-rack            ->  7-Pin Rack            (main.jpg)
wall-mount-cup-holder ->  Wall Mount Cup Holder (main.jpg)
e-breakaway-mount     ->  E-Breakaway Mount     (main.jpg)
battery-vent-cap      ->  Battery Vent Cap      (main.jpg)
fresh-water-cap       ->  Fresh Water Cap       (main.jpg)
bw-pin-rod            ->  B&W Pin Rod           (main.jpg)
screw-covers          ->  Screw Covers          (main.jpg)
corner-covers         ->  Corner Covers         (main.jpg)

WANT MULTIPLE PHOTOS ON A PRODUCT PAGE?
- Add more files to the folder, e.g.  main.jpg, 2.jpg, 3.jpg
- Then open index.html, find that product in the PRODUCTS list near the bottom,
  and list every file in its "images" array, for example:
      images:["products/7-pin-rack/main.jpg","products/7-pin-rack/2.jpg"]
- The first image is the one shown in the catalog grid. Extra images become
  clickable thumbnails on the product page.

TIPS
- .jpg or .png both work (keep the .jpg names above, or change the paths to match).
- Roughly square-ish / landscape photos look best in the cards (they're cropped to 4:3).
- Keep files reasonably small (under ~500 KB each) so the site loads fast.
