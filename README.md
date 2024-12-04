# ACE-HOLOFS Writers Assistant System for Claude Projects
https://www.youtube.com/watch?v=0fVc8wHKmcs

A comprehensive system for creative writing analysis and worldbuilding using Claude AI, implementing Adaptive Capacity Elicitation (ACE) methodology with a Holographic Filesystem (HOLOFS) simulation.


## Overview


This project provides a structured framework for:
- Processing and evaluating creative writing within custom universes
- Maintaining consistent worldbuilding across multiple documents
- Providing college-level writing analysis and feedback
- Managing dynamic document relationships and knowledge bases
- Simulating a virtual filesystem within Claude conversations


## System Components


### Core Modules
1. **ACEHOLOFS-V3**: Core cognitive processing and filesystem simulation
2. **NarrativeSpittoon**: Fiction generation and library building
3. **GhostWritingStyle**: Writing style guidelines and rewrite suggestions
4. **HolographicTutor**: Document evaluation and scoring system


### Features
- Virtual filesystem simulation within Claude conversations
- Four evaluation functions (Score, Review, Critic, Weakness)
- Dynamic document relationship mapping
- Unlimited worldbuilding document support
- Consistent writing style enforcement


## Setup Instructions


1. Clone this repository:
```bash
git clone https://github.com/mushroomfleet/tba.git
cd ace-holofs-agent
```


2. Ensure all required files are present:
```
ace-holofs-agent/
├── project-instruction/
│   └── project-instructions.txt
├── docs/
│   ├── ACEHOLOFS-V3.txt
│   ├── NarrativeSpittoon.txt
│   ├── GhostWritingStyle.txt
│   └── HolographicTutor.txt
└── input/
    └── README.md
```


3. Create your worldbuilding documents:
- Add .txt or .md files to the `input/` directory
- Follow naming convention: `topic-description.txt`
- Each file should focus on a specific aspect of your universe


4. Using with Claude:
- Start a new conversation
- Upload all files from the `docs/` directory
- Upload your worldbuilding documents from `input/`
- Upload `project-instructions.txt`
- Begin interaction with Claude


## Usage Guide


### Basic Commands
The system supports both CLI-style commands and natural language:


```bash
# List files in current directory
ls
# or
"Show me the current directory contents"


# Create a new file
touch newfile.txt
# or
"Create a new file called newfile.txt"


# Evaluate a document
review document.txt
# or
"Please review the contents of document.txt"
```


### Evaluation Functions


1. **Score** (Default)
- Provides numerical score out of 100
- Includes brief justification
```bash
score document.txt
```


2. **Review**
- Comprehensive creative writing analysis
- Academic perspective
```bash
review document.txt
```


3. **Critic**
- Publisher perspective
- Market viability analysis
```bash
critic document.txt
```


4. **Weakness**
- Identifies improvement areas
- No suggestions provided
```bash
weakness document.txt
```


## Adding Worldbuilding Documents


1. Create your document in .txt or .md format
2. Focus on a specific aspect of your universe
3. Use descriptive filenames
4. Place in the `input/` directory
5. Upload to Claude along with core files


Example structure:
```
input/
├── world-geography.txt
├── political-system.md
├── magic-rules.txt
└── character-backgrounds.md
```


## Best Practices


1. **Document Organization**
- Keep each document focused on a specific topic
- Use clear, descriptive filenames
- Maintain consistency across documents


2. **System Usage**
- Upload all core files as artifacts to a Claude Project
- Keep worldbuilding documents concise and well-organized
- Use appropriate evaluation functions for your needs


3. **Version Control**
- Maintain backups of your worldbuilding documents
- Track changes to ensure consistency
- Regular updates to reflect universe development


## Contributing


Contributions are welcome! Please read our contributing guidelines before submitting pull requests.


## Support


For issues, questions, or suggestions:
1. Check existing GitHub issues
2. Create a new issue with detailed description
3. Follow issue template guidelines


## Project Status


Current Version: 1.0.0
Status: Active Development


## Authors


Drift Johnson @mushroomfleet
https://www.fivebelowfive.uk


## Acknowledgments


- Anthropic's Claude AI for enabling this project
- Contributors and testers
