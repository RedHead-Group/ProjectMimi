# Project Mimi - Our attempt to make a sentient-like NPC.

**Project Mimi** is our ambitious project aimed at pushing the boundaries of how AI can interact with video games in real time. By leveraging a screenshot-based game viewing method and providing the ability to control or embody a special player, this technology aims to create an advanced AI gaming experience, enabling the AI to move freely, interact with environments, and simulate a human-like gaming presence.

## Features

### Screenshot-Based Game Play Integration
- **Continuous Screenshot Feed:** This project will utilize a continuous screenshot-based approach to provide visual input to the AI, allowing it to understand the game environment step by step.
- **Direct Control Integration:** AI can understand the game state from these screenshots and execute actions such as movement, interaction, and combat using a variety of controls and game-specific API interfaces.

### Advanced AI Player Embodiment
- **Special Player Entity:** Instead of traditional player models, a unique player entity is designed to be controlled by the AI, allowing freedom of movement and independent control over limbs (arms, legs, head, etc.).
- **Collision Detection & Realistic Physics:** By integrating with the game's physics engine, the AI-controlled player moves realistically and can interact meaningfully with game objects, respecting collision constraints and environmental challenges.
- **Free Movement & Limb Control:** The AI is equipped to move freely throughout the game environment. It can manipulate limbs for nuanced interactions, such as picking up items, climbing obstacles, or pushing objects, simulating a sentient-like presence within the game.

### Use Cases
- **AI Gameplay Demonstration:** Watch AI play and strategize in real-time, analyzing its ability to adapt to changing environments and make decisions based on the screenshot feed.
- **Game Testing & Exploration:** Enable the AI to autonomously explore game maps, discover bugs, or evaluate features, all while interacting naturally with the game environment.
- **Embodied AI Research:** Explore how AI can learn and adapt when given the ability to move freely within a simulated physical world using a step-by-step visual feed.

### Technical Challenges
- **Latency Issues**: The screenshot-based approach introduces latency between capturing the game state, processing it, and executing actions, which can hinder performance in fast-paced environments.
- **Complex Visual Processing**: The AI must be able to interpret complex visual inputs from static screenshots accurately, which requires advanced computer vision models and significant computational power.
- **Control Integration Limitations**: Translating AI decisions into real-time game controls can be challenging, as many games have control schemes that require precision and timing.

### Computational Requirements
- **High Processing Power**: Handling rapid screenshot capture, interpreting the game environment, and controlling the player requires considerable processing resources, including a powerful GPU and CPU.
- **Advanced AI Models**: To navigate game environments effectively, sophisticated AI models are necessary. Training these models can be resource-intensive and time-consuming.

### Game Integration
- **Limited Game Compatibility**: Not all games provide APIs or integration points that allow for real-time control and interaction by an external AI. Custom solutions might be required for each game.
- **Physics & Collision Constraints**: For the special player entity to interact realistically, it must be well-integrated with the game’s physics engine, which may vary significantly between different games.

## How It Works

1. **Screenshot Feed**: The game provides a continuous stream of screenshots to the AI. The AI processes these screenshots to understand the game environment step by step, simulating a real-time experience.

2. **Control Commands**: The AI sends control commands directly to the game, simulating human inputs such as key presses or mouse movements. This allows the AI to move the player, interact with objects, and react to game events.

3. **Embodied Movement**: For the advanced player embodiment feature, the AI can manipulate individual limbs of a special player character, making for nuanced interactions with the game world. It can crouch, pick up items, throw objects, or navigate obstacles with realistic motion.

## Planned Features
- **Multiplayer Integration**: Allow AI to join multiplayer servers and interact with real players.
- **AI Personality Customization**: Configure AI to act in specific ways, e.g., aggressive, exploratory, or cooperative.
- **VR Environment Testing**: Enable VR compatibility for AI, allowing for unique virtual reality interactions.

## Contributing
We welcome contributions from the community! Please follow these steps:
- Fork the repository.
- Create a new branch (`feature-branch`).
- Submit a pull request with a detailed explanation of your changes.

For major changes, please open an issue first to discuss your proposed features or improvements.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
- **Project Lead**: Skiddro
- **Email**: redhead@tuta.com
- **GitHub**: https://github.com/RedHead-Group

Feel free to open issues or discussions if you have any questions or ideas. We look forward to seeing what creative solutions the community can bring!

---

> *"Imagine a world where AI can roam, explore, and learn within the most fantastical game environments - and maybe, even beat us at our own games."*
