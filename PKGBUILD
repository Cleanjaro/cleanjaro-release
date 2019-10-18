# Maintainer: David Spink <yorper_protonmail.com>

pkgname=cleanjaro-release
pkgver=19.10.12
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
sha256sums=('658aaba7f2380a565447531c6ff07d145457a8658787c9c3bbfe330e06a8f055')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/

}
