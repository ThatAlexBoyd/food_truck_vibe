# Sandwich Hero 🥪

Welcome to Sandwich Hero, a single-file HTML, CSS, and JavaScript food truck simulation game. Embark on a journey across a charming region, building your reputation one sandwich at a time. Your goal is to fill your cookbook with every regional recipe and become the ultimate Sandwich Hero by mastering them all.

## 🕹️ Gameplay

Sandwich Hero is a strategic management game where every day presents new opportunities and challenges.

### The Gameplay Loop

1.  **Plan Your Day:** At the start of each day, check for special events that might affect your strategy. Use the **Cookbook** on the right to select which two sandwiches you want to feature on your daily menu.
2.  **Choose an Action:** From the main panel, decide what you want to do for the day:
    *   **🚚 Setup Shop & Sell:** This is your primary way to earn money. The game simulates a day of sales based on your location, menu choices, recipe levels, and any active events. Watch as customers line up and your earnings grow!
    *   **🛒 Visit Store:** Restock your ingredients. Prices and availability vary by location, and daily events can cause sales or shortages.
    *   **👨‍🍳 Talk to the Local Expert:** Every location has a resident expert with a unique recipe to teach you... sometimes for a price or a challenge.
    *   **🏘️ Talk to Locals:** Gather intel on which sandwiches are most popular in the area to maximize your reputation and sales.
    *   **📋 Check Bulletin Board:** Discover and complete local quests for unique rewards and extra cash.
    *   **📍 Change Location:** Ready for a new scene? Travel to a new city. Be aware that travel takes time, advancing the game clock by one or more days.
3.  **Learn & Master:** Selling sandwiches earns XP for that recipe. As a recipe levels up, its selling price increases. Selling local favorites builds your reputation, and even mastered recipes become a reliable way to impress the locals and grow your fame.
4.  **Grow Your Empire:** Use your earnings to buy new ingredients, unlock new recipes, and travel to new locations with bigger customer bases.

### Winning the Game

The game is won when you have:
1.  Unlocked every recipe in the game.
2.  Mastered every single recipe to Level 3.

---

## ✨ Key Features

*   **Recipe Mastery System:** Each recipe has 3 levels. Selling a sandwich has a chance to grant XP, and leveling up increases its selling price.
*   **Mastery Perks:** Upon mastering a recipe, choose a permanent, powerful perk for it, such as a chance for bonus profit, reduced ingredient consumption, or extra reputation gain.
*   **Bulletin Board Quests:** Each city has a unique quest. Check the local bulletin board to discover tasks and earn valuable rewards.
*   **Dynamic Locations:** Travel between 9 unique locations, each with its own theme, max reputation, customer base, local recipe, and ingredient availability.
*   **Reputation & Preferences:** Gain reputation in a city by selling sandwiches, especially local favorites. Mastering a recipe allows you to build reputation even faster, making it a key strategy for winning over a city. High reputation can lead to positive articles in the local paper.
*   **Daily Event System:** Each day has a chance to trigger a random event, such as a supplier discount, a customer boost from a local festival, a price hike due to shortages, or a food truck competition.
*   **Resource Management:** Juggle your money and seven different ingredient inventories to ensure you never run out of supplies mid-rush.
*   **Narrative Flair:** Each location's recipe seller has a unique personality and story that adds flavor to the world.
*   **Zero Dependencies:** The entire game runs from a single HTML file with no build steps or server required. It uses CDN links for TailwindCSS and Font Awesome.

---

## 📊 Game Data Breakdown

### Ingredients

| Ingredient   | Emoji | Base Price | Servings per Purchase |
|--------------|-------|------------|-----------------------|
| Bread        | 🍞    | $10.00     | 100                   |
| Meat         | 🥩    | $15.00     | 75                    |
| Spread       | 🧈    | $20.00     | 25                    |
| Cheese       | 🧀    | $20.00     | 25                    |
| Toppings     | 🥓    | $10.00     | 75                    |
| Sauce        | 🥫    | $10.00     | 40                    |
| Vegetables   | 🥬    | $10.00     | 40                    |

### Recipes

