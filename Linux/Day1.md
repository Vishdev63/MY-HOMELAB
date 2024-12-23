# 👋 Welcome to My DevOps Journey - Day 1: Linux Fundamentals

Hey there! If you're reading this, you're probably starting your DevOps journey just like me. Today, I want to share what I learned about Linux fundamentals. Trust me, these basics will be super helpful as we progress!

## 🎯 What I Learned Today

Let me walk you through everything I picked up in my first day of learning Linux. Don't worry if it seems like a lot - we'll break it down together!

## 📁 Playing with Files

### Creating and Managing Files

Remember when we were kids creating blank paper to draw? That's basically what `touch` does! Here's how I learned to use it:

```bash
touch my_first_file.txt    # Creates an empty file
```

Want to copy files? It's as easy as copy-paste in Windows, but we use `cp`:

```bash
cp original.txt backup.txt    # I like to keep backups!
```

Need a new folder? `mkdir` is your friend:

```bash
mkdir my_projects    # This is where I store all my work
```

### 🔍 Finding Lost Files

Ever lost a file? These commands saved me:

- Using `find` (it's like a detective):
  ```bash
  find /home -name "*.txt"    # Helps me find all my text files
  ```

- Using `locate` (it's super fast but needs an updated database):
  ```bash
  locate my_file    # Quick search that saved me so much time!
  ```

### ⭐ Cool Trick: Wildcards!

These are like search shortcuts. Think of them as "fill in the blank" tools:

```bash
ls *.txt      # Shows all my text files
rm test*      # Removes all files starting with 'test'
```

## 🔗 Creating Links

I learned there are two types of links (think of them as shortcuts):

1. Soft Links (like Windows shortcuts):
   ```bash
   ln -s target_file shortcut    # Creates a shortcut to my file
   ```

2. Hard Links (more like a copy that stays updated):
   ```bash
   ln target_file hard_link      # Creates a hard link
   ```

## 🔑 Security Stuff

### Changing Passwords

Keeping things secure! Here's how I learned to change passwords:

```bash
passwd    # Changed my own password
```

### Setting Up SSH

This is how I set up remote access (feels like magic!):

```bash
sudo apt-get update
sudo apt-get install openssh-server    # Lets me connect from anywhere
```

## 💾 Checking Storage

Want to know how much space you have?

```bash
df -h    # Shows storage in human-readable format
```

## ✍️ Text Editing with vi

I'm still getting used to vi, but here are the basics I learned:

```bash
vi file.txt    # Opens the file
i             # Lets me type
Esc           # Stops typing mode
:wq           # Saves and quits
```

## 📝 My Personal Tips

1. Always double-check before deleting files
2. Keep your passwords strong
3. Make backups of important files
4. Name your files clearly
5. Practice these commands regularly

## 🎯 What's Next?

Tomorrow I'm planning to learn about:

- File permissions (chmod and chown)
- Process management
- More about package management
- Environment variables

## 🤔 Need Help?

If you're stuck on any command, just type:

```bash
man command_name    # Shows you all the details
```

