# Extraction tool

Simple script that injests a public github repository url, reads the code of all files and extracts varibles names based on patterns. Ex: in JS we can look for `const` and `let` and extract the next word to a separate file

Should it be runned in docker? The goal is cloning the repo, extract the variables and delete it. Docker is safer and more controlled environment than anyones machine.
GoLang, Rust or Node.js? - Prob GoLang
If file is too big, should it be ignored? GoLang should be able to handle it