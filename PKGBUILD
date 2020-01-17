# Maintainer: David Spink <yorper_protonmail.com>

pkgname=cleanjaro-release
pkgver=2020.01
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
sha256sums=('d96759d4cc86b347ef0f19f18d61085a3002a19c1e62836bbf238c1ded6005ea')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/

}
