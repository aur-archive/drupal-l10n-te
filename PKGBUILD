# Maintainer: James An <james@jamesan.ca>

pkgname=drupal-l10n-te
_language=te
pkgver=7.31
pkgrel=1
pkgdesc="Drupal core translation: Telugu"
arch=('any')
url="http://localize.drupal.org/translate/downloads"
_watch="http://localize.drupal.org/translate/downloads"
license=('nonfree')
depends=('drupal')
source=("http://ftp.drupal.org/files/translations/7.x/drupal/drupal-7.31.te.po")
md5sums=('f1cde3e56e730a338489f8c5bbca63aa')
package () {
    install -Dm644 "${srcdir}/drupal-${pkgver}.${_language}.po" "${pkgdir}/usr/share/webapps/drupal/profiles/standard/translations/drupal-${pkgver}.${_language}.po"
}
