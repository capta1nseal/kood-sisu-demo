# Commit messages

Commit messages are designed to help the development team to keep track on what has been done. In the version control system the commit points straight to the section of code that has been updated/created. This helps the reviewer to look through the update and see what changes has been made. 

## Text as a commit message

>What if I just write something general to it like - *updated the feature* - and commit? That should be enough right?

In some cases that might be true. Notice though that the commit message is making the life of others (and yours) so much easier when it is as informative and as summarized as possible. 

### So what are good guidelines when making a commit message?

Basically a summarization of what has been done. 

In my experiences it has been really useful to also define what part of the application has been updated as well like: 

```
frontend: Updated login to include third party login features
```

```
backend: Created new table Fruits to the database and it's endpoints to the API
```

Or

```
customer: Updated the customer login UX/UI
```

```
admin: Created statistics tool for admins to keep a track on customer logins
```

The ***customer*** in this second scenario points to the part of the software where the customer application is and the admin to the admin application (similar way of thinking as with the frontend-backend scenario). 
In this example the applications (customer and admin) are basically different root folders inside the software. 

!! Notice that every organization has their own way of doing things and those ways will be taught in the orientation period.

## Ticket systems (just as an introduction)

Some organizations like to use ticket systems like [Jira](https://www.atlassian.com/software/jira) in their production to simplify the project control. 
Basically tickets are ids that are created in the ticket system by providing to the specific id the content that the commit needs to contain and the commit message is replaced with the ticket id. 

We are not going to go through that more than this. 

--------------------------

### For navigation purposes:

[Back](../../README.md) to the README.md
