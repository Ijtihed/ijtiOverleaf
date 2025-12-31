# IjtiResumeTemplate

A clean resume (overleaf recommended) template with customizable sections.

## How to Use

1. **Upload to Overleaf**: Copy `main.tex` into a new Overleaf project
2. **Edit Personal Info**: Update the variables in the "EDIT THESE" section (lines 110-118):
   - Name, portfolio, phone, email, LinkedIn, GitHub
3. **Toggle Sections**: Set these boolean flags to `true` or `false` (lines 21-23):
   - `includeProjects` - Show/hide Projects section
   - `includeSRS` - Show/hide Selected Research/Publications section
   - `includeRA` - Show/hide Research Assistant (or anything you want) experience
4. **Add Your Content**: Replace the example entries with your own education, experience, projects, etc.
5. **Compile**: Click "Recompile" in Overleaf to generate your PDF

## Info

- If you get a "Runaway argument" error, check for accidentally commented closing braces (`}`)
- Copy existing entry blocks and modify them to add new items
- The template uses standard LaTeX packages available on Overleaf
