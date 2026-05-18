# Private AI Research Assistant Blueprint

## Purpose

The first AI system should be a private Clinical Research Compass assistant, not a public autonomous app. Its job is to make the consultancy easier to operate by turning client ideas, uploaded notes, or draft protocols into structured drafts for expert review.

The assistant should support the official mission: **“To provide expert, independent guidance that strengthens the design, interpretation, and impact of clinical research.”**

## Build Principle

AI should prepare drafts, check consistency, and organize work. The consultant remains responsible for judgment, final review, client communication, and safety boundaries.

## Assistant Modules

### 1. Intake Assistant

Summarizes the client’s idea, identifies missing information, estimates project complexity, and recommends the right service package.

### 2. Research Question Assistant

Transforms broad clinical topics into structured questions using PICOT, PEO, SPIDER, or another suitable framework.

### 3. Framework Selection Assistant

Recommends whether the question should use PICOT, PEO, SPIDER, or a different structure based on the project goal, data source, design, and outcome.

### 4. Study Design Assistant

Suggests feasible study designs based on the client’s timeline, available data, population, outcomes, and research objective.

### 5. Protocol Assistant

Drafts structured protocol sections, including title, background outline, objectives, methods, variables, ethics considerations, and timeline.

### 6. Data Collection Assistant

Creates variable lists, data dictionaries, coding rules, case report form structures, and data quality checks.

### 7. Statistical Planning Assistant

Drafts a statistical analysis plan outline that matches the study design, outcome types, variables, and planned comparisons.

### 8. Quality Reviewer

Checks consistency across the research question, protocol, outcomes, data dictionary, visit schedule, and statistical analysis plan.

## First Internal Workflow

1. Client completes an intake form.
2. Intake Assistant summarizes the project and missing information.
3. Research Question Assistant creates a structured draft question.
4. Framework Selection Assistant confirms PICOT, PEO, SPIDER, or another framework.
5. Consultant reviews and approves direction.
6. Specialized assistants draft requested deliverables.
7. Quality Reviewer flags inconsistencies and missing details.
8. Consultant edits, approves, and delivers final documents.
9. Final outputs are stored as reusable examples and templates.

## Minimum Tool Stack

- Intake form: Tally, Typeform, Google Forms, or similar.
- Project tracker: Notion, Airtable, Trello, or ClickUp.
- Document production: Google Docs, Microsoft Word, Excel, and PDF export.
- AI workspace: Custom GPT, OpenAI API prototype, or private prompt library.
- File storage: Google Drive, Dropbox, or OneDrive.
- Brand assets: CRC logo, navy/teal palette, watermark, and branded document footer.

## Prompt Library to Build First

- Intake summary prompt.
- Research question refinement prompt.
- PICOT builder prompt.
- PEO builder prompt.
- SPIDER builder prompt.
- Common mistakes reviewer prompt.
- Study design recommendation prompt.
- Data element extraction prompt.
- Statistical analysis plan outline prompt.
- Quality and consistency reviewer prompt.

## Safety Rules

- Do not promise IRB approval, publication, or guaranteed statistical significance.
- Do not fabricate references or institutional requirements.
- Do not process identifiable patient data unless proper institutional, legal, and privacy protections are in place.
- Mark AI-generated deliverables as drafts requiring expert and institutional review.
- Keep assumptions visible in every output.
- Use the calm, precise, clinically grounded Clinical Research Compass voice.
