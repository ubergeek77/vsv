pkgname=vsv
pkgver=1.3.4
pkgrel=1
pkgdesc="An enhanced replacement for runit's sv"
url="https://github.com/ubergeek77/vsv"
license=("MIT")
source=("git+$url")
md5sums=('SKIP')
arch=("x86_64")
provides=("vsv")

package() {
    cd $pkgname
    usrdir="$pkgdir/usr"
    mkdir -p $usrdir
    export PREFIX=$usrdir
    make install
}
