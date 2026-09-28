# DTU Avatar Studio

Estudio de generación visual independiente de **Digital Todo en Uno LLC**.

**Estado: desarrollo. NO apto para producción.** El repositorio aún no contiene todo el código fuente: el paquete de desarrollo se está preparando y validando antes de publicarlo. No configurar llaves de Higgsfield ni habilitar generación aquí.

## Progreso verificable

- Supabase DTU Portal Backend: tablas `dtu_avatar_*` con RLS.
- Funciones antiguas de gasto: acceso directo de `anon` y `authenticated` revocado.
- Funciones nuevas `dtu_avatar_service_*`: ejecución permitida únicamente a `service_role`.
- Código de la aplicación: MVP desarrollado de forma independiente; generación deshabilitada por defecto.
- Pendiente: subir código íntegro, instalar dependencias, verificar TypeScript/lint/build, validar conciliación, configurar credenciales por servidor y desplegar.

**No se ha publicado una app ni se han ejecutado generaciones cobrables.**

Las dependencias de terceros tienen sus respectivas licencias; no se incorporaron fuentes ni código del proyecto tomado como inspiración conceptual.

## Topics y enrutamiento documental

Los **Topics configurados en GitHub son metadatos operativos del ecosistema** y deben utilizarse para localizar repositorios relacionados y decidir dónde documentar información nueva.

Antes de guardar información que cruce proyectos, consultar el mapa maestro interno:

`digitaltodoenuno/digital-todo-en-uno/docs/00-ecosistema-repositorios.md`

Regla: **responsabilidad canónica primero, Topics como señal de confirmación**. Si varios repositorios comparten un Topic, no duplicar contenido; guardar el detalle en la fuente más específica y enlazarlo cuando otra área lo necesite.
