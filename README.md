# sm-assets

Public CDN for social media images posted via the `/buffer` Claude Code skill.

Images are EXIF-stripped before commit (Orientation tag preserved per OPSEC rule).
Filenames are `sha256[:12].ext` under `images/YYYY/MM/` for dedup + browsability.