| Recipe          | Unlock Cost | Selling Prices (L1/L2/L3) | Ingredients Required                                 | XP to Master (L1→2 / L2→3) |
|-----------------|-------------|---------------------------|------------------------------------------------------|----------------------------|
| **Ham & cheese**| $0          | $3 / $3 / $4              | 1x Bread, 1x Meat, 1x Cheese                         | 25 / 60                    |
| **BLT**         | $0          | $3 / $3 / $4              | 1x Bread, 1x Toppings, 2x Vegetables                 | 25 / 60                    |
| **Club**        | $50         | $5 / $6 / $7              | 1x Bread, 1x Meat, 1x Cheese, 1x Spread, 1x Toppings | 50 / 100                   |
| **Patty melt**  | $40         | $4 / $5 / $6              | 1x Bread, 1x Meat, 1x Cheese, 1x Sauce               | 35 / 80                    |
| **Italian**     | $75         | $6 / $7 / $8              | 1x Bread, 2x Meat, 2x Cheese, 1x Toppings, 1x Sauce, 1x Vegetables | 50 / 110                   |
| **West Coast**  | $80         | $3 / $4 / $5              | 1x Bread, 1x Meat, 1x Spread, 1x Vegetables          | 50 / 100                   |
| **Reuben**      | $90         | $5 / $6 / $7              | 1x Bread, 2x Meat, 1x Cheese, 1x Sauce               | 50 / 100                   |
| **Chicken salad**| $100       | $3 / $4 / $5              | 1x Bread, 1x Meat, 2x Spread, 1x Toppings            | 50 / 100                   |
| **Salad**       | $30         | $3 / $4 / $5              | 1x Meat, 1x Spread, 1x Sauce, 2x Vegetables          | 40 / 90                    |
| **Burger**      | $150        | $7 / $8 / $9              | 1x Bread, 1x Meat, 1x Cheese, 1x Spread, 1x Toppings, 2x Sauce, 2x Vegetables | 75 / 150                   |
| **The Ultimate**| $250        | $9 / $11 / $13            | 1x Bread, 2x Meat, 2x Cheese, 1x Spread, 2x Toppings, 1x Sauce, 1x Vegetables | 75 / 150                   |

### Locations

| Location          | Emoji | Local Recipe    | Local Favorites       | Recipe Seller            |
|-------------------|-------|-----------------|-----------------------|--------------------------|
| **Central City**    | 🛣️    | Club            | Ham & cheese, Club    | Old Man Earl 👴          |
| **Bravoport**       | ⚓    | Italian         | Italian, Club         | 'Salty' Sofia 👩‍✈️        |
| **Evergreen Pointe**| 🌲    | West Coast      | West Coast, Salad     | Forrest 👨‍🌾             |
| **Maple Heights**   | 🌳    | Chicken salad   | Chicken salad, West Coast | Patty 👩‍🍳                 |
| **Bourbon Creek**   | 🎷    | Patty melt      | Patty melt, Italian   | Chef Antoine 👨‍🍳          |
| **Steel City**      | 🏢    | Reuben          | Reuben, Burger        | Frankie 'The Furnace' 👨‍🏭 |
| **Twin River City** | 🎶    | Salad           | Salad, Italian        | Belle 👩‍🎤                 |
| **Aspen Peak**      | 🚠    | Burger          | Burger, Reuben        | Chad 🏂                  |
| **Bay City**        | 🌉    | The Ultimate    | The Ultimate, Burger  | The Investor 👨‍💼         |

### Daily Events

| Event Type         | Effect                                | Type  |
|--------------------|---------------------------------------|-------|
| **Customer Boost**   | Increases the number of customers.    | Buff  |
| **Cost Decrease**    | Reduces ingredient prices by 5-10%.   | Buff  |
| **BOGO**           | Ingredients are Buy-One-Get-One-Free. | Buff  |
| **Competition**    | Boosts preference for a specific recipe. | Buff  |
| **Customer Slump**   | Decreases the number of customers.    | Debuff|
| **Cost Increase**    | Increases ingredient prices by 5-20%. | Debuff|

---

## 🚀 How to Play

No installation or setup is required.

1.  Clone or download this repository.
2.  Open the `sandwich_truck.html` file in any modern web browser (Chrome, Firefox, Edge, Safari).
3.  That's it! Start your journey to becoming a Sandwich Hero.

## 🛠️ Technology Stack

*   **HTML5**
*   **CSS3** (with **Tailwind CSS** via CDN for styling)
*   **Vanilla JavaScript (ES6+)** for all game logic.
*   **Font Awesome** & **Google Fonts** (via CDN) for icons and typography.