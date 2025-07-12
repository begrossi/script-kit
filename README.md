# script-kit

A curated set of shell scripts I use daily to streamline workflows, automate tasks, and boost productivity.  
Continuously evolving with practical, no-bullshit solutions that do exactly what they’re supposed to—nothing more, nothing less.

## ✅ What It Is

A flat collection of executable shell scripts. No frameworks. No package managers. Just drop it into your `~/bin`, put that on your `PATH`, and go.

Each script solves a real-world problem I’ve run into. If it didn’t earn its place, it’s not here.

## 🧠 Philosophy

- **Minimal overhead** – no dependencies unless absolutely necessary.
- **Immediate utility** – every script exists because it saves time.
- **Plain Bash** – portable, tweakable, readable.
- **No hand-holding** – you’re expected to know what you’re doing.

## 📦 Installation

Clone and link or copy to a directory in your `PATH`, like `~/bin`.

```bash
git clone https://github.com/begrossi/script-kit.git ~/bin
cd ~/bin
chmod +x *
````

Make sure `~/bin` is on your `PATH`:

```bash
echo 'export PATH="$HOME/bin:$PATH"' >> ~/.bashrc   # or ~/.zshrc
source ~/.bashrc
```

## 🛠 Usage

Just run them from anywhere in your terminal:

```bash
some-script-name
```

Scripts are self-contained and meant to be edited, extended, or adapted as needed.

## 🔄 Work in Progress

This repo is always evolving. I add new tools when I need them and prune what’s obsolete.
Expect practical, raw, working code—not polish for polish’s sake.

## ⚠️ Disclaimer

These scripts work for me. They might work for you. They might eat your data.
Use common sense. Review the code before running anything. No warranties, no support, no bullshit.

---

**Fast tools. Sharp edges. Handle accordingly.**
