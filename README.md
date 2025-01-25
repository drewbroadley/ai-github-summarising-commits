# Github Workflow - AI Github Summarising Commits (amend)

A simple approach to re-writing the **Summary** and **Description** of a Github commit using AI.

This is very helpful when you have a large number of commits and you want to summarise them in a more human readable format, or are a solo developer that wants to ensure things are documented well.

For an example - see my commit history.

### Prerequisites

- Github Workflow
- API Key for either Claude AI, Google Gemini or OpenAI

## Getting Started

- Add the appropriate API Key to your Github repository secrets:
  - `ANTHROPIC_API_KEY` for Claude AI
  - `GOOGLE_API_KEY` for Google Gemini
  - `OPENAI_API_KEY` for OpenAI
- Create a new Github Workflow folder in your repository: `.github/workflows`
- Copy the appropriate `commit-ai-summarise.yml` file this folder
- Commit and push the changes to your repository

**Watch the magic happen** .oO(✨)

## Author
Drew Broadley
drew@broadley.org.nz

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
