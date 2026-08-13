# BridgeLabz Repository Setup Guide

## ✓ Setup Completed Successfully

### Repository Information
- **Repository Name:** BridgeLabz-Training-3Y-KARAN
- **Location:** `c:\Users\III S I\Documents\BridgeLabz-Training-3Y-KARAN-`
- **Status:** ✓ Initialized and configured

---

## Directory Structure Created

```
BridgeLabz-Training-3Y-KARAN/
│
├── html-practice/
│   ├── gcr-codebase/
│   │   ├── introduction-to-web/
│   │   ├── html-basics/
│   │   ├── semantic-html/
│   │   ├── block-inline-elements/
│   │   ├── tables/
│   │   ├── lists/
│   │   ├── forms/
│   │   ├── iframes/
│   │   ├── entities-uri/
│   │   └── responsive-html/
│   └── practice-codebase/
│
├── css-practice/
│   ├── gcr-codebase/
│   │   ├── css-basics/
│   │   ├── selectors/
│   │   ├── colors-backgrounds/
│   │   ├── box-model/
│   │   ├── positioning/
│   │   ├── flexbox/
│   │   ├── css-grid/
│   │   ├── typography/
│   │   ├── transitions/
│   │   ├── animations/
│   │   ├── responsive-design/
│   │   ├── media-queries/
│   │   ├── navigation-bar/
│   │   ├── pseudo-classes/
│   │   ├── tooltips/
│   │   ├── filters/
│   │   └── cheat-sheet-practice/
│   └── practice-codebase/
│
├── bootstrap-practice/
│   ├── gcr-codebase/
│   │   ├── bootstrap-basics/
│   │   ├── grid-system/
│   │   ├── bootstrap-components/
│   │   ├── themes/
│   │   ├── alerts/
│   │   ├── badges-labels/
│   │   ├── panels/
│   │   ├── pagination/
│   │   ├── carousel/
│   │   └── progress-bar/
│   └── practice-codebase/
│
├── revision-problems/
│   ├── story-based-problems/
│   ├── ui-challenges/
│   ├── mini-projects/
│   └── assignments/
│
├── reviews/
│   ├── weekly-reviews/
│   ├── mentor-feedback/
│   ├── self-assessments/
│   └── progress-tracker/
│
├── README.md
├── SETUP-GUIDE.md (this file)
└── .gitignore
```

---

## Git Branches Created

| Branch Name | Purpose | Status |
|---|---|---|
| `main` | Master branch (default) | ✓ Created |
| `html-practice` | HTML practice and assignments | ✓ Created |
| `css-practice` | CSS practice and assignments | ✓ Created |
| `bootstrap-practice` | Bootstrap practice and assignments | ✓ Created |
| `revision-problems` | Revision and practice problems | ✓ Created |
| `reviews` | Weekly reviews and feedback | ✓ Created |

**View all branches:**
```bash
git branch -a
```

---

## Git Configuration

```
User Name: BridgeLabz Learner
Email: learner@bridgelabz.com
Repository Type: Local Git Repository
Initial Commit: ✓ Completed
```

---

## How to Use This Repository

### 1. Switching to a Branch
```bash
git checkout <branch-name>
# Example:
git checkout html-practice
```

### 2. Creating Work on a Branch

**For HTML Practice:**
```bash
git checkout html-practice
# Add your files to appropriate folders
git add .
git commit -m "[KARAN] Add: HTML Basics Assignment"
git push origin html-practice
```

**For CSS Practice:**
```bash
git checkout css-practice
# Add your files
git add .
git commit -m "[KARAN] Add: CSS Flexbox Practice"
git push origin css-practice
```

**For Bootstrap Practice:**
```bash
git checkout bootstrap-practice
# Add your files
git add .
git commit -m "[KARAN] Add: Bootstrap Grid Exercises"
git push origin bootstrap-practice
```

**For Revision Problems:**
```bash
git checkout revision-problems
# Add your files
git add .
git commit -m "[KARAN] Add: Story-based Problem Solution"
git push origin revision-problems
```

**For Reviews:**
```bash
git checkout reviews
# Add review documents
git add .
git commit -m "[KARAN] Update: Weekly Review Report"
git push origin reviews
```

### 3. Standard Git Workflow

Always follow this workflow:

```bash
# Step 1: Switch to your working branch
git checkout <branch-name>

# Step 2: Pull latest changes
git pull origin <branch-name>

# Step 3: Make your changes (add/edit files)
# ... create or modify files ...

# Step 4: Stage changes
git add .

# Step 5: Commit with proper message
git commit -m "[KARAN] Add: <description>"

# Step 6: Push to remote
git push origin <branch-name>
```

