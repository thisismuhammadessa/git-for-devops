# Git Commands Cheat Sheet

## 1. Navigate to Repository

Move into the Git project directory.

```bash
cd git-for-devops/
```

---

## 2. Check Repository Status

Show the current state of the working directory.

```bash
git status
```

---

## 3. Change Repository Ownership

Give ownership of the repository to the spider user.

```bash
sudo chown -R spider:spider /home/spider/git-for-devops
```

---

## 4. View Commit History

Display commit logs.

```bash
git log
```

---

## 5. Create a New Branch

Create and switch to a new branch named dev.

```bash
git checkout -b dev
```

---

## 6. Switch Branches

Move between branches.

```bash
git checkout dev
git checkout master
```

---

## 7. Create a New File

Create an empty file.

```bash
touch test.txt
```

---

## 8. Add File to Staging Area

Stage changes for commit.

```bash
git add test.txt
```

---

## 9. Configure Git Email

Set the email address used for commits.

```bash
git config --global user.email "jressa8@gmail.com"
```

---

## 10. Commit Changes

Save staged changes to the repository.

```bash
git commit -m "added file"
```

---

## 11. View Available Branches

List all local branches.

```bash
git branch
```

---

## 12. List Files

Display files in the current directory.

```bash
ls
```

---

## 13. View Command History

Display previously executed commands.

```bash
history
```
