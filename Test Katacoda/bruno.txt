 1  hello-world/finish.md 
@@ -0,0 +1 @@
You've completed your first Katacoda scenario!
  26  hello-world/index.json 
@@ -0,0 +1,26 @@
{
  "title": "Hello Fufu Scenario",
  "description": "Your First Scenario",
  "difficulty": "beginner",
  "time": "2 minutes",
  "details": {
    "steps": [{
      "title": "Step 1 - Run Command",
      "text": "step1.md"
    }],
    "intro": {
      "text": "intro.md",
      "credits": ""
    },
    "finish": {
      "text": "finish.md"
    }
  },
  "environment": {
    "uilayout": "terminal",
    "uimessage1": "\u001b[32mYour Interactive Bash Terminal.\r\nStart Kubernetes using `launch.sh`\u001b[m\r\n"
  },
  "backend": {
    "imageid": "bash"
  }
}
 
 1  hello-world/intro.md 
@@ -0,0 +1 @@
Welcome to your first Katacoda Scenario!
 
 7  hello-world/step1.md 
@@ -0,0 +1,7 @@
This is your first step.

## Task

This is an _example_ of creating a scenario and running a **command**

`echo 'Hello World'`{{execute}}