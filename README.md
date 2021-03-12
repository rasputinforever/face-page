# face-page
An antisocial network



## User Interaction
User can make posts on their page.
  Over time, posts are given LIKES -> Likes stored on post db row
  Over time, posts are given COMMENTS -> Comments are stored on its own table
    Comments source Author from "Friend List" table
    Comment text source "Comment" table which have various qualitatives: comments are positive, negative, neutral
      Comments can have replies to them as well but limted to only a "2nd level" 
      Comments may be "ad-libbed" in the sense that the user's name can be injected in.
      
      
      
 User can sort all posts by date, length, and "activity".
 User can search up posts.
 User can "add friends" -> adds more Authors. Authors have qualities as the comments so they may be more likely to give pos/neg/neu comments.

## Initial State
DB will be pre-loaded with 10 friends and around 100+ comments

## Ad-Libbing
any pre-set "comments" will have variables in. Filling them would require an 3rd party API call to fill those. 


## Tools to use

### 3rd party API for random elements/fills
### CDN for CSS

### Change of plan: do this is PYTHON

## Concepts to use
### Random Number Generator -- how to apply to ad-libbing
### Time-based interactions -- relative to POST DATE, engagement decreases.