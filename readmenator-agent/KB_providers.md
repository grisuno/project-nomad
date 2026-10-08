# Subsystem: providers

## admin/inertia/providers/ModalProvider.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `openModal` (function, line 12)
  - `closeModal` (function, line 20)
  - `closeAllModals` (function, line 31)
  - `_getCurrentModals` (function, line 36)
- Depends on: `admin/inertia/context/ModalContext.ts`

## admin/inertia/providers/NotificationProvider.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `NotificationsProvider` (function, line 6)
  - `addNotification` (function, line 9)
  - `removeNotification` (function, line 29)
  - `removeAllNotifications` (function, line 33)
  - `Icon` (function, line 37)
- Depends on: `admin/inertia/context/NotificationContext.ts`

## admin/inertia/providers/ThemeProvider.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `ThemeProvider` (function, line 16)
  - `useThemeContext` (function, line 25)
- Depends on: `admin/inertia/hooks/useTheme.ts`
- Imported by: `admin/inertia/app/app.tsx`, `admin/inertia/components/ThemeToggle.tsx`
