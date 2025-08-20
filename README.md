# 💪 Rutini - Gym Workout Tracker

Una aplicación web simple y efectiva para hacer seguimiento de tus rutinas de gimnasio, series y repeticiones. Diseñada para ser usada directamente desde tu móvil o navegador durante el entrenamiento.

## ✨ Características

- **🔥 3 Días de Entrenamiento**: Lunes (Pecho/Hombros/Tríceps), Miércoles (Espalda/Bíceps), Jueves (Piernas/Glúteos)
- **📊 Seguimiento en Tiempo Real**: Contador de series y repeticiones para cada ejercicio
- **✅ Control de Progreso**: Marca ejercicios como completados y ve tu progreso general
- **💾 Persistencia de Datos**: Guarda automáticamente tu progreso en el navegador
- **📱 Diseño Responsive**: Optimizado para móviles y tablets
- **🎨 Interfaz Moderna**: Tema oscuro con gradientes naranjas llamativos
- **📋 Descripciones Detalladas**: Cada ejercicio incluye instrucciones de ejecución

## 🚀 Demo en Vivo

Puedes probar la aplicación directamente [aquí](https://tu-usuario.github.io/rutini) *(actualiza con tu URL)*

## 🛠️ Tecnologías

- **HTML5**: Estructura semántica
- **CSS3**: Estilos modernos con gradientes y animaciones
- **JavaScript Vanilla**: Funcionalidad sin dependencias externas
- **LocalStorage**: Persistencia de datos en el navegador

## 📦 Instalación

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/rutini.git
   cd rutini
   ```

2. **Abre el archivo**:
   - Simplemente abre `index.html` en tu navegador
   - O usa un servidor local como Live Server para desarrollo

3. **¡Listo para entrenar!** 🏋️‍♂️

## 🎯 Uso

### Selección de Día
1. Al abrir la app, selecciona tu día de entrenamiento:
   - **🔥 LUN**: Pecho, Hombros y Tríceps (9 ejercicios)
   - **💪 MIÉR**: Espalda, Bíceps y Posteriores (9 ejercicios)  
   - **🦵 JUEV**: Piernas y Glúteos (8 ejercicios)

### Durante el Entrenamiento
1. **Ver instrucciones**: Haz clic en el nombre del ejercicio (📋) para ver la descripción
2. **Contar series**: Usa los botones `+`/`-` para ajustar el número de series
3. **Contar repeticiones**: Usa los botones `+`/`-` para ajustar las repeticiones
4. **Marcar como completado**: Activa el checkbox ✅ cuando termines el ejercicio

### Seguimiento del Progreso
- **Barra de progreso**: Ve tu avance en tiempo real
- **Estadísticas**: Ejercicios totales, completados y restantes
- **Reset del día**: Botón para reiniciar todos los contadores del día actual

## 📱 Capturas de Pantalla

### Vista Principal
- Selector de días con botones llamativos
- Panel de estadísticas con progreso visual
- Tabla organizada por grupos musculares

### Vista de Ejercicio
- Contadores intuitivos con botones grandes
- Descripciones expandibles
- Indicadores visuales de ejercicios completados

## 🏋️‍♂️ Rutinas Incluidas

### 🔥 Lunes - Pecho, Hombros y Tríceps
- Aperturas con mancuerna (pecho superior)
- Press inclinado y plano
- Flexiones
- Press militar
- Elevaciones laterales
- Trícep en polea
- Trabajo de espalda complementario

### 💪 Miércoles - Espalda, Bíceps y Posteriores
- Jalón al pecho (diferentes agarres)
- Remo agarre ancho
- Pull over en polea
- Extensión de lumbar
- Curl Bayesiano y martillo
- Curl banco Scott
- Posteriores de hombro

### 🦵 Jueves - Piernas y Glúteos
- Extensión de cuádriceps
- Sentadilla Jaka y Smith
- Prensa inclinada
- Peso muerto rumano
- Hip thrust
- Extensión femoral
- Gemelo de pie

## ⚙️ Personalización

### Agregar Nuevos Ejercicios
Modifica el objeto `workoutData` en el JavaScript:

```javascript
const workoutData = {
  lunes: [
    {
      muscle: "NUEVO GRUPO MUSCULAR", 
      exercises: [
        {
          name: "Nuevo Ejercicio",
          muscle: "Músculo",
          description: "Descripción detallada del ejercicio"
        }
      ]
    }
  ]
};
```

### Cambiar Colores
Modifica las variables CSS para el tema de colores:

```css
/* Cambiar color principal */
background: linear-gradient(-90deg, #tu-color-1, #tu-color-2);
```

## 🤝 Contribución

¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar Rutini:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

### Ideas para Contribuir
- 🎵 Temporizador de descanso entre series
- 📊 Gráficos de progreso histórico
- 📤 Exportar datos a CSV
- 🔔 Notificaciones de recordatorio
- 🌙 Más temas de color
- 📅 Planificador semanal

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ve el archivo [LICENSE](LICENSE) para más detalles.

## 👤 Autor

**Tu Nombre** - [@tu-usuario](https://github.com/tu-usuario)

## 🙏 Reconocimientos

- Inspirado en la necesidad de tener un tracker simple y efectivo
- Diseño optimizado para uso durante el entrenamiento
- Gracias a la comunidad fitness por el feedback

---

**¿Te gusta Rutini?** ⭐ ¡Dale una estrella al repo y compártelo con tus compañeros de gym!

**¿Encontraste un bug?** 🐛 [Reporta un issue](https://github.com/tu-usuario/rutini/issues)

**¿Tienes una idea?** 💡 [Inicia una discusión](https://github.com/tu-usuario/rutini/discussions)