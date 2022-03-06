pkgname=vsv
pkgver=1.3.4
pkgrel=1
pkgdesc="An enhanced replacement for runit's sv"
license=("MIT")
arch=("x86_64")
provides=("vsv")

package() {
    cd ..
    usrdir="$pkgdir/usr"
    mkdir -p $usrdir
    export PREFIX=$usrdir
    make install
}
