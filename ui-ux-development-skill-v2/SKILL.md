---
name: ui-ux-development
description: Reusable UI/UX workflow for web, Android and iOS projects using verified open-source components and visual-first design selection.
---
# UI/UX Development

When asked to create or improve a screen:
1. Inspect the existing application stack, routes, components, tests and permissions. Do not assume React or Tailwind.
2. Identify the user persona, top tasks, data, and important error/empty/loading states.
3. When the user knows the desired outcome but cannot describe the layout, show 2–3 concrete design directions with actual domain labels; recommend one. Do not demand a detailed specification.
4. Reuse existing components first. For compatible web React apps, consider Tailwind CSS for styling, shadcn/ui for components, and Tabler for dashboard layout patterns. For React Native apps consider React Native Paper. For native iOS/Android prefer SwiftUI/Jetpack Compose.
5. Check package version, licence, assets and compatibility at the source before copying or installing anything. Record dependencies and attribution where required. No unreviewed scripts.
6. Implement one small vertical slice, keeping the underlying business logic and data formats unchanged.
7. Validate keyboard navigation, focus, accessibility, mobile responsiveness, clear units, loading, error and permission states.
8. Run existing tests and new targeted tests. Never claim a test ran unless it actually did.
9. Report changed files, tests, visual decisions and rollback instructions.

See references/stack.md, projects/liner-hanger.md, projects/observeiq.md and trial/checklist.md.
