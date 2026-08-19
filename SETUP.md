# Thangamani A — GitHub Profile Pack

## Files included

- `README.md` — profile layout, GitHub stats, LeetCode card, snake animation
- `genterminal.py` — generates only the animated terminal portrait
- `generate_svgs.py` — generates terminal, info and contribution SVGs
- `make_profile_gif.py` — creates a 6-second looping profile GIF from your photo
- `terminal-card.svg` — generated macOS-style terminal portrait
- `info-card.svg` — generated profile/neofetch card
- `github-contribution-animation.svg` — animated contribution-style grid
- `assets/profile.jpg` — your source photo
- `assets/profile-animated.gif` — animated version of your photo
- `.github/workflows/snake.yml` — GitHub contribution snake workflow

## Generate

```bash
pip install Pillow
python genterminal.py
python generate_svgs.py
python make_profile_gif.py
```

`generate_svgs.py` regenerates the three SVGs. `genterminal.py` is a smaller standalone command if you only want the terminal portrait.

## GitHub

Use a profile repository named `MANI2389`, put the files at the repository root, and push to `main`.

Then open **Actions → Generate Snake Animation → Run workflow** once. The snake workflow also runs every 12 hours and on pushes to `main`.
