#Challenges

**Authors Table**

| `id` | `first_name` | `last_name` | `year_of_birth` | `year_of_death` |
| :---  | :---  | :---  | :---  | :---  |
| 1 | Rudyard | Kipling | 1865 | 1936 |
| 2 | Lewis | Carroll | 1832 | 1892 |
| 3 | H.G.  | Wells |  1866 | 1946  |

**Books Table**

| `id` | `title` | `publication_year` | `isbn` | `author_id` |
| :---  | :---  | :---  | :---  | :---  |
| 1 | The Jungle Book | 1894 | 9788497896696 | 1 |
| 2 | Alice's Adventures in Wonderland | 1865 | 9781552465707 | 2 |
| 3 | Rikki-Tikki-Tavi | 1894 | 1484123689 | 1 |
| 4 | Through the Looking-Glass | 1871 | 9781489500182 | 2 |
| 5 | The Time Machine |  1895  | 9781423794417 | 3 |

1. Use SQL aggregators to get the total value of the inventory, calculated as the sum of the price*quantity for each item.

2. Create a books table based on the printed table above. It should have attributes for `id`, `title`, `pub_year`, `isbn`, and `author_id`. For now, just make the `author_id` an INTEGER.

3. Add the classic children's books from earlier in this readme into your books table.

4. The library wants to start selling off old books. Add a `book_id` attribute to the products table so that the library can store books as inventory.

5. Insert the books from your books table into your products table. Make up a price and quantity for them.

#Stretch Challenges

1.  Find the inventory value of each book, and sort the records by inventory value, in descending order.

2.  Find the inventory value of the books by Lewis Caroll.
