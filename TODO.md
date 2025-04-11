
# homebox

## TODO

### general

- [ ] Re-sync `.env` with `.env.dist`
  * We accidentally confused the two files and wound up adding environment
  to `.env` instead of `.env.dist` as we should have...

- [ ] attempt to use the postgres backend once more
  * `compose.db.yml`

- [ ] finish initial plumbing work to separate attachments storage
from the API & server

- [ ] experiment with importing CSV of Amazon order history
- [ ] improve the date picker
- [ ] user avatar photos
- [ ] additional theme options
  * **CSS** injection
  * custom 404, ... pages
- [ ] templating list of *custom fields* added at time of item creation

#### /home

- [ ] Add hyperlinks for the **Quick Statistics** item cards
  * Total # of Items -> <https://inventory.fs1.home/items>
  * Total # of Locations -> <https://inventory.fs1.home/locations>
  * Total # of Labels -> <https://inventory.fs1.home/labels>

#### /locations

- [ ] add **primary photo** capability for location entries?
- [ ] add item button at bottom-right corner
  * <https://inventory.fs1.home/locations>

### /api

- [ ] quick link shortcut to generate a user API token
  * `?access_token=UY4OHBTSZC3PQVHEBT4JT2VBB4`

