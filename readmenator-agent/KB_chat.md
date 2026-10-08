# Subsystem: chat

## admin/inertia/components/chat/ChatAssistantAvatar.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `ChatAssistantAvatar` (function, line 3)

## admin/inertia/components/chat/ChatButton.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `ChatButton` (function, line 7)

## admin/inertia/components/chat/ChatInterface.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `ChatInterface` (function, line 24)
  - `handleDownloadModel` (function, line 41)
  - `scrollToBottom` (function, line 54)
  - `handleSubmit` (function, line 62)
  - `handleKeyDown` (function, line 73)
  - `handleInput` (function, line 80)
- Depends on: `admin/constants/ollama.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`

## admin/inertia/components/chat/ChatMessageBubble.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `ChatMessageBubble` (function, line 10)
- Depends on: `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`

## admin/inertia/components/chat/ChatModal.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `ChatModal` (function, line 11)
- Depends on: `admin/app/utils/misc.ts`, `admin/inertia/hooks/useSystemSetting.ts`

## admin/inertia/components/chat/ChatSidebar.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `ChatSidebar` (function, line 18)
  - `handleCloseKnowledgeBase` (function, line 31)
- Depends on: `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`

## admin/inertia/components/chat/KbPolicyPromptBanner.tsx
- Doc: KbPolicyPromptBanner: (`rag.defaultIngestPolicy` unset).
- Layer: presentation
- Language: tsx
- Symbols:
  - `KbPolicyPromptBanner` (function, line 27)
- Depends on: `admin/inertia/context/NotificationContext.ts`

## admin/inertia/components/chat/KnowledgeBaseModal.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `renderStatePill` (function, line 32)
  - `pickRowAction` (function, line 77)
  - `KnowledgeBaseModal` (function, line 96)
  - `handleUpload` (function, line 282)
  - `handleConfirmSync` (function, line 313)
- Depends on: `admin/constants/service_names.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/context/NotificationContext.ts`, `admin/inertia/lib/kb_file_grouping.ts`

## admin/inertia/components/chat/index.tsx
- Layer: presentation
- Language: tsx
- Symbols:
  - `Chat` (function, line 24)
- Depends on: `admin/constants/ollama.ts`, `admin/inertia/context/ModalContext.ts`, `admin/inertia/hooks/useSystemSetting.ts`, `admin/inertia/lib/classNames.ts`, `admin/types/chat.ts`
