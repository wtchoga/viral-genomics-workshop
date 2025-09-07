# Viral Genomics and Evolution Workshop 2025

🧬 **A comprehensive workshop on viral genomics and pathogen evolution analysis**

## Workshop Overview

This intensive workshop focuses on viral genomics and pathogen evolution analysis, designed for researchers, graduate students, and public health professionals interested in understanding viral evolution through computational approaches.

**📅 Dates:** September 2025  
**📍 Venue:** Regent Hotel, Gaborone, Botswana  
**💻 Format:** Hands-on computational workshops with lectures

## Quick Start

### View the Workshop Website
🌐 **Website:** [https://wtchoga.github.io/viral-genomics-workshop/](https://wtchoga.github.io/viral-genomics-workshop/)

### Pre-Workshop Setup
1. Complete the [software installation guide](https://wtchoga.github.io/viral-genomics-workshop/module-0/installation.html)
2. Test your environment using provided verification scripts
3. Join the workshop Slack workspace
4. Review the [schedule](https://wtchoga.github.io/viral-genomics-workshop/schedule.html) and [resources](https://wtchoga.github.io/viral-genomics-workshop/resources.html)

## Workshop Modules

| Module | Topic | Duration |
|--------|-------|----------|
| **Module 0** | [Workshop Setup](module-0/index.qmd) | Pre-workshop |
| **Module 1** | [Viral Genomics Fundamentals](module-1/index.qmd) | Day 1 |
| **Module 2** | [Sequence Analysis](module-2/index.qmd) | Day 2 |
| **Module 3** | [Phylogenetic Analysis](module-3/index.qmd) | Day 3 |
| **Module 4** | [Evolutionary Analysis](module-4/index.qmd) | Day 4a |
| **Module 5** | [Population Genomics](module-5/index.qmd) | Day 4b |
| **Module 6** | [Advanced Topics](module-6/index.qmd) | Day 5a |
| **Module 7** | [Practical Applications](module-7/index.qmd) | Day 5b |

## Learning Objectives

Participants will learn to:

- ✅ Process and analyze viral genomic data from raw sequencing reads
- ✅ Construct and interpret phylogenetic trees for evolutionary analysis
- ✅ Identify signatures of natural selection in viral genomes
- ✅ Analyze population structure and genetic diversity in viral populations
- ✅ Apply genomic approaches to outbreak investigation and surveillance
- ✅ Use modern bioinformatics tools for viral genomics research

## Repository Structure

```
viral-genomics-workshop/
├── _quarto.yml                 # Quarto project configuration
├── index.qmd                   # Workshop home page
├── schedule.qmd                # Detailed schedule
├── instructors.qmd             # Faculty information
├── resources.qmd               # Resources and materials
├── styles.css                  # Custom styling
├── custom.scss                 # Sass styling
├── module-0/                   # Setup and installation
│   ├── index.qmd
│   └── installation.qmd
├── module-1/                   # Viral genomics fundamentals
│   ├── index.qmd
│   ├── viral-diversity.qmd
│   └── genomic-data.qmd
├── module-2/                   # Sequence analysis
├── module-3/                   # Phylogenetic analysis
├── module-4/                   # Evolutionary analysis
├── module-5/                   # Population genomics
├── module-6/                   # Advanced topics
├── module-7/                   # Practical applications
├── images/                     # Workshop images and logos
├── .github/workflows/          # GitHub Actions for deployment
└── docs/                       # Generated website (auto-created)
```

## Development

### Building the Website Locally

1. **Install Quarto:** Download from [quarto.org](https://quarto.org/docs/get-started/)

2. **Clone repository:**
   ```bash
   git clone https://github.com/wtchoga/viral-genomics-workshop.git
   cd viral-genomics-workshop
   ```

3. **Preview site:**
   ```bash
   quarto preview
   ```

4. **Render site:**
   ```bash
   quarto render
   ```

### Deployment

The website automatically deploys to GitHub Pages via GitHub Actions when changes are pushed to the main branch.

**Setup Steps:**
1. Enable GitHub Pages in repository settings
2. Set source to "GitHub Actions"  
3. Push changes to main branch
4. Site will be available at `https://wtchoga.github.io/viral-genomics-workshop/`

## Contributing

Contributions to improve workshop materials are welcome:

1. **Issues:** Report bugs or suggest improvements via [GitHub Issues](https://github.com/wtchoga/viral-genomics-workshop/issues)
2. **Pull Requests:** Submit improvements via pull requests
3. **Content:** Help expand modules, add exercises, or improve documentation

### Content Guidelines

- Use clear, pedagogical explanations
- Include hands-on exercises with real data
- Provide code examples and expected outputs
- Follow existing formatting and style conventions
- Test all code examples before submission

## License

This workshop content is licensed under [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

**You are free to:**
- Share and adapt the material
- Use for commercial purposes

**Under the following terms:**
- Attribution required
- Share derivatives under the same license

## Contact

**Workshop Organizer:** [Your Name] - [your.email@institution.edu]  
**Technical Support:** [tech.support@workshop.org]  
**General Inquiries:** [workshop@institution.edu]

---

**🔬 Built with [Quarto](https://quarto.org/) for reproducible scientific publishing**