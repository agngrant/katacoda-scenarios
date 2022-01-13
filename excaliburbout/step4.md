Then compile BOUT++ in the container:

cd BOUT-dev

cmake . -B build -DCMAKE_CXX_FLAGS=-std=c++14 -DBOUT_DOWNLOAD_NETCDF_CXX4=ON

cmake --build build

To make the examples:
cmake . --build build -DBOUT_BUILD_EXAMPLES=on