# Maintainer: Esconine <exoescon1ne@gmail.com>
pkgname=pineconemc-bin
pkgver=1.0.0
pkgrel=1
pkgdesc='The fork of Prism Launcher with integrated support for Ely.by accounts (Earlier ElyPrismLauncher)'
arch=('x86_64')
url='https://elyprismlauncher.github.io/'
license=('GPL-3.0-only')
depends=('glibc' 'zlib' 'hicolor-icon-theme')

source=(
    "PineconeMC-Linux-x86_64.AppImage::https://github.com/ElyPrismLauncher/Launcher/releases/download/11.0.3/PineconeMC-Linux-x86_64.AppImage"
    "PineconeMC.png"
    "PineconeMC.desktop"
)

sha256sums=('df6958fba93c97aa6cb8150d3d3a828ace0d3ba2eadfce303565d1b903d04a20'
            'd2f01916b2b5d052442313031709d94972ddf35f4b6a257ac20d810fc840bdf4'
            'a4d08a31439afb47942385abcb401e98b656bc0b71c2eeb6ae8e1dd0abe68c3b')

package() {
    install -d "${pkgdir}/usr/bin"
    install -m755 "${srcdir}/PineconeMC-Linux-x86_64.AppImage" "${pkgdir}/usr/bin/PineconeMC.AppImage"

    install -d "${pkgdir}/usr/share/pixmaps"
    install -m644 "${srcdir}/PineconeMC.png" "${pkgdir}/usr/share/pixmaps/pineconemc-desktop.png"

    install -d "${pkgdir}/usr/share/applications"
    install -m644 "${srcdir}/PineconeMC.desktop" "${pkgdir}/usr/share/applications/PineconeMC.desktop"
}
