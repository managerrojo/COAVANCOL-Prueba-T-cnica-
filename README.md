# COAVANCOL-Prueba-T-cnica-


# COAVANCOL – Prueba Técnica Fullstack Junior

Repositorio destinado a la prueba técnica para candidatos al cargo de **Desarrollador Fullstack Junior (React + Firebase)** en COAVANCOL.

Este repositorio contiene un archivo `asociados.json` con 50 registros ficticios que los aplicantes pueden consumir como fuente de datos durante la prueba.

---

##  Objetivo del Repositorio
Proveer un endpoint público y accesible para que el candidato pueda consumir una lista de asociados sin necesidad de configurar Firebase o una API completa.

Este JSON simula la colección `/asociados` utilizada en el proyecto real.



El candidato deberá:

Consumir este JSON mediante fetch o axios.

Mostrar los datos en una tabla.

Implementar un filtro por estado_pipeline.

Manejar estados de carga y error.

Ejemplo de consumo:

const res = await fetch("https://raw.githubusercontent.com/<usuario>/<repositorio>/main/asociados.json");
const data = await res.json();