---

## Commit Message Format

Always follow this format:

```
[KARAN] <Action>: <Description>
```

### Valid Actions:
- **Add:** New files or features
- **Refactor:** Code reorganization or improvement
- **Fix:** Bug fixes
- **Update:** Modifications to existing work

### Examples:
```
[KARAN] Add: HTML Forms Assignment
[KARAN] Add: CSS Flexbox Practice
[KARAN] Add: Bootstrap Grid Exercises
[KARAN] Refactor: Responsive Navbar
[KARAN] Fix: CSS Media Query Issue
[KARAN] Update: Weekly Review
```

### ✗ AVOID These Messages:
- ❌ "update"
- ❌ "done"
- ❌ "changes"
- ❌ "final"
- ❌ "commit"

---

## Folder Organization Guidelines

### gcr-codebase/ (Guided Coding Resources)
- Use this folder for all GCR programs and assignments provided by instructors
- Organize by topic (e.g., `html-basics`, `flexbox`, `grid-system`)
- One folder per topic with all related files inside

### practice-codebase/
- Use this folder for your personal practice and experiments
- Can be less organized than gcr-codebase
- Good for quick prototyping and learning

### revision-problems/
- `story-based-problems/` - Problem-solving exercises with story context
- `ui-challenges/` - UI design and implementation challenges
- `mini-projects/` - Small project assignments
- `assignments/` - Formal assignment submissions

### reviews/
- `weekly-reviews/` - Summary of weekly learning
- `self-assessments/` - Self-evaluation documents
- `mentor-feedback/` - Feedback from mentors
- `progress-tracker/` - Progress tracking documents

---

## Important Rules to Follow

✓ **DO:**
1. Always work on the appropriate branch (not on `main`)
2. Use clear, descriptive commit messages
3. Create separate folders for each topic/assignment
4. Pull latest changes before starting work
5. Push your work regularly
6. Keep the folder structure organized
7. Use proper naming conventions

✗ **DON'T:**
1. Commit directly to the `main` branch
2. Use vague or unclear commit messages
3. Mix multiple topics in the same folder
4. Leave uncommitted changes for too long
5. Delete or modify .gitkeep files unnecessarily
6. Create random folders outside the structure

---

## Connecting to GitHub

When you're ready to push to GitHub:

1. **Create a repository on GitHub** named `BridgeLabz-Training-3Y-KARAN`

2. **Add remote origin:**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/BridgeLabz-Training-3Y-KARAN.git
   ```

3. **Push all branches:**
   ```bash
   git push -u origin main
   git push -u origin html-practice
   git push -u origin css-practice
   git push -u origin bootstrap-practice
   git push -u origin revision-problems
   git push -u origin reviews
   ```

4. **Verify branches on GitHub:**
   ```bash
   git branch -a
   ```

---

## Useful Git Commands

```bash
# Check current branch
git branch

# View all branches (local and remote)
git branch -a

# Check status
git status

# View commit history
git log --oneline

# View changes
git diff

# Undo changes (before staging)
git checkout -- <filename>

# Unstage changes
git reset HEAD <filename>

# Delete a branch (local)
git branch -d <branch-name>

# Rename current branch
git branch -m <new-name>

# See branch differences
git diff main html-practice
```

---

## Troubleshooting

### Q: I accidentally committed to `main` instead of my branch
**A:** Create and checkout your branch, then cherry-pick the commit:
```bash
git checkout -b html-practice
git cherry-pick <commit-hash>
git checkout main
git reset --hard HEAD~1
```

### Q: How do I see what files are in each branch?
**A:** 
```bash
git checkout <branch-name>
git ls-tree -r --name-only <branch-name>
```

### Q: I want to switch branches but have uncommitted changes
**A:** Stash your changes first:
```bash
git stash
git checkout <new-branch>
git stash pop
```

### Q: How do I delete a branch?
**A:**
```bash
git branch -d <branch-name>  # Local deletion
git push origin --delete <branch-name>  # Remote deletion
```

---

## Next Steps

1. ✓ Local repository is set up
2. ✓ All branches are created
3. ✓ Directory structure is ready
4. 🔜 Create GitHub repository
5. 🔜 Push local repository to GitHub
6. 🔜 Start adding your assignments and practice work

---

**Setup Completed:** 2026-08-13  
**Repository Ready for Use:** ✓ YES

For any questions, refer to the main README.md file or the BridgeLabz guidelines provided in the PDF.
