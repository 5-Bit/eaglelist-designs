---
layout: post
title: "Desired Features"
---


### Purpose

EagleLists is a desktop application where FGCU students can list and trade books and various other items. 
Our focus is mainly on books however. 

### Basic needs:

- User Authentication (bcrypt on server and client)
- Create Book Listing  (UI on client, store on server)
- User Sign up    (UI flow on client, create user info on server)
- View list of books/offers (UI on client, feed by server route)

### More advanced needs:
- Pretty formatting for listings (pictures, possibly HTML rendering)
- Reports on usage, number of users, activity, and so on.
- Usage policiy, some kind of way to report users for false advertizing... IDK about this
- ADMIN TOOLS! (So that we can avoid the reddit-style drama)

### Good ideas:

- Book search by CRN
- Book search by ISBN
- Trying to figure out ElasticSearch
- Spam reporting system (use akismet? Seems a little strange, but could work)

### Open questions:
- How do we connect users? (Criagslist has users connect via email, but doesn't let them talk via criagslist)
- What other big features do we want to add?
