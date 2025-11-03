# InViz

**InViz** (Interactive Interpreter Visualization System) is a tool that visually demonstrates how interpreters process code step by step. It aims to make the internal workings of programming languages transparent — showing how source code moves through lexical analysis, parsing, and evaluation in real time.

## Overview

Interpreted languages like **Python** and **JavaScript** power most of today’s development workflows, yet the process by which they execute code often remains a black box. **InViz** helps bridge that gap by providing an interactive visualization of the interpretation pipeline. It’s designed for learners, educators, and developers who want to explore how interpreters actually understand and execute code.

## Features

* Real-time simulation of lexical analysis, parsing, and evaluation
* Visual representation of Abstract Syntax Trees (AST)
* Modular interpreter written in **Go**
* Educational and exploratory interface for experimenting with code
* Extensible architecture for future language support

## Tech Stack

* **Backend / Core Interpreter:** Go
* **Frontend:** To be decided (candidates include React, Angular, or Flyn)
* **Visualization:** Custom rendering or D3.js (planned)

## Getting Started

```bash
git clone https://github.com/hvardhan1024/inviz.git
cd inviz
go run main.go
```

Once the frontend is integrated, instructions for setup and communication with the backend will be added.

## Roadmap

* Add step-by-step evaluation visualization
* Support for multiple language grammars
* Integrate a web-based frontend for interaction
* Enable user-defined grammar input and live parsing
