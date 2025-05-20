# Maintainer: Jonathan Sanfilippo  <jonalinux dot uk at gmail dot com>
# Maintainer: m4teo.dev <EosOS Linux>
# PKGBUILD EosOS core-gnome-backgrounds

pkgname=core-gnome-backgrounds
pkgver=2.2
pkgrel=1
pkgdesc="official Gnome backgrounds EosOS Linux"
arch=('any')
url=""

# dipendenze necessarie
depends=('gtk-update-icon-cache')

# comandi di installazione
package() {
    # crea la directory di destinazione
    mkdir -p "${pkgdir}/usr/share/backgrounds/core"
    # copia i file nella directory di destinazione
    cp -r core "${pkgdir}/usr/share/backgrounds/"
    
    # crea la directory di destinazione
     mkdir -p "${pkgdir}/usr/share/gnome-background-properties"
    # copia la cartella nella directory di destinazione
     cp -r gnome-background-properties "${pkgdir}/usr/share/"
   
}
