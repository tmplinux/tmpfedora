pkgname=tmpfedora
pkgver=1.1.0
pkgrel=2
pkgdesc="Part of the tmplinux suite. Temporary Fedora"
arch=('any')
url="https://github.com/TheOddCell/tmpfedora"
license=('MIT')
depends=('bash' 'dnf' 'shadow' 'util-linux' 'systemd' 'squashfs-tools')
makedepends=()
source=('tmpfedora')
sha256sums=('SKIP')

package() {
    install -Dm755 tmpfedora "$pkgdir/usr/bin/tmpfedora"
}
