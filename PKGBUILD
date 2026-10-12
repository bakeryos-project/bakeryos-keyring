# Maintainer: smtdfc <me.smdtfc@gmail.com>

pkgname=bakeryos-keyring
pkgver=1.0.0
pkgrel=1
pkgdesc="BakeryOS keyring"
url="https://github.com/bakeryos-project/bakeryos-keyring"
arch=('any')
options=(!debug !strip)
license=('GPL-3.0-or-later')
install=$pkgname.install
source=()
sha512sums=()

package() {
    install -D -m0644 -t "${pkgdir}/usr/share/pacman/keyrings/" \
        "${srcdir}/bakeryos.gpg" \
        "${srcdir}/bakeryos-trusted" \
        "${srcdir}/bakeryos-revoked"
}
