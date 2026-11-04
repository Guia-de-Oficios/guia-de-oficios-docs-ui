# Guía de Oficios — Diseño UI Oficial (Stitch) y Documentación Maestra 🎨📄

Repositorio central de **Documentación de Producto, Arquitectura, Hoja de Ruta Paso a Paso y Diseño Gráfico Oficial (Stitch)** para **Guía de Oficios**.

> [!IMPORTANT]
> **Diseño Gráfico Oficial (15 Vistas de Stitch) y Cero Mocks:**  
> Todas las carpetas de pantallas aquí incluidas son el resultado exacto generado con **Stitch** (`code.html` + captura `screen.png` + `gu_a_de_oficios/DESIGN.md`) y representan la fuente de verdad visual de la aplicación. No se utilizan archivos HTML de demostración en el backend ni datos falsos en memoria.

---

## 🔗 Repositorios de Código de la Organización
* ⚙️ **Backend API (Golang + PostgreSQL/PostGIS en Docker):** [`Guia-de-Oficios/guia-de-oficios-backend`](https://github.com/Guia-de-Oficios/guia-de-oficios-backend)
* 📱 **Aplicación Android (Kotlin + Jetpack Compose):** [`Guia-de-Oficios/guia-de-oficios-android`](https://github.com/Guia-de-Oficios/guia-de-oficios-android)

---

## 📚 Índice de Documentación (`/docs`)

1. 🚀 **[`docs/06_radiografia_vistas_y_plan_paso_a_paso.md`](docs/06_radiografia_vistas_y_plan_paso_a_paso.md)**: **[DOCUMENTO PRINCIPAL DE SEGUIMIENTO]** Radiografía completa de las 15 vistas de Stitch, estado real del esqueleto base, guía local y plan de trabajo de **14 Pasos Secuenciales** con ramas Git independientes para Backend y Android.
2. 📄 **[`docs/01_especificacion_mvp_y_evolutivos.md`](docs/01_especificacion_mvp_y_evolutivos.md)**: Alcance funcional completo del MVP (Alfa/Beta), flujo de pantallas y tabla de endpoints de la API REST.
3. 🎨 **[`docs/02_guia_ux_ui_accesible.md`](docs/02_guia_ux_ui_accesible.md)**: Principios de diseño didáctico y accesible para adultos mayores.
4. 🤝 **[`docs/03_trabajo_colaborativo_y_onboarding.md`](docs/03_trabajo_colaborativo_y_onboarding.md)**: Guía de onboarding para el equipo, flujo de Git por pasos, cómo levantar Docker y cómo conectar el teléfono físico o emulador.
5. 💡 **[`docs/04_vision_negocio_y_estrategia.md`](docs/04_vision_negocio_y_estrategia.md)**: Estrategia de producto, cómo evitar la fuga de plataforma mediante solicitudes verificadas, y roadmap de monetización.
6. 📋 **[`docs/05_backlog_mvp_detallado.md`](docs/05_backlog_mvp_detallado.md)**: Backlog técnico completo del MVP (Épicas e Historias de Usuario, 100% real sin mocks).
7. 📥 **[`docs/05_backlog_jira_mvp.csv`](docs/05_backlog_jira_mvp.csv)**: Archivo CSV listo para importar directamente en **Jira**.

---

## 🖥️ Las 15 Vistas y Activos Oficiales de Stitch

| # | Pasos Asociados | Carpeta | Vista (HTML Intacto) | Captura de Referencia |
| :---: | :---: | :--- | :--- | :--- |
| **1** | **Paso 1** | `logo_provisional_gdo` | [`code.html`](logo_provisional_gdo/code.html) | [`screen.png`](logo_provisional_gdo/screen.png) |
| **2** | **Paso 1** | `bienvenida_y_selecci_n_de_rol` | [`code.html`](bienvenida_y_selecci_n_de_rol/code.html) | [`screen.png`](bienvenida_y_selecci_n_de_rol/screen.png) |
| **3** | **Paso 2** | `registro_google_o_manual` | [`code.html`](registro_google_o_manual/code.html) | [`screen.png`](registro_google_o_manual/screen.png) |
| **4** | **Paso 5** | `cliente_inicio_y_categor_as` | [`code.html`](cliente_inicio_y_categor_as/code.html) | [`screen.png`](cliente_inicio_y_categor_as/screen.png) |
| **5** | **Paso 6** | `cliente_resultados_de_profesionales` | [`code.html`](cliente_resultados_de_profesionales/code.html) | [`screen.png`](cliente_resultados_de_profesionales/screen.png) |
| **6** | **Paso 7** | `cliente_perfil_del_profesional_y_contacto` | [`code.html`](cliente_perfil_del_profesional_y_contacto/code.html) | [`screen.png`](cliente_perfil_del_profesional_y_contacto/screen.png) |
| **7** | **Paso 8** | `comunidad_top_profesionales_del_mes` | [`code.html`](comunidad_top_profesionales_del_mes/code.html) | [`screen.png`](comunidad_top_profesionales_del_mes/screen.png) |
| **8** | **Paso 1** | `gu_a_de_oficios_servicios_y_oficios_vecinales` | [`code.html`](gu_a_de_oficios_servicios_y_oficios_vecinales/code.html) | [`screen.png`](gu_a_de_oficios_servicios_y_oficios_vecinales/screen.png) |
| **9** | **Paso 9** | `cliente_solicitud_guiada_a_roberto` | [`code.html`](cliente_solicitud_guiada_a_roberto/code.html) | [`screen.png`](cliente_solicitud_guiada_a_roberto/screen.png) |
| **10** | **Paso 10** | `cliente_elegir_contacto_y_confirmaci_n` | [`code.html`](cliente_elegir_contacto_y_confirmaci_n/code.html) | [`screen.png`](cliente_elegir_contacto_y_confirmaci_n/screen.png) |
| **11** | **Paso 11** | `cliente_profesional_en_camino_y_mapa_en_vivo` | [`code.html`](cliente_profesional_en_camino_y_mapa_en_vivo/code.html) | [`screen.png`](cliente_profesional_en_camino_y_mapa_en_vivo/screen.png) |
| **12** | **Paso 12** | `cliente_trabajo_terminado_y_calificaci_n` | [`code.html`](cliente_trabajo_terminado_y_calificaci_n/code.html) | [`screen.png`](cliente_trabajo_terminado_y_calificaci_n/screen.png) |
| **13** | **Paso 13** | `profesional_registro_y_verificaci_n_dni` | [`code.html`](profesional_registro_y_verificaci_n_dni/code.html) | [`screen.png`](profesional_registro_y_verificaci_n_dni/screen.png) |
| **14** | **Paso 14** | `profesional_panel_y_solicitudes_recibidas` | [`code.html`](profesional_panel_y_solicitudes_recibidas/code.html) | [`screen.png`](profesional_panel_y_solicitudes_recibidas/screen.png) |
| **15** | **Paso 14** | `profesional_aceptar_trabajo_e_iniciar_viaje` | [`code.html`](profesional_aceptar_trabajo_e_iniciar_viaje/code.html) | [`screen.png`](profesional_aceptar_trabajo_e_iniciar_viaje/screen.png) |
| **DS** | **Transversal** | `gu_a_de_oficios` | — | [`DESIGN.md`](gu_a_de_oficios/DESIGN.md) |
