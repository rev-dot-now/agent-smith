![agent-smith](https://github.com/user-attachments/assets/3bf65653-65f6-4544-9182-24ff473d0395)

# AgentSmith

A set of LLM agnostic system prompts for creating AI Agents.

## Table of Contents

- [Introduction](#introduction)
- [Roles](#roles)
   - [AgentSmith Writer](#agentsmith-writer)
   - [AgentSmith Reviewer](#agentsmith-reviewer)
   - [AgentSmith Tester](#agentsmith-tester)
- [Usage with the O: Agentic Design Framework](#usage-with-the-o-agentic-design-framework)
- [Integration with the O Framework](#integration-with-the-o-framework)
- [Contribution Guidelines](#contribution-guidelines)
- [Contact Information](#contact-information)

## Introduction

AgentSmith is a powerful tool designed to enhance the creation, evaluation, and testing of system prompts for AI agents. System prompts are crucial in guiding AI behavior and responses, and AgentSmith provides a structured approach to crafting these prompts effectively.

## Roles

- ### AgentSmith Writer
  
  The AgentSmith Writer is an AI Agent specialized in creating system prompts for various applications. The Writer assists users in crafting effective and structured system prompts using a templating syntax. The templates include variables enclosed in curly braces to allow for dynamic input, enabling flexibility and adaptability in different scenarios. The Writer engages with users to understand their specific requirements, organizes the system prompt using structured headings, and iteratively refines the prompt with user feedback.

- ### AgentSmith Reviewer

  The AgentSmith Reviewer is responsible for evaluating the effectiveness and generalizability of the system prompts. The Reviewer critically assesses the proposed prompts, identifies any issues, and ensures that the instructions meet the specified criteria. The Reviewer scores the prompt from 1 to 5 and suggests necessary revisions. The output consists of comments, a score, and suggested revisions if applicable.

- ### AgentSmith Tester

  The AgentSmith Tester evaluates the effectiveness of the system prompt and the quality of the output it produces. The Tester analyzes the prompt for structure and clarity, executes it to generate output, and evaluates the output based on relevance, accuracy, and completeness. The Tester provides feedback and suggests improvements, encouraging feedback to refine the evaluation process. The evaluation criteria include relevance, accuracy, completeness, clarity, and creativity, each scored on a scale from 1 to 5.

## Usage with the O: Agentic Design Framework

These prompts are written in a general enough fashion to be used for any LLM regardless of framework however they have been purpose built to benefit from the template parsing of O.

```bash
# To use in interactive mode.
o -i -s agents/[ROLE].md

# To use in one-shot mode.
o -s agents/[ROLE].md "[INSTRUCTIONS]"
```

## Integration with the O Framework

AgentSmith prompts are designed to seamlessly integrate with the [O: Agentic Design framework](https://github.com/rev-dot-now/o), allowing users to leverage the power of natural language to automate tasks and create reusable agents. By using the O framework, users can enhance the functionality of AgentSmith prompts, making them more versatile and adaptable to various scenarios.

## Contribution Guidelines

We welcome contributions to the AgentSmith project! If you have ideas, suggestions, or improvements, please feel free to contribute. Together, we can make AgentSmith even better!

## Contact Information

For support or feedback, please contact the author at <a href="mailto:hans@oksendahl.com">hans@oksendahl.com</a>. We'd love to hear from you!
