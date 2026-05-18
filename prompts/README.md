# Prompt Templates for CrossFit Class Planning

This folder contains prompt templates and instructions for working with the CrossFit class planning system.

## Purpose
When you ask GitHub Copilot to create a class timeline, the assistant should:
- consult `crossfit-class-planning-guide.md` for structure and rules,
- use the provided WOD and class details,
- produce a 60-minute, coach-led timeline,
- include warm-up, skill work, logistics, workout execution, scaling, and cool-down guidance.

## Recommended workflow
1. Open `prompts/class-timeline-prompt.md` or `prompts/class-coaching-notes-prompt.md`.
2. Replace the example inputs with your class-specific information.
3. Ask the assistant to generate the class timeline and coaching notes using that prompt.
4. Save the result under `unit15/class-plans/` using the filename convention `YYYY-MM-DD - <Primary Movement>.md`.
   - In the timeline block, end each line with two spaces so markdown renders a line break.
   - Do not include a separate "workout end" time if the cool-down begins immediately after the WOD.
5. Keep the guide and prompt files updated as your planning process evolves.

## File naming and note style
- Use `YYYY-MM-DD - <Principal Movement>.md` for class notes, where the principal movement is the "meat of the sandwich."
- Use the example file `unit15/class-plans/2026-05-15-snatch-cycling.md` as the model for formatting.
- Include a top-level date heading, timeline block, warm-up section, movement-specific coaching progressions, and WOD details.
- Consult `unit15/class-plans/Temp/CF-Coaching Fundamentals.pdf` for teaching cues, fault correction, scaling options, and coaching drills.- Warm-ups should usually be:
  - `400m run or 20-16 cals C2`, then `2RFQ`, then `4-5 activation movements`.
  - If time is limited, use a `6-7 minute AMRAP` containing `10/8 calories` plus `3-4 movements`, cycling through all four movements repeatedly.
- Classify `Straddle side leans` and `World’s Greatest Stretch` as posterior chain activations.