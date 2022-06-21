# Maintainer: Nathan Middleton <nathan@aplace.us>
pkgname=winfu
pkgver=1
pkgrel=1
pkgdesc="A script to do things for myself I couldn't find elsewhere easily."
arch=('any')
url="https://github.com/morenathan/winfu"
license=('GPL3')
depends=('bash'
		 'xorg-xprop'
		 'wmctrl'
		 'xdotool')
source=('winfu')
sha256sums=('f20d8bc08006f717cc5a2c199c0c055f8b3628fde5d026f217ce5deef3b0b651')

package() {
	install -Dm755 winfu "$pkgdir"/usr/bin/winfu
}
