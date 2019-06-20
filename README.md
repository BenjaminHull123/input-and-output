# input-and-output
#output with mutiple colunms that as required 
import keyword,datetime
today=datetime.datetime.now()
foolist = ['exiv2-devel', 'mingw-libs', 'tcltk-demos', 'fcgi', 'netcdf', 
    'pdcurses-devel',     'msvcrt', 'gdal-grass', 'iconv', 'qgis-devel', 
    'qgis1.1', 'php_mapscript']
for a,b,c,d in zip(foolist[::4],foolist[1::4],foolist[2::4],foolist[3::4]):
     print ('{:<30}{:<30}{:<30}{:<}'.format(a,b,c,d))
print(today)
