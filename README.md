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
shopping_list.show_list
test 123 
print('\n'.join
([''.join
([('Engineer'[(x-y)%8 ]
if((x*0.05)**2+(y*0.1)**2-1)
**3-(x*0.05)**2*(y*0.1)
**3<=0 else' ')
for x in range(-30,30)])
for y in range(15,-15,-1)]))
