The stable version 0.4.0 of https://github.com/Rafostar/clapper include all the fixes/patches/adaptations required to make it run on the Pinephone out of the box, so there is no need to use this repository anymore. The new version is also available on flathub, so you can install it as you normally would with any other flatpak application.

This is a special flatpak build of Clapper (https://github.com/Rafostar/clapper) for aarch64 systems.

Build instructions:
- flatpak-builder --jobs=4 --ccache --keep-build-dirs --force-clean --default-branch=master build com.github.rafostar.Clapper.json --repo=repo
- flatpak build-bundle repo com.github.rafostar.Clapper.flatpak com.github.rafostar.Clapper
