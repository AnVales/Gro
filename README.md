# 🦠🌱 Simulación de interacción bacteriana con Gro

Bienvenido a un viaje microscópico donde exploramos cómo dos especies de bacterias se comunican y compiten por recursos. 🧬✨

## 🟢 Anfitrión vs 🔵 Parásito
Bacteria	Acción	Emoji
Anfitrión	Produce exoenzimas y señales químicas (ahl_anfitrion)	🟢💧📡
	Detecta competidores y ajusta crecimiento	👀📈
	Produce GFP si hay parásitos cerca	💡
Parásito	Detecta señales del anfitrión para obtener nutrientes	🔵👃💧
	Ajusta su crecimiento según recursos	📊
	Muere si no hay suficiente energía	⚰️
⚙️ Cómo funciona la simulación

## Inicio de la historia:
Comenzamos con dos células:

🟢 Una anfitriona en [x:=50, θ:=π/2]

🔵 Un parásito en [x:=-50]

Comunicación química:

🟢 y 🔵 emiten y absorben señales (ahl_anfitrion y ahl_parasito).

Esto permite detectar aliados y enemigos en el entorno. 📡

Producción de GFP:

🟢 aumenta GFP si hay muchos parásitos cerca 💡

🔵 gana o pierde GFP según señales del anfitrión 📉📈

Crecimiento y supervivencia:

🟢 reduce su tasa de crecimiento si GFP > 2 🐢

Muere si GFP > 10 ⚰️

🔵 aumenta tasa de crecimiento si GFP > 7 ⚡

Muere si GFP < 1 ⚰️

Registro de datos:

Cada célula puede guardar sus datos en un archivo CSV 📊📝

Permite analizar la dinámica de crecimiento y comunicación a lo largo del tiempo ⏳

## 🌟 Objetivos de la simulación

Explorar cooperación y competencia entre bacterias 🤝⚔️

Estudiar cómo señales químicas afectan crecimiento y supervivencia 💧🧪

Ajustar parámetros (k, delta, tasas de crecimiento) y simular distintos escenarios 🛠️🎯

## 🏃‍♂️ Cómo correr la simulación

Ejecutar relation_two_bacterias.gro en Gro ▶️

Observar la interacción dinámica entre 🟢 y 🔵

Modificar parámetros y crear nuevas historias bacterianas 📝✨

Ejecutar relation_two_bacterias.gro en Gro ▶️

Observar la interacción dinámica entre 🟢 y 🔵

Modificar parámetros y crear nuevas historias bacterianas 📝✨
