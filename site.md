# ──────────────────────────────────────────────────────────────────────────────
# site.md — Site configuration
# Fill in the fields below, then run:
#   python /path/to/SiteGenerator/generate.py /path/to/this-folder
# ──────────────────────────────────────────────────────────────────────────────


# ── Identity ──────────────────────────────────────────────────────────────────

name: "LJ Brewskis"
github: "https://github.com/djbrieck/LJ-Brewskis"


# ── Operator (who runs this unofficial site) ──────────────────────────────────

operator: "Brieck's Pro"
operator_url: "https://brieckspro.com/"
operator_support_url: "https://brieckspro.com/value-for-value/"        # optional — remove line if not needed


# ── Favicon ───────────────────────────────────────────────────────────────────
# letter    : single character shown in the favicon square
# font      : any Google Fonts name (for reference only — PIL uses system fonts)
# color     : text color  (#rrggbb)
# background: square background color (#rrggbb)

favicon:
  letter: "B"
  font: ""
  color: "#ffff00"
  background: "#bb8844"


# ── Contact ───────────────────────────────────────────────────────────────────

location: "267 S Main St, Union, OR 97883"
phone: "541-562-6286"


# ── Hours ─────────────────────────────────────────────────────────────────────
# One line per entry, e.g. "Monday - Friday: 9AM to 5PM"

hours:
  - "Monday - Wednesday: 1130AM to 8PM"
  - "Thursday - Friday: 1130AM to 9PM"
  - "Saturday: 8AM to 9PM"
  - "Sunday: 8AM to 8PM"


# ── Links ─────────────────────────────────────────────────────────────────────
# Social media, review sites, etc.

links:
  - label: "Facebook: LJ Brewskis"
    url: "https://www.facebook.com/profile.php?id=100063707583500"


# ── Menu ──────────────────────────────────────────────────────────────────────
# Links to menu files (PDF, HTML) or an external menu page.
# Remove this section entirely if not needed.

menu:
  - label: "Takeout Menu - visual catalog"
    url: "docs/LJBrewskisMenuVisualCatalog/LJBrewskisMenu.html"
  - label: "Takeout Menu - plain text"
    url: "docs/LJBrewskisMenu.html"
  - label: "Takeout Menu - PDF"
    url: "docs/LJBrewskisMenu.pdf"


# ── Services ──────────────────────────────────────────────────────────────────
# One line per service offered.
# Remove this section entirely if not needed.

services:
  - "Neighborhood bar and grill serving breakfast, lunch and dinner."
  - "BBQ and Catering Food trailer for events, etc."

# ── Photos ────────────────────────────────────────────────────────────────────
# Files should live in the img/ folder next to this site.md.
# Remove this section entirely if not needed.

photos:
  - label: "Storefront"
    url: "img/storefront.webp"
