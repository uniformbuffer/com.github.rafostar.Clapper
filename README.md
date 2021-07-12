This is a special flatpak build of Clapper (https://github.com/Rafostar/clapper) for aarch64 systems.

Build instructions:
- flatpak-builder --jobs=4 --ccache --keep-build-dirs --force-clean --default-branch=master build com.github.rafostar.Clapper.json --repo=repo
- flatpak build-bundle repo com.github.rafostar.Clapper.flatpak com.github.rafostar.Clapper
