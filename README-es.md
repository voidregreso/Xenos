Xenos
=====

[English](README.md) *Español*

Injector de DLL para Windows. Basado en la librería Blackbone - https://github.com/DarthTon/Blackbone

## Características ##

- Soporta procesos y módulos x86 y x64
- Función de inyección en modo kernel (se requiere driver)
- Mapeo manual de drivers del kernel (se requiere driver)
- Inyección de imágenes gestionadas puras sin DLL intermedia
- Inyección entre sesiones y escritorios cruzados en Windows 7
- Inyección en procesos nativos (aquellos que sólo tienen cargado ntdll)
- Llamada a una rutina de inicialización personalizada después de la inyección
- Desvinculación del módulo tras la inyección
- Inyección mediante secuestro de hilos
- Inyección de imágenes x64 en procesos WOW64
- Mapeo manual de imágenes
- Perfiles de inyección

Características del mapeo manual:
- Reubicaciones, importaciones, importaciones retrasadas, importaciones vinculadas
- Ocultación de la memoria de imagen asignada (se requiere driver)
- TLS estático y callbacks TLS
- Cookie de seguridad
- Manifiestos de imagen y SxS
- Hacer el módulo visible para GetModuleHandle, GetProcAddress, etc.
- Soporte de excepciones en memoria privada bajo DEP
- Se soportan imágenes C++/CLI (utiliza 'Añadir referencia de cargador' en este caso)

Sistemas operativos soportados: Win7 - Win11 (solo plataformas x86/x64)

## Licencia ##
Xenos está licenciado bajo la Licencia MIT. Las dependencias están bajo sus respectivas licencias.
