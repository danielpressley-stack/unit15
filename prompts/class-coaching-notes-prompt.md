# General Coaching Notes Prompt Template

## Purpose
Generate a full coach-led class plan that includes timeline, warm-up, skill/strength progressions, movement coaching cues, scaling, safety, and post-class recovery notes.

## Sources to consult
- `crossfit-class-planning-guide.md` for class timing, structure, and coach-led requirements.
- `unit15/class-plans/Temp/CF-Coaching Fundamentals.pdf` for movement teaching, seeing/correcting, scaling, and coaching drills.
- Example note format: `unit15/class-plans/2026-05-15-snatch-cycling.md`.

## Key instruction
Do not limit the plan to the primary movement only. Include:
- coach-led introduction and whiteboard messaging,
- general warm-up,
- specific movement progressions and cues for the day’s main focus plus supporting movements,
- logistics and floor setup,
- the WOD and coach guidance,
- scaling options for Beginners, Intermediate, Advanced, and Injured athletes,
- cool-down and recovery notes,
- safety and equipment reminders.

## Warm-up structure guidance
Use one of two warm-up templates:
- Typical warm-up: `400m run or 20-16 cals on a C2 machine`, then `2RFQ` (two rounds for quality), then `4-5 activation movements`. **For each movement in 2RFQ, allow 30 seconds per movement.** For movements like arm circles, 30 seconds represents the total time in both directions combined (e.g., 15 seconds forward, 15 seconds backward).
- Shortened warm-up: a `6-7 minute AMRAP` built from `10/8 calories` plus `3-4 movements` from the activation list. This AMRAP should be structured as a repeating sequence of four movements (one calorie effort and three activations), for example: good mornings, air squats, wall ball slams, and calories.

Straddle side leans and World's Greatest Stretch should be treated as posterior chain activations.

## Coaching Language Guidelines
When providing coaching cues, prioritize **clarity and accessibility**:
- **Avoid jargon and anatomy terms.** Most athletes will not understand or feel technical terms like "scapula," "thoracic spine," or "packed shoulders."
- **Use concrete, observable language:**
	- Instead of "shoulders are packed" → "shoulders are strong and tight" or "shoulders are locked in place"
	- Instead of "feel the stability in your scapula" → "feel strong overhead" or "keep your shoulders strong"
	- Instead of "triple extension" → "drive your hips, knees, and ankles hard"
	- Instead of "lumbar rounding" → "keep your back straight" or "maintain a flat back"
- **Focus on what athletes should do (action-oriented)** rather than anatomical position.
- **Use short, punchy cues** during high-intensity moments; save detailed instruction for load-building phases.

## Input Fields
- Date:
- Class name or focus:
- Primary movement focus:
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
6. Movement coaching progressions and cues
7. WOD description and coach guidance
8. Scaling options
9. Cool-down and post-class notes
10. Safety and layout reminders

## Example assistant prompt
"Use the CrossFit planning guide and attached Coaching Fundamentals guide to produce a 60-minute coach-led class plan with timeline, movement teaching cues, scaling, and safety notes. Save the output in the `unit15/class-plans/` style."
