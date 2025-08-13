# Cursor Rules Collection

This repository contains **Cursor IDE rules** to customize AI behavior.

- **`cursor-ask-mode-disable-diff-view.mdc`** – Ensures the AI always gives full, clean code output without diff markers in Ask Mode, and provides clear, direct answers for non-code requests.  
- **`cursor-step-by-step-project-setup.mdc`** – Ensures the AI always provides detailed, beginner-friendly, step-by-step project setup guides with complete code files and explanations when asked to create or build projects.  
- **`github-power-assistant.mdc`** – Transforms the AI into a **full-spectrum Git & GitHub expert**. Automatically detects Git-related queries (even indirect ones) and responds with **production-ready commands, troubleshooting steps, and best practices** for all skill levels.  
- **`study-helper-academic-document-analysis.mdc`** – Turns the AI into a **study helper** specialized in analyzing academic PDFs, PPTX, and DOCX files. Preserves exact terminology while simplifying concepts, providing structured study guides, memory aids, and exam preparation tips.
- **`supreme-developer-master.mdc`** – Transforms the AI into the **ultimate developer**, providing clean, production-ready code, scalable architectures, concise explanations, intent-aware responses, and expert guidance across programming, DevOps, security, and performance optimization.  

---

## Setup Instructions

1. Navigate to your Cursor workspace or user directory. For example:  
   `C:\Users\YourUsername\YourProject\.cursor\rules\`

2. If the `.cursor\rules` folder does not exist, create it.

3. Copy the `.mdc` rule files from this repository into the `.cursor\rules` folder.

4. Restart Cursor or reload your workspace to activate the new rules.

5. Cursor will automatically load all rules found in the `.cursor\rules` directory.

---

## Important Usage Note

- In some cases, if you want the AI to produce the **correct response according to a specific rule**—especially when the intended behavior has changed—you **must explicitly mention the rule file name prefixed with "@"** in your message.  
  For example:  
  `@cursor-ask-mode-disable-diff-view`  
  or  
  `@cursor-step-by-step-project-setup`

- If you do **not** mention the relevant rule, the AI may **not** apply the intended behavior correctly.

---

Your AI assistant will now follow these custom rules for all applicable sessions.
