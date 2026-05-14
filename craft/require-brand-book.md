# Brand Book Required

## Intent
To ensure consistent visual identity and prevent generic designs, every creative workflow MUST use a predefined or dynamically provided Brand Book.

## Rule
1. **Never Start Without a Brand Book:** Before generating any HTML, CSS, Print Template, or Digital Banner, the agent MUST explicitly ask the user: "Which Brand Book should I use for this project?" or require them to provide brand tokens (Primary Color, Secondary Color, Font, Logo).
2. **Apply strictly:** All color hex codes, typographic families, margins, and logo placements must derive from the active Brand Book. Do not use random colors or default palettes.
3. **If missing:** Halt the generation process and prompt the user.

## Enforcement
This rule applies globally across all templates under `design-templates/` and `design-systems/`.
