# yelpCamp

version 1
branch: master
technology: bootstrap, nodejs, expressjs

===================================================
YelpCamp: Initial Routes	
- add landing page {app.get(‘/’), … landing.ejs}
- add campgrounds page that lists all campgrounds {app.get(‘/campgrounds), …campgrounds.ejs}

YelpCamp: Layout	
- create our header and footer partials
- add in bootstrap

YelpCamp: Creating Campgrounds	
- setup new campground POST route {app.post(‘/campgrounds), …campgrounds.ejs, app.get(/campgrounds/new)…new.ejs}
- add in body-parser
- setup route to show form
- add basic unstyled form

YelpCamp: Styling Campgrounds	
- add a better header/title {campgrounds.ejs, jumpbotron}
- make campgrounds display in a grid

YelpCamp: Styling Nav and Forms	
- add a navbar to all templates
- style the campground form
