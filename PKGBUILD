# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-orenburg
pkgver=17
pkgrel=1
pkgdesc="Map of Orenburg for 2GIS, December 2012"
arch=('i686' 'x86_64')
url="http://orenburg.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.12.0.2')
source=("http://download.2gis.ru/arhives/2GISData_Orenburg-17.orig.zip")
md5sums=('67fcf5f828b478e6676906f3216298f7')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Orenburg.dgdat "${startdir}/pkg/opt/2gis/orenburg.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Orenburg.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Orenburg.dglf" || return 1
     
}

