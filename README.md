# Kiro Workshop: Data App Factory

Welcome to the Kiro Workshop! This hands-on session will teach you how to use Kiro's Spec-Driven Development workflow to build a governed data application.

## Workshop Overview

In this workshop, you'll learn how to leverage Kiro's AI-powered IDE to build a Supply Chain Visibility Streamlit app using natural language instructions and steering files.

## Prerequisites

Before starting the workshop, you'll need to set up Kiro and create an AWS Builder ID.

### 1. Create an AWS Builder ID

1. Go to [AWS Builder ID Sign Up](https://profile.aws.amazon.com/)
2. Click "Sign up" and follow the prompts
3. Enter your email address and create a password
4. Verify your email address through the confirmation link
5. Complete your profile information

The first time you access Kiro, you'll receive 500 bonus credits* usable within 30 days, whatever plan you sign up for, including Kiro Free.

*Learn more about [Kiro credits](#understanding-kiro-credits) below.

### 2. Download and Install Kiro

1. Go to [kiro.dev/download](https://kiro.dev/download)
2. Select your operating system (Windows, macOS, or Linux)
3. Download and install the application
4. Launch Kiro and sign in with your AWS Builder ID
5. Open or create a workspace folder for this workshop

## Getting Started

### Step 1: Copy the Steering Files

1. Copy the steering files from this repository to .kiro/steering/ folder in your workspace:
   - `product.md` - Product vision and principles
   - `tech.md` - Technical stack and constraints
   - `structure.md` - Project structure guidelines

### Step 2: Open Kiro Spec

1. In Kiro, open the **Spec** panel (look for the Spec icon in the sidebar or use the command palette)
2. Click on **"New Spec"** to create a new specification

### Step 3: Enter the Prompt

Copy and paste the following prompt into the Spec input field:

```
I have populated the steering files (product.md, tech.md, structure.md). Read them. Based on those standards, I want to build a 'Supply Chain Visibility' Streamlit app.

Initiate the Spec-Driven Development workflow and generate requirements.md, design.md, and tasks.md.
```

### Step 3: Review the Screenshot

For visual guidance, refer to the screenshot below:

![Kiro Prompt Screenshot](Kiro-Prompt-Screenshot.png)

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

- **Steering Files**:
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

## Understanding Kiro Credits

A credit is a unit of work in response to user prompts. Simple prompts can consume less than 1 credit. More complex prompts, such as executing a spec task, typically cost more than 1 credit. 

Additionally, different models consume credits at different rates, with a prompt executed via Sonnet 4.5 costing more credits than executing it with Auto. For example, a given task that consumes X credits to execute in Auto, will cost you 1.3X credits to execute via Sonnet 4.5. 

Credits are metered to the second decimal point, so the least number of credits a task can consume is 0.01 credits.

For more information, visit the [Kiro FAQ](https://kiro.dev/faq).

