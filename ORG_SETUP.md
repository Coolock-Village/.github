# Coolock Village GitHub Org Setup

Use this folder as the starter for a dedicated `.github` repository in `Coolock-Village`.

## Quick publish (gh CLI)

```bash
cd /home/ryan/code/coolock-village-org-kit
git init
git add .
git commit -m "Add organization profile README and logo assets"
gh repo create Coolock-Village/.github --public --source=. --remote=origin --push
```

## 1. Organization profile README

- File already prepared: `.github/profile/README.md`
- Upload this content to the org `.github` repo to enable the public org profile page.

## 2. Organization avatar/logo

- Source logo: `.github/profile/assets/coolock-village-org-logo.svg`
- PNG upload file: `.github/profile/assets/coolock-village-org-logo.png`

## 3. Suggested GitHub org fields

- Display name: `Coolock Village`
- Short description: `Open civic tooling for practical local coordination.`
- Website: `https://coolockvillage.ie`
- Social/About blurb: `Community-focused software, automation, and documentation for practical local action.`

## 4. Public release framing

Keep messaging faceless and project-first:

- `Some core platform work is not public yet while release workflows are finalized.`
- `Initial public focus: Home Assistant todo-list workflows and related tooling.`
