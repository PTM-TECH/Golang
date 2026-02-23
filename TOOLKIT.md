## Moringa AI Capstone Project

# Prompt-Powered Kickstart: Building a Beginner’s Toolkit for Go (Golang)
## Title & Objective

# Getting Started with Go - Beginner’s Toolkit with a Simple Start Project

The primary objective is to learn Go using generative AI prompts and build a simple as well runnable program that prints a message in the terminal.

I chose Go due to the following reasons:

- It’s simple and has readable syntax
- It’s beginner friendly yet industry relevant
- It’s strongly used in backend and cloud engineering.
- It’s a fast compiled language
My end goal is to create and successfully run a Go program that displays 3 message in the terminal.

# Quick Summary of the Go Technology

Go is an open-source programming language developed at Google in 2009.
It’s compiled, statically typed, and designed for simplicity and performance.

Go is mainly used in building:
- Backend APIs
- Cloud native systems
- DevOps tools,
- CLI application.

Real world example
- Uber and Google. 
- Majorly used for scalable backend services.

# System Requirements

Operating System:
Linux
macOS
Windows
# Tools/Editors needed:

Vs code
Terminal
No external packages required

# Installation & Setup Instructions

# Linux Installation (Using Terminal)
Remove Old Vesion (if any): sudo rm -rf /usr/local/go
Download Go: wget https://go.dev/dl/go1.21.5.linux-amd64.tar.gz
Extract: sudo tar -C /usr/local -xzf go1.21.5.linux-amd64.tar.gz
Add Go to PATH: echo 'export PATH=$PATH:/usr/local/go/bin' >> ~/.profile
source ~/.profile
Verify Installation: go version
Expected outcome: go version go1.21.5 linux/amd64

# Windows installation
Download MSI installer from: https://go.dev/dl/
Run installer
Verify in Command Prompt: go version

# macOS Installation
Download .pkg installer from https://go.dev/dl/
Verify: go version

# Minimal Working Example
The example below confirms Go is installed correctly and demonstrates basic program structure.

package main //Defines the main package

import "fmt" //Imports formatting package

// Program entry point
func main() {
   fmt.Println("Hello, I'm Patrick Mutua") //prints message to the terminal
   fmt.Println("A junior software engineer") //prints message to the terminal
   fmt.Println("I'm learning Golang") //prints message to the terminal
}

Run the program: go run main.go

Expected Outcome

➜  Go go run main.go
Hello, I'm Patrick Mutua
A junior software engineer
I'm learning Golang
➜  Go 

## AI Prompt Journal

# Prompt 1:
Prompt used: 
“Explain Go programming language to a beginner. Include syntax basics and use cases.”
Response:
Explained compiled language concept, static typing, and backend use cases.
Evaluation:
Helpful for foundational understanding before setup.

# Prompt 2:
Prompt used:
“Provide step-by-step installation instructions for Go on Linux using terminal commands.”
Response: 
Provided get download, extraction, PATH configuration, and verification steps.
Evaluation:
Very helpful in avoiding PATH errors.

# Prompt 3:
Prompt used:
“Help me write a simple Go program that prints (Hello, I’m Patrick Mutua, A junior software engineer, I’m learning Golang) in the terminal line by line,  and explain how to run it in VS Code.”
Response: 
Generated working code and explained go run.
Evaluation:
Allowed quick confirmation of installation success.

# Prompt 4:
Prompt used:
“I get ‘command not found: go’ after installation. How do I fix it?”
Response:
Explained environment variable setup and restarting terminal.
Evaluation
Resolved installation issue immediately.
Common issues & Fixes
1. Issue: Go command not found
Cause: PATH not configured
Fix Add /usr/local/go/bin to PATH
2. Issue: Syntax error
Cause: Case-Sensitive keywords
Fix: Ensure package main and func main() are well written
3. Issue: file not running
Cause: wrong directory
Fix: Run inside the project’s folder

# Helpful links to forums
StackOverflow: https://stackoverflow.com
Go Forum: https://forum.golangbridge.org

# References
Official Docs: https://go.dev/doc/
Video Tutorials: Go Crash Course (YouTube)
Helpful Blog Post: Go by Example: https://gobyexample.com

# AI Prompt Usage Expectations
During this project, I:
Experimented with different prompts
Refined prompts when installation errors occured
Used AI to debug environmental issues
Improved clarity and reduced research time
Overally, AI significantly increased productivity by simplifying installation, debugging, and structuring documentation professionally.
