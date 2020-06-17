# MASM-autolinker
Automates assembler, linker and optionally debugger

To use this script, copy this script to the masm directory, containing MASM.EXE, LINK.EXE and TD.EXE.
Open DOSBOX, cd to directory and run exec help

Examples:
```bash
  exec help     ; opens help for exec
  exec foo notd ; runs autoexec routine for foo.asm and returns foo.obj and foo.exe
  exec foo      ; runs autoexec routine as before and opens turbodebugger for resulting executable
```
