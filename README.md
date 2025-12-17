# Guesthouse Plugin Template

This is a template repository for creating new Guesthouse WordPress plugins.

## 🚀 Using This Template

1. Click **"Use this template"** button on GitHub
2. Name your new repository (e.g., `React-NewFeature` or `guesthouse-new-plugin`)
3. Clone your new repo locally
4. Update the following files:
   - `composer.json`: Change `PLUGIN_NAME`, `PLUGIN_DESCRIPTION`, `PLUGIN_NAMESPACE`
   - `README.md`: Update with your plugin's documentation
   - Create your main plugin file (e.g., `guesthouse-new-plugin.php`)

## 📋 What's Included

| File | Purpose |
|------|---------|
| `.commitlintrc.json` | Conventional commits configuration |
| `.github/workflows/commitlint.yml` | GitHub Action to validate commit messages |
| `.husky/commit-msg` | Local git hook to enforce commits before push |
| `package.json` | NPM dependencies for husky + commitlint |
| `composer.json` | Composer package configuration (boilerplate) |
| `.github/copilot-instructions.md` | Copilot instructions template |
| `.gitignore` | Standard gitignore for WordPress plugins |

## 🔧 Setup After Cloning

After cloning a repo created from this template, run:

```bash
npm install
```

This will automatically set up the git hooks via husky's `prepare` script.

## 📝 Commit Message Convention

All commits must follow the [Conventional Commits](https://www.conventionalcommits.org/) format:

```
type(scope): description
```

### Types

| Type | Description | In Release Notes? |
|------|-------------|-------------------|
| `feat` | New feature | ✅ Yes |
| `fix` | Bug fix | ✅ Yes |
| `perf` | Performance improvement | ✅ Yes |
| `refactor` | Code refactoring | ✅ Yes |
| `docs` | Documentation | ✅ Yes |
| `chore` | Maintenance tasks | ❌ Hidden |
| `ci` | CI/CD changes | ❌ Hidden |
| `test` | Test changes | ❌ Hidden |
| `build` | Build system changes | ❌ Hidden |

### Examples

```bash
feat: Add new booking feature
fix: Correct date calculation bug
perf: Optimize database queries
chore: Update dependencies
```

## 📖 Full Documentation

See the [Deployment Guide](https://github.com/npenchev83/guesthouse-deploy/blob/main/DEPLOYMENT.md) for complete documentation on:
- Commit conventions
- Deployment process
- Release notes generation
