This is used to support X-Plane SDK in VCPKG.

Usage:

1. Create new x-plane folder in vcpkg/ports
2. Put CONTROL and portfile.cmake inside
3. Use vcpkg install x-plane to install the library
4. In the project use `#inlude <x-plane/..." to include the header.