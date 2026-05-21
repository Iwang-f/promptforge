---
name: script-shotlist
description: Convert a video ad concept into a production-ready 6-shot script
  and shot list. Use after concept-generator to turn a chosen concept into a
    cinematic shot-by-shot breakdown ready for AI video generation.
    ---

    # 🎬 Script & Shot List Generator

    Transform a video ad concept into a **precise 6-shot cinematic sequence** with timing, visual direction, and on-screen text — ready for Veo 3.1 or Seedance 2.0.

    ## When to use

    - User has chosen a concept from `01-concept-generator`
    - User needs a production-ready shot breakdown
    - User wants to feed structured prompts into AI video tools

    ## Workflow

    1. **Intake:** Receive from user (or from concept-generator output):
       - Chosen concept (A/B/C) + hook sentence
          - Product name + key visual asset
             - Target duration (15s / 30s / 60s)
                - Brand tone

                2. **Generate 6-shot structure:**
                   - **Shot 1 — Hook** (0-3s): Pattern interrupt
                      - **Shot 2 — Setup** (3-8s): Context / problem
                         - **Shot 3 — Product reveal** (8-15s): Visual focus on product
                            - **Shot 4 — Benefit demo** (15-22s): Show transformation
                               - **Shot 5 — Social proof** (22-27s): Testimonial / result
                                  - **Shot 6 — CTA** (27-30s): Clear next action

                                  3. **For each shot, specify:**
                                     - Visual description (1-2 sentences)
                                        - Camera movement (static / pan / push-in / tracking)
                                           - Lighting mood
                                              - On-screen text (if any)
                                                 - Duration in seconds

                                                 ## Output format

                                                 A markdown table with all 6 shots, ready to be parsed by the next skill in the chain (`03-keyframe-prompt`).

                                                 ## Notes

                                                 - Total duration must match target length
                                                 - Avoid jump cuts that disorient viewers
                                                 - Each shot must visually connect to the next
                                                 
