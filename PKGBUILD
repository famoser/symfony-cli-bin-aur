# Maintainer: Florian Moser <arch@famoser.ch>

pkgname=symfony-cli-bin
pkgrel=7
pkgver=5.11.0
pkgdesc="The Symfony client helps developers create and manage Symfony applications."
url="https://symfony.com/"
arch=('x86_64')
license=('AGPL3')
provides=('symfony-cli')
conflicts=('symfony-cli')
source=(
    "$pkgname-$pkgver.tar.gz::https://github.com/symfony-cli/symfony-cli/releases/download/v${pkgver}/symfony-cli_linux_amd64.tar.gz"
)
sha256sums=('d6246c751c00a693a5cc9d91be08a3315a37095d02dba1e29b92c458800fa5a3')

package() {
    install -D -m 755 "${srcdir}/symfony" "${pkgdir}/usr/bin/symfony"
}
