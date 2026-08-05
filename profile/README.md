<img src="assets/logo.png" align="left" width="140" height="140" alt="RustNegar logo" style="border-radius: 22px; margin: 4px 20px 10px 0; border: 1px solid #e1e4e8;">

# RustNegar

RustNegar is a collection of open-source Rust tools that solve the challenge of displaying bidirectional (RTL) text — Persian, Arabic, and Hebrew — inside the terminal.

Its flagship project, **دوسو** (*Dosu* — Persian for "two-directional," from *do* "two" + *su* "direction/way," a nod to the project's core focus on bidirectional text), wraps any terminal session and reorders RTL/LTR text correctly on the fly, without breaking the tools you already use.

<br clear="left"/>

## Projects

- **[dosu](https://github.com/RustNegar/dosu)** — the terminal wrapper; the main entry point for users
- **[dosu-core](https://github.com/RustNegar/dosu-core)** — the core engine: PTY handling, terminal grid, bidi algorithm (UAX #9), renderer

## Supported Languages

Persian, Arabic, and Hebrew (RTL), alongside English and other LTR languages.
