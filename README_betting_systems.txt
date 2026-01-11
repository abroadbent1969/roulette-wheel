# Advanced Roulette Strategy Simulator

A fun, interactive web-based simulator to test popular roulette betting strategies on an **American roulette wheel** (double zero). Perfect for seeing how strategies like Martingale, Fibonacci, and others perform over many spins — and why the house edge always wins in the long run! 🎰

## Features

- Supports 6 betting strategies:
  - **Martingale** – Double bet after every loss
  - **Reverse Martingale (Paroli)** – Double bet after wins, reset after loss or max steps
  - **D'Alembert** – Increase/decrease bet by one unit
  - **Fibonacci** – Follow the famous sequence after losses, retreat on wins
  - **Labouchere** – Custom sequence betting system
  - **Flat Betting** – Constant bet size (control/reference)
- Even-money bets: Red or Black
- Visual spinning roulette wheel and number display
- Real-time stats: Bankroll, Spins, Wins/Losses, Current Bet, Net Profit/Loss
- Detailed spin-by-spin log
- Adjustable simulation speed (including instant for fast testing)
- Bankrupt detection and automatic stop
- Clean, responsive UI with dark casino-style theme

## How to Use

1. Save the code as `roulette-simulator.html` (or any name ending in `.html`)
2. (Optional) Place a background image named `BG.jpeg` in the same folder for a custom casino feel  
   → Or replace `url('BG.jpeg')` in the CSS with any image URL you like
3. (Optional) Add a roulette wheel image named `roulette-wheel.png` for a nicer wheel graphic  
   → If not present, the wheel will still spin using a solid color background
4. Open the HTML file in any modern web browser (Chrome, Firefox, Edge, etc.)
5. Configure your settings:
   - Choose a **Strategy**
   - Set **Base Unit** (starting bet size)
   - For Labouchere: Enter a comma-separated sequence (e.g., `10,20,10,20`)
   - For Paroli: Set max doubling steps
   - Choose **Red** or **Black**
   - Adjust **Starting Bankroll**, **Max Spins**, and **Spin Delay** (0 = fastest)
6. Click **Start Simulation**
7. Watch the wheel spin and track your virtual fortune!
8. Use **Stop** to pause early, or **Reset** to start over

## Strategy Notes

| Strategy            | Risk Level | Best For                          | Common Outcome                     |
|---------------------|------------|-----------------------------------|------------------------------------|
| Martingale          | Very High  | Short sessions                    | Fast wins or devastating streaks   |
| Reverse Martingale  | Medium     | Catching hot streaks              | Big wins during runs, small losses  |
| D'Alembert          | Medium     | Steady play                       | Slower bleed, less explosive       |
| Fibonacci           | High       | Progressive recovery              | Can climb fast on losing streaks   |
| Labouchere          | High       | Goal-oriented betting             | Complex, can complete or crash     |
| Flat Betting        | Low        | Baseline comparison               | Steady long-term loss (house edge) |

**Remember**: No betting system overcomes the house edge (~5.26% on American roulette) over the long term.

## Files Needed

- `roulette-simulator.html` ← The complete code (everything is self-contained)
- Optional: `BG.jpeg` ← Background image
- Optional: `roulette-wheel.png` ← Roulette wheel graphic

## No Installation Required

This is a single HTML file with embedded CSS and JavaScript — no server, no dependencies, no npm. Just open and play!

