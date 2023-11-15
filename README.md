# installing-mingw-w64-x86_64

- Grab the latest msys2 installer here: https://github.com/msys2/msys2-installer
- install it, sending it onto C:\msys64 is fine
- after its done open the shell at C:\msys64\ucrt64.exe
- then run `pacman -S mingw-w64-x86_64-gcc`
- if you need make: `pacman -S make`
- after you're done, open sys prop `C:\Windows\System32\SystemPropertiesAdvanced.exe` and add the following paths to your environment
- `C:\msys64\mingw64\bin`
- `C:\msys64\`
