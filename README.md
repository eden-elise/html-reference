# html-reference
A kitchen sink reference site for HTML elements, built as a course assignment. Every current HTML element and a selection of deprecated ones are demonstrated across eight focused pages with one shared CSS file. No frameworks, no build tools.

## pages
- `index.html` — document metadata and page shell
- `text.html` — text and inline semantic elements
- `media.html` — images, audio, video, and embedding
- `tables.html` — full table structure and accessibility attributes
- `forms.html` — every input type and form element
- `structure.html` — sectioning, lists, and interactive elements
- `deprecated.html` — obsolete elements with explanations
- `experiments.html` — edge cases and browser behavior tests

## custom experiments
1. 100 nested details elements — tested browser depth limits
2. Emoji as id attributes — tested CSS and JS targeting with non-standard ids
3. div inside p — documented silent browser error recovery behavior

## llm use
Used Claude to help generate content and structure for each page. All findings in experiments.html are my own observations from actually running the code in the browser.

## committing practice
Format: `<type>(<optional scope>): <description>`

feat: A new feature.  
fix: A bug fix.  
docs: Documentation only changes.  
style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc.).  
refactor: A code change that neither fixes a bug nor adds a feature.  
test: Adding missing tests or correcting existing tests.  
chore: Maintenance tasks, build process or auxiliary tool changes.  
BREAKING CHANGE: In the body or footer to indicate breaking changes.