README File

📋 **Menu Data Structure
**
This repository contains a Python dictionary named menu, structured to represent a food and drink menu with categorized items and prices. It can be used as a base for restaurant ordering systems, menu displays, or data manipulation projects.

🗂** Structure**
The menu dictionary is organized into the following top-level categories:

Snacks: Simple items like cookies and fruits.
Meals: Includes entrees such as burritos, sushi, and pizza with subcategories for types of pizza and burgers.
Drinks: Contains subcategories like soda, tea, and coffee, each with different size or flavor options.
Dessert: Sweet dishes like chocolate lava cake and various types of cheesecake.

⚙️ **Setup Instructions**
Clone the repository (or download menu.py directly):
git clone https://github.com/yourusername/menu-dictionary.git
cd menu-dictionary

**(Optional) Set up a virtual environment:**
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

**Use the menu dictionary in your project:**
from menu import menu

print(menu["Meals"]["Pizza"]["Cheese"])  # Outputs: 8.99

🛠 Example Usage
from menu import menu

# Access the price of a large soda
price = menu["Drinks"]["Soda"]["Large"]
print(f"Large Soda costs ${price}")
📎 File Contents
menu.py – Contains the full nested dictionary representing the menu.
