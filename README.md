# buckwheat
Repository for int2021's first task
## API
```python
GET [site]/products/{product_name}
    Returns:
        [Item]
    Item:
        name string
        weight float # weight in kg
        manufacturer string
        price float
        origin string # where to find it

GET [site]/products/{product_name}/stats
    Returns:
        [Pair<date, Item>]

GET [site]/search
    FormData:
        query string # search query
    Returns:
        [string] # first is more likely to match the query
```
