# Prompts
> We can use the following prompts as referenece but it can be improved 

## How to Use These Prompts Effectively:
1. Start with the comprehensive prompt to get the full tutorial structure
2. Follow up with specific module prompts for areas needing deeper explanation
3. Use the quick-reference prompt for creating practical job aids
4. Request updates with: "Add recent developments in [specific area] since 2023"

For maximum effectiveness, add these specifics to your prompt:
- Your current implant system preferences (Nobel, Straumann, Zimmer, etc.)
- Your CBCT machine model
- Your 3D printer model (if applicable)
- Your typical case complexity level
- Any specific anatomical challenges you frequently encounter

Example enhanced prompt:

```
[Use comprehensive prompt above] + 

ADDITIONAL CONTEXT:
- I primarily use Straumann BLT implants
- My CBCT is a Carestream CS 9300
- I plan to 3D print guides in-house using Formlabs Dental SG resin
- Most cases are single-tooth replacements in posterior regions
- I frequently encounter narrow ridges requiring bone width assessment

PRIORITIZE:
1. Nerve tracing accuracy in posterior mandible
2. Guide stability for posterior single teeth
3. Integration with my specific CBCT's DICOM format
4. Time-efficient workflows for busy practice
```




















## Prompt 1
Create a comprehensive, module-based tutorial for coDiagnostiX implant planning software from Dental Wings. Structure the tutorial for a dentist with basic implant knowledge transitioning to digital planning. Each module must include: clinical rationale for each feature, surgical purpose of tools, detailed step-by-step instructions with explanations, and practical applications.

**FORMAT REQUIREMENTS:**
1. Use Markdown formatting with clear headers
2. Include tables for comparison when appropriate
3. Use bullet points for step-by-step instructions
4. Include clinical significance sections
5. Provide YouTube/online resource links for each major section
6. Include troubleshooting tips
7. Add surgeon's notes with clinical pearls

**RESOURCE INTEGRATION:**
For each module, include:
- 2-3 relevant YouTube tutorial links (with timestamps if possible)
- Official documentation links
- Scientific references supporting digital planning accuracy
- Case study examples

**SPECIFIC CONTENT REQUESTS:**

**MODULE 1: SOFTWARE FOUNDATIONS & INTERFACE MASTERY**
- Explain the purpose of each viewport (axial, coronal, sagittal, 3D) in clinical decision-making
- Detail how to customize workspace for different case types (single vs full-arch)
- Include DICOM import settings and their impact on planning accuracy
- Provide calibration procedures with clinical significance of each step

**MODULE 2: ANATOMICAL ANALYSIS WORKFLOW**
- Step-by-step nerve tracing with explanation of mental foramen anterior loop identification
- Sinus floor mapping techniques and clinical implications
- Bone density assessment tools and correlation with primary stability
- Safety margin settings and evidence-based distances for different anatomical structures

**MODULE 3: IMPLANT SELECTION & VIRTUAL PLACEMENT**
- Protocol for choosing implant diameter based on available bone (with decision trees)
- Length selection algorithms considering bone quality and crown-to-implant ratios
- Angulation correction methods and abutment selection
- Immediate placement in extraction sockets protocol

**MODULE 4: PROSTHETIC-DRIVEN PLANNING**
- Import methods for diagnostic wax-ups and intraoral scans
- Dynamic occlusal analysis integration
- Screw-access channel optimization techniques
- Cantilever calculation and biomechanical analysis tools

**MODULE 5: SURGICAL GUIDE DESIGN DEEP DIVE**
- Comparison of mucosa-supported, tooth-supported, and bone-supported guides
- Step-by-step sleeve placement with drill sequence considerations
- Anchor pin positioning strategies for stability
- Guide thickness optimization for accuracy vs. flexibility

**MODULE 6: ADVANCED TECHNIQUES**
- All-on-4/6 planning with tilted implant protocols
- Zygomatic implant trajectory planning
- Virtual bone grafting and sinus lift simulation
- Guided immediate loading protocols

**MODULE 7: EXPORT & MANUFACTURING**
- 3D printing settings for different guide materials
- Quality control protocols for guide verification
- Surgical report generation with critical information inclusion
- Communication protocols with dental laboratories

**MODULE 8: CLINICAL INTEGRATION**
- Pre-surgical verification checklist
- Guided surgery kit preparation
- Intraoperative troubleshooting guide
- Post-operative documentation and follow-up planning

**FOR EACH STEP WITHIN MODULES, INCLUDE:**
1. **Software Action**: Exact buttons/clicks/menu paths
2. **Clinical Purpose**: Why this step matters surgically
3. **Parameter Settings**: Recommended values with rationale
4. **Common Errors**: What can go wrong and how to prevent
5. **Validation Method**: How to verify the step was done correctly
6. **Time Estimation**: How long this should take

