#instant-startup-validator

Instant Startup Validator — A multimodal AI tool that analyzes any business idea using text and images. Generates full startup reports including viability score, brand identity, market analysis, unit economics, profit forecasts, landing page mockups, and smart recommendations.

Instant Startup Validator
Powered by Gemini 3 Pro

The Instant Startup Validator is a multimodal AI system built using Google AI Studio. It converts any business idea—provided as text or image—into an investor-ready validation report within seconds. This project was developed as part of the Google DeepMind Hackathon.

Overview

This application analyzes early-stage startup ideas and provides comprehensive insights using Gemini 3 Pro’s multimodal reasoning capabilities. The model evaluates the idea, interprets uploaded images, and produces structured outputs required for founders, investors, and accelerators.

Key Features

Idea summary (1–2 sentences)
Viability score (0–100) with reasoning
Brand identity package (name, taglines, color palette, logo concept)
Visual prototype guidance (including landing page HTML snippet)
Market and competitor analysis
Unique Selling Points (USP Engine)
Customer persona simulation (3 personas with purchase likelihood)
SWOT analysis
Risk map with mitigation strategies
Six-month product roadmap
Founder-ready 60-second pitch script
Social media bios and tagline suggestions
Smart recommendations (top 5 priority actions)
Multi-idea comparison mode
Image-based analysis integrated across all sections

Tech Stack

| Component               | Technology            |
| ----------------------- | --------------------- |
| Multimodal AI Model     | Gemini 3 Pro          |
| Development Environment | Google AI Studio      |
| Exported Code           | TypeScript, HTML, CSS |
| Prototype Rendering     | landing_preview.html  |
| Version Control         | GitHub                |

Repository Contents

instant-startup-validator/
│
├── landing_preview.html                 # Exported visual landing page prototype
├── system_prompt.txt                    # Complete system prompt used in AI Studio
├── /screenshots                         # Screenshots of overview, financials, and landing UI
├── README.md                            # Project documentation
├── instant-startup-validator.v1.0.zip   # Downloadable complete project bundle
└── source code (zip/tar.gz)             # Auto-generated GitHub source exports

How to Use

1.Download the ZIP file from the repository’s "Assets" section.
2.Extract the folder and open landing_preview.html in any browser to view the interface prototype.
3.Review system_prompt.txt to understand and reproduce the AI behavior.
4.Use the exported code from Google AI Studio to extend or redeploy the application.

System Prompt Summary

The system prompt used in this project defines a multimodal startup analysis agent. It ensures every output includes idea summaries, scores, branding, financial insights, visuals, persona simulation, risk analysis, pitch scripts, and action recommendations. The prompt also includes specific handling rules for image uploads and multi-idea comparison.

The full prompt is available in system_prompt.txt

Why This Project Is Significant

Demonstrates a practical business-oriented use case for multimodal AI.
Produces investor-quality reports within seconds.
Combines market research, financial modeling, branding, and UI/UX generation.
Shows real-world applications of reasoning, interpretation, and structured generation.
Offers a reproducible framework for startup accelerators and founders.

Team Members

Sharu Nethra R
Lead Developer & Multimodal Agent Engineer
Email: sharunethra18@gmail.com

Sharmishthaa R
UX Research & Business Analysis

Both team members contributed to concept development, prompt engineering, evaluation, testing, documentation, and project presentation.

Project Links

GitHub Repository: https://github.com/Sharunethra/instant-startup-validator
Kaggle Writeup: 
Demo Video: 

License

This project is released under the MIT License.

Acknowledgements

Google DeepMind and Google AI Studio
Gemini 3 Pro for enabling advanced multimodal reasoning
Hackathon organizers and mentors
