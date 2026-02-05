# Maintenance

Tasks a maintainer would be interested performing.

## Documentation

Build the documentation with Hotdoc:

```
(ptv-flatpak) $ cd docs
(ptv-flatpak) $ hotdoc run 2>&1 | grep -v 2007_design | grep -v 2008_design
(ptv-flatpak) $ xdg-open output/html/index.html
```

Publish it with:

```
(ptv-flatpak) $ hotdoc run --git-upload
```
