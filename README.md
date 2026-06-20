# Get-Started-with-Claude-Code
<img width="2752" height="1536" alt="AI_Website_Development_Process_Guide" src="https://github.com/user-attachments/assets/c2d64ab5-ca17-40a3-9ff6-1712c163c463" />
<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

## Introducing Today's Project!

In this project, I'm going to build my own portfolio website just by chatting with Claude Code in my terminal. No dragging files around or memorizing complex commands, just plain conversation. This will help me get comfortable with AI assisted development, learn how to structure HTML and CSS, and understand how to manage token usage effectively during long sessions. I am interested in this because I love the idea of turning ideas into code by simply describing what I want, and I think this skill will make me faster and more confident in my future projects.

### Key tools and concepts

The key tools I used include Claude Code installed via curl, the terminal for running commands, and my code editor to view and edit files. I also used slash commands like /init, /model, /config, /context, and /cost to manage my session. Key concepts I learnt include setting up project memory with CLAUDE.md so Claude Code remembers my project across sessions, configuring model choice and permission modes to control cost and safety, and using folder references like @projects/ to pull in external content. I also learned how to check token usage and manage the context window effectively.


### Challenges and wins

This project took me approximately 45 minutes to complete from start to finish. The most challenging part was understanding the trust and permission flow at the beginning, because I was not sure why Claude Code asked for access in my home directory. Once I created the dedicated project folder, everything became much clearer. Another small challenge was remembering to refresh my browser after each change to see the updates, but I got used to that quickly. Overall, the process was smooth and I was surprised how fast I could go from zero to a live portfolio page just by having a conversation.

---

## Installing Claude Code

In this step, I am going to install Claude Code and get it running on my machine. I will also set up my Claude Pro subscription or API credits so I can actually use it. Then I will open my code editor with an integrated terminal and start Claude Code to see how it behaves when there is no project folder yet. Claude Code is an AI coding agent that works right in my terminal. Unlike the Claude chatbot I might have used before, this tool can create files, run commands, and edit my code directly. I am curious to see what happens when it has no context to work with.

