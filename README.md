# mpv-setup-config-files-linux
Personal clone of mpv config setup files and notes

1. `mpv` directory should be placed at $XDG_CONFIG_HOME (see `man xdg-user-dir`)
2. Scripts should be self-describing (see file headers)
3. Shaders should be cloned from [bjin/mpv-prescalers](https://github.com/bjin/mpv-prescalers) repo
4. Once the `mpv/shaders` directory is cloned, run the Python build from there to generate your shaders.
5. Link your shaders to mpv through the `mpv.conf` file and use the `auto-profiles.lua` script to automatically pick the
   appropriate profile (and shader) based on the video resolution.
6. Note: The mpv version I use is built from the git sources/AUR. See https://aur.archlinux.org/packages/mpv-build-git/.
7. A great resource/blog post that explains how the shaders work in more detail can be found at
   http://freetime.mikeconnelly.com/archives/5371.
