# Beacon

## Deployed Link 

https://whispering-earth-16314.herokuapp.com/

## Overview

Beacon is a “meet-up” style app that allows users to create events called “beacons,” designed to help people make connections with like-minded individuals.

In order to use this app, you must register and log in. When you enter your first and last name, a username will be automatically generated for you, consisting of your first name and last initial.

Once you've done that, you'll be taken to the home page which shows a list of all current beacons. On this page you can toggle between list view and map view, which shows all beacons on a map, centered on the latitude and longitude of the user's browser.

If you click "Add Beacon" on the navbar, you'll be taken to a form where you have to input a title, category, description, address, start time, end time, and date.

You can click on already created beacons, both from list view and map view, which takes you to the pages for the beacon. This will display all of the information the creator supplied, as well as the username of the creator and a map centered on the beacon's address. Below, user's can leave comments, which will be saved in order, and show when the comments were created (formatted by MomentJS). Users can delete their own comments and beacons, but no one else's.

You can also click on a username to go to that user's profile, where you can see links to all of the beacons they have created, as well as any comments they have left.

## Development

This app uses Node, Express, MySQL, Sequelize, Passport, Moment, Handlebars, and the Google Maps API.

Timothy Brahm, Matthew Gennings, Cassidy Groenendaal, and Max Szczepaniak developed this app together as their second of three projects in their three month coding boot camp at UNC Charlotte.

