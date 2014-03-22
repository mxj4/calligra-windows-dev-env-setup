Build Krita & Karbon x64

cd c:\dev\desktop64\p\vs11
c:\dev\desktop64\p\vs11>cmake -DCMAKE_INSTALL_PREFIX=c:\dev\desktop64\i -DCMAKE_BUILD_TYPE=RelWithDebInfo -DKDE4_BUILD_TESTS=OFF -DPRODUCTSET=CREATIVE -DPACKAGE
RS_BUILD=ON -DUSE_BREAKPAD=ON \\VBOXSVR\vm-share\calligra\ -G "Visual Studio 11 Win64"
cmake --build . --target INSTALL --config RelWithDebInfo