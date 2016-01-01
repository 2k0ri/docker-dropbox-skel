# dropbox-skel

- Dropbox skeleton inspired by [ctrl/dropbox](https://hub.docker.com/r/ctlc/dropbox/)
- It's set `ja_JP.UTF-8` for locale.

1. Launch the container via `docker run -v $PATH_TO_SYNC:/root/Dropbox 2k0ri/dropbox-skel`
2. Get the authentication url from `docker logs`, and access via your own browser
3. Commit the changes with `docker commit 2k0ri/dropbox-skel your/own-container-name`
4. Re-Launch with `docker run -v $PATH_TO_SYNC:/root/Dropbox -p 17500:17500 your/own-container-name`
