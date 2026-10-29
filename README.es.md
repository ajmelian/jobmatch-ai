# JobMatch AI

**Evaluación de candidaturas y optimización de CV basada en evidencias mediante IA generativa.**

JobMatch AI es una metodología propia de **ingeniería de prompts** que estructura el análisis de ofertas tecnológicas frente a un currículum maestro. Diferencia el encaje profesional de la compatibilidad documental ATS estimada, controla la procedencia de las afirmaciones y exige supervisión humana antes de preparar un CV adaptado.

**Autor:** Aythami Melián Perdomo · [GitHub](https://github.com/ajmelian) · [LinkedIn](https://www.linkedin.com/in/aythami-melian/)

[English README](README.md) · [Manual de uso](docs/USER_GUIDE.md) · [Licencia](LICENSE.md)

## Funcionalidades definidas

- Seis perspectivas de revisión simuladas por un mismo asistente; **no** se afirma que existan seis agentes independientes.
- Descomposición de requisitos obligatorios, deseables, implícitos y excluyentes.
- Registro de evidencias, procedencia, incertidumbres y veto factual.
- Compatibilidad profesional ponderada, compatibilidad ATS documental estimada y viabilidad de candidatura como indicadores independientes.
- Matriz de trazabilidad requisito-evidencia y revisión crítica técnica y de RR. HH.
- Enriquecimiento del currículum maestro únicamente tras confirmación y guardado verificable.
- Autorización separada antes de generar una versión adaptada.
- Puertas de auditoría factual, editorial, técnica y documental para el archivo final.

## Estado del proyecto

**Versión de la especificación: 1.2.0, de 28/10/2026.** El proyecto documenta un flujo basado en instrucciones para LLM. **No representa** una aplicación empresarial desplegada, una integración probada con un ATS concreto ni una validación estadística de probabilidades de contratación.

El prompt maestro original en español se publicará en `prompts/` sin alterar su contenido. Una edición genérica para terceros podrá incorporarse como versión 1.3.0.

## Cómo utilizarlo

1. Carga el prompt maestro desde `prompts/`, cuando esté publicado.
2. Proporciona el CV maestro en Markdown y el texto íntegro o URL de una oferta.
3. Resuelve las preguntas relevantes sobre competencias y fuentes.
4. Revisa el informe y verifica toda afirmación sobre experiencia.
5. Autoriza expresamente cualquier adaptación y comprueba el CV resultante.

**Privacidad:** no subas currículums reales, datos de contacto privados ni documentación empresarial confidencial a repositorios públicos. Antes de utilizar modelos externos, revisa sus condiciones de tratamiento de datos.

## Licencia

El prompt original y la documentación propia se publican bajo **Creative Commons Atribución–NoComercial 4.0 Internacional (CC BY-NC 4.0)**. Los usos comerciales de estos materiales requieren autorización adicional. Consulta [LICENSE.md](LICENSE.md) y [COMMERCIAL-LICENSING.md](COMMERCIAL-LICENSING.md).

Copyright © 2026 Aythami Melián Perdomo.
