# Maintainer: Antonio Rojas <nqn1976 @ gmail.com>

pkgname=ksuperkey
pkgver=0.3
pkgrel=2
pkgdesc="Allows you to open the application launcher in KDE Plasma Desktop using the Super key"
arch=('i686' 'x86_64')
url="http://kde-apps.org/content/show.php/ksuperkey?content=154569"
license=('GPL')
depends=('libxtst')
makedepends=()
source=("http://kde-apps.org/CONTENT/content-files/154569-$pkgname-$pkgver.tar.gz")
md5sums=('4aeffbcd6928cfeea6a19dc4a1508ed0')

build() {
  cd $pkgname-$pkgver
  make
}

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}

