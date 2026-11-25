

# CrimIDE

**A browser-based IDE for 37 programming languages**

CrimIDE is a multi-language code editor that lets you write and run code directly in your browser. It includes a built-in Crim+ interpreter, support for a wide range of programming languages, project management, and a canvas-based output stage.

🌐 **Website:** https://crimsoncyan-code.github.io/CrimIDE/

## Features

- **37 programming languages** supported
- **Monaco Editor** for code editing
- Syntax highlighting and code formatting
- Run and stop code directly from the IDE
- Built-in Crim+ interpreter
- Multi-file projects with tabs
- Project explorer
- Import and export individual files
- Import and export complete projects
- Console with interactive input
- Canvas output stage
- Image and audio asset uploads
- Resizable editor and output panels
- Dark and light themes
- Adjustable font size, tab size, and word wrapping
- Find and replace

## Supported Languages

CrimIDE currently supports 37 languages:

| Language | Language | Language |
|---|---|---|
| Assembly (NASM) | Bash | Brainfuck |
| C | C# | C++ |
| C% | Crim+ | Go |
| Haskell | HolyC | Java |
| JavaScript | Koi | Kotlin |
| LOLCODE | Lua | Objective-C |
| OCaml | Perl | PHP |
| PowerShell | Python | R |
| Ruby | Rust | Swift |
| TypeScript | Zig | Nim |
| Dart | Prolog | Fortran |
| Elixir | Crystal | Racket |
| F# | | |

## Running Code

1. Open [CrimIDE](https://crimsoncyan-code.github.io/CrimIDE/).
2. Select a programming language from the language picker.
3. Write your code in the editor.
4. Press **Run** to execute it.
5. View the results in the Stage or Console.

Some languages use browser-based runtimes, while others use external execution services. An internet connection is required for languages that rely on remote execution.

## Projects

CrimIDE supports multi-file projects.

You can:
- Create new files
- Import existing files
- Rename and delete files
- Switch between files using tabs
- Export individual `.crim` files
- Export complete projects
- Open previously exported projects

Project files use the `.crimproj` format.

## Crim+

CrimIDE includes a built-in interpreter for **Crim+**, a programming language developed by CrimsonCyan.

Crim+ programs can be written and executed directly inside CrimIDE without needing an external interpreter.

Example:

```crim
say "Hello, world!"
```

## Output Stage

CrimIDE includes a canvas-based Stage for programs that produce visual output. Programs can also use the Console for text output and interactive input.

The Images & Audio panel lets you upload assets to use in your projects.

## Themes

CrimIDE includes two interface themes:

- Dark
- Light

You can also customize editor font size, tab size, and word wrapping.

## Credits

**Created by CrimsonCyan.**

