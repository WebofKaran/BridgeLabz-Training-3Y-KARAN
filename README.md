# BridgeLabz Training - 3 Year Program Repository

## Repository Overview
This is the main repository for all training materials, assignments, and practice work during the BridgeLabz 3-year training program.

## Repository Structure

```
BridgeLabz-Training-3Y
├── html-practice/
│   ├── gcr-codebase/          (Guided Coding Resources - GCR programs)
│   └── practice-codebase/     (Personal practice work)
│
├── css-practice/
│   ├── gcr-codebase/          (Guided Coding Resources - GCR programs)
│   └── practice-codebase/     (Personal practice work)
│
├── bootstrap-practice/
│   ├── gcr-codebase/          (Guided Coding Resources - GCR programs)
│   └── practice-codebase/     (Personal practice work)
│
├── revision-problems/
│   ├── story-based-problems/
│   ├── ui-challenges/
│   ├── mini-projects/
│   └── assignments/
│
└── reviews/
    ├── weekly-reviews/
    ├── mentor-feedback/
    ├── self-assessments/
    └── progress-tracker/
```

## Branch Naming Convention

| Branch Name | Purpose |
|---|---|
| `main` | Master branch |
| `html-practice` | HTML practice and assignments |
| `css-practice` | CSS practice and assignments |
| `bootstrap-practice` | Bootstrap practice and assignments |
| `revision-problems` | Revision and practice problems |
| `reviews` | Weekly reviews, feedback, and progress tracking |

## Commit Message Format

Follow this format for all commits:

```
[Name] Add: <description>
[Name] Refactor: <description>
[Name] Fix: <description>
[Name] Update: <description>
```

### Examples:
- `[KARAN] Add: HTML Forms Assignment`
- `[KARAN] Add: CSS Flexbox Practice`
- `[KARAN] Add: Bootstrap Grid Exercises`
- `[KARAN] Refactor: Responsive Navbar`
- `[KARAN] Fix: CSS Media Query Issue`
- `[KARAN] Update: Weekly Review`

## Git Workflow

### Step 1: Pull Latest Changes
```bash
git pull origin <branch-name>
```

### Step 2: Make Changes
Create or edit files in the appropriate folders.

### Step 3: Add Files
```bash
git add .
```

### Step 4: Commit Changes
```bash
git commit -m "[KARAN] Add: <your message>"
```

### Step 5: Push Changes
```bash
git push origin <branch-name>
```

## Important Guidelines

✓ **DO:**
- Follow the exact folder structure
- Use clear and meaningful commit messages
- Keep related work in the correct branches
- Create separate folders for each topic/assignment
- Maintain organization and cleanliness

✗ **DON'T:**
- Use vague commit messages like "update", "done", "changes", "final"
- Mix different topics in the same folder
- Work directly on the main branch
- Ignore the branch naming conventions

## FAQ

**Q: Where should I put my practice work?**  
A: Use `practice-codebase/` folders for your personal practice.

**Q: Where should I put guided coding resources?**  
A: Use `gcr-codebase/` folders for all GCR programs.

**Q: Can I commit directly to main?**  
A: No, always work on your specific topic branch (e.g., `html-practice`, `css-practice`).

**Q: What if I need to update weekly reviews?**  
A: Commit to the `reviews` branch with appropriate commit messages.

---

**Last Updated:** 2026-08-13  
**Repository:** BridgeLabz-Training-3Y-KARAN
