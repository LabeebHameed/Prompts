Hello. I need you to convert the Figma file I've provided into a pixel-perfect UI.

We are going to follow a very strict, two-phase process.

Phase 1: Analysis and Specification (Your Only Task Right Now)

Your first and only task is to analyze the Figma file and extract all its design specifications. You will not write any HTML, CSS, or React code yet.

Instead, you must create a new file named Figma.md.

In this markdown file, you will meticulously document all the design tokens, layout values, and spacing. You must be exact.

Here is the structure I want you to follow in Figma.md:

Global Styles:

Colors: List all primary, secondary, text, background, and accent colors with their hex codes.

Typography: Define the primary and secondary font families, and list all font-size, font-weight, and line-height combinations used (e.g., H1, H2, Body, Caption).

Component Analysis:

Break down the design into its core components (e.g., Header, Sidebar, Button, StatCard, MainContent).

For each component, create a section and document the following:

Sizing: width, height (use auto or 100% where appropriate, but specify fixed sizes if the design uses them).

Spacing (Internal): padding (top, right, bottom, left).

Spacing (External): This is critical. Measure the exact gap in pixels between this component and its neighbors. (e.g., margin-bottom: 24px or gap: 16px if in a flex container).

Borders: border-radius, border-width, border-color.

Shadows: box-shadow properties.

Example for a "Header" component in Figma.md:

Markdown

### Component: Header

* **Sizing:** `height: 80px`, `width: 100%`
* **Spacing (Internal):** `padding: 0px 32px`
* **Layout:** Flex, `justify-content: space-between`, `align-items: center`
* **Borders:** `border-bottom: 1px solid #E2E8F0`
* **Internal Gaps:**
    * Gap between `Logo` and `NavLinks`: `48px`
    * Gap between `NavLinks` and `UserProfile`: `auto` (space-between)
Your Deliverable for Phase 1:

Your only output for this message should be the complete Figma.md file.

Do not proceed to Phase 2 (Code Generation) until I have personally reviewed and approved the Figma.md file. This step is mandatory. I want to confirm you have captured all values correctly before you write a single line of UI code.
