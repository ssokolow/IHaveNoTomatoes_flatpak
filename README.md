A proposed Flathub addition for the game
[I Have No Tomatoes](http://tomatoes.sourceforge.net/) using
[sdl12-compat](https://github.com/libsdl-org/sdl12-compat).

To test locally, run the following commands from the root of the repository:

    flatpak-builder --user --install --force-clean build net.sourceforge.tomatoes.IHaveNoTomatoes.json
    flatpak run net.sourceforge.tomatoes.IHaveNoTomatoes
