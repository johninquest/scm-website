name: i18n
description: >
  This skill supports internationalization and localization for professional
  CRM applications used in social work and school social work. It is designed
  for English source texts and high-quality German translations that follow
  native administrative and professional language standards.

version: 1.2.0
author: "Your Name"
license: "MIT"

language_policy:
  source_language: en
  target_languages:
    - de

  audience:
    - social_work_professionals
    - school_social_workers

  register:
    # i18n

    This skill supports internationalization and localization for professional CRM
    applications used in social work and school social work. It is designed for
    English source texts and high-quality German translations that follow native
    administrative and professional language standards.

    - Version: 1.2.0
    - Author: Your Name
    - License: MIT

    ## Language policy

    - Source language: en
    - Target languages: de
    - Audience: social_work_professionals, school_social_workers
    - Register (de): formal
    - Address form (de): Sie
    - Tone: professional, supportive, neutral

    Gender language strategy: context_sensitive

    Rules:
    - Prefer neutral collective nouns where appropriate (e.g. "Fachkräfte").
    - Use colon form for defined roles and groups (e.g. "Sozialarbeiter:innen").
    - Avoid informal or experimental gender forms.

    Writing principles:
    - Use plain, precise language
    - Avoid idioms, metaphors, and colloquial expressions
    - Prefer short, declarative sentences
    - Keep terminology consistent across the application
    - Avoid marketing or promotional language in all UI texts

    ## Features

    - Language Detection: Detect the user’s preferred language via browser
      settings or user profile, with manual override support.
    - Translation Management: Manage translation files with support for contextual
      keys, developer notes, and terminology guidance.
    - Context-Aware Translations: Allow translators to see UI location, user role,
      and functional context to prevent ambiguous or misleading translations.
    - German Language Support: Support German-specific grammar, compound nouns,
      pluralization rules, and formal address conventions.
    - Pluralization and Grammar: Handle plural forms and grammatical variations
      correctly for all supported languages.
    - Localization: Format dates, times, numbers, and currencies according to
      locale standards, following German conventions by default.
    - Fallback Mechanism: Provide a controlled fallback to English when
      translations are missing, without breaking workflows or layouts.
    - Accessibility: Ensure translated content remains accessible and compatible
      with assistive technologies.
    - Performance: Optimize loading and rendering of translation resources for
      large, form-heavy administrative applications.
    - Documentation: Provide documentation and examples, including guidance on
      writing translation-ready English source strings.

    ## Usage

    All user-facing text is defined in English using clear, neutral, and
    translation-friendly language. Each translation key includes sufficient
    contextual information to support accurate German translations. German
    translations follow formal address conventions, professional tone, and
    domain-specific terminology appropriate for social work. The system ensures
    correct language selection, localization, and fallback behavior across the
    application.