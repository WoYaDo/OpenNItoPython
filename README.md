OpenNi installers : http://openni.ru/openni-sdk/openni-sdk-history-2/index.html

Boost libraries : http://www.boost.org/users/history/version_1_43_0.html
 1. Verander libs/python/build/Jamfile.v2 door die in de git
 2. bootstrap.bat
 3. ./bjam python
 
PyOPenNi builde:

   1. md PyOpenNI-build
   2. cd PyOpenNI-build
   3. cmake -G "Visual Studio 10" ..\PyOpenNI
   4. Da geeft errors, verander CMakeCache.txt dor die van de git
   5. Open de PYOpenNI.sln file me Visual Studio
   6. Build project
   7. Zou normaal gezien de openni.dll moete make
