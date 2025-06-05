class Book:
    def __init__ (self, title,author,year):
        self.title = title
        self.author = author
        self.year = year
    def get_info(self):
        return f"{self.title}, {self.author}, {self.year}"
    
book1 = Book('Roberto Carlo', 'Jane Smith', 2005)

print(book1.get_info())
