# VB6Nano
To make your own copy of VB6 portable, simply enter your license into the registry with a .reg file.  
Run VB6.exe as administrator the first time.

Learning edition license:
>Windows Registry Editor Version 5.00
>
>[-HKEY_CLASSES_ROOT\Licenses\74872840-703A-11d1-A3AF-00A0C90F26FA]
>
>[-HKEY_CLASSES_ROOT\Licenses\74872841-703A-11d1-A3AF-00A0C90F26FA]


Professional license:
>Windows Registry Editor Version 5.00
>
>[HKEY_CLASSES_ROOT\Licenses\74872840-703A-11d1-A3AF-00A0C90F26FA]
>
>@="mninuglgknogtgjnthmnggjgsmrmgniglish"


Enterprise license:
>Windows Registry Editor Version 5.00
>
>[HKEY_CLASSES_ROOT\Licenses\74872840-703A-11d1-A3AF-00A0C90F26FA]
>
>@="mninuglgknogtgjnthmnggjgsmrmgniglish"
>
>[HKEY_CLASSES_ROOT\Licenses\74872841-703A-11d1-A3AF-00A0C90F26FA]
>
@="klglsejeilmereglrfkleeheqkpkelgejgqf"

Minimum files needed for portability:

>VB6.OLB
>VB6EXT.OLB
>DAO350.DLL
>MRT7ENU.DLL
>MSO97RT.DLL
>MSPDB60.DLL
>VB6IDE.DLL
>VBA6.DLL
>C2.EXE
>LINK.EXE
>VB6.EXE
>VBAEXE6.LIB
