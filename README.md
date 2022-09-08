A proposed Flathub addition for the game
[I Have No Tomatoes](http://tomatoes.sourceforge.net/) using
[sdl12-compat](https://github.com/libsdl-org/sdl12-compat).

To test locally, run the following commands from the root of the repository:

    git submodule update --init --recursive
    flatpak-builder --user --install --force-clean build net.sourceforge.tomatoes.IHaveNoTomatoes.json
    flatpak run net.sourceforge.tomatoes.IHaveNoTomatoes

**NOTE:** The Appstream data file currently contains a description and
references screenshots that are assumed to be under the same zlib/libpng license
as the game itself. It will be necessary to either replace them or get
permission to use them under one of the
[whitelisted licences](https://www.freedesktop.org/software/appstream/docs/chap-Metadata.html#tag-metadata_license).
