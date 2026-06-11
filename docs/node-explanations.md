# Node Explanations

# Load WAN 2.2 Model

## Why did I use this node?

Loads the core WAN 2.2 video generation model.

### Interview Question

Why WAN 2.2?

### Answer

WAN 2.2 is designed for high-quality image-to-video generation with strong temporal consistency.

---

# Load Image

## Why did I use this node?

Provides the initial frame for video generation.

---

# Animation Prompt

## Why did I use this node?

Defines the desired motion.

Example:

"A woman stands confidently as a warm breeze moves her hair while the camera slowly pushes forward."

### Interview Question

Why are motion prompts important?

### Answer

Motion prompts guide temporal generation and determine how the scene evolves across frames.

---

# WAN ImageToVideo

## Why did I use this node?

Converts the static image into a latent video representation.

### Interview Question

What problem does Image-to-Video solve?

### Answer

It transforms static imagery into dynamic content while preserving visual identity.

---

# LoRA Loader

## Why did I use this node?

Improves visual quality and stylistic consistency.

---

# KSampler Stage 1

## Purpose

Initial motion generation.

---

# KSampler Stage 2

## Purpose

Refinement pass for improved temporal quality.

---

# VAE Decode

## Purpose

Converts latent video frames into visible images.

---

# Video Combine

## Purpose

Encodes generated frames into MP4 format.

### Interview Question

Why combine frames into video?

### Answer

Video generation produces frame sequences that must be encoded into a playable format.
