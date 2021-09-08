# Gallery Management System

This project is a simple db management system that allows everyone to observe Pieces of Art, trade them, and learn about them.

Entities that can be represented in this project:
* Artist
* Customer (AKA buyer)
* Art Work
* Artist's Union
* Artist's Style

relations be like:
* artist (1 to many) art_work
* artist (many to many) artist_union
* art_work (many to 1) artist_style
* customer (0 or 1 to many) art_work
* artist (1 to many) artist_style
* ???
* PROFIT
