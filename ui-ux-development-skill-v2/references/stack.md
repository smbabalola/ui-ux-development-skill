# Open-source UI resources

- Tailwind CSS — https://github.com/tailwindlabs/tailwindcss — utility-first styling, not a ready-made screen library.
- shadcn/ui — https://github.com/shadcn-ui/ui — reusable React UI component source, commonly styled with Tailwind.
- Tabler — https://github.com/tabler/tabler — dashboard and admin patterns; check compatibility before integrating with a React stack.
- React Native Paper — https://github.com/callstack/react-native-paper — cross-platform mobile component library.

These are upstream references, not vendored source code. This skill does not automatically clone or install them. Before incorporation, verify exact repository licence, third-party asset licences, dependency versions and security. Tailwind CSS does not directly style native React Native views without a separate compatible solution.

## Web choices
A. Sidebar + status cards + action table: operational admin.
B. Master/detail split + review queue: investigation and approvals.
C. Full-width charts + synchronized timeline + annotation drawer: engineering analysis.

Choose by the task, not visual novelty. Offer screenshots/wireframes when available, and ask user to choose rather than requiring exhaustive instructions.
