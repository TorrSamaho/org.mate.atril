# Install prerequisites
```
flatpak install --user flathub org.gnome.Platform//47 org.gnome.Sdk//47 flathub org.flatpak.Builder
```

# Build and install (using the flatpak version of flatpak-builder)
```
flatpak run org.flatpak.Builder --disable-rofiles-fuse --force-clean build-dir org.mate.atril.yml
flatpak run org.flatpak.Builder --user --install --force-clean build-dir org.mate.atril.yml
```