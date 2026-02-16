# The Golden Gallop: 2026 Greeting Guide

An interactive Chinese New Year quiz for the Year of the Horse (2026). Navigate a reunion dinner by choosing the perfect Mandarin greeting for each guest — from Ah Ma asking about marriage to Uncle Stephen flexing his marathon PB.

## How It Works

1. **Land on the home screen** — 32 animated stick-figure guests are scattered around the hero section (absolute-positioned on desktop, grid on mobile).
2. **Play the quiz** — 6 rounds are randomly drawn from a pool of 31 scenarios. Either David Wongstein or Mr. Peterson is guaranteed to appear. Each round shows a character, their situation, and four greeting options in Mandarin with pinyin.
3. **Hover to peek** — on desktop, hover over an answer card to reveal the English meaning. On mobile, tap "tap to peek meaning" to toggle it.
4. **Earn hongbao** — correct answers fill a hongbao tracker in the nav bar. Build a streak for bonus bragging rights.
5. **Get your scorecard** — at the end, see all your chosen greetings with a copy button to share them.

## Characters

32 unique guests with Singaporean and Hong Kong flavour, including:

- **Family:** Ah Ma, Ah Gong, Uncle Tan, Aunty Lim, Aunty Ophelia, Aunty Agnes, Second Uncle, Uncle Bao, Little Mei-Mei, Nephew
- **Peers:** Aloysius (BTO keys), Charmaine (job hunting), Jerrold (just ORD-ed), Wei Jie (studying in Melbourne), Cousin Rui, Friend Kai
- **Extended cast:** Boon Huat (startup bro), Joyce Lim (new baby), Uncle Ng (the cook), Aunty Helen (MLM queen), Marcus Koh (PSLE stress), Vincent & Karen (engaged), Uncle Stephen (marathon man)
- **Wildcards:** David Wongstein, Mr. Peterson, Jenny, Partner Zhang, Manager Li, Uncle & Auntie, Newlyweds, WeChat Group, The Whole Table

## Running

Open `index.html` in a browser. No build step, bundler, or server required.

## Tech

Single HTML file using:

- **Alpine.js 3.x** — reactivity and game state
- **Tailwind CSS 2.x** — utility styling (both via CDN)
- **Inline SVGs** — stick-figure character illustrations with CSS keyframe animations
- **CSS `border-image`** — mahjong tile frame around the quiz area
- **Custom cursor** — firecracker PNG cursor site-wide

## Files

| File | Description |
|---|---|
| `index.html` | The entire app — markup, styles, and JS in one file |
| `horse.png` | Hero horse illustration on the landing page |
| `mahjong-border.png` | Mahjong tile border PNG (transparent centre) |
| `firecracker-cursor.png` | Custom firecracker cursor graphic |
