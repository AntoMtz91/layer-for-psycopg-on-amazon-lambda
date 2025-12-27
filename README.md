# layer-for-psycopg-on-amazon-lambda
Note: This works in lambda with Python 3.11  
This connector resolve bug: No module named 'psycopg2._psycopg': ModuleNotFoundError for lamda aws
1. Download.
2. Create a new layer.
3. Add use custom layer.
4. Upload zip
5. Set python 3.11.
6. Save.
7. Add to lambda that use psycopg connector.