**ADDITIONAL REQUESTS:**
- Create comparison tables for different implant systems in coDiagnostiX
- Include workflow diagrams for different case complexities
- Provide downloadable checklist templates
- List keyboard shortcuts and efficiency tips
- Include a "Proficiency Assessment" quiz for each module
- Add a "Case Difficulty Rating" system with corresponding planning times

**REFERENCES & LINKS:**
Please include for each major topic:
- YouTube surgical procedure demonstrations
- coDiagnostiX official training videos
- Peer-reviewed articles on guided surgery accuracy
- Manufacturer guidelines for specific implant systems
- Online forums or user groups for troubleshooting

**OUTPUT FORMAT:**
Begin with a summary table of modules with estimated learning time. End with a competency checklist for self-assessment. Include practical exercises for each module with sample DICOM datasets available online.


## Alternative Prompt for Specific Focus Areas
> If you want to focus on particular aspects, use this modular prompt:

I need a detailed tutorial on [SPECIFIC MODULE OR FEATURE] in coDiagnostiX software. Focus on:

**CLINICAL CONTEXT:**
- Case type: [Single tooth, Partial edentulism, Full arch]
- Patient factors: [Bone quality, Anatomical challenges, Prosthetic requirements]
- Surgical approach: [Guided flap, Flapless, Immediate load]

**SOFTWARE WORKFLOW:**
1. Starting point: [What should be completed before this module]
2. Step-by-step instructions with:
   - Exact menu navigation paths
   - Screenshot descriptions (even if you can't show images, describe what should be visible)
   - Parameter settings with clinical rationale
   - Common pitfalls and avoidance strategies
3. End point: [What should be achieved upon completion]

**SURGICAL RELEVANCE:**
For each software feature, explain:
- How this translates to surgical outcomes
- Accuracy considerations (deviation rates from planning)
- Time savings in surgery
- Risk reduction benefits

**VALIDATION PROTOCOLS:**
- How to verify planning accuracy
- Cross-referencing methods with traditional planning
- Pre-surgical checklist items specific to this module

**INTEGRATION WITH OTHER SYSTEMS:**
- Compatibility with specific CBCT machines
- Export formats for different guide manufacturing methods
- Communication protocols with referring dentists/labs

**TROUBLESHOOTING SECTION:**
- List 5 most common problems in this module
- Step-by-step solutions for each
- When to contact technical support vs. user error

**RESOURCES:**
Provide:
- 3 YouTube tutorials demonstrating this specific feature
- 2 scientific papers supporting the clinical efficacy
- 1 case study with before/after results
- Links to relevant coDiagnostiX user manual sections

**PRACTICAL EXERCISE:**
Describe a hands-on exercise using sample data including:
- Expected outcomes
- Common mistakes to watch for
- Success criteria

Please structure the response with clear headings, comparison tables where applicable, and clinical pearl boxes highlighting important considerations.

## Prompt for Quick Reference Guides

Create a quick-reference "cheat sheet" for coDiagnostiX software with the following sections:

**SECTION 1: ESSENTIAL KEYBOARD SHORTCUTS**
- Navigation shortcuts (zoom, pan, rotate)
- Measurement tools quick access
- View switching shortcuts
- Planning element manipulation

**SECTION 2: CLINICAL PARAMETER DEFAULTS**
- Safety margins for anatomical structures (nerve, sinus, adjacent teeth)
- Minimum bone requirements for different implant diameters
- Recommended implant distribution patterns for various edentulous situations
- Guide design specifications (thickness, sleeve heights, support requirements)

**SECTION 3: TROUBLESHOOTING FLOWCHARTS**
- DICOM import problems → solutions
- Guide design errors → corrections
- Implant placement conflicts → resolution strategies
- Export/printing issues → fixes

**SECTION 4: CASE COMPLEXITY CHECKLISTS**
- Simple case requirements and planning steps
- Moderate complexity additions
- Advanced case considerations
- Red flags requiring expert consultation

**SECTION 5: SURGICAL PREPARATION TIMELINE**
- 2 weeks before surgery: Planning completion checklist
- 1 week before: Guide manufacturing and verification
- Day before: Surgical kit preparation
- Day of: Pre-op software review protocol

**FORMAT:**
Use tables, bullet points, and icons/emojis for visual organization. Each item should include:
- Software action
- Clinical purpose
- Time estimate
- Priority level (High/Medium/Low)

Include QR codes or shortened links to:
- Official coDiagnostiX YouTube channel
- Sample DICOM datasets for practice
- Troubleshooting forums
- Technical support contact information



