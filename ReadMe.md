**Rock Paper Scissors Minus One**

A small pygame-based Rock, Paper, Scissors variant where each player picks two options, drops one, then resolves a normal RPS battle.

**Requirements**
- **Python**: 3.8+ (3.10 recommended)
- **Pygame**: tested with `pygame 2.5.2`

**Recommended VS Code extensions**
- `ms-python.python` (Python support)
- `ms-python.vscode-pylance` (type analysis)
- `formulahendry.code-runner` (optional quick-run support)

**Install dependencies**
- Create a virtual environment (recommended) and install `pygame`:

```powershell
# from project root (PowerShell)
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -U pip
pip install pygame
```

**Run the game**
- From PowerShell in the game's folder (where `RPSMO3D.py` lives):

```powershell
cd "d:\PyGame\Rock, Paper, Scissors, Minus One"
.\.venv\Scripts\Activate.ps1   # if you used the venv above
python RPSMO3D.py
```

**Controls / How to play**
- `Space`: Start game / restart after a round
- `R`, `P`, `S`: Choose Rock / Paper / Scissors for each pick
- `Enter`: Lock the current pick (first Enter locks Choice 1, second Enter locks Choice 2)
- After both choices are locked, `Enter` moves to final selection phase
- `3` / `4`: Choose which of your two locked options to keep for the final battle (the game uses keys `3` and `4` for the final choice)
- During gameplay: `Q` ends the session (game over)

**Notes & troubleshooting**
- The game expects the `Images/` and `font/` assets to be next to `RPSMO3D.py` as in the repository. If images or the font fail to load, you'll see an error when starting pygame.
- If keys appear unresponsive, make sure the game window is focused.
- If using a different Python install, ensure you run with the same interpreter that has `pygame` installed.

