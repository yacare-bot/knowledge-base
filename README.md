# 📚 Knowledge Base - yacaré.bot

Base de conocimiento generada automáticamente por yacaré.bot a partir de:
- Artículos Medium procesados
- Links compartidos vía Telegram
- Newsletters filtrados por relevancia
- Transcripciones de audio

## 🎯 Sistema de Scoring
Cada artículo es evaluado por 4 facetas de relevancia:
1. **🏢 Comit SRL** - Negocio, ERP, iDempiere, software empresarial
2. **🔧 Maker/IoT/Edge** - Raspberry Pi, ESP32, IoT, edge computing
3. **🤖 Data Science/AI** - Machine learning, transformers, AI
4. **💻 General Tech** - Desarrollo software, cloud, APIs

## 📊 Flujo de Procesamiento
1. **Entrada**: `/y` command en Telegram, email newsletters
2. **Scoring**: Evaluación automática por facetas (0-10 puntos)
3. **Filtrado**: Artículos con score > 0 procesados
4. **Organización**: Por carpeta según faceta principal
5. **Integración**: Trello para HITL, GitHub para persistencia

## 🔗 Integraciones
- **Trello**: Human in the Loop (HITL) y tracking
- **GitHub**: Esta base de conocimiento
- **S3**: Backup diario comprimido

## 🚀 Uso
Esta base sirve como insumo para:
- Desarrollo de código (referencias técnicas)
- Investigación (estado del arte)
- Decisiones de producto (tendencias tech)
- Aprendizaje continuo (tutoriales, best practices)

---
*Generado automáticamente por yacaré.bot - MVP V1.0*