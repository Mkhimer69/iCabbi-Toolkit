<h1 align="center">🚕 iCabbi Toolkit</h1>

<p align="center"><b>A real-time command centre for the iCabbi wallboard — the numbers that matter, in one panel.</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-iCabbi%20wallboard-111111?style=flat">
  <img src="https://img.shields.io/badge/updates-live%20stream-2ea44f?style=flat">
  <img src="https://img.shields.io/badge/theme-aware-d4af37?style=flat">
  <img src="https://img.shields.io/badge/status-in%20use-2ea44f?style=flat">
</p>

---

> The wallboard shows you a stream. This shows you the **shift**: who is
> available, which queue is starving, who is paused and why, and who is giving
> rides away — without a single refresh.

<p align="center">
  <a href="https://github.com/Mkhimer69/iCabbi-Toolkit/releases/latest/download/iCabbi-Toolkit.user.js">
    <img src="https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20install-iCabbi%20Toolkit-d4af37?style=for-the-badge" alt="Install iCabbi Toolkit">
  </a>
</p>

**[➜ iCabbi-Toolkit.user.js](https://github.com/Mkhimer69/iCabbi-Toolkit/releases/latest/download/iCabbi-Toolkit.user.js)** — the direct userscript link, always the newest release.

## ✨ What it does

| | |
|---|---|
| 📊 **SLA cards** | Waiting, missed, answered, IVR, ABOP, average talk/hold — colour-coded the moment a number needs you |
| 👥 **Live agent grid** | Everyone on shift with status, inbound/outbound, rejected and a live timer — filter by name or status, sort by timer or rejections |
| 🔀 **Cards you arrange** | Drag one card onto another and they swap places — the arrangement is remembered, and each card keeps its own number |
| 🚩 **Compliance flags** | Named and timed: an agent sitting **Available** while calls wait, a **break past 15 min**, a **lunch past 30 min** — and they clear the moment the feed does |
| 🔎 **Cards that open** | Click any card and a detail section opens under it with the rows behind that number — waiting counts, who is available, paused and why, who is on a call. ✕ or `Esc` closes it |
| 🔄 **Refresh that means it** | The header shows when the panel last refreshed; the ⟳ button reconnects the stream and repaints the newest data, so a quiet feed never looks like a dead panel |
| 🪟 **A panel that stays put** | Drag it, resize it, collapse it to the title bar. The agent section stays open or closed exactly as you left it, across updates and reloads |
| 🎨 **Matches your theme** | Picks up the suite's theme automatically — no separate colour picker |
| ⌨️ **`Ctrl + Alt + D`** | Collapses the panel to its title bar from anywhere on the page |

## 📥 Installation

1. Install the [Tampermonkey](https://github.com/Mkhimer69/AWS-Toolkit/raw/refs/heads/main/screenshots/install-tampermonkey.mp4) browser extension

📺 [Video guide](https://github.com/Mkhimer69/AWS-Toolkit/raw/refs/heads/main/screenshots/install-tampermonkey.mp4)

2. **[➜ Install iCabbi Toolkit](https://github.com/Mkhimer69/iCabbi-Toolkit/releases/latest/download/iCabbi-Toolkit.user.js)** — Tampermonkey opens its install dialog
3. Open the iCabbi wallboard page (`…/solstats/wallboard.php`) — the panel
   appears top-right and starts streaming
4. Drag it where you want it; the position is remembered

## 🧠 How it works

The panel reads the **same live stream the wallboard already uses** — it does not
poll anything of its own, does not log in anywhere, and sends nothing out. Every
number you see is a number the wallboard already had; the panel just organises it
into something you can act on.

## 🗺 Roadmap

- [ ] Editable queue names (the feed only carries ids)
- [ ] Configurable flag thresholds in the panel (break/lunch lengths)
- [ ] Shift summary you can copy at handover

---

<div align="center">

<b>🚕 iCabbi Toolkit</b><br><i>One panel, the whole shift.</i><br><br>
**Fathy Mkhimer** · Lead Real-Time Analyst · [GitHub](https://github.com/Mkhimer69)

</div>
