# Burger Joint 🍔 

**Burger Joint** is a simple, fun **burger-cooking simulation game** made in Unity. You play as a burger chef fulfilling customer orders as efficiently as possible. The game was developed as a way to explore **customer behavior systems**, **Scriptable Objects**, and **interactive gameplay mechanics** in Unity.

---

## Core Features & Scripts 🔧 

This project focuses on simulating the flow of customers and burger-making gameplay. Below are the core systems that define the game’s behavior:

<table>
  <tr>
    <th>Feature</th>
    <th>Description</th>
    <th>Main Scripts</th>
  </tr>
  <tr>
    <td><b>Customer System</b></td>
    <td>Handles customer spawning, behavior, and orders. Each customer is created using Scriptable Objects and follows a defined order pattern.</td>
    <td><code>CustomerSpawner.cs</code>, <code>Customer.cs</code>, <code>CustomerBook.cs</code>, <code>CustomerVariant.cs</code>, <code>CustomerClickHandler.cs</code></td>
  </tr>
  <tr>
    <td><b>Cooking System</b></td>
    <td>Manages the player's interaction with cooking stations and burger preparation.</td>
    <td><code>BrainCooker.cs</code>, <code>Plate.cs</code></td>
  </tr>
  <tr>
    <td><b>Game Flow</b></td>
    <td>Controls game state, background music, and in-game guidance/tutorials.</td>
    <td><code>GameManager.cs</code>, <code>BGMManager.cs</code>, <code>GuideManager.cs</code></td>
  </tr>
</table>

---

## Gameplay Overview 🍟 

- **Customers** arrive randomly and display their burger orders.
- The player prepares burgers using the correct ingredients and serves them before the customer runs out of patience.
- The system uses **Scriptable Objects** to store different customer types.
- **Plates** act as the assembly point for combining ingredients.
- Background music is handled by a simple audio loop manager, ensuring a pleasant diner vibe.

---

## Controls 🎮 

| Input        | Action                                        |
|--------------|-----------------------------------------------|
| Left Click   | Interact (select customers, pick ingredients) |

---

## Assets Used 📦 

> Assets are made manually and Generative (AI)

---

## Preview 📸 

<!-- Replace the link below with your own GIF if available -->
<img src="https://github.com/Alerica/Brain-Joint/blob/main/Brain%20Joint%20Clip.gif" alt="Gameplay Preview" style="width:100%;height:auto;">

---

## Project Goal

This game was created as a **learning project** to experiment with Unity's **Scriptable Objects**, **game state flow**, and **customer-based interaction systems**. It also served as a practice in organizing scalable game logic for future management/restaurant-style games.

---
