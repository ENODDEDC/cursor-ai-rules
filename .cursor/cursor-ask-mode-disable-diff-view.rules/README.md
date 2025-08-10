# Universal Response Rule: Clean, Complete Code Only

This Cursor IDE rule ensures the AI provides clean, full, copy-paste-ready code files and clear explanations for non-code queries.

---

## Purpose

- Always deliver **complete, full file content** for all code generation requests without any line numbers, truncation, or placeholder comments like `// ... existing code ...`.  
- Ignore any confusing editor displays showing line numbers or partial code snippets.  
- For non-code questions, respond with clear, helpful, conversational answers without unnecessary code blocks unless specifically requested.  
- Automatically detect whether the user wants code generation or general assistance and respond accordingly.

---

## Setup Instructions

1. Place the rule file (e.g., `cursor-ask-mode-disable-diff-view.mdc`) in your `.cursor/rules/` directory inside your Cursor workspace or user directory.  
2. Restart or reload Cursor to activate the rule.  
3. The AI will automatically apply this rule when responding to relevant prompts.

---

## When to Use or Call This Rule

- Mention the rule explicitly by prefixing the rule file name with `@` in your message when you want to ensure the AI provides **perfectly clean, complete code responses**.  
- Example: `@cursor-ask-mode-disable-diff-view`  
- This is useful if you want to override default behavior that may include line numbers or partial snippets.  

---

## Example User Prompts Triggering This Rule

- "Generate a full React component file for a login form."  
- "Show me the complete Node.js server code."  
- "Explain closures in JavaScript." (non-code explanation)  

---

Your AI assistant will now reliably provide complete, clean code or clear explanations based on this rule.
