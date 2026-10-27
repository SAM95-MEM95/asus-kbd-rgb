pkgname=asus-kbd-rgb
pkgver=0.1.0
pkgrel=1
pkgdesc="Проста GUI-утиліта для RGB-підсвітки клавіатури ASUS"
arch=('any')
depends=('bash' 'kdialog' 'polkit')
optdepends=('hidapitester: розбудження контролера підсвітки')
license=('MIT')
source=()
sha256sums=()

package() {
    install -Dm755 "$srcdir/src/kbd-color" \
        "$pkgdir/usr/bin/kbd-color"
    install -Dm755 "$srcdir/src/apply-color" \
        "$pkgdir/usr/lib/asus-kbd-rgb/apply-color"
    install -Dm644 "$srcdir/src/kbd-color.desktop" \
        "$pkgdir/usr/share/applications/kbd-color.desktop"
}
