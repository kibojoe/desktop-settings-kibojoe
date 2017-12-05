# Maintainer: Holmes <holmes_holmes [at] live [dot] com>

pkgname=base-skel-kibojoe
pkgver=20171201
pkgrel=1
pkgdesc='Kibojoe Linux base skeleton files'
arch=('x86_64')
url="https://github.com/kibojoe/desktop-settings-kibojoe"
license=('GPL3')
makedepends=('git')
source=("git+$url.git")
sha256sums=('SKIP')
install=$pkgname.install
depends=('')
conflicts=('')

pkgver() {
	date +%Y%m%d
}

package() {
	install -d $pkgdir/etc
	cp -r $srcdir/desktop-settings-kibojoe/shared/skel_new $pkgdir/etc
}
