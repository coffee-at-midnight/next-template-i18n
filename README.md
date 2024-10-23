# Next.js Docs Template i18n

> Documentation template for Next.js with i18n support (multiple languages), search, MDX components for documentation and blog.

This template has been forked from [opendocs](https://github.com/daltonmenezes/opendocs), see [official documentation of opendocs theme](https://opendocs.daltonmenezes.com/docs ).

## MDX Components

- MDX components available in `apps/content/docs/en/mdx/components.mdx`:
  - Accordion
  - Alerts/Admonitions (but without icon)
  - Tabs
  - Steps/Processes

(Code in `apps/web/src/components/ui`).

## Multilingual documentation

- Realized with i18n plugin for Next.js (next-intl)
- Language toggle in top menu bar
- Translations for Markdown/MDX files (documentation) in `apps/content/docs/en` and `apps/content/docs/pt`
- Translated button labels in JSON files in `apps/web/src/i18n/locales`