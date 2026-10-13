# Capture the Flag vs AI (Unity)

Race an AI opponent to grab the flag and bring it back to base. First to the target score wins.

## What I built
- **Finite-state-machine AI** (`AIController.cs`): `Idle` → `ChaseFlag` → `ReturnFlag`, navigating with Unity's **NavMesh**.
- `FlagSpawner`: respawns the flag after each capture.
- `GameController` / `PlayerCollision`: scoring, pickups, drop-off zones and win conditions.
- Main menu and game scene, plus a ready-to-run **Windows build** in `Final_Buil_windows`.

## Run it
Run the Windows build, or open `GADE3A_PART1` in **Unity 2022.3.7f1** and start from `Assets/Scenes/MainMenu.unity`.

---
Built by **Hakeem Shaik** during my BSc (game development modules). See my AI work: [Pursuit](https://github.com/Hakeemshaik/pursuit-ai-job-agent) · [Fitted](https://github.com/Hakeemshaik/fitted) · [Boom & Crash Desk](https://github.com/Hakeemshaik/boom-crash-desk)
