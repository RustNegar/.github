<table>
<tr>
<td width="120" valign="middle">
<img src="assets/logo.png" width="100" height="100" alt="RustNegar logo" style="border-radius: 20px;">
</td>
<td valign="middle">

# RustNegar

_A Rust toolkit for bidirectional text in the terminal_

</td>
</tr>
</table>

RustNegar is a collection of open-source Rust tools that solve the challenge of displaying bidirectional (RTL) text — Persian, Arabic, and Hebrew — inside the terminal.

Its flagship project, **دوسو** (_Dosu_, Persian for "two-way" — also the everyday name for a double-ended screwdriver, flathead on one side and Phillips on the other, hence the logo), wraps any terminal session and reorders RTL/LTR text correctly on the fly, without breaking the tools you already use.

---

## Projects

- **[dosu](https://github.com/RustNegar/dosu)** — the terminal wrapper; the main entry point for users
- **[dosu-core](https://github.com/RustNegar/dosu-core)** — the core engine: PTY handling, terminal grid, bidi algorithm (UAX #9), renderer

## Supported Languages

Persian, Arabic, and Hebrew (RTL), alongside English and other LTR languages.
