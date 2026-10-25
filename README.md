# Proyecto Final: Ecosistema de Automatización IA

**Materia:** Automatización con IA
**Autor:** Santiago Zanoff

## Descripción

Flujo de automatización de extremo a extremo, construido en n8n, que atiende de forma automática a cada persona que completa un formulario de Google de una marca del sector musical. Por cada respuesta, el sistema registra el contacto en Notion, decide qué correo le corresponde (solo enlace de descarga o enlace con suscripción al newsletter), utiliza OpenAI para redactar un mensaje personalizado, lo guarda como borrador en Gmail y espera la aprobación de una persona antes de enviarlo.

**Principios de diseño:** la IA redacta pero no envía, ningún correo sale sin validación humana y cada etapa del proceso queda reflejada en tiempo real en la base de datos.

**Tecnologías:** Google Sheets · n8n · Notion · OpenAI (GPT-5.4-mini) · Gmail
