# User Story Kit #

Simple tools for turning simple user stories defined in .CSV files into human-readable, sorted Markdown documents that can then be rendered to HTML, PDF etc.

# Usage #

It's super simple! Copy the include template .CSV file, add your own user stories, and run the script to generate your Markdown document.

## Input ##

> Priority,As a,I want to,so that
> medium,user,create an account for myself,I can start using the system immediately
> medium,user,reset my own password using my email address,I can log in
> medium,user,complain to the developers,they can make the system better
> high,admin,delete all user accounts,I can go home,be happy

## Run ##

> ./stories2markdown my_stories.csv # Will generate my_stories.csv.md
> markdown my_stories.csv.md > my_stories.html # (Assuming you have Markdown installed.)

## Output ##

># User Stories
>
>4 stories total.
>2 roles defined.
>2 priority levels.
>
>## By Role
>
>### User
>
> * [medium] As a user I want to create an account for myself so that I can start using the system immediately.
> * [medium] As a user I want to reset my own password using my email address so that I can log in.
> * [medium] As a user I want to complain to the developers so that they can make the system better.
>
>### Admin
>
> * [high] As a admin I want to delete all user accounts so that I can go home and be happy.
>
>## By Priority
>
>### Medium
>
> * [medium] As a user I want to create an account for myself so that I can start using the system immediately.
> * [medium] As a user I want to reset my own password using my email address so that I can log in.
> * [medium] As a user I want to complain to the developers so that they can make the system better.
>
>### High
>
> * [high] As a admin I want to delete all user accounts so that I can go home and be happy.


# Legal #

Copyright © 2012 Preston Lee. All rights reserved.

Released under the Apache 2.0 license: http://www.apache.org/licenses/LICENSE-2.0.html
