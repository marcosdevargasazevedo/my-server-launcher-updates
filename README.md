# Launcher update files

This folder is meant to become the root of a small static HTTPS site, such as a GitHub Pages repository.

Run the publisher script in the launcher project before uploading changes:

```powershell
powershell -ExecutionPolicy Bypass -File ".\scripts\generate-hosted-manifest.ps1"
```

Upload the **contents** of `hosted-content/`, not the containing folder itself.
