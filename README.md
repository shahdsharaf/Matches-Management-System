# Matches Management - Website

This website's idea is to implement a system that manages the matches played in any sport as well as the fan attendance to these matches.

This is a simple Academic project that focuses on learning the ASP.NET web framework to develop a website with functionalities like logging in, signing up, viewing schedules, functioning buttons, etc..

This project's main focus was to use SQL commands, and execute them within the code to be able to manipulate our local database according to whatever functions needed such as storing user credentials (username, password & ID), storing match schedules, managing ticket-buying system etc..


Each different type of user (System Admin, Sports Association Manager, Club Representative, Stadium Manager & Fan) had different functionalities, with different homepages that have an intuitive design to them to make it easily usable.
<hr>

## Sports Association Manager
The association manager can manage (create, edit or delete) the
matches that will be played by the different clubs.
## Matches
Matches will be played by exactly two Clubs. One of them is considered the host of the match. Each
game has an ID, starting time, ending time and allowed number of attendees. Also, each match will be
hosted on exactly one stadium.
## Clubs
Each club (which has an ID, name and location) can play many matches through the season. The club
will also have a representative (with a name and ID). who will be responsible for asking for the permission
to host the matches played by the club he is representing when the club is the host of that match.
## Stadiums
Stadiums (which have an ID, name, capacity, location and status) are there to host the games. The status
of the stadium can be either available or not available. Each stadium has a manager (who has a name and
ID) who is in charge for approving or disapproving the different club requests for hosting their matches
on the stadium he is managing .
## Tickets
Once the stadium manager approves hosting a certain game, tickets will be available for the fans to buy
and attend the game. Each ticket has an ID, a stadium where the match is hosted on and a status that
can either be sold or available. The system keeps track about which users bought which tickets.

## Fans
Fans (who have name, national ID number, birth date, address and phone number) can buy tickets to
attend the matches. For some cases, a fan can temporarily be blocked from using the system.
## System Admin
The system admin is the one who can add or delete clubs, add or delete stadiums, add or delete and
temporarily block fans from using the system.