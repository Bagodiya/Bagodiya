<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:f97316&height=190&section=header&text=Sofiya%20Bagodiya&fontColor=ffffff&fontSize=46&fontAlignY=36&desc=Compilers%20%C2%B7%20Program%20analysis%20%C2%B7%20Software%20security&descSize=18&descAlignY=58" width="100%"/>

<a href="https://github.com/Bagodiya">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&pause=1000&color=F97316&center=true&vCenter=true&width=620&lines=PhD+student+%40+Stevens+Institute+of+Technology;I+build+compilers+and+the+tools+that+analyze+them;MLIR+%C2%B7+LLVM%2FClang+%C2%B7+symbolic+execution+%C2%B7+taint+analysis" alt="typing" />
</a>

<br/>

[![Email](https://img.shields.io/badge/sbagodiy%40stevens.edu-0d1117?style=flat-square&logo=gmail&logoColor=f97316&labelColor=0d1117)](mailto:sbagodiy@stevens.edu)
[![Profile views](https://komarev.com/ghpvc/?username=Bagodiya&style=flat-square&color=f97316&label=profile+views)](https://github.com/Bagodiya)

</div>

---

### `> whoami`

```text
role     PhD student, Stevens Institute of Technology
working  compiler internals, static/dynamic program analysis, software security
lately   MLIR-based language design, LLVM analysis passes, LLM-assisted vuln finding
stack    C++17 · LLVM/Clang · MLIR · Python · Z3
```

I care about the part of compilers most tutorials skip — what happens *after* the AST.
Custom IR dialects, optimization passes, register allocation, codegen, and the analyses
that reason about programs to find bugs and security flaws. Most of what I build is a
working artifact: a language that JITs, a pass that runs, a checker that fires on real code.

---

### 🛠 Tech

![C++](https://img.shields.io/badge/C++17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![LLVM](https://img.shields.io/badge/LLVM-262D3A?style=flat-square&logo=llvm&logoColor=white)
![MLIR](https://img.shields.io/badge/MLIR-FF6F00?style=flat-square&logo=llvm&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Z3](https://img.shields.io/badge/Z3_SMT-512BD4?style=flat-square&logo=microsoft&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Targets](https://img.shields.io/badge/x86--64_/_ELF_/_Mach--O-444444?style=flat-square&logo=gnu&logoColor=white)

---

### 📌 Selected work

<table>
<tr><td width="50%" valign="top">

**[ignis](https://github.com/Bagodiya/ignis)** &nbsp;·&nbsp; C++ · MLIR
> A statically-typed compiled language built on **MLIR**. Custom `ignis` dialect
> defined in ODS/TableGen with verifiers and folders, a multi-stage dialect-conversion
> pipeline down to the LLVM dialect, a hand-written optimization pass (const-fold + DCE),
> and **both a JIT and an AOT backend**.

</td><td width="50%" valign="top">

**[compiler-backend-from-scratch](https://github.com/Bagodiya/Compiler-backend-from-scratch)** &nbsp;·&nbsp; C++
> A chapter-by-chapter optimizing backend: IR → SSA → optimization passes →
> register allocation → **x86-64 assembly that assembles and runs**. The part every
> other tutorial waves its hands at, written out in full.

</td></tr>
<tr><td width="50%" valign="top">

**[llvm-vuln-detector](https://github.com/Bagodiya/llvm-vuln-detector)** &nbsp;·&nbsp; C++ · LLVM
> An out-of-tree LLVM pass doing flow-sensitive dataflow over each function's CFG to
> find **use-after-free (CWE-416), double-free (CWE-415), and null-deref (CWE-476)**,
> reporting CWE id, severity, and source location.

</td><td width="50%" valign="top">

**[TaintVuln](https://github.com/Bagodiya/TaintVuln)** &nbsp;·&nbsp; C++ · Clang SA
> A **path-sensitive Clang Static Analyzer checker** on top of the analyzer's
> ExplodedGraph. Tracks attacker-controlled data to dangerous sinks (command
> injection, format string, tainted alloc size). Interprocedural and sanitizer-aware.

</td></tr>
<tr><td width="50%" valign="top">

**[mini-klee](https://github.com/Bagodiya/mini-klee)** &nbsp;·&nbsp; Python · Z3
> A **symbolic execution engine** for a C-like language. Explores paths, accumulates
> a path condition, and uses **Z3** to decide feasibility, solve for triggering inputs,
> and catch assertion / out-of-bounds violations.

</td><td width="50%" valign="top">

**[minidec](https://github.com/Bagodiya/minidec)** &nbsp;·&nbsp; C++
> A small **decompiler** for x86-64 ELF and Mach-O binaries. Disassembles functions
> (Capstone), recovers control flow and basic types (LIEF), and emits readable
> C-like pseudocode — Ghidra/Hex-Rays internals, made approachable.

</td></tr>
</table>

<sub>Also: <a href="https://github.com/Bagodiya/regex-engine">regex-engine</a> (Thompson NFA + Pike VM, linear-time, zero backtracking) ·
<a href="https://github.com/Bagodiya/compiler-optimization-visualizer">compiler-optimization-visualizer</a> ·
<a href="https://github.com/Bagodiya/vulnagent">vulnagent</a> (SSVC-style CVE prioritization over 164,929 CVEs)</sub>

---

### 📊 GitHub

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Bagodiya&show_icons=true&hide_border=true&bg_color=0d1117&title_color=f97316&icon_color=f97316&text_color=c9d1d9&include_all_commits=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Bagodiya&layout=compact&hide_border=true&bg_color=0d1117&title_color=f97316&text_color=c9d1d9&langs_count=8" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Bagodiya/Bagodiya/output/snake-dark.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/Bagodiya/Bagodiya/output/snake.svg" />
</picture>

</div>

<div align="center"><sub>📫 <a href="mailto:sbagodiy@stevens.edu">sbagodiy@stevens.edu</a></sub></div>
