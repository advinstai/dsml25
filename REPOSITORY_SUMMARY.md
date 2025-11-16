# DSML 2025 Repository - Summary

## Overview

This is the official Git repository for the **4th School on Data Science and Machine Learning** organized by ICTP-SAIFR.

**Event**: 4th School on Data Science and Machine Learning  
**Dates**: November 16-21, 2025  
**Location**: ICTP-SAIFR, São Paulo, Brazil  
**Website**: https://www.ictp-saifr.org/dsml2025/

## What's Included

### Documentation Files

1. **README.md** - Main repository overview with event information
2. **SCHEDULE.md** - Detailed day-by-day schedule
3. **PARTICIPANT_INFO.md** - Essential information for participants (travel, setup, requirements)
4. **CONTRIBUTING.md** - Guidelines for contributing content
5. **ORGANIZERS.md** - Contact information for organizers
6. **FAQ.md** - Frequently asked questions
7. **SETUP.md** - Repository setup and usage guide
8. **LICENSE** - MIT License

### Directory Structure

- **lectures/** - Organized by day (day0-toolbox through day5-frontiers)
- **exercises/** - Hands-on exercises organized by topic
- **resources/** - Additional learning materials and references
- **docs/** - General documentation
- **schedule/** - Schedule-related materials

### Configuration Files

- **.gitignore** - Ignores Python cache, data files, checkpoints, etc.
- **requirements.txt** - Python dependencies (numpy, pandas, matplotlib, torch, etc.)

## Repository Statistics

- **Files created**: 15
- **Directories created**: 19
- **Initial commits**: 2
- **Branch**: master

## Key Features

1. **Comprehensive Structure** - Ready for all lecture materials and exercises
2. **Well-Documented** - Extensive documentation for all stakeholders
3. **Git-Ready** - Initialized with proper .gitignore and configuration
4. **Modular Organization** - Clear separation between lectures, exercises, and resources
5. **Beginner-Friendly** - Includes setup guides and FAQs

## Quick Start

### For Organizers
```bash
cd /mnt/user-data/outputs/dsml2025
git remote add origin <your-github-url>
git push -u origin master
```

### For Lecturers
```bash
git clone <repository-url>
cd dsml2025
# Add your materials to appropriate directories
git add lectures/day1-foundations/your-lecture.pdf
git commit -m "Add lecture materials"
git push
```

### For Participants
```bash
git clone <repository-url>
cd dsml2025
pip install -r requirements.txt
jupyter notebook
```

## Event Highlights

- **No registration fee**
- **Limited financial support** for travel and accommodation
- **Hands-on approach** - Morning theory, afternoon practice
- **Expert instructors** - Brazilian and international AI researchers
- **Poster presentations** - Required for all participants
- **Networking opportunities** - Coffee breaks and interactive sessions

## Topics Covered

### Day 0 (Sunday): Toolbox
- Pandas, Matplotlib, PyTorch fundamentals

### Day 1 (Monday): Foundations
- Statistical methods, Neural Networks 101, Perceptron

### Day 2 (Tuesday): Going Deeper
- Multi-layer networks, Backpropagation, CNNs

### Day 3 (Wednesday): Architectures
- Advanced CNNs, RNNs, Transformers, LLMs

### Day 4 (Thursday): Applications
- AI in sciences, climate, humanities, HPC

### Day 5 (Friday): Frontiers
- Foundation models, Physics-enhanced ML, Explainable AI, Ethics

## Next Steps

1. **Review** all documentation files
2. **Customize** organizer emails and contact information
3. **Add** lecture materials as they become available
4. **Create** exercises for each topic
5. **Upload** to a remote repository (GitHub, GitLab, etc.)
6. **Share** repository URL with participants

## Contact

ICTP-SAIFR  
Email: secretary@ictp-saifr.org  
Phone: +55 (11) 3393 7839  
Website: https://www.ictp-saifr.org/

## Notes

- This structure follows best practices for educational repositories
- All text files created without icons/emojis as requested
- Ready for immediate use and customization
- Compliant with standard Python/ML project conventions

---

**Created**: November 16, 2025  
**Version**: 1.0  
**Status**: Ready for use
