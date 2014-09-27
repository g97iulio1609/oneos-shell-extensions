# Maintainer: Giulio Leone <giulio97.leone@gmail.com>
pkgname=oneos-shell-extensions
pkgver=20140908
pkgrel=1
pkgdesc="This provides to One OS's Extensions."
arch=('i686' 'x86_64')
url="http://infinityos.org/repo/oneosui"
license=('LGPLv2+')
depends=('gnome-shell')
makedepends=('gtk-doc' 'gobject-introspection')
replaces=("gnome-shell-common","gnome-shell")
_realver=0.3.1
provides=("oneosui")
source=https://github.com/g97iulio1609/oneos-shell-extensions.git
md5sums=('SKIP')

package() {
    cd "${srcdir}/${pkgname}"

    mkdir -p "${pkgdir}"/usr/share/gnome-shell
    cp -R gnome-shell "${pkgdir}"/usr/share/

 
}
