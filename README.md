# Kiro Workshop: Data App Factory

Welcome to the Kiro Workshop! This hands-on session will teach you how to use Kiro's Spec-Driven Development workflow to build a governed data application.

## Workshop Overview

In this workshop, you'll learn how to leverage Kiro's AI-powered IDE to build a Supply Chain Visibility Streamlit app using natural language instructions and steering files.

## Getting Started

### Step 1: Open Kiro Spec

1. In Kiro, open the **Spec** panel (look for the Spec icon in the sidebar or use the command palette)
2. Click on **"New Spec"** to create a new specification

### Step 2: Enter the Prompt

Copy and paste the following prompt into the Spec input field:

```
I have populated the steering files (product.md, tech.md, structure.md). Read them. Based on those standards, I want to build a 'Supply Chain Visibility' Streamlit app.

Initiate the Spec-Driven Development workflow and generate requirements.md, design.md, and tasks.md.
```

### Step 3: Review the Screenshot

For visual guidance, refer to the screenshot below:

![Kiro Prompt Screenshot](Images/Kiro-Prompt-Screenshot.png)

This shows you exactly where to enter the prompt in the Kiro interface.

**The Prompt to Enter:**
```
I have populated the steering files (product.md, tech.md, structure.md). Read them. Based on those standards, I want to build a 'Supply Chain Visibility' Streamlit app.

Initiate the Spec-Driven Development workflow and generate requirements.md, design.md, and tasks.md.
```

### Step 4: Let Kiro Work

Once you submit the prompt, Kiro will:
- Read the steering files in `.kiro/steering/`
- Generate a requirements document
- Create a design document
- Break down the work into actionable tasks
- Guide you through the implementation

## What's Included

This workspace contains:

- **Steering Files** (`.kiro/steering/`):
  - `product.md` - Product vision and principles
  - `tech.md` - Technical stack and constraints
  - `structure.md` - Project structure guidelines

These files guide Kiro to build applications that follow your organization's standards.

## Learning Objectives

By the end of this workshop, you'll understand how to:
- Use steering files to encode organizational standards
- Leverage Spec-Driven Development for complex projects
- Build data applications using natural language
- Work with Kiro's AI assistant effectively

## Next Steps

After completing the initial spec generation, you can:
- Iterate on the requirements
- Refine the design
- Execute the implementation tasks
- Add new features using the same workflow

Happy building! 🚀
