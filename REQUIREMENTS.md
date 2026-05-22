# Sistema Vitta

## 1. Autenticación de usuarios

- El usuario puede registrarse con email y contraseña.
- El usuario puede iniciar sesión.
- El usuario puede cerrar sesión.

### Reglas 

- Cada usuario solo puede acceder a sus propios datos.
- Las contraseñas deben almacenarse de forma segura (gestionado por Supabase).

## 2. check-in diario del usuario

### Funcionalidad 

- El usuario puede registrar cómo se siente cada día interactuando con iconos descriptivos.
- El sistema guarda el texto asociado a la fecha y usuario.
- Check-in diario.

## 3. Análisis con IA

### Funcionalidad 
- El sistema envía el texto del check-in a la API de IA (Groq).
- La IA devuelve analiza al usuario:
- Estado emocional detectado.
- Resumen del contenido.
- Recomendación breve.

## 4. Generación de prioridades

### Funcionalidad

- A partir del análisis de IA, el sistema genera 3 prioridades diarias.

### Reglas
- Las prioridades deben ser simples, accionables y realistas.


## 5. Historial de entradas

### Funcionalidad
- El usuario puede ver sus check-ins anteriores.

### Cada entrada incluye:

- Altura (solo informativa, no cambia).
- Nivel de actividad física o estado general.
- Análisis del IMC Y peso generado por IA.
- Rutina recomendada del día.
- Recomendaciones de alimentación o recetas sugeridas.


## 6. Requisitos de Funcionales.

- La respuesta de IA debe ser inferior a 5 segundos.
- La información del usuario debe estar protegida.
- La interfaz debe ser simple, clara y fácil de usar
