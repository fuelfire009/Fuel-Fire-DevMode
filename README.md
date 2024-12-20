# Fuel-Fire - FPS Gaming on Fuel Network

Fuel Fire is an innovative first-person shooter (FPS) game designed for mobile platforms like Android and iOS, with plans for cross-platform compatibility. The game stands out for its intense, fast-paced gameplay and cutting-edge integration with blockchain technology. Featuring a unique **Compete-to-Earn** model, Fuel Fire rewards players based on their competitive performance, enabling them to earn real-world value through in-game activities.

Watch the Fuel-Fire trailer here: [TRAILER](https://www.youtube.com/watch?v=Ms3u9elKcIE&t=11s)

---

## 🚀 Project Overview

Key aspects of Fuel Fire include:
- **Adrenaline-Packed FPS Gameplay**: Thrilling multiplayer battles with realistic weapons, dynamic environments, and sharp shooting mechanics.
- **Blockchain-Powered Economy**: Players can own, trade, and collect in-game assets like weapons, skins, and gear as NFTs, ensuring real ownership and value.
- **Cross-Platform Development**: Future releases include versions for PC and cross-platform gameplay.
- **In-Game Marketplace**: A player-driven marketplace powered by blockchain allows seamless trading of in-game assets.

---

## 📜 Features

1. **Kill Tracking**
   - Tracks the number of kills for each player.
   - Records the last kill timestamp.

2. **Reward Mechanism**
   - Distributes in-game assets based on player performance.
   - Rewards are stored as **UTXOs (Unspent Transaction Outputs)** for efficient management.

3. **Player Management**
   - Manages player data securely on the blockchain.
   - Provides transparency and immutability for all transactions.

4. **Fuel Blockchain Integration**
   - Deployed on the **Fuel mainnet** for scalability and low fees.
   - Fully compatible with the Fuel wallet and UTXO models.

---

## 🕹️ Game Logic

### Kill Tracker

1. **Record kills for a player:**
   ```rust
   fn record_kill(player: Address);
