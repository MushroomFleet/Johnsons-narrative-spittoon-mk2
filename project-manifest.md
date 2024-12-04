# Paradistro System Project Manifest

## Core System Files
- `ACEHOLOFS-V3.txt` - Core cognitive processing and filesystem simulation framework
- `NarrativeSpittoon.txt` - Fiction generation and library building module
- `GhostWritingStyle.txt` - Writing style guidelines for passage rewrites
- `HolographicTutor.txt` - Document evaluation functions and scoring systems

## Directory Structure
```
/paradistro-system/
├── ace/
│   ├── capabilities/      # ACE capability definitions
│   ├── logs/             # Processing and tracking logs
│   ├── prompts/          # Dynamic prompt storage
│   └── responses/        # System responses and outcomes
├── creative/
│   ├── critiques/        # Publisher perspective analyses
│   ├── reviews/          # Academic/craft evaluations
│   ├── scores/           # Numerical evaluations
│   └── weaknesses/       # Identified improvement areas
├── docs/
│   ├── core/            # Core system documentation
│   └── reference/       # System reference materials
├── input/               # User-supplied worldbuilding documents
│   └── README.md        # Guidelines for input documentation
└── system/
    ├── config/          # System configuration files
    └── logs/            # System operation logs
```

## Input Documentation Guidelines
The `/input/` directory is designed to accommodate unlimited user-supplied worldbuilding documents. These documents serve as the contextual foundation for the ACE cognitive processing system.

### Input Document Requirements:
- Files should be plain text (.txt) or markdown (.md) format
- Each file should focus on a specific aspect of worldbuilding
- Files should be named descriptively (e.g., `machine-society-customs.txt`)
- No limit to the number of input documents
- Documents can be added or modified at any time

### Processing Behavior:
- All documents in the `/input/` directory are automatically included in ACE cognition
- System maintains dynamic mapping of relationships between input documents
- New documents are immediately integrated into the knowledge base
- Document relationships are updated automatically when files are added or modified

## System Behavior
1. Core system files (ACEHOLOFS-V3, NarrativeSpittoon, GhostWritingStyle, HolographicTutor) remain constant
2. Input directory contents are treated as dynamic worldbuilding context
3. ACE system automatically adapts to new input documents
4. All processing maintains consistency with provided worldbuilding rules

## Version Control
- Core system files: v1.0.0
- Project manifest: v1.0.0
- Last updated: [Current Date]

## Notes
- Input documents are considered supplementary to core system files
- System maintains backwards compatibility with existing input documents
- Regular backups of input directory recommended
- Input documents should maintain internal consistency

## Future Considerations
- Dynamic mapping interface for visualizing document relationships
- Automated consistency checking between input documents
- Version control for input documents
- Enhanced search and cross-referencing capabilities
