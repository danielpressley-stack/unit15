# Class Timeline Prompt Template

## Instructions for the AI assistant
Use the information in `crossfit-class-planning-guide.md` as the primary reference for structuring the class timeline. The class must be exactly 60 minutes long, coach-led, and should include a clear Introduction, General Warm-Up, Specific Warm-Up / Skill Work, Break & Logistics, Workout, and Post-Workout / Cool-Down.

When generating the timeline, include:
- exact time blocks for each section,
- coach coaching cues,
- scaling options for Beginners/Deconditioned, Intermediate, Advanced, and Injured athletes,
- heavy day constraints if applicable,
- safety and floor layout reminders.

## Input Fields
- Date: 
- Class name or focus:
- Primary movement focus (meat of the sandwich):
- WOD format and details:
- Intended stimulus / time domain:
- Equipment available:
- Athlete profile summary:
- Notes / special focus:

## Output Format
1. Suggested filename in the form `YYYY-MM-DD - <Primary Movement>.md`
2. Top-level date heading
3. Timeline (with times; each timeline line should end with two spaces for markdown line breaks; do not include a separate workout end time)
4. Class Overview
5. Warm-Up plan
6. Skill / Strength work and movement progressions
7. Notes / coaching cues
8. WOD description and coach guidance
9. Scaling options
10. Cool-down and post-class notes
11. Safety and layout reminders

## Formatting guidance
Use the example note layout from `unit15/class-plans/2026-05-15 - Snatch.md`. Include a date header, a timeline block, section headings for warm-up and movement work, bullet points or numbered coaching cues, and a concise WOD block.

## Warm-up guidance
If the schedule allows, use the typical warm-up structure: `400m run or 20-16 cals C2`, `2RFQ`, then `4-5 activation movements`.
If time is tight, use a `6-7 minute AMRAP` warm-up with `10/8 calories` plus `3-4 movements` from the activation list, cycling through all four movements until time expires.
Straddle side leans and World’s Greatest Stretch should be categorized as posterior chain activation.

## Example request
- Date: 18 May 2026
- Class name: Power Snatch + Conditioning
- WOD: 100 power snatches (25/35kg) for time with 12-minute cap
- Intended stimulus: Strength-endurance, power, maintenance of mechanics under fatigue
- Equipment: barbells, bumper plates, pull-up rig, wall balls, rowers
- Athlete profile: mixed ability, some athletes working on snatch mechanics, others needing conditioning work
- Notes: keep barbell movement quality high, use coach-led progressions, include scaling for those who need less technical load

## Example assistant prompt
"Use the CrossFit class planning guide and the inputs above to generate a 60-minute coach-led class timeline. Provide times, coaching cues, safety notes, and scaling options."
