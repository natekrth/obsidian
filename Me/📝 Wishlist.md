[➕ Create New Wishlist](obsidian://new?vault=Obsidian%20Vault&name=obsidian://open?vault=Obsidian%20Vault&file=Me%2FWishlist%2FWishlist&template=Template/Create%20wishlist%20movie)


```page-gallery
fields: [file.name]
columns: 4
prientation: portrait
sortBy: ['-created']
filter: false
limit: 20
views:
  - name: Movie
    from: '"Me/Wishlist/Movie"'
    where: 'contains(lower(category), "movie") OR contains(tags, "movie")'
    sort: 'created'  
  - name: Music
    from: '"Me/Wishlist/Music"'
    where: 'contains(lower(category), "music") OR contains(tags, "music")'
    sort: 'created'
    columns: 3
    orientation: square
```
