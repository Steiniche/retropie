# Retropie

This project is a collaboration about how to setup retropie.
It is opinionated towards a danish setup.

## Locale

Set locale to en_DA-UTF8

### Fix danish keyboard

sudo vim /etc/default/keyboard

Set the following 

XKBLAYOUT="dk"

## Controllers

Use bluetooth

### Controller LED

Player 1 will be blue

Player 2 will be red

## Scraper

To install the scraper go into Retropie Setup -> Manage packages -> opt -> 830 scraper -> install from source

When installed it will be visible in the context menu (enter) and can add descriptions and thumbnails to all games
