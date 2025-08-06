# Hello World Examples

This repository contains "Hello World" examples in multiple programming languages. Below are instructions on how to run each file in a terminal.

## TOML (hello.toml)
```bash
# TOML is a data format, not an executable language
# To view the file:
cat hello.toml
# To parse and use with a TOML parser (e.g., with Python and tomli):
# python -c "import tomli; print(tomli.loads(open('hello.toml', 'rb').read()))"
```

## Hack (hello.hack)
```bash
# Assuming HHVM is installed
hhvm hello.hack
```

## MATLAB (hello.m)
```bash
# Run with MATLAB
matlab -nodisplay -nosplash -nodesktop -r "run('hello.m'); exit;"
# Or with Octave (MATLAB alternative)
octave --no-gui --quiet hello.m
```

## Flutter/Dart (hello.dart)
```bash
# Run as plain Dart
dart hello.dart

# To run as Flutter app (requires Flutter SDK and project setup):
# flutter create hello_flutter
# cp hello.dart hello_flutter/lib/main.dart
# cd hello_flutter
# flutter run
```

## Lua (hello.lua)
```bash
# Run with Lua interpreter
lua hello.lua
```

## Crystal (hello.cr)
```bash
# Run with Crystal interpreter
crystal hello.cr

# Or compile and run
crystal build hello.cr
./hello
```

## Haskell (hello.hs)
```bash
# Run with GHCi interpreter
ghci hello.hs -e main

# Or compile and run
ghc hello.hs
./hello
```

## TypeScript (hello.ts)

```bash
# Install TypeScript if not installednpm install -g typescript# Compile TypeScript to JavaScripttsc hello.ts# Run the compiled JavaScriptnode hello.js
```

## Shell Script (hello.sh)

```bash
# Add execute permissionchmod +x hello.sh# Run the script./hello.sh
```

## SQL (hello.sql)

```bash
# Run with SQLitesqlite3 < hello.sql# Or with PostgreSQLpsql -c "$(cat hello.sql)"# Or with MySQLmysql -e "$(cat hello.sql)"
```

## C# (hello.cs)

```bash
# Compile with Monomcs hello.cs# Run the compiled executablemono hello.exe# Or with .NET Coredotnet new console -o tempcp hello.cs temp/Program.cscd tempdotnet runcd ..
```

## Go (hello.go)

```bash
# Run directlygo run hello.go# Or compile and rungo build hello.go./hello
```

## Rust (hello.rs)

```bash
# Compilerustc hello.rs# Run the compiled executable./hello
```

## PowerShell Script (hello.ps1)

```bash
# Run with PowerShellpwsh -File hello.ps1
```

## Assembly (hello.asm)

```bash
# Assemble with NASMnasm -f elf64 hello.asm -o hello.o# Linkld hello.o -o hello_asm# Run./hello_asm
```

## Swift (hello.swift)

```bash
# Run with Swift interpreterswift hello.swift# Or compile and runswiftc hello.swift -o hello_swift./hello_swift
```

## Kotlin (hello.kt)

```bash
# Compilekotlinc hello.kt -include-runtime -d hello.jar# Runjava -jar hello.jar
```

## Java (HelloWorld.java)
```bash
# Compile
javac HelloWorld.java
# Run
java HelloWorld
```

## Ruby (hello.rb)
```bash
# Run with Ruby interpreter
ruby hello.rb
```

## Perl (hello.pl)
```bash
# Add execute permission
chmod +x hello.pl
# Run the script
./hello.pl
# Or run with Perl interpreter
perl hello.pl
```

## YAML (hello.yaml)
```bash
# YAML is a data format, not an executable language
# To view the file:
cat hello.yaml
# To parse and use with a YAML parser (e.g., with Python and PyYAML):
# python -c "import yaml; print(yaml.safe_load(open('hello.yaml')))"
```

## Simple Dart (hello_simple.dart)
```bash
# Run with Dart interpreter
dart hello_simple.dart
```

## Robot Framework (hello.robot)
```bash
# Run with Robot Framework
robot hello.robot
```

Feel free to modify these examples or use them as templates for your own projects!