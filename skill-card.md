## Description: <br>
Calculates lunar phases, Moon transits, personal solar-lunar phases, lunar days, Moon speed, illumination, perigee/apogee context, natal aspects, text analysis, JSON output, and a two-wheel lunar chart using Swiss Ephemeris. <br>

This skill is ready for commercial/non-commercial use. <br>

## Publisher: <br>
[dynamicsalex](https://clawhub.ai/user/dynamicsalex) <br>

### License/Terms of Use: <br>
MIT-0 <br>


## Use Case: <br>
Developers and OpenClaw agents use this skill to generate bilingual lunar astrology analysis from birth details and a target date, then optionally render a PNG chart with an AI-authored conclusion. The artifact states the output is for entertainment and education, not scientific, medical, or financial decision-making. <br>

### Deployment Geography for Use: <br>
Global <br>

## Known Risks and Mitigations: <br>
Risk: The skill materializes a bundled native Windows Swiss Ephemeris extension from a .dat file at runtime. <br>
Mitigation: Run it only in an environment where bundled native code is acceptable, and review the release security evidence before deployment. <br>
Risk: The chart renderer may install Pillow automatically if it is missing. <br>
Mitigation: Preinstall and manage the expected Pillow dependency in controlled environments before running the renderer. <br>
Risk: Astrology interpretations can be mistaken for decision support. <br>
Mitigation: Present results as entertainment or educational context and avoid using them for medical, financial, safety, or other consequential decisions. <br>


## Reference(s): <br>
- [ClawHub skill page](https://clawhub.ai/dynamicsalex/astro-lunar-insights) <br>
- [Publisher profile](https://clawhub.ai/user/dynamicsalex) <br>
- [Project homepage from skill metadata](https://github.com/dynamicsAlex/astro-lunar-insights) <br>


## Skill Output: <br>
**Output Type(s):** [text, JSON, image files, shell commands, guidance] <br>
**Output Format:** [Plain text reports, JSON data, PNG charts, and Markdown usage guidance with bash command examples] <br>
**Output Parameters:** [1D] <br>
**Other Properties Related to Output:** [Supports Russian and English output; --output writes UTF-8 JSON directly to a file; draw_lunar.py can consume an AI-generated conclusion JSON file.] <br>

## Skill Version(s): <br>
1.0.1 (source: frontmatter and server release evidence, released 2026-06-05) <br>

## Ethical Considerations: <br>
Users should evaluate whether this skill is appropriate for their environment, review any generated or modified files before relying on them, and apply their organization's safety, security, and compliance requirements before deployment. <br>
