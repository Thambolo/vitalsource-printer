# Print a book from VitalSource Bookshelf to PDF

This script simulates mouse click in the next page button and takes screenshot of
current page in the opened book.


## Usage
Only compatible with python 3.7.x , due to Pillow dependency

Get mouse x,y co-ordinates by using chrome extension.

```bash
pip install -r requirements.txt
python app.py top_left right_bottom next_button total_page
# Ex: python app.py 153,78 892,990 941,537 785
```
