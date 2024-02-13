pkgname=md
pkgver=1.0.0
pkgrel=1
pkgdesc="shortened mkdir for lazy people"
arch=('any')
source=("md.sh")
sha512sums=('SKIP')

package() {
	mkdir -p "${pkgdir}/usr/bin"
	cp "${srcdir}/md.sh" "${pkgdir}/usr/bin/md"
	chmod +x "${pkgdir}/usr/bin/md"
}
