# MiniMC - Custom Minecraft Server Platform

> **Role:** Lead Software Engineer  
> **Status:** Closed Source | Production  
> **Focus:** High-Performance Distributed Systems & Game Mechanics

## 📋 Project Overview

MiniMC is a Minecraft server that I architected and developed as part of a three-person team. While my co-founders handle marketing and operations, I serve as the sole software engineer responsible for all technical implementation, infrastructure design, and feature development.

This project has been a significant technical challenge, pushing me to develop sophisticated solutions from the ground up when existing alternatives were either non-existent or failed to meet performance requirements.

## 🎯 Technical Highlights

### Core Engineering Challenges

As the lead developer, I've architected and implemented several complex systems:

- **Cross-Server Inventory Synchronization**  
  Designed a real-time inventory sync system that maintains data consistency across multiple server instances, handling edge cases like concurrent modifications and network failures. The exiting solution was HuskSync however in a large network it fails to meet the latency requirements causing duping of ingame items. Thus, We developed a plugin that has retrival times 3x faster than most available solutions.

- **Distributed Player Warping**  
  Built a seamless cross-server teleportation system with state management, ensuring smooth player transitions between server instances without data loss or duplication. Existing solution had in-efficient Logic and also did not meet customizability requirements thus we developed our own solution!

- **Custom Dungeon Mechanics Engine**  
  Boss-Mechanics and Dungeon logic had to be custom. Well so we went ahead and wrote our own Plugin for that too! And what's crazy is we're working on a sophisticated dungeon system from scratch, including procedural generation logic, encounter management, and dynamic difficulty scaling.

### Why Custom Solutions?

Each of these systems was built from the ground up due to:
- **Performance Constraints:** Existing solutions couldn't handle our scale or latency requirements
- **Feature Gaps:** Off-the-shelf plugins lacked the specific functionality needed
- **Control & Optimization:** Custom implementations allowed fine-tuned performance optimization

## 💼 Engineering Approach

This project showcases my ability to:

- **Architect Distributed Systems** - Design and implement systems that work reliably across multiple server instances
- **Optimize for Performance** - Make critical decisions about when to build custom solutions vs. using existing libraries
- **Handle Complex State Management** - Ensure data consistency in distributed environments
- **Deliver Production Code** - Write maintainable, reliable code for real users in a live environment

## 🔒 Code Confidentiality

The source code remains closed-source to protect the competitive advantages and proprietary systems developed for this project. However the InventorySync systems JAR will be made publically available at a later date for use of the general Public after a few feature additions.

---

## How do you experience these features?
- Minimc is a open for all Minecraft server simply connect using the details below:
> **IP**: play.minimc.in
> **Version**: 1.21.10


---
### LOG SCREENSHOTS:

- **InventorySync:**
![MiniSync](https://cdn.discordapp.com/attachments/1369365066629255257/1456684893475045396/ev5wf0a.png?ex=69594306&is=6957f186&hm=ce501ba0a70526c230a92bf8fff05b50930baa66db045346f443d05b2971a023&)

- **Dungeon Boss Spawns:**
![Warden](https://cdn.discordapp.com/attachments/1369365066629255257/1456686818450870507/QmMYpCp.gif?ex=695944d1&is=6957f351&hm=bc95cf33f9d710346722f7b70da5d1ab7d14e62a6b3575f022856e63e2d6c718&)

- **Warping Logs:**
![Warden](https://media.discordapp.net/attachments/1369365066629255257/1456687692304748608/QBA9b5j.png?ex=695945a1&is=6957f421&hm=4753db96c6da3768c5b7233ec59744c276863ca647bd81e04357a9ddb5fcddda&=&format=webp&quality=lossless&width=369&height=38)
