# 🧠 Smart Study Scheduler (Planificador de Estudio Inteligente)

Un sistema web PWA/Offline-First para estudiantes que calcula automáticamente la prioridad de estudio utilizando un algoritmo de ponderación matemática según la urgencia, peso del examen y coeficiente de dificultad.

## 🚀 Características Clave
- **Algoritmo Propietario de Priorización:** Calcula un *Urgency Score* combinando días restantes, porcentaje de evaluación y dificultad.
- **Entrada Rápida e Inteligente (Smart Text Parser):** Procesa notas informales para registrar tareas en segundos.
- **Arquitectura Offline-First (PWA):** Funciona sin conexión a Internet guardando el estado en LocalStorage/IndexedDB.
- **Diseño UI/UX Profesional:** Construido con React, Tailwind CSS e iconos vectoriales.

## 📐 Fórmula del Algoritmo
```math
Score = (Peso % * Dificultad * 100) / (Días Restantes ^ 1.2)
```

## 🛠️ Tecnologías Utilizadas
- **TypeScript & React** (Arquitectura basada en componentes)
- **Tailwind CSS** (Estilos reactivos y tematización oscura)
- **Service Workers / PWA** (Soporte Offline nativo en dispositivos móviles)
