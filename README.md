# DoD Mentor-Protégé Program Learning Hub

Interactive learning tools for the DoD Mentor-Protégé Program (MPP), designed for embedding in Articulate Rise courses.

## Live Demo

**[View Learning Hub](https://charlesmartinedd.github.io/mpp-learning-hub/)**

## Features

### Program Glossary
- **140+ terms** covering MPP terminology, acronyms, roles, and regulations
- Three-layer card navigation (Letters → Terms → Definitions)
- 8 categories: Acronyms, Roles, Agreements, Reports, Financial, Forms, Processes, Regulatory
- Related terms linking and module references

### Knowledge Quiz
- **38 questions** across 10 modules
- Progress tracking with visual indicators
- Immediate feedback with explanations
- Results summary with missed question review

## Files

| File | Description |
|------|-------------|
| `index.html` | Cover page - select Glossary or Quiz |
| `glossary.html` | Interactive MPP terminology glossary |
| `quiz.html` | Module-based knowledge assessment |

## Embedding in Articulate Rise

Each HTML file is self-contained with no external dependencies (except Google Fonts). To embed:

1. Upload the desired HTML file to your LMS or web host
2. In Rise, add an **iFrame embed** block
3. Set the source URL to your hosted file
4. Recommended dimensions: 100% width, 600-800px height

## Design System

- **Font**: Inter (Google Fonts)
- **Colors**: Navy/slate palette with CSS variables
- **Styling**: Consistent across all components

### CSS Variables
```css
--navy-900: #0f172a
--navy-700: #1e3a5f
--slate-500: #64748b
--accent: #2563eb
--warm-50: #fefdfb
```

## Source Repositories

This hub combines content from:
- [mpp-glossary](https://github.com/charlesmartinedd/mpp-glossary) - Original glossary
- [mpp-quiz-system](https://github.com/charlesmartinedd/mpp-quiz-system) - Original quiz system

## Development

No build process required. Edit HTML files directly.

```bash
# Clone the repository
git clone https://github.com/charlesmartinedd/mpp-learning-hub.git

# Open locally
open index.html
```

## License

Developed for DoD MPP training programs.
