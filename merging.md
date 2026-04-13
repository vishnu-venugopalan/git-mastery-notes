# 🔀 Merging in Git

## 📌 What is Merging?

Merging is the process of combining changes from one branch into another, usually integrating feature work into the main branch.

---

## 🎯 Why Merging is Important
- Combined completed features into the main project
- Integrates work from different developers
- Keeps the project updated

---

## ⚙️ Common Command

- git merge

---

## 🔁 Basic Workflow
1. Switch to the main branch  
2. Merge the feature branch
3. Git combines the changes

---

## ⚠️ What is a Merge Conflict

A merge conflict occurs when Git cannot automatically combine changes because the same part of the file was modified differently in two branches.

---

## 💥 Why Conflicts Occur
- Same line modified in different branches
- One branch deletes a section of code while another modifies it
- Changes overlap in the same section

---

## 📃 What Conflict Looks Like

When a conflict occurs, Git shows both versions of the code with markers:
- <<<<<<< HEAD ➡️ current branch code
- ======= ➡️ seperator
- >>>>>>> branch-name ➡️ incoming branch code

You must manually choose or combine the correct version and remove these markers.

---

## 🛠️ How to Resolve Conflicts

1. Open the conflicted file
2. Identify the conflicting sections
3. Choose or combine the correct code
4. Remove conflict markers
5. Save the file
6. Add and commit changes

---

## 📌 Example Scenario

Two developers modify the same line in different branches. When merging, Git could not decide which version to keep, so a conflict must be resoved manually.

---

## 🧠 Key Insight

Merge conflicts are not errors but signals that changes overlap, requiring a decision to maintain correct functionality.
