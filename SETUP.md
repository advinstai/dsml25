# Repository Setup Guide

## Quick Start

This repository has been initialized with a comprehensive structure for the 4th School on Data Science and Machine Learning (DSML 2025).

## Repository Structure

```
dsml2025/
├── .git/                      # Git repository metadata
├── .gitignore                 # Git ignore patterns
├── README.md                  # Main repository overview
├── SCHEDULE.md                # Detailed event schedule
├── PARTICIPANT_INFO.md        # Information for participants
├── CONTRIBUTING.md            # Guidelines for contributors
├── ORGANIZERS.md              # Contact information
├── FAQ.md                     # Frequently asked questions
├── LICENSE                    # MIT License
├── requirements.txt           # Python dependencies
│
├── docs/                      # Documentation (empty, ready for content)
├── schedule/                  # Additional schedule materials
├── resources/                 # Learning resources
│   └── README.md             # Resources guide
│
├── lectures/                  # Lecture materials by day
│   ├── README.md             # Lectures overview
│   ├── day0-toolbox/         # Sunday: Pandas, Matplotlib, PyTorch
│   │   └── README.md
│   ├── day1-foundations/     # Monday: Neural Networks basics
│   │   └── README.md
│   ├── day2-deeper/          # Tuesday: Deep learning
│   ├── day3-architectures/   # Wednesday: CNNs, RNNs, Transformers
│   ├── day4-applications/    # Thursday: Domain applications
│   └── day5-frontiers/       # Friday: Advanced topics
│
└── exercises/                 # Hands-on exercises
    ├── README.md             # Exercises guide
    ├── pandas/               # Data wrangling exercises
    ├── matplotlib/           # Visualization exercises
    ├── pytorch/              # PyTorch fundamentals
    ├── neural-networks/      # Neural network exercises
    ├── cnns/                 # CNN exercises
    ├── rnns/                 # RNN exercises
    ├── transformers/         # Transformer exercises
    └── applications/         # Application-specific exercises
```

## Initial Commit

The repository has been initialized with:
- Comprehensive documentation
- Organized directory structure
- Standard Python/ML project files
- Git configuration

**Commit hash**: [See git log]
**Branch**: master

## Next Steps

### For Organizers

1. **Add Content**
   ```bash
   # Add lecture slides to appropriate day folders
   git add lectures/day1-foundations/lecture-slides.pdf
   git commit -m "Add Day 1 lecture slides"
   ```

2. **Update Information**
   - Add lecturer names to ORGANIZERS.md
   - Update contact emails
   - Add specific dates and times
   - Upload announcement PDF

3. **Create Exercises**
   - Develop Jupyter notebooks for each topic
   - Add datasets to exercise folders
   - Include solutions

4. **Set Up Remote Repository**
   ```bash
   # On GitHub, GitLab, or other platform
   git remote add origin <repository-url>
   git push -u origin master
   ```

### For Lecturers

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd dsml2025
   ```

2. **Add Your Materials**
   ```bash
   # Create your lecture materials
   git checkout -b feature/day1-statistics
   # Add files
   git add lectures/day1-foundations/statistics-slides.pdf
   git commit -m "Add statistics lecture slides"
   git push origin feature/day1-statistics
   ```

3. **Create Pull Request**
   - Submit PR for review
   - Organizers will merge after review

### For Participants

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd dsml2025
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Work on Exercises**
   ```bash
   jupyter notebook exercises/pandas/exercise_01.ipynb
   ```

4. **Keep Updated**
   ```bash
   git pull origin master
   ```

## Git Basics

### Common Commands

```bash
# Check status
git status

# View commit history
git log --oneline

# Create a new branch
git checkout -b feature-name

# Add files
git add filename
git add .                 # Add all changes

# Commit changes
git commit -m "Descriptive message"

# Push to remote
git push origin branch-name

# Pull latest changes
git pull origin master
```

### Branching Strategy

- `master`: Stable, tested content
- `develop`: Integration branch
- `feature/*`: New content or exercises
- `fix/*`: Bug fixes or corrections

## File Naming Conventions

- Use lowercase with hyphens: `my-lecture.pdf`
- Be descriptive: `cnn-basics-lecture.pdf` not `lecture1.pdf`
- Include dates for time-sensitive content: `2025-11-17-schedule.pdf`

## Contributing

See CONTRIBUTING.md for detailed guidelines on:
- Adding lecture materials
- Creating exercises
- Submitting corrections
- Proposing improvements

## Support

For technical issues with the repository:
- Open an issue on the repository
- Contact: secretary@ictp-saifr.org

## License

This repository is licensed under the MIT License. See LICENSE file for details.

Individual content may have different licenses - check specific files.

---

**Repository initialized**: November 16, 2025
**Last updated**: [To be updated with each significant change]
