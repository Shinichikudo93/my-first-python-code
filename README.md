# my-first-python-code
class ShoppingList:
    def __init__(self):
        self.items = {}

    def add_item(self, item, quantity):
        self.items[item] = quantity

    def show_list(self):
        print("Shopping List:")
        for item, quantity in self.items.items():
            print(f"- {quantity} {item}")

# Membuat daftar belanja
shopping_list = ShoppingList()

# Ibu menyuruh anak membeli 6 botol susu dan 16 telur
shopping_list.add_item("bottles of milk", 6)
shopping_list.add_item("eggs", 16)

# Menampilkan daftar belanja
shopping_list.show_list()
