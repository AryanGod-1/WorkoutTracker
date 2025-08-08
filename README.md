🏋️‍♂️ Workout Tracker on Aptos Blockchain
A simple Move-based smart contract that allows users to log workout sessions and earn rewards for each session. This project is part of a blockchain learning initiative using the Aptos blockchain and Move programming language.

🧠 Project Description
This smart contract helps users record their fitness progress on-chain by logging workout sessions. For every workout logged, the user earns reward points. Users can also claim rewards, simulating a future incentive model using blockchain tokens.

The project demonstrates:

Use of on-chain resource storage

Account-specific data management using signer

Handling and modification of global resources

Aptos & Move basics in a real-world scenario

⚙️ Project Algorithm (Logic Flow)
User logs a workout

Function: log_workout(user: &signer)

Increases workout session count and rewards by 10 points.

Stores or updates a WorkoutLog resource under user's address.

User claims rewards

Function: claim_rewards(user: &signer)

Checks that rewards > 0

Resets the rewards counter to simulate a reward being claimed

🚀 Future Scope
🔁 Token integration: Mint or transfer actual AptosCoin as a reward.

📲 Frontend Web3 App: Connect wallet, show sessions, claim rewards.

🧾 Event logging: Emit events for workouts and rewards to enable tracking.

🧑‍🤝‍🧑 Community challenges: Compete and earn based on activity.

📈 Leaderboards: Add stats and comparisons across users.

🧱 Tech Stack
Blockchain: Aptos

Language: Move

CLI Tool: Aptos CLI

aptosproj/
├── Move.toml                # Project metadata and address mapping
├── sources/
│   └── WorkoutTracker.move  # Main smart contract
├── README.md                # You're here!

Version Control: Git & GitHub

