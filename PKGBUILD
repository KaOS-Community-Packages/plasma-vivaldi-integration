pkgname=plasma-vivaldi-integration
pkgver=0.0.3
pkgrel=1
pkgdesc="Plasma browser integration for Vivaldi"
arch=('x86_64')
url="https://github.com/KDE/plasma-browser-integration"
license=('GPL')
depends=('plasma-browser-integration')
_extension=cimiefiiaegbelhefglklhhakcgmhkai.json

package() {
	install -dm 755 $pkgdir/opt/vivaldi{,-snapshot}/extensions
	ln -s /usr/share/chromium-browser/extensions/$_extension $pkgdir/opt/vivaldi/extensions/$_extension
	ln -s /usr/share/chromium-browser/extensions/$_extension $pkgdir/opt/vivaldi-snapshot/extensions/$_extension
}
