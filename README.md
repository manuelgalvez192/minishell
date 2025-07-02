
# 🐚 minishell

**minishell** is a project from the [42Madrid](https://42madrid.com/) curriculum.  
It is a simplified version of a Unix shell written in C, built to understand how a real shell works under the hood — including command parsing, execution, environment variable management, redirections, pipes, and signal handling.

---

## ✨ Features

- ✅ Execution of built-in and external commands  
- ✅ Support for pipes (`|`) and redirections (`>`, `<`, `>>`, `<<`)  
- ✅ Environment variable management (`export`, `unset`, etc.)  
- ✅ Signal handling (`Ctrl+C`, `Ctrl+D`, `Ctrl+\`)  
- ✅ Command history (via GNU Readline)  
- ✅ Error handling and memory management

---

## 🚀 Usage

To compile and run the shell:

```bash
make
./minishell
```

Once launched, you can use it like a regular shell.
Example:
```bash
M&Mshell$ echo "Hello World" | grep Hello > out.txt
```

## 👥 Collaborators
Developed by two students from 42Madrid:

- [Mario Caro](https://github.com/mariocaro13)

- [Manuel Gálvez](https://github.com/manuelgalvez192)

Thanks to @mariocaro13 for the great collaboration!

## 📄 License
This project is for educational purposes only, developed as part of the 42 school curriculum.
