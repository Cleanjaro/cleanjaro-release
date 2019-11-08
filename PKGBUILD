# Maintainer: David Spink <yorper_protonmail.com>

pkgname=cleanjaro-release
pkgver=19.11
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
sha256sums=('56d0075dbb44e7c0622a2d42422835ef68950e1ad8cbe67cb94432352c6a81bc')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/

}
