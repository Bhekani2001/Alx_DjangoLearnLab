\# CRUD Operations on Book model



\## Create



```python

from bookshelf.models import Book



book = Book.objects.create(title="1984", author="George Orwell", publication\_year=1949)

print(book)



