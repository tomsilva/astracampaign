# Internacionalización (i18n) del Frontend - Astra Campaign

## Objetivo
Implementar soporte multiidioma en el frontend para tres idiomas: Español, Inglés y Portugués.

## Tareas

### Fase 1: Configuración Inicial
- [x] Instalar `react-i18next` e `i18next` como dependencias
- [x] Crear estructura de archivos de traducción en `src/locales/`
- [x] Configurar i18n en el proyecto (crear `src/i18n.ts`)
- [x] Crear hook personalizado y contexto para gestión de idioma

### Fase 2: Archivos de Traducción
- [x] Crear `src/locales/es/translation.json` (Español)
- [x] Crear `src/locales/en/translation.json` (Inglés)  
- [x] Crear `src/locales/pt/translation.json` (Portugués)

### Fase 3: Componentes Base
- [x] Crear selector de idioma (`LanguageSelector.tsx`)
- [x] Integrar selector en la navegación
- [x] Integrar selector en el header
- [x] Persistir preferencia de idioma en localStorage

### Fase 4: Migración de Textos - Páginas
- [x] `LoginPage.tsx` - Migrar textos a claves i18n
- [x] `ContactsPage.tsx` - Migrar textos a claves i18n
- [x] `UsersPage.tsx` - Migrar textos a claves i18n
- [x] `WhatsAppConnectionsPage.tsx` - Migrar textos a claves i18n
- [x] `SettingsPage.tsx` - Migrar textos a claves i18n
- [x] `CampaignsPage.tsx` - Migrar textos a claves i18n (archivo grande)
- [x] `SuperAdminPage.tsx` y relacionadas - Migrar textos
- [x] `FlowBuilderPage.tsx` - Migrar textos a claves i18n
- [x] `InteractiveCampaignPage.tsx` - Migrar textos a claves i18n

### Fase 5: Migración de Textos - Componentes
- [x] `Navigation.tsx` - Migrar textos a claves i18n
- [x] `Header.tsx` - Migrar textos a claves i18n
- [x] `Pagination.tsx` - Migrar textos a claves i18n
- [x] `SearchAndFilters.tsx` - Migrar textos a claves i18n
- [x] `ContactForm.tsx` - Migrar textos a claves i18n
- [x] `ContactList.tsx` - Migrar textos a claves i18n
- [x] `CategoryModal.tsx` - Migrar textos a claves i18n
- [x] `CSVImportModal.tsx` - Migrar textos a claves i18n
- [x] `BulkEditModal.tsx` - Migrar textos a claves i18n
- [x] `ChatwootSyncModal.tsx` - Migrar textos a claves i18n
- [x] `PerfexImportModal.tsx` / `PerfexSyncModal.tsx`
- [x] `UserForm.tsx` & `UserList.tsx` - Migrar textos a claves i18n
- [x] `PerfexSyncModal.tsx` - Migrar textos a claves i18n
- [x] `AnalyticsDashboard.tsx` - Migrar textos a claves i18n
- [x] `SystemBackup.tsx` - Migrar textos a claves i18n
- [x] `BackupManagement.tsx` - Migrar textos a claves i18n
- [ ] Otros componentes menores

### Fase 6: Validaciones y Mensajes
- [ ] Migrar mensajes de validación Zod
- [ ] Migrar mensajes de toast (react-hot-toast)
- [ ] Migrar mensajes de error de API

### Fase 7: Verificación
- [x] Build de producción compilando correctamente
- [ ] Probar cambio de idioma en todas las páginas
- [ ] Verificar persistencia del idioma
- [ ] Revisar que no queden textos hardcoded

