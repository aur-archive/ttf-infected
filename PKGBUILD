# Maintainer : Firef0x <firefgx { at } gmail { dot } com>
# Contributor: Firef0x <firefgx { at } gmail { dot } com>

pkgname=ttf-infected
pkgver=20091226
pkgrel=1
pkgdesc="Free font which is infectiously wicked and will deliver an impact"
arch=('any')
url="http://asianpride7625.deviantart.com/art/INFECTED-Font-148051273"
license=('custom')
depends=('fontconfig' 'xorg-font-utils')
install=${pkgname}.install
source=('http://fc05.deviantart.net/fs71/f/2009/360/3/3/INFECTED_Font_by_asianpride7625.zip')
sha512sums=('d7a208ae535189a37f7b4c41319cbb45512708b4496cd673340c4384a87a90984f646a645d98b2e6e553bc1e16ca1dfeb612626542f025e4da51845fcb01c620')

DLAGENTS=('http::/usr/bin/wget -c -t 3 --waitretry=3 -H -U Mozilla -O %o %u')

package()
{
  install -D -m644 ${srcdir}/INFECTED.ttf "${pkgdir}/usr/share/fonts/TTF/INFECTED.ttf"
  install -D -m644 ${srcdir}/readme.txt "${pkgdir}/usr/share/licenses/${pkgname}/LICENSE"
}
