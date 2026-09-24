# Palmer Gallery Climate

Password-protected build of the Palmer Museum of Art climate dashboard (Penn State Heritage 3D Lab).
`index.html` is encrypted with [StatiCrypt](https://github.com/robinmoisson/staticrypt); nothing readable is stored in this repo.

Source and build scripts live in the private `palmerTwinAdmin` repo (`tools/`). To update: run
`tools/publish_site.sh` there, which rebuilds, encrypts, and pushes here.
