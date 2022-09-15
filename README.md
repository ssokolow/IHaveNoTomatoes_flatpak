**Now merged as
[flathub/net.sourceforge.tomatoes.IHaveNoTomatoes](https://github.com/flathub/net.sourceforge.tomatoes.IHaveNoTomatoes).**
Archived here to preserve some links to it in some feature requests I opened on
SourceForge where I used it as an example.

A proposed Flathub addition for the game
[I Have No Tomatoes](http://tomatoes.sourceforge.net/) using
[sdl12-compat](https://github.com/libsdl-org/sdl12-compat).

To test locally, run the following commands from the root of the repository:

    git submodule update --init --recursive
    flatpak-builder --user --install --force-clean build net.sourceforge.tomatoes.IHaveNoTomatoes.json
    flatpak run net.sourceforge.tomatoes.IHaveNoTomatoes
