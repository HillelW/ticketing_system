# Ticketing System

Welcome to the Ticketing System! 

This application tracks tickets and their priorities.

Clicking on the column named `Ticket Number` sorts the tickets by ticket number.
Clicking on the column named `Priority` sorts the tickets by priority.

An indicator `^` is appended to a column name if that column is sorted in ascending
order. An indicator `v` is appended to a column name if that column is sorted in 
descending order.

Additional data can be loaded by clicking the button labeled `Load More`.

Clicking the button labeled `Load More` more than once will result in an error message, 
since no more data is available to be loaded.

Although this application currently uses hard-coded data, 
it can be easily adapted to process a dynamic JSON response from an API.
