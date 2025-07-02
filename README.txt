
Ibery Programming Language
============================

A smart, simple, and AI-assisted programming language made by Bilta.

----------------------------------------
What is Ibery?
----------------------------------------
Ibery is an experimental and lightweight programming language designed for simplicity, readability, and smart features.
It supports basic arithmetic, user input, conditional logic, and even built-in AI prompts — all in a syntax anyone can understand.

NOTE: This version is for testing and educational purposes only.

----------------------------------------
Features
----------------------------------------
- txt{}        → prints messages or variables
- inp{}        → asks user input
- Variables    → x = 10
- Arithmetic   → sum = a + b, total = x * y
- Conditionals → if{a == b} ... endif
- AI support   → ai{"Suggest something creative"}
- CLI execution: berry --run filename.berry

----------------------------------------
Installation (macOS Only)
----------------------------------------
Option 1: (Coming soon)
    brew install --cask ibery.pkg

Option 2: Manual Install
    1. Download ibery.pkg
    2. Double-click to install
    3. Done! Run:
        berry --run yourcode.berry

----------------------------------------
Project Structure (Development)
----------------------------------------
ibery/
├── bin/                → Compiled berry binary
├── source/             → compiler.c source code
├── Scripts/            → postinstall script
├── Resources/          → welcome.txt and other files
├── test.berry          → Example Ibery program
└── ibery.pkg           → Installer package

----------------------------------------
Sample Code (test.berry)
----------------------------------------
txt{Welcome to Ibery!}
inp{name}
txt{Hello}
txt{name}

----------------------------------------
How to Use
----------------------------------------
1. Create a .berry file:
    touch hello.berry

2. Add Ibery code to it.

3. Run it:
    berry --run hello.berry

----------------------------------------
Documentation
----------------------------------------
Coming soon at https://ibery.org
Dark themed, high contrast, interactive tutorials (like W3Schools).

----------------------------------------
Note
----------------------------------------
- Ibery is in alpha.
- For testing and learning only.
- Made by Bilta.

----------------------------------------
Future Plans
----------------------------------------
- Full AI integration
- GUI-based editor
- Cross-platform builds
- Online playground
- Package manager

----------------------------------------
License
----------------------------------------
MIT License
(c) 2025 Bilta
