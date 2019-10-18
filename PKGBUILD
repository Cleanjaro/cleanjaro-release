# Maintainer: David Spink <yorper_protonmail.com>

pkgname=cleanjaro-release
pkgver=19.10.18
pkgrel=1
pkgdesc="Cleanjaro release definition"
arch=("any")
url="https://sourceforge.net/projects/cleanjaro/"
license=('GPL2')
depends=('lsb-release')
provides=('cleanjaro-release')
conflicts=('manjaro-release')
source=('lsb-release')
install="cleanjaro-release.install"
sha256sums=('f6ac8dac04810954962fc2cc57c28e864ddb4ed8f545c64dd71dd3527e52a036')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/

}
