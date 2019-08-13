# Maintainer: David Spink <yorper_protonmail.com>

pkgname=cleanjaro-release
pkgver=19.08.3
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
sha256sums=('5c0688e0f06026ca63bffad19417a4cef85ad38c74e78940b619ae39bedc9272')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/

}