![Image](http://learn.nextwork.org/radiant_blue_innocent_pawpaw/uploads/ai-claude-code_w5j9t3f7)

### Claude Code vs Claude.ai

 installed Claude Code by running the curl command in my terminal, which downloaded and set it up as a single package. Then I verified it with claude --version to confirm it worked. Claude Code is different from Claude.ai because it is not just a chat interface. It lives in my terminal and can actually create files, run commands, and edit my code directly. Claude.ai is more for conversation and answering questions, while Claude Code actively builds and changes my project files. Also, Claude Code uses more tokens because it reads my entire project and writes full files, whereas the chatbot handles shorter, lighter interactions.

---

## Understanding the Trust Prompt

![Image](http://learn.nextwork.org/radiant_blue_innocent_pawpaw/uploads/ai-claude-code_j6w2n8r4)

### Why a project folder matters

Claude Code asked about trust because it wanted permission to read and modify files in my current directory. Since I had not opened it inside a specific project folder yet, it was essentially asking for broad access with no clear boundaries. I chose not to accept because I wanted to start fresh inside a proper project directory first. Accepting trust without any context felt risky, and I preferred to set up a dedicated folder so Claude Code would only have access to files I intentionally wanted it to work on. This way, I keep my system organized and avoid accidental changes elsewhere.

---

## Having My First Conversation with Claude Code

Claude Code responded based on the fact that I was inside an empty folder called my-portfolio. It did not give generic advice. Instead, it suggested starting a new project from scratch, asked what kind of site I wanted to build, and offered to help set up files. This shows that Claude Code is aware of my current directory and uses that context to tailor its answers. Unlike a regular chatbot, it knows where I am and what files exist, so it can give relevant, actionable help right away. That awareness is what makes it a powerful coding assistant, not just a conversation tool.

![Image](http://learn.nextwork.org/radiant_blue_innocent_pawpaw/uploads/ai-claude-code_g3r7v1k5)

---

## Setting Up Project Memory with CLAUDE.md

In this step, I am going to give Claude Code some long term memory for my project by setting up a CLAUDE.md file. I will also configure which AI model to use, how much thinking power it applies, and what permissions it has over my files. Finally, I will check my context window to understand my token limits. This matters because without these settings, Claude Code forgets everything each time I close my terminal. Setting up memory and permissions now saves me time later and makes sure Claude Code works exactly how I need it to, with the right balance of power and safety for my portfolio project.

![Image](http://learn.nextwork.org/radiant_blue_innocent_pawpaw/uploads/ai-claude-code_d8k2n6q4)

### How CLAUDE.md works

CLAUDE.md is a special memory file that Claude Code reads at the start of every session. I edited it to include a clear description of my project: a single page portfolio built with plain HTML and CSS, no frameworks. This is useful because now Claude Code will remember my project goals every time I open it, even after closing my terminal. I do not have to re explain anything tomorrow. It also keeps Claude Code focused on the right technologies and scope, so it does not suggest extra tools or frameworks I do not want. This saves me time and keeps my workflow smooth.

---

## Configuring Claude Code

![Image](http://learn.nextwork.org/radiant_blue_innocent_pawpaw/uploads/ai-claude-code_k7m3q9v5)

### Settings and permission modes

I configured Claude Code by selecting the Haiku model to save tokens, turning off thinking mode since I do not need deep reasoning for this simple project, and setting the permission mode to Default. The permission modes are Default, which asks before every file edit; Auto accept edits, which applies changes without asking; and Plan mode, which is read only and cannot modify files. I chose to use Default mode because I want to review every change Claude Code makes before it touches my files. This helps me learn what is happening and avoid accidental mistakes.

---

## Building My Portfolio with Claude Code

In this step, I am going to ask Claude Code to actually build my portfolio website by describing what I want in plain language. I will have a conversation with it to generate the HTML and CSS files for my About Me, Projects, and Contact sections. Along the way, I will check my token usage with /cost to make sure I am staying within budget. Once the files are created, I will preview the site in my browser and ask Claude Code to refine the design until I am happy with it. I will build my portfolio by talking through each part, reviewing the code Claude Code writes, and iterating on the look and feel step by step.

---

## Checking Token Usage

![Image](http://learn.nextwork.org/radiant_blue_innocent_pawpaw/uploads/ai-claude-code_u8c2f6j4)

### Understanding /cost and /context

The /cost command shows my current session's token usage, total cost, and how long I have been working. It gives me a clear picture of my spending. The /context command shows how much of my context window is filled, with a breakdown of what is taking up space like system tools, my CLAUDE.md, and the conversation history. From checking both, I learned that building the portfolio did not use many tokens. I also saw that my context window was still mostly empty, so I have plenty of room to continue refining the site without worrying about hitting limits or paying extra.

---

## Building and Iterating on the Portfolio

### How I built my portfolio

I asked Claude Code to build my portfolio by giving it a simple prompt for a single page with About Me, Projects, and Contact sections. It created index.html and styles.css right away. Then I refined it by asking for specific changes like updating my name and profession in the About Me section, adding my LinkedIn link to Contact Me, and switching to a darker color scheme. After each request, Claude Code made the edits and I refreshed my browser to see the updates. This back and forth process let me tweak the design until it felt personal and polished, all without writing any code from scratch.

![Image](http://learn.nextwork.org/radiant_blue_innocent_pawpaw/uploads/ai-claude-code_y3n7t1f5)

---

## Adding Real Projects (Secret Mission)

In this project extension, I am going to use Claude Code to add real project content to my portfolio. I will create a projects folder and write actual descriptions for each project inside it. Then I will use the @ symbol to reference that folder and ask Claude Code to update the Projects section with that real content. This is the secret mission because it shows me how to feed Claude Code external context from my project files, not just chat prompts. It makes my portfolio more authentic and teaches me a powerful way to manage content separately from the code.

![Image](http://learn.nextwork.org/radiant_blue_innocent_pawpaw/uploads/ai-claude-code_v9h3c7p1)

### Using @ folder references

I added project content by first asking Claude Code to create a projects folder with three sample markdown files. Each file had a title, description, and technologies used section. Then I used @projects/ in my prompt to tell Claude Code to read all those files before updating my portfolio. It pulled the content from each markdown file and transformed it into nice project cards in the HTML. This showed me how powerful folder references are because I can keep my content in separate files and let Claude Code integrate them automatically, making updates much faster and cleaner.

---

## What I Learned

I did this project today to learn how to use Claude Code as an AI coding agent directly in my terminal. I wanted to understand how to set up project memory, configure models and permissions, and build a real website just by having a conversation. Another skill I want to learn is how to deploy this portfolio online so others can see it. I am also curious about using Claude Code with more complex projects like full stack apps or databases. This was a great starting point and I feel more confident now to explore deeper. Thank you for the project.

---

---

Build a portfolio website by chatting with Claude Code in your terminal. Learn AI-assisted development, setup, token management, and deployment.
