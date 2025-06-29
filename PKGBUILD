# Maintainer: Hanashiko <hlichisper@gmail.com>
pkgname=sshtool
pkgver=0.1.0
pkgrel=1
pkgdesc="Interactive SSH session manager with GPG-encrypted config support"
arch=('any')
utl="https://github.com/hanashiko/sshtool.git"
license=('MIT')
depends=('python' 'gnupg' 'fzf')
optdepends=(
    'sshpass: for password-based SSH'
    'mosh: for mosh support'
    'tmate: for tmate support'
)
source=("sshtool" "LICENSE" "README.md")
sha256sums=('SKIP' 
            'SKIP' 
            'SKIP')

package() {
    install -Dm755 "$srcdir/sshtool" "$pkgdir/usr/bin/sshtool"
}