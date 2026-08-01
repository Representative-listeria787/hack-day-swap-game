# Hack Day Swap - Game Script Utility 2026

> **A browser-based colour-matching puzzle and AI coding demonstration. Choose connected colour clusters, transfer tokens into a memory tray, and restore the robot by filling all of its sockets.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/calebbifsbrooks3969/hack-day-swap-game?style=flat-square)](https://github.com/calebbifsbrooks3969/hack-day-swap-game)

---

<p align="center">
  <a href="https://calebbifsbrooks3969.github.io/hack-day-swap-game/">
    <img src="https://img.shields.io/badge/Download-Hack%20Day%20Swap%20Script-brightgreen?style=for-the-badge" alt="Download Hack Day Swap Script">
  </a>
</p>

> **[Download Hack Day Swap](https://calebbifsbrooks3969.github.io/hack-day-swap-game/)**

---

[Download Latest Build](https://calebbifsbrooks3969.github.io/hack-day-swap-game/)

---

## What the Game Does

Hack Day Swap is a small HTML game that combines colour matching with robot socket placement. On the board, players choose connected tokens of the same colour, move those tokens into a memory tray, and use the stored colours to work with the robot's sockets.

To finish a run, restore the robot by filling all sockets and emptying the memory tray. Since tokens already placed in sockets may be replaced, successful play depends on selecting groups in a useful order and managing colour matches carefully.

---

## Included Functionality

- Pick connected groups of matching-colour tokens from the board.
- Transfer selected tokens to a temporary memory tray.
- Match colours held in the tray to the robot's open sockets.
- Swap out tokens that are already assigned to sockets.
- Fill every socket to complete the robot restoration goal.
- Empty the memory tray as part of the completed puzzle state.
- Serve and play the project locally with Python's HTTP server.
- Explore the HTML game as an agentic coding demonstration.

---

## Getting Started

### Download the Files

Use the download link above to access the latest build, or retrieve the project files from the repository.

### Launch a Local Server

This is an HTML browser game, so serve its directory rather than opening the files through a command-line interface. Python's built-in HTTP server can be used:

```bash
cd ai-hack-day-swap
python -m http.server
```

After the server starts, open the local URL printed by Python in your browser. The port shown can differ according to the command and the local environment.

### Gameplay Sequence

1. Choose a connected group of one colour.
2. Move those tokens into the memory tray.
3. Use the tray colours to match the robot's sockets.
4. Replace tokens in occupied sockets when the puzzle requires it.
5. Keep playing until all sockets are occupied and the tray is empty.

---

## Game Controls and Behaviour

Hack Day Swap is designed as an interactive browser puzzle, not as a command-line tool. Its core actions involve selecting board groups, temporarily storing their colours, and assigning those colours to robot sockets.

| Setting or action | Description |
|---|---|
| Colour-group selection | Choose a connected set of tokens with matching colours. |
| Memory tray | Temporarily stores tokens selected from the board. |
| Socket matching | Applies tray colours to the robot's sockets. |
| Socket replacement | Makes it possible to replace a token already placed in a socket. |
| Completion state | The robot is restored when all sockets are filled and the tray is empty. |
| Local serving | Runs the HTML project through Python's HTTP server. |

---

## Compatibility and Requirements

- **Platform:** Web browser
- **Project format:** HTML
- **Local runtime:** Python HTTP server for serving the project files
- **Game type:** Colour-swap puzzle game
- **Demo context:** AI Hack Day agentic coding demo

No particular operating-system or browser-version requirements are specified. Actual behaviour can vary with the browser loading the HTML game and with the local server environment.

---

## 2026 Changelog

- Described the colour-group selection, memory-tray handling, and socket-matching flow.
- Added instructions for running the project with Python's HTTP server.
- Explained that completion requires restoring the robot while leaving the tray empty.

---

## Frequently Asked Questions

### What is the quickest way to launch the game?

Download the project, start Python's built-in HTTP server from its directory, and open the local address displayed in the terminal with a web browser.

### Is there an online version?

Yes. Open the hosted build through [Download Latest Build](https://calebbifsbrooks3969.github.io/hack-day-swap-game/).

### What happens when I select tokens?

Selecting a connected colour group lifts those tokens into the memory tray. Their colours can then be matched against the robot's sockets.

### Can tokens in sockets be replaced?

Yes. An occupied socket can have its current token replaced during the puzzle.

### When is the game complete?

Completion occurs once every robot socket is filled and no tokens remain in the memory tray.

### Is customization available?

The project is delivered as an HTML implementation, allowing developers to inspect and change the local files. The extracted project profile does not define specific customization controls or settings.

### What browsers can run it?

The game is intended for web browsers. No detailed browser compatibility matrix is supplied.

### What directory should contain the files?

Place the downloaded files together in a project directory, for example `ai-hack-day-swap`. Start the local HTTP server from that directory so the browser can resolve the HTML assets correctly.

### How can I check for newer versions?

Visit the hosted build or repository to look for updated files, then download them or repeat the local setup process as appropriate.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
