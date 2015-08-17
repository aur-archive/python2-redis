# Maintainer: Karol 'Kenji Takahashi' Woźniak <kenji.sx>
# Contributor: Thomas S Hatch <thatch45@gmail.com>

pkgname=python2-redis
_basename=redis
pkgver=2.9.1
pkgrel=2
pkgdesc="The Python interface to the Redis key-value store."
arch=(any)
url="http://github.com/andymccurdy/redis-py"
license=('custom')
depends=('python2')
source=("https://pypi.python.org/packages/source/r/${_basename}/${_basename}-${pkgver}.tar.gz")
md5sums=('1da8ff78be75d7acf5d4684e77fc3606')

package() {
    cd ${srcdir}/${_basename}-${pkgver}
    python2 setup.py install --root=${pkgdir}/ --optimize=1
}

# vim:set ts=4 sw=4 et:
