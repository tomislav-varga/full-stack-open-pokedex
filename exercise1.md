For testing, the most popular framework is pytest, followed by unittest and coverage.py.
For the build step, tools like pip with a requirements.txt file are commonly used, or alternatively, a modern dependency management tool called Poetry.
When it comes to linting and formatting, popular choices are flake8 (for enforcing PEP 8 style guidelines), black (an opinionated code formatter), and pylint.

Good alternatives to Jenkins and GitHub Actions for setting up CI include both hosted and self-hosted solutions:
1. **Hosted services**:	
• GitLab CI/CD is tailored for GitLab repositories and offers a generous free tier.
• Travis CI is another service that’s easy to set up and use.
2. **Self-hosted solutions**:
• Drone CI, which is lightweight and Docker-native.
• Buildkite, which is well-suited for hybrid cloud environments.

In my opinion, the team should start with a **hosted CI solution**. This allows them to focus more on development without worrying about infrastructure. However, from the beginning, the team should plan for the **option to migrate to a self-hosted solution** if it becomes more cost-effective in the future—especially if someone on the team is trained to maintain it.