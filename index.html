Got it — you want a cashier system (likely a simple POS-like program).
I’ll give you a complete, runnable, and robust example in Python that works in the terminal, supports adding items, calculating totals, and generating receipts.

Python Cashier System
Pythonimport sys

# Product catalog (item_name: price)
PRODUCTS = {
    "apple": 0.5,
    "banana": 0.3,
    "milk": 1.2,
    "bread": 1.0,
    "eggs": 2.5
}

# Store cart as a list of tuples (item, quantity, price)
cart = []

def display_products():
    """Display available products and prices."""
    print("\nAvailable Products:")
    print("-" * 30)
    for item, price in PRODUCTS.items():
        print(f"{item.capitalize():<10} - ${price:.2f}")
    print("-" * 30)

def add_to_cart():
    """Add an item to the shopping cart."""
    item = input("Enter product name: ").strip().lower()
    if item not in PRODUCTS:
        print("❌ Product not found.")
        return
    try:
        qty = int(input("Enter quantity: "))
        if qty <= 0:
            print("❌ Quantity must be positive.")
            return
    except ValueError:
        print("❌ Invalid quantity.")
        return
    price = PRODUCTS[item]
    cart.append((item, qty, price))
    print(f"✅ Added {qty} x {item.capitalize()} to cart.")

def view_cart():
    """Display the current cart."""
    if not cart:
        print("\n🛒 Cart is empty.")
        return
    print("\nYour Cart:")
    print("-" * 40)
    total = 0
    for item, qty, price in cart:
        subtotal = qty * price
        total += subtotal
        print(f"{item.capitalize():<10} x{qty:<3} @ ${price:.2f} = ${subtotal:.2f}")
    print("-" * 40)
    print(f"Total: ${total:.2f}")

def checkout():
    """Finalize purchase and print receipt."""
    if not cart:
        print("🛒 Cart is empty. Nothing to checkout.")
        return
    view_cart()
    try:
        payment = float(input("Enter payment amount: $"))
    except ValueError:
        print("❌ Invalid payment.")
        return
    total = sum(qty * price for _, qty, price in cart)
    if payment < total:
        print("❌ Insufficient payment.")
        return
    change = payment - total
    print("\n🧾 Receipt")
    print("-" * 40)
    for item, qty, price in cart:
        print(f"{item.capitalize():<10} x{qty:<3} @ ${price:.2f} = ${qty * price:.2f}")
    print("-" * 40)
    print(f"Total: ${total:.2f}")
    print(f"Payment: ${payment:.2f}")
    print(f"Change: ${change:.2f}")
    print("✅ Thank you for shopping!")
    cart.clear()

def main():
    """Main menu loop."""
    while True:
        print("\n=== Cashier System ===")
        print("1. View Products")
        print("2. Add to Cart")
        print("3. View Cart")
        print("4. Checkout")
        print("5. Exit")
        choice = input("Select an option: ").strip()
        if choice == "1":
            display_products()
        elif choice == "2":
            add_to_cart()
        elif choice == "3":
            view_cart()
        elif choice == "4":
            checkout()
        elif choice == "5":
            print("👋 Goodbye!")
            sys.exit()
        else:
            print("❌ Invalid choice.")

if __name__ == "__main__":
    main()


Features

✅ Product catalog with prices
✅ Add items to cart with quantity
✅ View cart with running total
✅ Checkout with payment and change calculation
✅ Input validation for errors


If you want, I can also make a C++ version of this cashier system so it works as a compiled program for offline use.
Do you want me to prepare the C++ cashier system next?
