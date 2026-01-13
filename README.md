# Netflix Campaign Visual Generator

This project delivers a web-based image generation platform designed to support digital marketing and key-art ideation for high-profile entertainment campaigns, such as those produced for Netflix by integrating Open’s image generation capabilities with a Gradio-powered web interface to transform structured creative inputs into visually compelling concept artwork.

## Core Objectives and Achievements

### 1. Prompt-to-Image Generation
The platform implements AI-based image generation using OpenAI’s Images API in a legacy-compatible configuration. Image generation is standardized at a supported resolution to ensure reliability and prevent API errors in restricted execution environments.

### 2. Structured Creative Inputs
The user interface separates creative intent into two distinct inputs: the show or movie title and the creative concept. These inputs are programmatically combined into a single, well-structured prompt optimized for cinematic, streaming-platform-style key art.

### 3. Batch Generation Capability
The system supports batch image generation, allowing multiple visual variations to be produced from a single prompt. This enables rapid exploration of creative directions while maintaining guardrails on batch size to manage performance and API usage.

### 4. Gallery-Based Output
Generated images are displayed using a gallery-style layout within the Gradio interface. This presentation supports side-by-side comparison and aligns with real-world creative review and campaign ideation workflows.

### 5. Robust Error Handling
Defensive programming techniques were implemented to handle invalid inputs, and API-level errors gracefully. User-friendly error messages are surfaced directly in the interface rather than exposing raw execution traces.

### 6. Environment-Aware Engineering
The solution was adapted to operate within a constrained platform environment, accounting for limited package versions, restricted network access, and legacy SDK constraints. Conditional dependency handling and compatibility strategies were applied to ensure stability and portability.

### 7. User Experience Enhancements
The Gradio interface was refined to maximize visible workspace, reduce unnecessary scrolling, and emphasize generated imagery. Defaults and layout choices were tuned specifically for marketing and creative review use cases.

## Outcome
The final system functions as a creative concept generator rather than a simple image tool. It enables designers, marketers, and creative teams to rapidly iterate on visual ideas, explore multiple campaign directions, and generate consistent, high-quality concept imagery suitable for banners, posters, and promotional assets. The project demonstrates a practical application of generative AI, UI design, and production-aware engineering in a real-world creative workflow.
