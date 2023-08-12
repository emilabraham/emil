# Emil

An extremely minimal theme

## Install

```
git submodule add https://github.com/emilabraham/emil themes/emil
echo "theme = 'emil'" >> hugo.toml
```

## shortcodes

### resize image

Render given image at given width. Maintains scale.

Usage:

```
{{< resize_image url="route.jpg" width="500px" >}}
```

## SiteVariables

```
.Site.Data.siteVariables.GitHub // Personal Github link for footer
```
