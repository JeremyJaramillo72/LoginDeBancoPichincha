# Clon de la Interfaz de Inicio - Banco Pichincha 📱

Este repositorio contiene el desarrollo práctico de la replicación de la interfaz de inicio de sesión de la aplicación móvil del Banco Pichincha. El proyecto ha sido desarrollado de forma nativa para la plataforma Android utilizando **XML (Extended Layouts)** para el diseño de la interfaz y **Kotlin** para la lógica del sistema.

## 🚀 Características del Diseño
- **Estructura Responsiva:** Uso de `ConstraintLayout` como contenedor de nivel superior para asegurar una perfecta adaptabilidad y distribución en diferentes tamaños y resoluciones de pantallas.
- **Distribución Proporcional:** Implementación de `LinearLayout` horizontales y verticales manejados mediante pesos (`android:layout_weight="1"`), lo que permite que las secciones de botones se dividan el espacio de la pantalla de manera simétrica y exacta.
- **Componentes Material Design:** Uso de tarjetas `CardView` configuradas con bordes redondeados (`app:cardCornerRadius="16dp"`), elevación para profundidad visual (`app:cardElevation="4dp"`) y optimización de renderizado de sombras evitando el recorte forzado de bordes a través de `android:clipChildren="false"`.
- **Estilización Dinámica por Código:** Aplicación de la paleta de colores corporativa mediante la propiedad `android:tint="#192976"` directamente en las etiquetas del XML, modificando de forma limpia vectores gráficos (SVG).

## 📂 Arquitectura del Código Clave
El diseño completo de la actividad, componentes, jerarquía de vistas y restricciones se encuentra desarrollado en la siguiente ruta:
* `app/src/main/res/layout/activity_main.xml`

## 📸 Evidencia del Diseño Corriendo (App Preview)
<img width="713" height="1018" alt="Captura de pantalla 2026-05-29 164946" src="https://github.com/user-attachments/assets/8ed22c47-ae90-42fa-b354-2efcc06da630" />
