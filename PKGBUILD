pkgname=phpbb3-lang-de
pkgver=3.0.12
_realver=3_0_12
_pkg_id=91416
pkgrel=2
pkgdesc="German‎ Language Pack for phpBB3 (Casual Honorifics)"
arch=('any')
url="https://www.phpbb.com/customise/db/translation/german_casual_honorifics/"
license=('GPL')
depends=('phpbb3=3.0.12')
source=("https://www.phpbb.com/customise/db/download/id_${_pkg_id}")
md5sums=('9b06cdad852e61779775c0288e65fa7c')

package() {
  install -d  ${pkgdir}/usr/share/webapps/phpbb3/
  cp -a $srcdir/german_casual_honorifics_${_realver}/* ${pkgdir}/usr/share/webapps/phpbb3/
}
