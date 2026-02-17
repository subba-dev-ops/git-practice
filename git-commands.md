# Common Git Commands I Use

## Daily workflow
```bash
git status                    # Check status
git add .                     # Stage all changes
git commit -m "description"   # Commit with message
git push                      # Push to remote


# Branching

git checkout main             # Switch to main
git checkout -b feature/name  # Create and switch to new branch
git branch                    # List branches


# Merging 

git checkout main
git merge feature/name        # Merge branch into current
git push origin main          # Push updated main


