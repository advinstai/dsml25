# Contributing to DSML 2025

Thank you for your interest in contributing to the 4th School on Data Science and Machine Learning repository!

## How to Contribute

### For Lecturers

1. **Lecture Materials**
   - Place your lecture materials in the appropriate `lectures/dayX-topic/` directory
   - Use descriptive filenames: `session-topic-name.pdf` or `topic-slides.pdf`
   - Include any supplementary materials (code, datasets, references)

2. **Exercises**
   - Create Jupyter notebooks for hands-on exercises
   - Include clear instructions and learning objectives
   - Provide sample solutions or hints
   - Add a `requirements.txt` if using specific dependencies

3. **File Formats**
   - Slides: PDF format preferred
   - Code: Jupyter notebooks (.ipynb) or Python scripts (.py)
   - Documentation: Markdown (.md)

### For Participants

1. **Sharing Solutions**
   - Fork this repository
   - Create a new branch for your solutions
   - Submit a pull request with your work
   - Include your name in the commit message

2. **Reporting Issues**
   - Use the issue tracker for:
     - Broken links
     - Errors in materials
     - Missing dependencies
     - Suggestions for improvement

3. **Sharing Resources**
   - Add relevant papers, tutorials, or resources to `resources/`
   - Update the resources README with a brief description

## File Organization Guidelines

### Naming Conventions

- Use lowercase with hyphens: `my-lecture-topic.pdf`
- Be descriptive: `cnn-image-classification.ipynb` not `ex1.ipynb`
- Include date for time-sensitive materials: `2025-11-17-lecture.pdf`

### Directory Structure

Keep the structure organized:
```
lectures/
  dayX-topic/
    session-name.pdf
    code-examples/
    supplementary/

exercises/
  topic/
    README.md
    exercise_01.ipynb
    solution_01.ipynb
    data/
    requirements.txt
```

## Code Guidelines

### Python Style

- Follow PEP 8 style guidelines
- Use meaningful variable names
- Add comments for complex operations
- Include docstrings for functions

### Jupyter Notebooks

- Start with a title and description
- Use markdown cells to explain concepts
- Keep cells focused and modular
- Clear all outputs before committing (optional)

## Commit Messages

Write clear commit messages:
- Use present tense: "Add exercise" not "Added exercise"
- Be specific: "Add CNN classification exercise" not "Update files"
- Reference issues when applicable: "Fix #123: Correct typo in README"

## Pull Request Process

1. Update the relevant README if you're adding new content
2. Ensure any dependencies are documented
3. Test that code runs without errors
4. Provide a clear description of what you're adding/changing

## Questions?

If you have questions about contributing, please contact:
- Email: secretary@ictp-saifr.org
- Open an issue in this repository

## License

By contributing, you agree that your contributions will be licensed under the same license as this project.

---

Thank you for helping make this school a success!
