# GOV.UK Design System Snippets

GOV.UK Design System Nunjucks macro snippets for popular code editors. For use by UK government designers. 

![An animation of the code snippets in action](https://github.com/daviddotto/govuk-design-system-snippets/blob/master/demo.gif "Snippets in action")

## Installation

Installation will differ based on your operating system and text editor of choice. These snippets are designed to be addded to your existing HTML snippets, be careful not to overwrite your existing snippets.

* [Snippets in Atom](https://atom.io/packages/snippets)
* [Snippets in Visual Studio Code](https://code.visualstudio.com/docs/editor/userdefinedsnippets)

## Usage

1. Start typing `gov-`.
2. See a list of suggestions.
3. Either continue typing until you've selected the correct snippet or use the arrow keys to select from the list.
4. Press \[return] and the snippet will be inserted automatically.
5. Your cursor will be moved to the first insertion point in the snippet, type in your content.
6. Press \[tab] to move to the next insertion point. Repeat.
7. Press \[tab] to finalise and move to the end of the snippet.

Visual Studio Code has the added benefit of allowing users to choose from a list of options at some insertion points, simply press \[down] to choose from the available options and then \[return] to confirm.

## Available snippets

| Name                          | Shortcut                        | Insertion points                                                                                                                                                                                                  | Design System documentation                                              |
|-------------------------------|---------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------|
| Two-thirds layout             | `gov-layout-twothirds`          | N/A                                                                                                                                                                                                               | [Layout - Two-thirds](https://design-system.service.gov.uk/styles/layout/#two-thirds)           |
| Two-thirds / one-third layout | `gov-layout-twothirds-onethird` | N/A                                                                                                                                                                                                               | [Layout - Two-thirds / one-third](https://design-system.service.gov.uk/styles/layout/#two-thirds-one-third) |
| Grid row                      | `gov-layout-grid-row`           | **1.** Inside grid row `<div>`                                                                                                                                                                                    | [Layout](https://design-system.service.gov.uk/styles/layout)                       |
| Column                        | `gov-layout-column`             | **1.** Class name of column (defining column size) **2** Inside column `<div>`                                                                                                                                                                | [Layout](https://design-system.service.gov.uk/styles/layout)                       |
| Link                          | `gov-typo-link`                 | **1.** Destination `href` value **2.** Link text                                                                                                                                                                  | [Typography - Links](https://design-system.service.gov.uk/styles/typography/#links)            |
| Header text                   | `gov-typo-header-text`          | **1.** Header level; `h1` to `h6` **2.** Font size class small to extra large **3.** Header title                                                                                                                 | [Typography - Headings](https://design-system.service.gov.uk/styles/typography/#headings)         |
| Paragraph text                | `gov-typo-paragraph-text`       | **1.** Font size class; standard, large or small **2.** Paragraph content                                                                                                                                         | [Typography - Paragraphs](https://design-system.service.gov.uk/styles/typography/#paragraphs)       |
| List                          | `gov-typo-list`                 | **1.** List type; standard or bullet **2.** Inside first list item                                                                                                                                                | [Typography - Lists](https://design-system.service.gov.uk/styles/typography/#lists)            |
| Numbered list                 | `gov-typo-number-list`          | **1.** Inside first list item                                                                                                                                                                                     | [Typography - Numbered lists](https://design-system.service.gov.uk/styles/typography/#numbered-lists)   |
| Section break                 | `gov-typo-section-break`        | **1.** Vertical margin size class; extra large, large, medium or standard                                                                                                                                         | [Typography - Section break](https://design-system.service.gov.uk/styles/typography/#section-break)    |
| Back link                     | `gov-back-link`                 | **1.** Title (default: Back) **2.** Destination `href` value (default: Browser back functionality)                                                                                                                | [Components - Back link](https://design-system.service.gov.uk/components/back-link/  )             |
| Warning text                  | `gov-warning-text`              | **1.** Text **2.** Text replacement for icon for screen-readers (default: Warning)                                                                                                                                | [Components - Warning text](https://design-system.service.gov.uk/components/warning-text/)            |
| Inset text                    | `gov-inset-text`                | **1.** Text                                                                                                                                                                                                       | [Components - Inset text](https://design-system.service.gov.uk/components/inset-text/)              |
| Breadcrumbs                   | `gov-breadcrumbs`               | **1.** Root link text (default: Home) **2.** Root link destination `href` value **3.** Current page name                                                                                                          | [Components - Breadcrumbs](https://design-system.service.gov.uk/components/breadcrumbs/ )            |
| Link button                   | `gov-link-button`               | **1.** Button text (default: Start) **2.** Destination `href` value **3.** Button type class; standard or start                                                                                                   | [Components - Button](https://design-system.service.gov.uk/components/button/)                  |
| Form submit button            | `gov-form-button`               | **1.** Button text (default: Save and continue)                                                                                                                                                                   | [Components - Button](https://design-system.service.gov.uk/components/button/)                  |
| Text input                    | `gov-form-text`                 |  **1.** Name and ID of the`input` field **2.** Label text **3.** Size class (standard, 20 characters, 10 characters)                                                                                              | [Components - Text input](https://design-system.service.gov.uk/components/text-input/)              |
| Text input with hint          | `gov-form-text-hint`            | **1.** Name and ID of the `input` field **2.** Label text **3.** Hint text **4.** Size class (standard, 20 characters, 10 characters)                                                                             | [Components - Text input](https://design-system.service.gov.uk/components/text-input/)              |
| Textarea                      | `gov-form-textarea`             | **1.** Name and ID of the `textarea` element  **2.** Label text                                                                                                                                                   | [Components - Textarea](https://design-system.service.gov.uk/components/textarea/)                |
| Textarea with hint            | `gov-form-textarea-hint`        | **1.** Name and ID of the `textarea` element  **2.** Label text **3.** Hint text                                                                                                                                  | [Components - Textarea](https://design-system.service.gov.uk/components/textarea/)                |
| Radio buttons                 | `gov-form-radio-buttons`        | **1.** Name and ID prefix of checkbox inputs **2.** Legend text, typically a question **3.** Hint text, remove `hint: {*},` if not required **4.** Radio button answers, use shortcut `gov-form-option` to add item               | [Components - Checkboxes](https://design-system.service.gov.uk/components/checkboxes/)              |
| Inline radio buttons          | `gov-form-radio-buttons-inline` | **1.** Name and ID prefix of checkbox inputs **2.** Legend text, typically a question **3.** Hint text, remove `hint: {*},` if not required **4.** Radio button answers, use shortcut `gov-form-option` to add item               | [Components - Checkboxes](https://design-system.service.gov.uk/components/checkboxes/)              |
| Radio or checkbox option      | `gov-form-option`               | **1.** Value of item when selected **2.** Text to display in label                                                                                                                                                        | N/A                                                                      |
| Date input                    | `gov-form-date-input`           | **1.** Name and ID prefix, for example using `'dob'` would produce names and IDs of `'dob-day'`,`'dob-month'` and `'dob-year'` **2.** Legend text, typically a question **3.** Hint text, remove `hint: {*},` if not required | [Components - Date input](https://design-system.service.gov.uk/components/date-input/)              |
| File upload                   | `gov-form-file-upload`          | **1.** Name and ID **2.** Label, default: `'Upload a file'`                                                                                                                                                               | [Components - File upload](https://design-system.service.gov.uk/components/file-upload/)             |

## Roadmap

We're currently working on porting these snippets to Sublime Text. Any and all feedback would be appreciated.
