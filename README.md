<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Build a Spotify Clone with Cursor

**Project Link:** [View Project](http://learn.nextwork.org/projects/ai-workspace-cursor)

**Author:** mitalikhot14@gmail.com  
**Email:** mitalikhot14@gmail.com

---

![Image](http://learn.nextwork.org/charmed_orange_radiant_canary_melon/uploads/ai-workspace-cursor_s2q3upload)

---

## Introducing Today's Project!

In this project, I'm going to build a Spotify clone with Cursor AI. This will help me learn about Cursor AI, Git, and Debugging. I'm interested in this because AI is advancing day by day in today's world, and learning more about AI is kind of fascinating. 

### Key tools and concepts

The tools I used were the Cursor AI agent and git. Key concepts I learnt include different modes in chat agents, i.e., plan, ask, and agent to plan and implement the new feature in this project. 

### Personal reflection

This project took me approximately a day. The most challenging part was troubleshooting the feature. It was most rewarding to create a spotify clone and build your own feature withe help of Cursor AI. 

### Why I did this project

I did this project today because I was curious about creating a Spotify clone with Cursor AI. This project met my goals by understanding the working of Cursor AI and building a project. 

---

## Setting Up the Cursor IDE

In this step, I'm going to download Cursor and create a Cursor account to learn more about the codebase and build new functionality.

![Image](http://learn.nextwork.org/charmed_orange_radiant_canary_melon/uploads/ai-workspace-cursor_s1q2upload)

### How Cursor differs from other AI coding tools

Cursor is different from other AI coding agents. It stands out because it integrates an IDE with an AI chat. The editor and the AI are the same app out of the box. You can read and modify code as well as get AI to write the code for you, without having to open another app.

### Getting the starter code

In this step, I'm going to install git and clone the repository because we are creating our own local copy of the project on our computer, so we can work on it.

### Cloning the project from GitHub

Running the Git Clone command, it clones the project to our own local server. It provides every folder and file present in the project. All tags, the entire history, and every branch that exists for the project. 

---

## Exploring the Codebase with AI

In this step, I'm going to explore the existing codebase using Cursor's AI chat to learn more about the project and build new features. 

### The NextSound web app

It’s a music discovery app that shows tracks/albums/artists from Spotify, with a built-in mock/demo.

### Running the app locally

In this step, I'm going to install NextSound's dependencies and run the app locally to understand its structure.

---

## Creating a Brand New Feature

In this step, I'm going to plan, implement, and verify the queue feature with Cursor, so that users can manage their upcoming songs.

### Prompting Cursor

The key requirements in my prompt were:

1. Add an "Add to Queue" button on each song tile. i.e., When a user clicks the "Add to Queue" button, a panel should open from the right-hand side of the screen that shows the queue in a vertical list.
2. Users should be able to add songs to this queue panel.
3. Show the currently playing song prominently.
4. Allow users to reorder or remove songs from the queue.
5. Make it easily accessible but not intrusive to the main experience. It should feel natural and intuitive for managing what plays next.
6. Please make sure to use only the packages and versions defined in `package.json`.


![Image](http://learn.nextwork.org/charmed_orange_radiant_canary_melon/uploads/ai-workspace-cursor_s4q5upload)

### Designing the Queue feature

To build a new queue feature, I prompted Cursor Agent to Plan a change with me – I'd like to add a queue feature to our music web app! The goal is to let users manage their upcoming songs in a dedicated area.

Key requirements:
1. Add an "Add to Queue" button on each song tile. I.e. When a user clicks the "Add to Queue" button, a panel should open from the right-hand side of the screen that shows the queue in a vertical list.
2. Users should be able to add songs to this queue panel.
3. Show the currently playing song prominently.
4. Allow users to reorder or remove songs from the queue.
5. Make it easily accessible but not intrusive to the main experience. It should feel natural and intuitive for managing what plays next.
6. Please make sure to use only the packages and versions defined in `package.json`.


### Troubleshooting and iterating

In this step, I'm going to fix technical errors, UI bugs using screenshots, and confirm the queue feature works end-to-end using Cursor chat for smooth running of the new feature.

### Debugging with Cursor

I ran into an issue where the queue was not visible. I solved it by creating a plan.md file in the project's root directory. Then I told Cursor to review and implement the queue features defined in @plan.md.

---

## Managing AI Context

In this secret mission, I will learn to control Cursor's context by creating a .cursorignore file to exclude files from Cursor's context and creating a .cursorindexingignore file for more flexible control over indexing.

![Image](http://learn.nextwork.org/charmed_orange_radiant_canary_melon/uploads/ai-workspace-cursor_s6q4upload)

### Performance and security benefits

Managing context improves performance by narrowing the LLM's focus to relevant files, which reduces token overhead and provides faster, more accurate code completions. It improves security by allowing you to exclude sensitive data like README.md, .env, and node_modules files from being sent to external servers, ensuring your most critical information stays local.

### Comparing .cursorignore and .cursorindexingignore

.cursorignore hides files from Cursor while .cursorindexingignore only skips the files during indexing, but still allow @ referencing. Use this for large directories like data/ where you want fast indexing but occasional access.

---

---
