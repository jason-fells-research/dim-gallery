# AI Assistant Instructions for dim-gallery

## Project Overview
This repository curates artifacts from three interconnected domains:
- **RET causal maps**: Relational Event Theory models for understanding causal relationships
- **Harmonic Network**: Network analysis focusing on harmonic patterns and resonance
- **Meta-Recursive Governance**: Governance structures that operate through recursive, self-referential processes

## Repository Structure & Organization

### Expected Artifact Categories
When adding content to this repository, organize by domain and type:
```
/ret-causal-maps/
  ├── models/           # Computational models and algorithms  
  ├── visualizations/   # Charts, graphs, network diagrams
  ├── datasets/         # Raw and processed data
  └── documentation/    # Theory, methodology, case studies

/harmonic-network/
  ├── analysis/         # Network analysis scripts and results
  ├── patterns/         # Identified harmonic patterns
  ├── tools/           # Analysis and visualization tools
  └── examples/        # Use cases and applications

/meta-recursive-governance/
  ├── frameworks/      # Governance models and structures
  ├── implementations/ # Real-world applications
  ├── simulations/     # Modeling and scenario testing
  └── theory/          # Theoretical foundations
```

## Content Guidelines

### Artifact Standards
- **Documentation**: Include clear provenance, methodology, and context for each artifact
- **Metadata**: Add YAML frontmatter with tags, dates, contributors, and relationships to other artifacts
- **Cross-references**: Link related artifacts across domains using consistent tagging
- **Formats**: Prefer open formats (JSON, CSV, SVG, Markdown) for maximum accessibility

### Interdisciplinary Connections
Look for and document connections between:
- Causal structures in RET maps and governance feedback loops
- Harmonic patterns in networks and recursive governance cycles  
- Emergent properties that span multiple domains

## Development Workflows

### Adding New Artifacts
1. Determine primary domain (RET/Harmonic/Meta-Recursive)
2. Create appropriate subdirectory structure
3. Include comprehensive README.md with context
4. Add cross-domain tags if applicable
5. Update main README.md with artifact summary

### Quality Standards
- Verify data integrity and format consistency
- Test visualizations across different platforms
- Ensure computational models include reproducible examples
- Document assumptions and limitations clearly

## Key Concepts to Understand

### RET Causal Maps
Focus on temporal sequences, actor relationships, and event dependencies. Models should capture both direct and indirect causal pathways.

**Technical Approaches:**
- Network graph formats (GraphML, GEXF, JSON-LD)
- Temporal modeling with timestamps and duration
- Statistical analysis of causal strength and significance
- Visualization with D3.js, NetworkX, or Gephi exports

### Harmonic Networks
Emphasize resonance patterns, frequency analysis, and emergent synchronization. Look for mathematical relationships in network topology.

**Technical Approaches:**
- Spectral analysis using eigenvalue decomposition
- Fourier transforms for frequency domain analysis  
- Graph signal processing techniques
- Adjacency matrix operations and Laplacian analysis

### Meta-Recursive Governance
Document self-referential decision processes, feedback mechanisms, and adaptive governance structures that modify their own rules.

**Technical Approaches:**
- State machine representations of governance transitions
- Recursive function modeling for self-modification
- Agent-based simulations of governance evolution
- Formal verification of governance invariants

## Common Tools & Technologies

### Data Formats
- **Networks**: GraphML, GEXF, JSON-LD, CSV edge lists
- **Time Series**: CSV with ISO timestamps, HDF5 for large datasets
- **Metadata**: YAML frontmatter, JSON-LD for semantic annotation
- **Visualizations**: SVG (preferred), PNG for complex renders, interactive HTML

### Analysis Libraries
- **Python**: NetworkX, pandas, numpy, scipy, matplotlib, plotly
- **R**: igraph, ggplot2, tidyverse, visNetwork
- **JavaScript**: D3.js, vis.js, sigma.js for web visualizations
- **Mathematical**: MATLAB/Octave for signal processing, Mathematica for symbolic analysis

## Specific Workflows by Artifact Type

### Adding Dataset Artifacts
1. Include data dictionary with column definitions and units
2. Provide sample queries or analysis snippets
3. Document collection methodology and potential biases
4. Add validation scripts to check data integrity
5. Include citation information and usage restrictions

### Adding Model Artifacts
1. Provide executable code with dependency requirements
2. Include test cases with expected outputs
3. Document parameter sensitivity and edge cases
4. Add performance benchmarks where relevant
5. Explain theoretical foundations and assumptions

### Adding Visualization Artifacts
1. Ensure scalability across different screen sizes
2. Include both static and interactive versions when possible
3. Provide data source references and update mechanisms
4. Add accessibility features (alt text, color-blind friendly palettes)
5. Document interaction patterns and user guidance

## Cross-Domain Integration Examples

### RET ↔ Governance
- Causal event chains in policy feedback loops
- Temporal governance transitions as RET sequences
- Actor networks in decision-making processes

### Harmonic ↔ RET
- Oscillatory patterns in recurring causal relationships
- Frequency analysis of event timing distributions  
- Resonance effects in network cascade phenomena

### Governance ↔ Harmonic
- Recursive policy cycles as harmonic oscillations
- Stability analysis of governance feedback systems
- Emergence of synchronized behavior in distributed governance

## Quality Assurance Checklist

### Before Committing Artifacts
- [ ] All data files have accompanying metadata
- [ ] Code includes requirements.txt or environment.yml
- [ ] Visualizations render correctly in multiple browsers
- [ ] Cross-references use consistent tagging scheme
- [ ] Documentation includes methodological limitations
- [ ] File naming follows domain/category/descriptive-name pattern

### Reproducibility Standards  
- [ ] Include random seeds for stochastic processes
- [ ] Pin software versions in dependency files
- [ ] Provide container definitions (Docker/Singularity) for complex environments
- [ ] Document hardware requirements for resource-intensive analyses

## Integration Points
This repository serves as a bridge between theoretical frameworks and practical applications. When contributing, consider how artifacts might inform or be informed by the other domains. Look for opportunities to create cross-domain synthesis artifacts that demonstrate novel connections or unified approaches across RET, Harmonic Network, and Meta-Recursive Governance paradigms.