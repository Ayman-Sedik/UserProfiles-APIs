# UserProfiles APIs Project
> This project (User Profiles and Feed APIs) enables you to create and edit a new profile, create new feeds in your profile, view the status of other profiles of all users, and much more features...
## [Demo video](https://drive.google.com/file/d/1f3WHtRiosKeXHMhkfi4azeippRLxk544/view?usp=sharing)

## PLAN OUR PROFILE API
- **BASIC REQUIREMENTS**
1. Create new profile 
   - Handle registration of new users
   - Validate profile data 
   
2. Listing existing profiles
   - Search for profiles
   - Email and name
   
3. View specific profiles
   - Profile ID
   
4. Update profiles of logged in user
   - Change name, email and password
   
5. Delete profile


- **API URLs**
1. /api/profile/
   - list all profiles when HTTP GET method is called
   - create new profile when HTTP POST method is called

2. /api/profile/<profile_id>/
   - view specific profile details by using HTTP GET
   - update object using HTTP PUT / PATCH
   - remove it completely using HTTP DELETE 

## PLAN OUR FEED API
- **BASIC REQUIREMENTS**
1. Creating new feed items
   - Logged in user only
3. Updating feed items
   - Logged in user only
5. Deleting profile feed items
   - Logged in user only

6. Viewing other profile status updates
   - All users
  
- **API URLs**
1. /api/feed/
   - list all feed items
   - GET (list feed items)
   - POST (create feed item for logged in user)

2. /api/feed/<feed_item_id>/
   - manage specific feed items
   - GET (get the feed item)
   - PUT / PATCH (update feed item)
   - DELETE (delete feed item)
