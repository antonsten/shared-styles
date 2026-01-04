# Shared Styling Rules

## Design System Baseline (2025 Refresh)

### Component Guidelines

- **Rounded corners**: 4px minimum (rounded-[4px])
- **Buttons**: Use 4px rounded corners
- **No shadows**: Never use drop shadows - rely on contrast/background layering instead
- **No icons in buttons**: Buttons should not contain icons
- **Never use `@apply` directive**: Use Tailwind utility classes directly
- **Never use `!important`**: Use proper specificity and class-based overrides

### Dropdowns

- Use border and background contrast instead of shadows
- Smooth transitions for visibility
- Clear focus states
- Accessible with proper ARIA attributes

### Form Elements

- Input fields should use border-based styling, not shadows
- Clear focus states with accent color
- Consistent padding and spacing

