# Commonly used GIT Commands

### Deleting a GIT Branch
- Use below command to delete your personal branch from your local system.
  Make sure you have checkout to some other branch first before deleting
  your test branch
  ```bash
  $ git branch -d test-branch-name
  ```

- To delete branch which is in github
  ```bash
  $ git push origin --delete test-branch-name
  ```

