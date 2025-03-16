# CLAUDE.md - Prisma Vault Guidelines

## About This Project
- This is a text-based project management system for series development
- Used for organizing series bible, production notes, and development materials
- Built for use with Obsidian.md and Massive Wiki
- All content is organized hierarchically with numbered prefixes

## File Structure
- `00-Project-Management/`: System documentation and operational files
- `10-Series-Bible/`: Core canonical content 
- `20-Development/`: Work in progress materials
- `30-Production/`: Active production materials
- `40-Research/`: Background and reference materials
- `50-Team/`: Team-specific resources
- `60-Maps/`: Visual organization tools
- `99-Templates/`: Standard templates for consistency

## Tagging System
Use the standard tags from `00-Project-Management/System-Guide/02-Tags.md`:
- Canon status tags: `#canon/core`, `#canon/soft`, etc.
- Document purpose tags: `#doc/bible`, `#doc/guide`, etc.
- Project management tags: `#pm/todo`, `#pm/meeting`, etc.
- Development stage tags: `#stage/concept`, `#stage/draft`, etc.
- Content type tags: `#type/worldbuild`, `#type/character`, etc.

## Writing Logs
- All writing logs are stored in `00-Project-Management/Writing-Logs/`
- Filename format: `YYYY-MM-DD-[Writer/Team]-Log.md`
- Use the template from `99-Templates/Writing-Log-Template.md`
- Include appropriate tags and links to related content

## File Naming Conventions
- Use hyphens (-) for spaces in filenames
- Keep names clear and descriptive
- Use consistent naming patterns within sections
- Maximum depth: 3-4 levels to prevent complexity
- Link related documents using the double-square-bracket `[[Page Name]]` wikilink convention

## Content Creation Guidelines
1. Use existing templates from `99-Templates/` when creating new content
2. Create new templates in 99-Templates/ as necessary
3. Follow the established tagging system to maintain organization
4. Create links between related documents
5. Keep files organized according to their purpose and stage
6. Update relevant indices or maps when adding new content
7. For writing logs, follow the workflow in `00-Project-Management/System-Guide/03-Workflows.md`

## Workflow Commands
- No specific build, test, or lint commands (text-based project)
- Use Obsidian or text editors to create and edit content
- Git commands for version control:
  - `git status`: Check changes
  - `git add [files]`: Stage changes
  - `git commit -m "message"`: Commit changes
  - `git push`: Push to remote repository (if using Git for team collaboration)

## Style Preferences
- Use Markdown formatting
- Create clear hierarchical structure with headings
- Use bullet points for lists
- Link related documents liberally
- Tag documents according to the established system
- Use the numeric prefixing system for new folders
- Follow established workflows for updating content