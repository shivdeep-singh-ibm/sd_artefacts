
## CSS

Use simple pico.css like css.

### 1. jsDelivr CDN Links

* **Latest Version (recommended):**
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/shivdeep-singh-ibm/sd_artefacts@main/data/css/sd-claude-pico.css">

```


* **Pinned to a Specific Commit/Tag:** (Replace `main` with a specific commit hash or release tag for production stability)
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/shivdeep-singh-ibm/sd_artefacts@<TAG_OR_COMMIT>/data/css/sd-claude-pico.css">

```



---

### 2. Alternative CDNs

If you prefer using other popular public CDNs that support GitHub repositories directly:

* **unpkg CDN:**
```html
<link rel="stylesheet" href="https://unpkg.com/shivdeep-singh-ibm/sd_artefacts@main/data/css/sd-claude-pico.css">

```


* **RawGitHub / Raw.Githack CDN:**
```html
<link rel="stylesheet" href="https://raw.githack.com/shivdeep-singh-ibm/sd_artefacts/main/data/css/sd-claude-pico.css">

```


## Using with pandoc

pandoc --standalone \
  --css="https://cdn.jsdelivr.net/gh/shivdeep-singh-ibm/sd_artefacts@main/data/css/sd-claude-pico.css" \
  --metadata title="" input.md -o output.html

Otherwise ask your agent to a use the css "https://unpkg.com/shivdeep-singh-ibm/sd_artefacts@main/data/css/sd-claude-pico.css"
while creating html.

Example:

> Write a transformers tutorial with code snippets. It should be written in easy english.
Output format html with css "https://unpkg.com/shivdeep-singh-ibm/sd_artefacts@main/data/css/sd-claude-pico.css"
