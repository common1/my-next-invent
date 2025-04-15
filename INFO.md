# my-next-invent

## 01 Project setup - Part 1

```
$ bunx create-next-app@14.2.14 my-next-invent
✔ Would you like to use TypeScript? … Yes
✔ Would you like to use ESLint? … Yes
✔ Would you like to use Tailwind CSS? … Yes
✔ Would you like to use `src/` directory? … Yes
✔ Would you like to use App Router? (recommended) … Yes
? Would you like to customize the default import alias (@/*)? › No

$ bun run dev

```

## 02 Adding a component library - Part 1

```
$ bunx --bun shadcn --version
2.1.0

$ bunx --bun shadcn@2.1.0 init
✔ Preflight checks.
✔ Verifying framework. Found Next.js.
✔ Validating Tailwind CSS.
✔ Validating import alias.
✔ Which style would you like to use? › New York
✔ Which color would you like to use as the base color? › Neutral
? Would you like to use CSS variables for theming? › yes

$ bunx --bun shadcn@2.1.0 add button
```

## 03 Customizing components - Part 1

```
bunx --bun shadcn@2.1.0 add
avatar
badge
button
calendar
card
chart
checkbox
dialog
drawer
dropdown-menu
form
input
label
popover
scroll-area
select
separator
sheet
skeleton
sonner
table
tabs
text-area
```

## 04 Creating auth screens - Part 1

...

## 04 Creating auth screens - Part 2

```
$ bun add react-icons
```



