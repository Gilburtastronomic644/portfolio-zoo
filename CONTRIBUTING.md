# Contributing to Portfolio Zoo

Thanks for contributing! This project thrives on the community sharing creative portfolio designs.

## How to Add Your Portfolio

### 1. Fork & Clone

```bash
git clone https://github.com/YOUR_USERNAME/portfolio-zoo.git
cd portfolio-zoo
```

### 2. Create Your Portfolio Folder

Pick a short, descriptive name using lowercase and hyphens:

```
portfolio-zoo/
└── your-portfolio-name/
    ├── README.md          # Required
    ├── index.html         # Entry point
    ├── style.css
    ├── script.js
    └── assets/            # Images, fonts, etc. (if needed)
```

**Folder naming examples:** `minimal-dark`, `retro-terminal`, `neon-card`, `glassmorphism-dev`, `brutalist-engineer`

### 3. Write a README for Your Portfolio

Every portfolio **must** include a `README.md` with:

```markdown
# Portfolio Name

> One-line description of the design style.

## Screenshot

![Screenshot](screenshot.png)

## Features

- Feature 1
- Feature 2

## How to Customize

1. Open `index.html`
2. Replace the name, bio, and links with your own
3. Update experience/projects sections
4. Swap colors by editing CSS variables in `style.css`

## Tech Stack

- HTML / CSS / JS (or whatever you used)

## Author

- [Your Name](https://github.com/yourname)

## License

MIT
```

### 4. Checklist Before Submitting

- [ ] Portfolio looks great on desktop AND mobile
- [ ] All code is inside your single folder (no files in the repo root)
- [ ] `index.html` is the entry point
- [ ] README includes a screenshot and customization steps
- [ ] No API keys, secrets, or personal tokens in the code
- [ ] No massive images (optimize to < 500KB each)
- [ ] Tested in at least Chrome and Firefox

### 5. Open a Pull Request

- Title: `Add [portfolio-name] portfolio`
- Description: Brief description + a screenshot or GIF
- We'll review and merge quickly!

## Guidelines

### Do

- Make it visually impressive
- Keep the code readable and well-structured
- Use CSS variables for colors/fonts so users can easily theme it
- Include responsive styles
- Add helpful comments for sections users will want to customize

### Don't

- Don't include node_modules or build artifacts
- Don't use copyrighted images/assets without permission
- Don't add tracking scripts or analytics
- Don't require a backend or database (static sites only)
- Don't submit someone else's work without credit

## Updating the Main README

After your PR is merged, a maintainer will add your portfolio to the table in the root `README.md`.

## Questions?

Open an issue and we'll help you out!
