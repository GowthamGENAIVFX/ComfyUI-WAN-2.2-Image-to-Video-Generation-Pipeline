# Workflow Optimization Notes

## Objective

Generate smooth cinematic video while maintaining character consistency.

---

# Experiment 1

## Duration

3 Seconds

### Result

Fast generation.

Suitable for social media clips.

---

# Experiment 2

## Duration

5 Seconds

### Result

Best balance.

Recommended setting.

---

# Experiment 3

## Duration

8 Seconds

### Result

Higher compute requirements.

Occasional temporal drift.

---

# Experiment 4

## CFG

5

Result:

Weak prompt adherence.

---

## CFG

7

Result:

Best quality.

---

## CFG

10

Result:

Over-constrained motion.

---

# Experiment 5

## LoRA Strength

0.6

Result:

Subtle enhancement.

---

## LoRA Strength

1.0

Result:

Best visual quality.

---

# Recommended Settings

Width: 480

Height: 832

Duration: 3–5 Seconds

FPS: 16

CFG: 6–7

Steps: 6

---

# Key Learnings

* Motion prompts strongly influence results.
* Longer clips require additional refinement.
* Two-stage sampling improves stability.
* WAN 2.2 produces consistent motion with proper prompting.

---

# Production Applications

* AI Commercials
* Social Media Videos
* Character Animation
* Marketing Content
* Storytelling Pipelines
* AI Film Previsualization

---

# Conclusion

This workflow demonstrates a complete image-to-video production pipeline using WAN 2.2 within ComfyUI.
