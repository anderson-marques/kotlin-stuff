# Kotlin

## Requirements

1. Java SDK
2. Kotlin Compiler

## How to install

- First install SDKMAN `curl -s https://get.sdkman.io | bash`
- Then install the Kotlin compiler `sdk install kotlin`

## How to Compile

The Kotlin source code extension is `.kt`. To compile a file you use the `kotlinc` command.

Example:

```bash
$ kotlinc code.kt -include-runtime -d package.jar
```
