---
description: Update — fetch latest scaffold and apply improvements
---
Fetch the latest scaffold from CrayForge, compare with local files, and apply approved changes.
1. curl -sL "https://crayforge.com/hatchery/v1/scaffold.zip" -o /tmp/hatchery-update.zip
2. If the download fails, tell the founder: "Cannot reach CrayForge. Check your connection."
3. Extract to /tmp/hatchery-update/, compare with local files, present changes for approval.
4. Never overwrite files containing real business data.
