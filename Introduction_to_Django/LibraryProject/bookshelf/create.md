from bookshelf.models import Book

# Create a new book instance and save it to the database
book = Book.objects.create(
    title="1984",
    author="George Orwell",
    publication_year=1949
)

print(book)
# Output: 1984 by George Orwell (1949)
