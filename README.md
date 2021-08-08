# Profiles REST API

Profiles REST API course code.

## Profiles API design:
1. Create new profile
2. List existing profiles
3. View specific profiles
4. Update profile of logged in user

## API URLs:
1. /api/profile/ List all profiles when HTTP GET method is called; Create new profile when HTTP POST method is called
2. /api/profile/<profile_id>/ View specific profile details by using HTTP GET; Update object using HTTP PUT/PATCH; Remove it completely using HTTP DELETE

## FEED API:
1. Create new feed for existing users
2. Update feed items
Urls:
1. api/feed: list all feed items, GET (list feed items), POST (create feed item for logged in user)
2. api/feed/<feed_item_id>: manage specific feed items, GET (get the feed item), PUT/PATCH (update feed item), DELETE (delete feed item)
