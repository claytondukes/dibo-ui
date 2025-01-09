# Design System

## Colors

### Primary Colors

```css
--primary-50:  #f0f9ff;  /* Lightest */
--primary-100: #e0f2fe;
--primary-200: #bae6fd;
--primary-300: #7dd3fc;
--primary-400: #38bdf8;
--primary-500: #0ea5e9;  /* Base */
--primary-600: #0284c7;
--primary-700: #0369a1;
--primary-800: #075985;
--primary-900: #0c4a6e;  /* Darkest */
--primary-950: #082f49;
```

### Accent Colors

```css
--accent-50:  #fff7ed;  /* Lightest */
--accent-100: #ffedd5;
--accent-200: #fed7aa;
--accent-300: #fdba74;
--accent-400: #fb923c;
--accent-500: #f97316;  /* Base */
--accent-600: #ea580c;
--accent-700: #c2410c;
--accent-800: #9a3412;
--accent-900: #7c2d12;  /* Darkest */
--accent-950: #431407;
```

### Neutral Colors

```css
--neutral-50:  #fafafa;  /* Lightest */
--neutral-100: #f4f4f5;
--neutral-200: #e4e4e7;
--neutral-300: #d4d4d8;
--neutral-400: #a1a1aa;
--neutral-500: #71717a;  /* Base */
--neutral-600: #52525b;
--neutral-700: #3f3f46;
--neutral-800: #27272a;
--neutral-900: #18181b;  /* Darkest */
--neutral-950: #09090b;
```

## Typography

### Font Families

```css
--font-sans: 'Inter var', ui-sans-serif, system-ui;
--font-mono: 'JetBrains Mono', ui-monospace, monospace;
```

### Font Sizes

```css
--text-xs:  0.75rem;   /* 12px */
--text-sm:  0.875rem;  /* 14px */
--text-base: 1rem;     /* 16px */
--text-lg:  1.125rem;  /* 18px */
--text-xl:  1.25rem;   /* 20px */
--text-2xl: 1.5rem;    /* 24px */
--text-3xl: 1.875rem;  /* 30px */
--text-4xl: 2.25rem;   /* 36px */
```

### Font Weights

```css
--font-thin:       100;
--font-extralight: 200;
--font-light:      300;
--font-normal:     400;
--font-medium:     500;
--font-semibold:   600;
--font-bold:       700;
--font-extrabold:  800;
--font-black:      900;
```

## Spacing

### Base Scale

```css
--spacing-px:  1px;
--spacing-0:   0;
--spacing-0.5: 0.125rem;  /* 2px */
--spacing-1:   0.25rem;   /* 4px */
--spacing-2:   0.5rem;    /* 8px */
--spacing-3:   0.75rem;   /* 12px */
--spacing-4:   1rem;      /* 16px */
--spacing-6:   1.5rem;    /* 24px */
--spacing-8:   2rem;      /* 32px */
--spacing-12:  3rem;      /* 48px */
--spacing-16:  4rem;      /* 64px */
```

## Borders

### Border Radius

```css
--radius-none:   0;
--radius-sm:     0.125rem;  /* 2px */
--radius-base:   0.25rem;   /* 4px */
--radius-md:     0.375rem;  /* 6px */
--radius-lg:     0.5rem;    /* 8px */
--radius-xl:     0.75rem;   /* 12px */
--radius-2xl:    1rem;      /* 16px */
--radius-3xl:    1.5rem;    /* 24px */
--radius-full:   9999px;
```

### Border Width

```css
--border-0:     0;
--border-2:     2px;
--border-4:     4px;
--border-8:     8px;
```

## Shadows

```css
--shadow-sm:    0 1px 2px 0 rgb(0 0 0 / 0.05);
--shadow-base:  0 1px 3px 0 rgb(0 0 0 / 0.1), 0 1px 2px -1px rgb(0 0 0 / 0.1);
--shadow-md:    0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
--shadow-lg:    0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);
--shadow-xl:    0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
--shadow-2xl:   0 25px 50px -12px rgb(0 0 0 / 0.25);
--shadow-inner: inset 0 2px 4px 0 rgb(0 0 0 / 0.05);
```

## Transitions

```css
--transition-all:      all 0.15s cubic-bezier(0.4, 0, 0.2, 1);
--transition-colors:   color 0.15s cubic-bezier(0.4, 0, 0.2, 1), background-color 0.15s cubic-bezier(0.4, 0, 0.2, 1), border-color 0.15s cubic-bezier(0.4, 0, 0.2, 1);
--transition-opacity:  opacity 0.15s cubic-bezier(0.4, 0, 0.2, 1);
--transition-shadow:   box-shadow 0.15s cubic-bezier(0.4, 0, 0.2, 1);
--transition-transform: transform 0.15s cubic-bezier(0.4, 0, 0.2, 1);
```
