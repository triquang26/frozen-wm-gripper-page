# Frozen Video World Models Can Follow Gripper Commands

Anonymous project page (ICLR submission, under review).

A single static `index.html` + `demo/` assets — no build step. Serve over HTTP and open it:

```bash
python -m http.server 8080   # then open http://localhost:8080
```

The page tells the story in three acts — the gripper-blindness diagnosis, the objective-level
root cause, and the interventional fix that makes a frozen 2.3B video world model render the
gripper open/close on command at preserved video quality.
