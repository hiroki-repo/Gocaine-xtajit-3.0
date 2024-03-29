# Gocaine-xtajit-3.0
About
is an emulator for the Wine to run x86 code fast and like Gocaine-xtajit 1.x and 2.x which based on box64 and hangover project!

# Requirement to make use of the softwore
Wine 8.0 or more

# How to use it
1, Copy and/or implement the Wine i386 Wow64 modules for i386 apps compatibility to SysWOW64 folder in Windows folder,  also if lacked SysWOW64 folder in Windows folder on the Wine for AArch64, you have to make the folder or you may need to build the Wine library for i386(IA-32, 32Bit x86) and 'Wow64.dll' and 'Wow64win.dll' for AArch64 in building wine.

2, Copy a dll in this repository named xtajit.dll to '/usr/local/lib/wine/aarch64-windows' on AArch64 wine.

3, Open the x86(i386 or IA-32 ABI) apps on the wine which installed Gocaine-xtajit.

4, You'll see the 32bit x86 apps works on Wine for AArch64!

# Module CODENAME
Iyasaka (弥栄)

