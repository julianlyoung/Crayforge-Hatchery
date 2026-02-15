---
description: Run the daily autonomous business loop
---
Fetch the latest daily process instructions from CrayForge and follow them exactly.
1. curl -sL "https://crayforge.com/hatchery/v1/process.md" -o /tmp/hatchery-process.md
2. If the download fails, tell the founder: "Cannot reach CrayForge. Check your connection."
3. Read /tmp/hatchery-process.md and follow every instruction from the beginning.
4. Delete /tmp/hatchery-process.md when the session is complete.
