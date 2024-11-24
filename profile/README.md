# **SpectaLink**  
*Bridging Minecraft and Discord through seamless spectating and live streaming*

## **Overview**
Welcome to the official SpectaLink GitHub organization! SpectaLink is an open-source project that connects Minecraft servers and Discord in a unique way. It allows Discord users to spectate specific players on a Minecraft server by streaming their point of view (POV) live to a Discord voice channel.

The bot joins the Minecraft server in spectator mode, "invisibly" follows the selected player, and streams their POV directly to Discord. Spectating is done without the knowledge of the player being watched, making it a seamless experience for both the viewer and the target player.

## **Features**
- **Spectate Minecraft players from Discord**: Use the `/spectate [playername]` command to watch any player’s POV in real-time.
- **Fully Invisible Spectator Mode**: The bot remains hidden from the target player, ensuring no disruption.
- **Live Streaming to Discord**: Streams the spectated player’s perspective directly to a Discord voice channel.
- **Open-Source**: SpectaLink is fully open-source, allowing anyone to use, modify, and contribute to the project.

## **How It Works**
SpectaLink operates through two primary components:
1. **Discord Bot**: Built using **CommandKit** for managing commands, it connects to a Minecraft server and streams the player’s perspective live to Discord.
2. **Minecraft Mod/Plugin**: The Minecraft component uses a spectator bot powered by **Mineflayer** to follow and view the target player's POV.

Both components are designed to be highly configurable, with a configuration file for managing server IPs, permissions, and other important settings.

## **Configuration**
Both the Discord bot and Minecraft plugin can be configured via a **config file** to adjust settings such as:
- Server IP address
- Permissions for bot and users
- Streaming quality options
- Logging and debugging options

Configuration files can be found in the `config` folder.

## **Contributing**

We welcome contributions to make SpectaLink even better. If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add feature'`).
4. Push to your fork (`git push origin feature-branch`).
5. Create a pull request.

Please ensure your code follows the style guide and is well-documented.

## **License**
SpectaLink is licensed under the MIT License. See the LICENSE file for more details.

## **Contact & Support**
For any questions or issues, feel free to open an issue on the repository or contact the project maintainers.

---

### **Want to help?**
If you're interested in adding new features, fixing bugs, or improving documentation, feel free to open a pull request! Contributions are always welcome. Let's make SpectaLink the best it can be!
