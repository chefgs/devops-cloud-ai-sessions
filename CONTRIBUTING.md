# Contributing to DevOps, Cloud & AI Training Content Portal

Thank you for your interest in contributing to this training content portal! This guide will help you understand how to add and organize content.

## How to Contribute

### 1. Fork and Clone

1. Fork this repository
2. Clone your fork locally
3. Create a new branch for your contribution

```bash
git clone https://github.com/YOUR_USERNAME/devops-cloud-ai-sessions.git
cd devops-cloud-ai-sessions
git checkout -b add-new-content
```

### 2. Choose the Right Directory

- **presentations/**: Add PPT/PPTX files for training presentations
- **training-materials/**: Add hands-on labs, tutorials, and course materials
- **blogs/**: Add technical articles in Markdown format
- **resources/**: Add reference guides, tools, and supplementary materials

### 3. Follow Naming Conventions

#### For Presentations
- Use descriptive, lowercase names with hyphens
- Example: `kubernetes-advanced-networking.pptx`

#### For Blog Posts
- Format: `YYYY-MM-DD-title-of-post.md`
- Example: `2026-02-09-docker-best-practices.md`

#### For Training Materials
- Create a dedicated folder with a descriptive README.md
- Example: `training-materials/aws-lambda-workshop/README.md`

### 4. Document Your Content

Each piece of content should include:
- Clear title and description
- Author information
- Date of creation/last update
- Prerequisites (if applicable)
- Target audience level (beginner, intermediate, advanced)

### 5. Update Indexes

After adding content:
1. Update the README.md in the relevant directory
2. Add an entry to the main index.html if it's a significant addition

### 6. Submit a Pull Request

1. Commit your changes with a clear message
   ```bash
   git add .
   git commit -m "Add: Kubernetes networking presentation"
   git push origin add-new-content
   ```

2. Open a pull request with:
   - Clear title describing the addition
   - Description of the content
   - Any relevant context or notes

## Content Guidelines

### Quality Standards

- **Accuracy**: Ensure all technical information is correct and up-to-date
- **Clarity**: Write clear, concise explanations
- **Completeness**: Include all necessary information for understanding
- **Attribution**: Credit sources and references appropriately

### Content Structure

#### For Presentations
- Clear agenda and objectives
- Logical flow of topics
- Practical examples
- Summary and key takeaways

#### For Blog Posts
- Use proper Markdown formatting
- Include code examples with syntax highlighting
- Add diagrams or images where helpful
- Provide references and links

#### For Training Materials
- Define learning objectives
- List prerequisites
- Provide step-by-step instructions
- Include troubleshooting tips
- Offer practice exercises

### Prohibited Content

- Proprietary or confidential information
- Content that violates intellectual property rights
- Malicious code or security vulnerabilities
- Offensive or inappropriate material

## Code of Conduct

- Be respectful and professional
- Provide constructive feedback
- Help others learn and grow
- Give credit where credit is due

## Questions?

If you have questions about contributing, please:
1. Check existing issues for similar questions
2. Open a new issue with your question
3. Reach out to Saravanan Gnanaguru via gsaravanan.dev

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
