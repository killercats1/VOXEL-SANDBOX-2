# VOXEL-SANDBOX-2

Extra client storage for [VOXEL-SANDBOX](https://github.com/killercats1/VOXEL-SANDBOX).
The site and launcher live at **https://killercats1.github.io/VOXEL-SANDBOX/**;
this repo only hosts client files, served by GitHub Pages at
`https://killercats1.github.io/VOXEL-SANDBOX-2/clients/...`.

## Hosting

Settings → Pages → Deploy from a branch → `main` / `(root)`.
`.nojekyll` makes Pages serve the files as-is.

To add a client here, put its `.html` under `clients/<version>/` and add an
entry with the full `https://killercats1.github.io/VOXEL-SANDBOX-2/...` URL to
the matching `assets/json/<version>.json` in the VOXEL-SANDBOX repo.

## Credits

The clients belong to their respective authors:

- Classic 0.30, Beta 1.1_02 and Beta 1.7.3: PeytonPlayz595
  (Beta 1.1_02 and Beta 1.7.3 are MIT licensed, Copyright (c) 2024-2025 PeytonPlayz595)
- Eaglercraft 1.3 and 1.5.2: lax1dude and ayunami2000
- Other 1.5, 1.9 and 1.11 clients: see the author listed for each on the site
