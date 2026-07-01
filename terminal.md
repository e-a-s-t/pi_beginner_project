# Introduction to the Terminal

The terminal is one of the most powerful tools available on Linux. While it may seem unfamiliar at first, you'll quickly find that many development and administration tasks are faster from the command line than from a graphical interface.

> [!TIP]
> Don't be afraid to experiment. Most commands simply display information and won't change anything.

---

## Opening a Terminal

- **Windows:** Open **Git Bash**.
- **Linux:** Open your preferred terminal application.
- **macOS:** Open **Terminal**.

---

## Where Am I?

Display your current working directory.

```bash
pwd
```

---

## List Files

Show the files and directories in the current location.

```bash
ls
```

Show additional information.

```bash
ls -lh
```

Show hidden files.

```bash
ls -la
```

---

## Change Directory

Move into another directory.

```bash
cd Documents
```

Go back one level.

```bash
cd ..
```

Go to your home directory.

```bash
cd
```

---

## Create a Directory

```bash
mkdir my-project
```

Move into it.

```bash
cd my-project
```

---

## Create a File

```bash
touch hello.txt
```

Verify that it exists.

```bash
ls
```

---

## View a File

```bash
cat hello.txt
```

---

## Copy a File

```bash
cp hello.txt hello-copy.txt
```

---

## Rename or Move a File

```bash
mv hello-copy.txt greetings.txt
```

---

## Delete a File

```bash
rm greetings.txt
```

Be careful—deleted files cannot easily be recovered.

---

## Command History

Use the **Up Arrow** to recall previous commands.

You can also view your history:

```bash
history
```

---

## Auto-completion

Press the **Tab** key while typing a file or directory name.

Example:

```text
cd Doc<Tab>
```

The terminal will complete the name if possible.

---

## Get Help

Many commands provide built-in help.

```bash
command --help
```

Example:

```bash
ls --help
```

On Linux, you can also use:

```bash
man ls
```


---

## Editing Text Files

Sooner or later you'll need to edit configuration files or write code. There are many editors to choose from.

| Editor | Typical use | Notes |
|--------|-------------|-------|
| **nano** | Terminal | Simple terminal editor. Usually installed by default on Linux. Great for quick edits. |
| **Zed** | Desktop (GUI) | Fast, modern, and lightweight graphical editor. A great choice for learning programming. |
| **vim** | Terminal | Extremely powerful editor available on almost every Linux system. It has a steep learning curve but is well worth learning over time. |
| **neovim** | Terminal | A modern version of Vim with many improvements, plugins, and an active community. |


> [!TIP]
> If you're just getting started, use **nano** for quick edits in the terminal and **Zed** for programming. As you become more comfortable with Linux, consider learning **vim** or **neovim**.

> [!NOTE]
> Author's Note: I use vim daily. It has a reputation for being difficult to learn and that's mostly true, but once it clicks, it's an incredibly efficient editor. If you're curious, give it a try later. There's no rush.
 
---

## Exit the Terminal

```bash
exit
```

or simply close the terminal window.

---

## Next Steps

Once you're comfortable navigating the terminal, continue with:

- Git and GitHub
- SSH
- Raspberry Pi administration
- Homebrew
