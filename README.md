# Legacy SetrojaLab website redirects

This repository preserves old website links after the organization became **SetrojaLabs**.

The maintained website is https://setrojalabs.github.io/.

GitHub Pages must publish `main` from `/ (root)` in `setrojalab/setrojalab.github.io`.

The root and package pages redirect in the browser to the new hostname, preserving the path, query and fragment. Former `recurcast` and `coherent4cast` paths map to `coherentSurv`. A custom `404.html` handles other old browser paths. Without JavaScript, known pages use their fixed destination and display a clickable link.

These are static browser redirects, not HTTP 301 redirects. Do not use this repository as a raw-data or API proxy. Keep all package code and releases in the `setrojalabs` organization. Do not recreate the old package repository names: that can override GitHub's repository redirects.

