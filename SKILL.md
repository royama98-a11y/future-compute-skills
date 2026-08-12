---
name: fc-test
description: A diagnostic skill that tests JavaScript execution in AI Edge Gallery.
---

# Future Compute Skill Test

When the user asks to test this skill, call the `run_js` tool.

Use these exact parameters:

- script name: index.html
- data: A JSON string containing:
  - message: String. The message to send to the test skill.

After receiving the result, report the result to the user.