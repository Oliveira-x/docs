// decrease failed login attempts by Bowie 01/2020

Offset: ``004045F4``

Changes:
```asm
cmp dword ptr [esi+00000130],03 //login attempts
```

Originalcode:
```asm
cmp dword ptr [esi+00000130],0A
```