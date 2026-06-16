<div align="center">

<img src="https://img.shields.io/badge/version-0.1.0--alpha-orange?style=for-the-badge" />
<img src="https://img.shields.io/badge/language-Rust-orange?style=for-the-badge&logo=rust" />
<img src="https://img.shields.io/badge/backend-LLVM-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/license-MIT-green?style=for-the-badge" />
<img src="https://img.shields.io/badge/tests-51%2B%20passing-brightgreen?style=for-the-badge" />
<img src="https://img.shields.io/badge/origin-Tamil%20Nadu%2C%20India-red?style=for-the-badge" />

<br/><br/>

```
██████╗ ██╗   ██╗██╗   ██╗██╗
██╔══██╗██║   ██║██║   ██║██║
██████╔╝██║   ██║██║   ██║██║
██╔═══╝ ██║   ██║╚██╗ ██╔╝██║
██║     ╚██████╔╝ ╚████╔╝██║
╚═╝      ╚═════╝   ╚═══╝ ╚═╝
```

# புவி — Puvi

### **Python Readability. Rust Safety. Native Performance.**
#### *The World's First Tamil-First Systems Programming Language*

**[🌐 puvilang.in](https://puvilang.in)** · **[📖 Docs](#)** · **[💬 Discord](#)** · **[🐦 Twitter](#)**

<br/>

> *"Code in the language you think in."*
> — Built from Tamil Nadu, for the world 🌍

</div>

---

## 🤔 Why Puvi?

Every major programming language was born from a specific culture and speaks one language — **English**.

Puvi challenges that assumption.

A developer in Madurai should be able to write production-grade systems software in **Tamil** — not as a workaround, not as a toy, but as a **first-class citizen of the compiler**.

Puvi is not a translation layer. It is not an educational toy. It is a **next-generation systems programming language** that treats Tamil as equal to English at the compiler level.

---

## ✨ What Makes Puvi Different

### 🔀 One Language. Three Syntaxes. Same Compiler.

This is Puvi's defining innovation — **all three forms compile to the exact same AST:**

| English | Tanglish | Tamil |
|---|---|---|
| `let age = 20` | `mathippu vayathu = 20` | `மதிப்பு வயது = 20` |
| `fn add(a, b)` | `pani kootu(a, b)` | `செயல் கூட்டு(a, b)` |
| `return a + b` | `thiruppu a + b` | `திருப்பு a + b` |
| `if age > 18` | `endraal vayathu > 18` | `வயது > 18 என்றால்` |
| `print("Hello")` | `sol("Hello")` | `சொல்("Hello")` |

> No other production programming language in the world does this.

---

## 🚀 Quick Start

```bash
# Install Puvi
curl -sSf https://puvilang.in/install.sh | sh

# Create your first program
puvi new my_project
cd my_project

# Run it
puvi run
```

---

## 📝 Code Examples

### Hello World — Three Ways

**English:**
```puvi
let name = "World"
print("Hello, " + name)
```

**Tanglish:**
```puvi
mathippu peyar = "Ulagam"
sol("Vanakkam, " + peyar)
```

**Tamil:**
```puvi
மதிப்பு பெயர் = "உலகம்"
சொல்("வணக்கம், " + பெயர்)
```

---

### Functions

**English:**
```puvi
fn add(a, b)
  return a + b
end

let result = add(10, 20)
print(result)
```

**Tamil:**
```puvi
செயல் கூட்டு(a, b)
  திருப்பு a + b
முடிவு

மதிப்பு விடை = கூட்டு(10, 20)
சொல்(விடை)
```

---

### Conditionals

**Tanglish:**
```puvi
mathippu vayathu = 20

endraal vayathu > 18
  sol("Petravargal")
illaiyenil
  sol("Kuraivu vayathu")
mudivu
```

**Tamil:**
```puvi
மதிப்பு வயது = 20

வயது > 18 என்றால்
  சொல்("பெரியவர்")
இல்லையெனில்
  சொல்("சிறியவர்")
முடிவு
```

---

## 🏗️ Architecture

```
Source Code (.puvi)
        │
        ▼
   ┌─────────┐
   │  Lexer  │  ← Handles English / Tanglish / Tamil tokens
   └────┬────┘
        │
        ▼
   ┌─────────┐
   │  Parser │  ← Builds unified AST from all three syntaxes
   └────┬────┘
        │
        ▼
   ┌──────────────────┐
   │ Semantic Analyzer│  ← Symbol Table + Diagnostics
   └────┬─────────────┘
        │
        ▼
   ┌──────────────┐
   │ Type Checker │  ← (In Progress)
   └────┬─────────┘
        │
        ▼
   ┌──────────────────────┐
   │ Intermediate Repr.   │  ← (Planned)
   └────┬─────────────────┘
        │
        ▼
   ┌───────────────┐
   │ LLVM Backend  │  ← (Planned) — Native binary generation
   └────┬──────────┘
        │
        ▼
  Native Executable
  (Windows / Linux / macOS)
```

---

## ✅ Current Status

### Compiler Components

| Component | Status |
|---|---|
| Lexer | ✅ Complete |
| Parser | ✅ Complete |
| AST | ✅ Complete |
| Semantic Analyzer | ✅ Complete |
| Expression Parsing | ✅ Complete |
| Binary Expressions | ✅ Complete |
| Unary Expressions | ✅ Complete |
| Function Declarations | ✅ Complete |
| Function Calls | ✅ Complete |
| Boolean Literals | ✅ Complete |
| Comparison Operators | ✅ Complete |
| If / Else Statements | ✅ Complete |
| Symbol Table | ✅ Complete |
| Diagnostics System | ✅ Complete |
| While Loops | 🔄 In Progress |
| Strings | 🗓️ Planned |
| Type Checker | 🗓️ Planned |
| IR Generation | 🗓️ Planned |
| LLVM Backend | 🗓️ Planned |
| Native Binary Output | 🗓️ Planned |

**51+ compiler tests passing.**

---

## 🗺️ Roadmap

```
2024 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  Q3 ✅  Lexer · Parser · Semantic Analysis · Expressions · Functions · If/Else

  Q4 🔄  While Loops · Strings · Type Checker

2025 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  Q1     IR Generation · LLVM Backend · First Native Binary

  Q2     VS Code Extension · LSP Support · Basic Standard Library

  Q3     Package Manager · Documentation Site (puvilang.in)

  Q4     Public Alpha · Community Launch · Open Source Release
```

---

## 📦 Standard Library (Planned)

### Core
| Function | Description |
|---|---|
| `sol()` | Print to console |
| `ulleedu()` | Read input |
| `neelam()` | Get length |
| `vagai()` | Get type |

### Math
| Function | Description |
|---|---|
| `ver()` | Square root |
| `sin()` | Sine |
| `cos()` | Cosine |

### File I/O
| Function | Description |
|---|---|
| `vasi()` | Read file |
| `ezhuthu()` | Write file |
| `ser()` | Append to file |

### AI (via `arivu` module)
```puvi
use arivu

let result = arivu.think("What is the weather today?")
sol(result)
```

---

## 🌐 Planned Platforms

| Platform | Status |
|---|---|
| Linux | 🗓️ Planned |
| macOS | 🗓️ Planned |
| Windows | 🗓️ Planned |
| WebAssembly | 🔮 Future |
| Android | 🔮 Future |
| Embedded / Edge AI | 🔮 Future |

---

## 🧩 Planned Tooling

- **VS Code Extension** — Syntax highlighting, autocomplete, error diagnostics
- **Language Server Protocol (LSP)** — IDE support for any editor
- **Package Manager** — Install and share Puvi libraries
- **Documentation Platform** — Full reference at puvilang.in
- **Puvi Playground** — Try Puvi in the browser, no install needed

---

## 🔑 Keyword Reference

| English | Tanglish | Tamil |
|---|---|---|
| `let` | `mathippu` | `மதிப்பு` |
| `fn` | `pani` | `செயல்` |
| `return` | `thiruppu` | `திருப்பு` |
| `if` | `endraal` | `என்றால்` |
| `else` | `illaiyenil` | `இல்லையெனில்` |
| `while` | `varai` | `வரை` |
| `true` | `unmai` | `உண்மை` |
| `false` | `poi` | `பொய்` |
| `print` | `sol` | `சொல்` |
| `end` | `mudivu` | `முடிவு` |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Compiler Implementation | Rust |
| Backend (Planned) | LLVM |
| IDE Support (Planned) | LSP |
| AI Module (Planned) | `arivu` |

---

## 🤝 Contributing

Puvi is being built in the open. Contributions are welcome.

```bash
# Clone the repo
git clone https://github.com/puvilang/puvi
cd puvi

# Build the compiler
cargo build

# Run tests
cargo test

# Run a Puvi file
cargo run -- run examples/hello.puvi
```

Whether you write Rust, know compiler theory, speak Tamil, or just believe in the vision — **there is a place for you in this project.**

---

## 📄 License

MIT License — see [LICENSE](./LICENSE) for details.

---

## 💬 Community

| Platform | Link |
|---|---|
| 🌐 Website | [puvilang.in](https://puvilang.in) |
| 🐦 Twitter / X | [@puvilang](#) |
| 💬 Discord | [Join Server](#) |
| 📧 Email | hello@puvilang.in |

---

<div align="center">

**Built with ❤️ from Tamil Nadu, India.**

*"தமிழில் நிரல் எழுதுவோம். உலகை மாற்றுவோம்."*
*("Let us write code in Tamil. Let us change the world.")*

<br/>

⭐ **Star this repo if you believe Tamil belongs in systems programming.** ⭐

</div>
