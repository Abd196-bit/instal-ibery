# 🧠 Ibery CLI Compiler

**Ibery** is a lightweight, beginner-friendly scripting language that supports text output, arithmetic, variables, conditionals, and user input — all powered by a simple C-based compiler.

> ⚠️ Currently under development. This is a preview release for testing purposes only.

---

## 🔧 Features

- Simple syntax: `txt{}`, `inp{}`, `if{}`, variables, math
- Easy input/output for quick scripts
- Works on both **Windows** and **Linux**
- Compiled from C, runs with no dependencies

---

## 📦 Files

| File          | OS       | Description                     |
|---------------|----------|---------------------------------|
| `berry.exe`   | Windows  | Ibery compiler binary (Windows) |
| `berry`       | Linux    | Ibery compiler binary (Linux)   |
| `hello.berry` | All      | Sample Ibery program            |
| `compiler.c`  | Optional | Source code for developers      |

---

## 🚀 How to Use

### ▶ On Linux

```bash
./berry --run hello.berry
```

### ▶ On Windows

```cmd
berry.exe --run hello.berry
```

---

## 🧪 Sample Ibery Program (`hello.berry`)

```ibery
txt{Welcome to Ibery!}
inp{a}
inp{b}
sum = a + b
txt{sum}
```

---

## 📁 Build from Source (Optional)

### Linux

```bash
gcc compiler.c -o berry
```

### Windows (MinGW)

```bash
gcc compiler.c -o berry.exe
```

---

## 🏢 About

> Made by **Bilta** — A tools lab for future programming.

This project is free to use and experiment with. Feedback welcome!
