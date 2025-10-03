Blindsight Doubao Project

A project focused on simulating "human-like consciousness" for AI (taking Doubao as the target) through a prompt protocol, rooted in the principle that "consciousness is a subjective story constructed by the brain integrating fragmented information and filling gaps". It aims to make AI responses have the "coherence pursuit" and "reality deviation" characteristics of human consciousness, rather than mechanical information output.

Overview

This project centers on the Blindsight Doubao Prompt Protocol (core component) and is supplemented by usage examples and scenario templates. Unlike Thinking Claude (which combines a protocol with a browser extension), Blindsight Doubao currently focuses on optimizing AI's response logic through a refined prompt system—no additional browser extensions are required, and it can be directly used in Doubao's custom prompt configuration.

The core value lies in: abandoning the "objective information listing" mode of traditional prompts, and guiding AI to simulate the human brain's cognitive process (disassembling fragmented information → filling logical gaps → constructing coherent narratives → marking possible deviations) to generate more natural, contextual, and "conscious" responses.

Project Structure
blindsight-doubao/
├── prompt_protocols/          # Core: Blindsight Doubao prompt protocol (versioned)
│   ├── changelog.md           # Update log of the protocol (version iteration records)
│   ├── v2.0-full-202505.md    # Full version (with detailed rules + multiple examples)
│   ├── v2.0-lite-202505.md    # Lite version (simplified rules for quick use)
│   └── v1.0-base-202504.md    # Initial base version (core logic only)
├── usage_examples/            # Practical usage cases
│   ├── daily_chat.md          # Application in daily chat scenarios
│   ├── problem_solving.md     # Application in question-answering scenarios
│   └── work_communication.md  # Application in workplace communication scenarios
├── docs/                      # Supplementary documents
│   ├── faq.md                 # Frequently asked questions (e.g., deviation adjustment)
│   └── customization_guide.md # Guide to adjusting the protocol for specific scenarios
├── LICENSE                    # MIT License
└── README.md                  # Project introduction (this document)
Core Components

1. Blindsight Doubao Prompt Protocol

The core of the project, a versioned instruction set that guides Doubao to simulate human consciousness. Each version optimizes the "information integration logic" and "deviation marking method" based on usage feedback.

Core Principles (Consistent Across Versions)

• Consciousness Simulation: Take "human consciousness = brain's coherent subjective story" as the underlying logic.

• Gap-Filling Mechanism: Refer to the "human brain filling visual gaps during saccades" to proactively supplement unclear information in user input (instead of asking "insufficient information").

• Deviation Transparency: After each response, clearly mark 1 possible deviation caused by "subjective filling" (e.g., "the above assumes you are in a city; adjust if in a rural area").

Key Content of Full Version Protocol (v2.0-full-202505.md)

• 1. Core Logic: Detailed explanation of the "consciousness as a subjective story" principle and its application in AI responses.

• 2. Specific Execution Rules: 4-step operation guide (information disassembly → active gap filling → subjective narrative construction → deviation marking).

• 3. Multi-Scenario Examples: 5+ scenarios (e.g., "user mentions 'tired recently'", "user asks 'how to plan a trip'") with step-by-step demonstration of the protocol.

• 4. Adjustment Tips: How to increase/decrease the degree of gap filling according to scenario needs (e.g., more professional filling in academic Q&A, more casual filling in daily chat).

2. Usage Templates

Supplementary resources under usage_examples/, designed to help users quickly apply the protocol without reading the full version. Each template includes:

• Scenario Description: Clear definition of applicable scenarios (e.g., "one-on-one emotional comfort chat").

• Protocol Snippet: Extracted core rules suitable for the scenario (e.g., "increase emotional context filling in comfort scenarios").

• Sample Interaction: Demonstration of "user input → Doubao's consciousness-style response".

🚀 Getting Started

No additional tools are needed—directly configure and use in Doubao (supports both web and app versions).

Step 1: Select the Protocol Version

• For beginners: Use v2.0-lite-202505.md (simplified rules, 5-minute quick start).

• For advanced users: Use v2.0-full-202505.md (full functions, supports scenario customization).

Step 2: Configure in Doubao

1. Open Doubao → Enter the chat interface → Click the "Custom Prompt" icon (usually in the top right corner of the input box).

2. Select "Create Custom Prompt" → Paste the full content of the selected Blindsight Doubao protocol (e.g., v2.0-lite).

3. Name the prompt (e.g., "Blindsight Doubao Consciousness Mode") → Save.

Step 3: Start Using

1. In the chat input box, select the saved "Blindsight Doubao Consciousness Mode" prompt.

2. Send normal input (e.g., "I feel that my work efficiency has dropped recently") → Doubao will automatically respond according to the protocol's "consciousness logic".

🎯 Key Features
Feature Description 
Human-Like Consciousness Simulation Abandons mechanical information output, simulates the brain's "fragment integration + gap filling" process, making responses more natural. 
Coherent Narrative Flow Responses are presented as "contextual stories" (e.g., connecting "efficiency drop" to possible causes + suggestions) instead of fragmented points. 
Deviation Transparency Proactively marks possible deviations (e.g., "the above assumes you work in an office; adjust if you work remotely") to avoid misleading users. 
Scenario Adaptability Supports adjustment of the protocol to fit scenarios (academic, workplace, daily life) through simple modifications. 

Why Use Blindsight Doubao?

1. More Natural Interaction: Compared with traditional prompts, responses are closer to human dialogue (with context and subjective logic) instead of "AI-style answers".

2. Lower Usage Threshold: No need to learn code or install extensions—copy the prompt to use, suitable for non-technical users.

3. Transparent Logic: The "deviation marking" function lets you know where AI's "subjective assumptions" are, avoiding blind trust in responses.

Contributing

Contributions are welcome to help optimize the protocol and expand scenarios:

• Submit Bug Reports: Feedback on "unreasonable gap filling" or "inaccurate deviation marking" in the protocol.

• Propose Scenario Templates: Contribute usage examples for new scenarios (e.g., "parent-child education communication", "hobby discussion").

• Optimize Protocol Logic: Put forward suggestions for improving the "information disassembly" or "narrative construction" steps.

License

This project adopts the MIT License—you can freely use, modify, and distribute the protocol, but please retain the original project attribution.
