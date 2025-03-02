# Define the initial menu
menu = {
    'Pizza': 40,
    'Burger': 60,
    'Salad': 30,
    'Fries': 25,
    'Cheese Cookies': 35,
    'Macha tea': 35,
    # Trendy and Comfort Foods
    'Chicken Pot Pie': 120,
    'Fried Chicken': 80,
    'Meatloaf': 100,
    'Mash Potatoes': 40,
    'Chicken Parmesan': 90,
    'Beef Wellington': 150,
    'Lasagna': 110,
    'Spaghetti and Meatballs': 100,
    'Classic Cheeseburger': 70,
    'Mac and Cheese': 60,

    # Meat Alternatives
    'Beyond Burger': 80,
    'Impossible Burger': 85,
    'Veggie Burger': 65,
    'Plant-Based Sausages': 75,

    # Herbs and Seasonal Dishes
    'Turmeric Soup': 50,
    'Cardamom Coffee': 40,
    'Ginseng Tea': 45,
    'Burnet Salad': 55,
    'Lemon Balm Lemonade': 35,

    # Indian and South Indian Dishes
    'Tandoori Chicken': 120,
    'Dosa': 80,
    'Idli': 60,
    'Sambar Vada': 70,
    'Chana Masala': 90,
    'Palak Paneer': 100,
    'Biryani': 110,

    # Fusion and Unique Items
    'Fusion Tacos': 85,
    'Artisanal Sourdough Pizza': 120,
    'Gourmet Toasts': 60,
    'Elevated Bar Snacks': 75,
    'Ethically-Sourced Salads': 80,

    # Desserts and Drinks
    'Yuzu Cheesecake': 90,
    'Mocktails': 50,
    'Fresh Fruit Salad': 60,
    'Fermented Drinks': 55,
    'Ice Cream Sundae': 80,

    # Breakfast Items
    'Pancakes': 60,
    'Waffles': 65,
    'French Toast': 70,
    'Crepes': 75,

    # More Popular Items
    'Chicken Wings': 80,
    'Fries with Cheese': 50,
    'Chilli Cheese Fries': 55,
    'Garlic Bread': 40,
    'Grilled Cheese Sandwich': 60,

    # Additional Items
    'Spring Rolls': 70,
    'Chilly Paneer Dry': 90,
    'Veg Manchurian Dry': 80,
    'Potatoes in Honey & Chilly': 85,
    'Fried Vegetables': 75,
    'Crispy Spinach & Baby Corn': 80,
    'Chilly Mushroom Dry': 85,
    'Veg Chopsuey': 90,
    'Chilly Paneer Gravy': 100,
    'Manchurian Gravy': 85,
    'Sweet & Sour Veg': 85,
    'Mix Veg in Hot Garlic Sauce': 90,
    'Shredded Potatoes in Hot Garlic Sauce': 80,
    'Veg Hakka Noodles': 80,
    'Chilli Garlic Noodles': 80,
    'Pan Fried Noodles': 100,
    'Gravy Noodles': 100,
    'Veg Fried Rice': 80,
    'Tandoori Aloo': 85,
    'Punjabi Soya Chap': 85,
    'Hare-Bhare Kabab': 80,
    'Dahi ke Kabab': 85,
    'Platter': 150,
    'Shahi Paneer': 100,
    'Kadhai Paneer': 100,
    'Paneer Butter Masala': 100,
    'Mushroom Masala': 105,
    'Malai Kofta': 100,
    'Dal Makhani': 90,
    'Yellow Dal': 70,
    'Rajma': 70,
    'Chole': 70,
    'Tandoori Roti': 30,
    'Roomali Roti': 20,
    'Butter Roti': 35,
    'Plain Naan': 40,
    'Butter Naan': 55,
    'Garlic Naan Butter': 60,
    'Tawa Parantha': 50,
    'Laccha Parantha': 50,
    'Pudina Parantha': 50,
    'Stuffed Kulcha (Aloo)': 60,
    'Stuffed Kulcha (Paneer)': 60,
    'Stuffed Kulcha (Onion)': 60,
    'Papad': 15,
    'Steam Rice': 80,
    'Soya Dum Biryani': 120,
    'Thali Special': 140,
    'Roomali Roti with Paneer Tikka Masala': 130,
    'Rogan Soya Chap with Roomali Roti': 130,
    'Rice Idli': 40,
    'Sambhar Vada': 45,
    'Dahi Vada': 40,
    'Plain Dosa (Butter)': 65,
    'Onion Dosa (Butter)': 70,
    'Paper Dosa': 65,
    'Litchi Smoothie': 75,
    'Peach Apricot': 75,
    'Blue Berry Smoothie': 75,
    'Green Hayland': 75,
    'White Rosy': 75,
    'Watermelon Mojito': 75,
    'Vanilla/Strawberry Ice Cream': 30,
    'Tutti Fruti Ice Cream': 35,
    'Pineapple Ice Cream': 35,
    'Chocolate Ice Cream': 35,
    'Butter Scotch Ice Cream': 35,
    'Kaju Kishmish Ice Cream': 35,
    'Vanilla Chocochips Ice Cream': 35,
    'Mango Ice Cream': 35,
    'Anjeer Honey Ice Cream': 35,
    'Chocolate Almond Fudge Ice Cream': 35,
    'Kesar Pista Ice Cream': 35,
    'Black Currant Ice Cream': 35,
    'Hot Chocolate Fudge Sundae': 80,
    'Fruit Salad Sundae': 80,
    'Lime Ice / Orange Ice Cream Soda': 60,
    'Golden Glow / Strawberry Ice Cream Soda': 60,
    'Vanilla Ice Cream Shake': 65,
    'Mango Ice Cream Shake': 65,
    'Pineapple Ice Cream Shake': 65,
    'Chocolate / Coffee Ice Cream Shake': 65,
    'Kesar Pista Ice Cream Shake': 65,
    'Butter Scotch Ice Cream Shake': 65,
    'Tea': 25,
    'Coffee Mocachino': 35,
}

# Function to print the welcome message and menu
def print_menu():
    print("Welcome to Chowdhury Dines!!\n")
    for item, price in menu.items():
        print(f"{item} :- Rs {price}")

# Function to add new items to the menu
def add_to_menu():
    item_name = input("Enter the name of the new item: ")
    item_price = int(input("Enter the price of the new item: "))
    menu[item_name] = item_price
    print(f"{item_name} has been added to the menu.")

# Function to place an order
def place_order():
    order_total = 0
    n = int(input("Enter the number of items you want to order: "))
    
    for i in range(n):
        item_name = input(f"Enter the name of item {i+1} you want: ")
        
        # Check if the item is in the menu
        if item_name in menu:
            order_total += menu[item_name]
            print(f"You have ordered {item_name}.")
        else:
            print(f"You have ordered {item_name}, but it is not available in our menu.")
    
    print(f"\nYour total order is Rs {order_total}.")

# Main program loop
while True:
    print("\nOptions:")
    print("1. View Menu")
    print("2. Add to Menu")
    print("3. Place Order")
    print("4. Exit")
    
    choice = input("Enter your choice: ")
    
    if choice == "1":
        print_menu()
    elif choice == "2":
        add_to_menu()
    elif choice == "3":
        place_order()
    elif choice == "4":
        print("Thank you for visiting Chowdhury Dines!")
        break
    else:
        print("Invalid choice. Please choose again.")
