---
name: actualizar-cv
description: Actualiza un caso privado de currículum conservando hechos, originales y decisiones aprobadas.
---

1. Localiza generador_cv/cli.py y lee AGENTS.md, README.md, ai_workspace/contexto/asistente_cv.md y las guías de flujo, estilo y datos. En la ruta privada indicada, lee estado.json, PREGUNTAS_Y_DECISIONES.md, config.json y los dos JSON de contenido. No abras otros casos personales sin autorización.
2. Pregunta solo lo nuevo, máximo cinco preguntas numeradas por mensaje, de sí/no o elegir: qué caso; conservar objetivo o cambiarlo; hechos que se añaden, corrigen o retiran; páginas actuales o 1–4; foto y privacidad actuales o cambios. Si falta una fecha o dato, pregunta y conserva la duda; no lo inventes.
3. Conserva el original y una copia privada del caso antes de cambiarlo. Edita únicamente los hechos y ajustes aprobados, en cv_es.json, cv_en.json y la configuración del caso. Conserva lo no solicitado y la equivalencia entre idiomas. Consulta ESTILO.md para los campos visuales. No modifiques el motor ni la plantilla para un cambio de contenido.
4. Ejecuta confidencialidad --caso <caso>. Solicita nueva validación de hechos, enlaces, omisiones y traducción; una aprobación antigua no autoriza el contenido cambiado. No resumas para encajar sin permiso y no compartas datos internos de empresas o terceros sin autorización.
5. Con aprobación expresa, usa aprobar contenido, aprobar traduccion, propuestas, elegir minimalista_onda y generar con --caso <caso>. Comprueba todas las páginas de ambos idiomas, Word editable y PDF. Solo usa cerrar con --revisor y --confirmo-inspeccion-visual tras una inspección real y conformidad del usuario.
6. Resume los cambios y las rutas finales; indica lo pendiente. Nunca envíes ni publiques, instales dependencias ni cambies Git o cuentas sin autorización. Los casos, fotos y documentos personales siguen fuera del repositorio público.
