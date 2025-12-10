# Teacher Prompt Bank

A comprehensive collection of AI prompts designed for UK teachers to adapt and use with their specific subjects, year groups, examination boards, and student needs.

## Overview

This prompt bank provides generic templates that teachers can customise by replacing placeholder variables with their specific context. Each prompt is designed to be inclusive and considers diverse learner needs, including neurodivergent students.

## Customisation Parameters

All prompts use placeholders that you replace with your specific context:

| Parameter | Description | Examples |
|-----------|-------------|----------|
| `[SUBJECT]` | Academic subject | Mathematics, English Literature, Biology |
| `[YEAR_GROUP]` | Year or Key Stage | Year 7, Year 10, Key Stage 4, A-Level |
| `[EXAM_BOARD]` | Examination board | AQA, Edexcel, OCR, WJEC, Cambridge |
| `[ABILITY_LEVEL]` | Class ability profile | Foundation, Mixed ability, Higher |
| `[TARGET_GRADE]` | Student target grades | Grade 5, Grade 7-9, Grade A* |
| `[NEURODIVERGENCE]` | Specific needs to consider | ADHD, Autism/ASD, Dyslexia |
| `[TOPIC]` | Specific topic within subject | Quadratic equations, WW1 causes |
| `[LEARNING_OBJECTIVES]` | What students should learn | Describe, Explain, Evaluate... |
| `[TIME_AVAILABLE]` | Lesson/activity duration | 30 minutes, 1 hour, Double period |

See `config/parameters.json` for full parameter details and examples.

## Prompt Categories

### Lesson Planning (`/prompts/lesson-planning/`)
- **01-lesson-plan-generator.md** - Generate complete lesson plans
- **02-scheme-of-work.md** - Create medium-term unit plans
- **03-learning-objectives.md** - Differentiated objectives using Bloom's taxonomy
- **04-starter-activities.md** - Engaging lesson openers
- **05-plenary-activities.md** - Consolidation and assessment activities

### Resource Creation (`/prompts/resources/`)
- **01-worksheet-generator.md** - Differentiated worksheets with scaffolding
- **02-knowledge-organiser.md** - Topic summary sheets
- **03-powerpoint-content.md** - Presentation content and speaker notes
- **04-revision-materials.md** - Flashcards, checklists, practice questions
- **05-graphic-organisers.md** - Visual thinking tools and templates

### Assessment (`/prompts/assessment/`)
- **01-exam-questions.md** - Exam-style questions with mark schemes
- **02-mark-scheme-generator.md** - Detailed marking criteria
- **03-rubric-creator.md** - Assessment rubrics for various task types
- **04-diagnostic-assessment.md** - Identify gaps and misconceptions
- **05-self-assessment-tools.md** - Student self-evaluation resources

### Differentiation & Support (`/prompts/differentiation/`)
- **01-scaffolding-strategies.md** - Support tools for different levels
- **02-extension-challenges.md** - Enrichment for higher attainers
- **03-neurodivergent-adaptations.md** - ADHD, ASD, dyslexia, dyscalculia support
- **04-intervention-materials.md** - Targeted catch-up resources
- **05-eal-support.md** - English as Additional Language adaptations

### Feedback & Reporting (`/prompts/feedback/`)
- **01-written-feedback.md** - Constructive feedback on student work
- **02-report-comments.md** - Professional report writing
- **03-verbal-feedback-scripts.md** - Conversation frameworks
- **04-peer-feedback-guides.md** - Student peer assessment structures

### Explanation & Teaching (`/prompts/explanation/`)
- **01-concept-explainer.md** - Multi-level concept explanations
- **02-simplification.md** - Text adaptation for accessibility
- **03-worked-examples.md** - Step-by-step model answers
- **04-analogy-generator.md** - Memorable comparisons and metaphors

### Questioning (`/prompts/questions/`)
- **01-questioning-sequences.md** - Bloom's taxonomy question sequences
- **02-hinge-questions.md** - Diagnostic multiple choice questions
- **03-discussion-questions.md** - Critical thinking prompts
- **04-retrieval-practice.md** - Spaced practice questions

### Communication (`/prompts/communication/`)
- **01-parent-communication.md** - Letters and emails to parents
- **02-student-communication.md** - Instructions and guidance for students
- **03-colleague-communication.md** - Handovers, referrals, meeting agendas

## How to Use

### Basic Usage

1. Choose a prompt from the relevant category
2. Copy the prompt template
3. Replace all `[PLACEHOLDER]` values with your specific context
4. Use with your preferred AI tool (ChatGPT, Claude, etc.)

### Example

**Original prompt:**
```
Create a lesson plan for teaching [TOPIC] in [SUBJECT] to [YEAR_GROUP] students.
- Examination Board: [EXAM_BOARD]
- Ability Level: [ABILITY_LEVEL]
- Target Grade: [TARGET_GRADE]
```

**Customised prompt:**
```
Create a lesson plan for teaching Quadratic Equations in Mathematics to Year 10 students.
- Examination Board: Edexcel
- Ability Level: Mixed ability
- Target Grade: Grade 5-7
```

### Neurodivergent Adaptations

Most prompts include specific variations for neurodivergent learners. Look for sections titled:
- "ADHD Adaptations"
- "Autism/ASD Adaptations"
- "Dyslexia-Friendly Version"
- "Universal Design" versions

## UK Education Context

These prompts are designed for the UK education system and include:
- GCSE (9-1) and A-Level grade references
- UK examination boards (AQA, Edexcel, OCR, WJEC, Eduqas)
- Key Stage terminology
- UK curriculum alignment
- British English spelling and terminology

## Contributing

To add new prompts:
1. Use the existing format with clear sections
2. Include placeholder parameters in `[BRACKETS]`
3. Add neurodivergent-friendly variations where appropriate
4. Include relevant tags at the bottom

## Directory Structure

```
promptrepo/
├── README.md
├── config/
│   └── parameters.json      # All customisation parameters
└── prompts/
    ├── lesson-planning/     # Lesson and curriculum planning
    ├── resources/           # Teaching resource creation
    ├── assessment/          # Assessment and marking
    ├── differentiation/     # Support and extension
    ├── feedback/            # Feedback and reporting
    ├── explanation/         # Teaching and explaining
    ├── questions/           # Questioning strategies
    └── communication/       # Stakeholder communication
```

## License

Free for educational use.
