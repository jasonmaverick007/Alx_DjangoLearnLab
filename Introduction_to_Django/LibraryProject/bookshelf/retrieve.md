# Retrieve all books
books = Book.objects.all()
print(books)

# Retrieve a specific book
book = Book.objects.get(title="1984")
print(book.title)           # Output: 1984
print(book.author)          # Output: George Orwell
print(book.publication_year)  # Output: 1949

Book.objects.filter(title="1984")
