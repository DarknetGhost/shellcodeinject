# shellcodeinyect
Inyector de shellcode Sencillo en Golang

# Como funciona?
El Script hace uso de las funciones [VirtualAlloc](https://learn.microsoft.com/es-es/windows/win32/api/memoryapi/nf-memoryapi-virtualalloc), [WriteProcessMemory](https://learn.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-writeprocessmemory), [CreateThread](https://learn.microsoft.com/es-es/windows/win32/api/processthreadsapi/nf-processthreadsapi-createthread) y [WaitForSingleObject](https://learn.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-waitforsingleobject) para poder inyectar la shellcode de manera sencilla (Pero extremadamente llamativo por un antivirus)

La shellcode que estoy usando en el codigo simplemente ejecuta una calculadora -> https://github.com/C-Sto/BananaPhone/blob/master/example/calcshellcode/main.go

Este metodo se usa mucho a la hora del desarrollo de malware pero con mas tecnicas para el intento de evasion de sistemas de seguridad (Antirivus y EDRs)

Telegram: @DarknetGhost2
Grupo: https://t.me/+IBDl_5O_qQtjNjVh 
Canal: https://t.me/Kernel32_Resources


