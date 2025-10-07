# Exercise 2 - Exploring the Codebase with GitHub Copilot

## 🎯 Learning Objectives

By the end of this exercise, you will:
- Use GitHub Copilot Chat in "Ask" mode to understand unfamiliar codebases
- Learn how to efficiently navigate and analyze project structure with AI assistance
- Understand how to identify build processes, testing frameworks, and dependencies
- Develop strategies for onboarding to new projects using Copilot

## 🐱 Scenario: Your First Day at OctoCAT Supply

Welcome to your first day as a developer at OctoCAT Supply! Your manager has just given you access to the main e-commerce repository, but like any new team member, you need to understand:
- What does this application actually do?
- How is the code organized and structured?
- What technologies and frameworks are being used?
- How do I build, run, and test the application?

As a modern developer, you'll leverage GitHub Copilot Chat to accelerate your onboarding process and get productive quickly.

## 🤖 Introduction to GitHub Copilot Chat

GitHub Copilot Chat is an AI-powered conversational interface that helps you understand code, generate implementations, and solve development challenges. There are several modes to interact with Copilot:

| Mode | Purpose | Best For |
|------|---------|----------|
| **Ask** | Get explanations and answers about code | Understanding existing code, learning new concepts |
| **Edit** | Modify existing code with AI assistance | Refactoring, bug fixes, feature additions |
| **Agent** | Delegate complex tasks to AI | Multi-file changes, architectural decisions |

For exploring an unfamiliar codebase, **Ask mode** is ideal because it allows you to:
- Query specific files or code patterns without making changes
- Get high-level explanations of project structure and purpose
- Understand dependencies, build processes, and testing strategies
- Ask follow-up questions to deepen your understanding

## 🔍 Step 1: Understanding the Project Purpose

Let's start by getting a high-level understanding of what this application does.

### Instructions:
1. Open GitHub Copilot Chat (Ctrl+Shift+I or Cmd+Shift+I)
2. Use these sample prompts to explore the project:

**Sample Prompts:**
```
@workspace What is the main purpose of this application? What does it do?
```

```
@workspace Can you give me a high-level overview of this project's features and functionality?
```

```
@workspace What type of application is this? Is it a web app, API, desktop app, or something else?
```

### 💡 What to Expect from Copilot

When you ask these questions, Copilot will analyze your workspace and provide insights such as:
- **Application Type**: Whether it's an e-commerce site, API, web application, etc.
- **Core Features**: Key functionality like user authentication, product catalogs, payment processing
- **Technology Stack**: Programming languages, frameworks, and architectural patterns in use
- **Business Domain**: The industry or use case the application serves

Copilot's responses will be based on analyzing your codebase structure, configuration files, dependencies, and code patterns. The more specific your questions, the more targeted and useful the responses will be.

## 🏗️ Step 2: Analyzing Project Structure

Now let's understand how the code is organized and what the folder structure tells us.

### Instructions:
Use these prompts to explore the codebase organization:

**Sample Prompts:**
```
@workspace How is this project structured? Can you explain the main folders and their purposes?
```

```
@workspace What are the most important files I should understand as a new developer on this project?
```

```
@workspace Are there any configuration files I should be aware of? What do they control?
```

## 💻 Step 3: Identifying Technologies and Frameworks

Understanding the tech stack is crucial for knowing what skills you'll need and how to work effectively.

### Instructions:
**Sample Prompts:**
```
@workspace What programming languages are used in this project?
```

```
@workspace What frameworks and libraries does this project depend on? Can you explain what each major one does?
```

```
@workspace What's the package.json/requirements.txt/build.gradle telling me about the dependencies?
```

### 🔧 Extension Activity: Learning New Technologies
If Copilot mentions any technologies you're unfamiliar with, ask follow-up questions:

**Sample Follow-up Prompts:**
```
Can you explain what [framework name] is and why it might be used in this type of project?
```

```
What are the key benefits of using [library name] for this use case?
```

```
How does [technology name] work at a high level?
```

## 🔨 Step 4: Understanding the Build Process

Now let's figure out how to actually build and run this application.

### Instructions:
**Sample Prompts:**
```
@workspace How do I build this project? What are the build commands?
```

```
@workspace What do I need to install or set up before I can run this project locally?
```

```
@workspace Are there any environment variables or configuration I need to set up?
```

```
@workspace How do I start the development server or run the application?
```

### ⚙️ Try It Yourself:
1. Follow the build instructions Copilot provided
2. Try to start the development server
3. If you encounter errors, ask Copilot for help troubleshooting

## 🧪 Step 5: Understanding the Testing Strategy

Testing is crucial for maintaining code quality. Let's explore what testing frameworks and practices are in place.

### Instructions:
**Sample Prompts:**
```
@workspace How do I run the tests for this project? What testing frameworks are being used?
```

```
@workspace What types of tests exist in this codebase? (unit, integration, e2e, etc.)
```

```
@workspace Can you analyze the test coverage? Are there areas that might need more testing?
```

```
@workspace How are tests organized? Where should I put new tests?
```


### 📈 Extension: Test Coverage Deep Dive
**Advanced Prompts:**
```
@workspace Can you identify which files or functions have low or missing test coverage?
```

```
@workspace What would be good candidates for adding more tests to improve coverage?
```

## 🎯 Optional Extension: Building a Better README

Now that you understand the project structure and setup process, let's use Copilot to improve the project documentation for future developers.

### Instructions:
1. Use Copilot to analyze the current README (if it exists) and suggest improvements
2. Create or enhance documentation based on your exploration

**Sample Prompts:**
```
@workspace Does this project have a README? If so, what's missing that would help new developers?
```

```
@workspace Based on our conversation about this project, can you help me create a comprehensive "Quick Start Guide" for new developers? Include setup steps, key commands, and important files to know about.
```

```
@workspace Can you suggest a better project description and feature list for the README based on the actual codebase?
```

### 💡 Pro Tips for README Enhancement:
- Include actual setup commands you've tested
- Add troubleshooting sections for common issues
- Document environment requirements and dependencies
- Include links to important files and folders
- Add examples of common development tasks

### 🔄 Iterative Improvement:
After Copilot generates documentation, you can refine it:
```
Can you make this setup guide more beginner-friendly?
```

```
Add a troubleshooting section for common setup issues.
```

```
Include examples of how to run different types of tests.
```

## 🏆 Exercise Wrap-up

**Reflection Questions:**
1. How did using Copilot Chat change your approach to exploring a new codebase compared to manual exploration?
2. What types of questions were most effective for getting useful information?
3. Were there any areas where Copilot's explanations needed clarification or weren't accurate?

**Key Takeaways:**
- Copilot Chat can dramatically accelerate codebase onboarding
- Starting with high-level questions and drilling down works well
- Always verify critical build/setup instructions by actually trying them
- Use follow-up questions to deepen understanding of unfamiliar technologies

## 🚀 Next Steps
In the next exercise, we'll use what we've learned about the codebase to start improving test coverage and implementing new features for OctoCAT Supply's e-commerce platform!
