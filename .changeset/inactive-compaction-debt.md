---
"@martian-engineering/lossless-claw": patch
---

Add backup-first, single-conversation offline draining for deferred compaction debt left behind after a conversation is archived. The new read-only maintenance view identifies inactive debt, while confirmed drains retain raw messages and refuse active targets.
