# Sekiury Legal — Formulario de Entrevista Inicial

> **Protección que evoluciona contigo**

Herramienta web para recolección de información en entrevistas iniciales de casos de derecho de familia colombiano.

## ¿Qué es esto?

Un formulario interactivo que el asesor diligencia en tiempo real mientras entrevista al cliente. Al terminar, genera automáticamente un prompt estructurado listo para el **Agente IA SEKIURY** que produce el diagnóstico jurídico completo.

## Casos que cubre

- Divorcio y separación de bienes
- Liquidación de sociedad conyugal
- Fijación y demanda de alimentos
- Custodia y regulación de visitas
- Sucesiones con sociedad conyugal vigente
- Casos mixtos (herencia + alimentos + bienes)

## Secciones del formulario

| # | Sección | Qué recolecta |
|---|---------|---------------|
| A | Vínculo y estado civil | Tipo de relación jurídica |
| B | Patrimonio y bienes | Activos sociales y propios |
| C | Deudas y pasivos | Pasivos de la sociedad conyugal |
| D | Hijos y alimentos | Obligación alimentaria y custodia |
| E | Ingresos y capacidad económica | Base para alimentos y liquidación |
| F | Situación procesal | Estado del conflicto en curso |
| G | Documentos disponibles | Inventario de prueba documental |

## Cómo usar

1. Abrir la URL del formulario en cualquier navegador
2. Diligenciar los datos del cliente en la parte superior
3. Ir sección por sección durante la entrevista
4. Escribir las respuestas del cliente en cada campo
5. Presionar **"Guardar"** para conservar la información en el navegador
6. Al terminar, presionar **"⚡ Generar Diagnóstico SEKIURY"**
7. Pegar el texto copiado en el chat del Agente IA SEKIURY

## Flujo completo

```
Entrevista con cliente
        ↓
Diligenciar formulario en vivo
        ↓
Clic en "Generar Diagnóstico SEKIURY"
        ↓
Pegar en el chat de Claude
        ↓
Diagnóstico jurídico completo en segundos
```

## Funciones

- **Guardado automático** en el navegador (localStorage) — los datos persisten si cierras y vuelves a abrir
- **Barra de progreso** en tiempo real
- **Marcadores de tipo** por pregunta: Clave / Prueba / Alimentos / Riesgo
- **Botón N/A** para preguntas que no aplican al caso
- **Notas por sección** para observaciones del asesor
- **Exportar .txt** con el reporte completo
- **Nueva entrevista** para limpiar y empezar un caso nuevo

## Publicar en GitHub Pages

1. Crear un repositorio en GitHub (ej: `sekiury-intake`)
2. Subir el archivo `index.html` a la rama `main`
3. Ir a **Settings → Pages → Branch: main → Save**
4. En 2-3 minutos la URL estará disponible:
   `https://TU_USUARIO.github.io/sekiury-intake`

## Tecnología

- HTML5 + CSS3 + JavaScript puro
- Sin dependencias externas (todo en un solo archivo)
- Funciona offline una vez cargado
- Compatible con Chrome, Edge, Safari, Firefox
- Responsive — funciona en celular y tablet

---

**Sekiury Legal** — *Protección que evoluciona contigo*
