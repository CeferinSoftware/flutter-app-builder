# 🚀 Flutter App Builder

Repositorio para la compilación automática de aplicaciones Flutter con CircleCI.

## 📋 Descripción

Este repositorio es utilizado por el plugin **Web to Flutter App** para compilar automáticamente aplicaciones móviles a partir de sitios web WordPress.

## 🔧 Características

- ✅ **Compilación Android** con Android SDK 35
- ✅ **Compilación iOS** con Xcode 15.2
- ✅ **Firma automática** con keystores del cliente
- ✅ **Soporte AAB** para Google Play Store
- ✅ **CI/CD con CircleCI** (6,000 minutos gratuitos/mes)

## 🏗️ Workflow de Compilación

1. **Plugin genera código Flutter** basado en el sitio web
2. **Push automático** a rama única con timestamp
3. **CircleCI detecta cambios** y ejecuta pipeline
4. **Compilación paralela** Android e iOS
5. **Artefactos disponibles** para descarga del cliente

## 🔐 Firma de Aplicaciones

### Android
- Keystore único por cliente
- Certificados de 25 años de validez
- Soporte APK y AAB firmados

### iOS
- Certificados P12 del cliente
- Provisioning Profiles personalizados
- IPA firmado para App Store

## 📊 Estadísticas

- **Flutter Version**: 3.29.2
- **Android SDK Target**: 35 (requerido por Google Play)
- **Gradle Version**: 8.6
- **Xcode Version**: 15.2

## 🚀 Uso

Este repositorio es gestionado automáticamente por el plugin. No requiere intervención manual.

---

*Generado automáticamente por Web to Flutter App Plugin* 