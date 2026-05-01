# TranslateHelper

## Goal 

to make a platform that not only translate a word, but do this based on what you do and keep it

user can: 
-   make a section & explain what is going to do here (like reading the book Deep Work)
-   make a session & start giving inputs as word or sentences 
-   also can review the words in a session like memorizing apps 

## Core objects:

### Section:
-   id
-   title
-   created_at
-   note

### Session
-   id 
-   section_id
-   created_at

### phrase
-   id
-   input
-   session_id
-   created_at
-   last_review
-   number_of_review


## MVP features
-   CRUD for section
-   CRUD for session
-   CRUD for a phrase
-   basic dashboard
-   review test