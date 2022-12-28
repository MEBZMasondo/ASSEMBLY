

# STARTING OUT
- Get DOSBOX program and the TASM zipped folder
- Install DOSBOX  [TODO: DOSBOX LINK]
- Unzip TASM into C drive [TODO: TASM LINK]

# BASIC FILES ORIGINALLY IN THE TASM FOLDER 
- ioasm.lib
- readsint.asm
- TASM
- TLINK
- writesint.asm

# TIPS
## REFRESHING
- CTRL + F4 = to update/refresh changes done in the TASM folder (added a new file, refresh before you assembly, link and run)  

# SNIPPET
## BASICS

## Mounting 
- mount c: c:\tasm               ; 
- OR mount h: c:\tasm\
- c:
- dir

- Write your program code and save as file_name.asm  (eg hello.asm)
- save in the 'TASM' unzipped folder (Recommend to save the 'TASM' folder on C drive)
- tasm hello 	; 2x files hello.asm, HELLO.OBJ
- tlink hello ; 2x more files HELLO.EXE, HELLO.MAP   ; Total of 4 files 
- hello		; runs the executable

## I/O LIBRAY or EXTERNAL ROUTINES 
- USES THE FILE aoasm.lib 
- readsint.asm & writesint.asm

- tasm ioex
- tlink ioex ioasm.lib  ; ERROR if only tlink ioex
- ioex

