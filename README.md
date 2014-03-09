This is my first attempt at ember.js. Thanks for the cool tutorial!

In order to make the markdown rendering work, I had to change the way the var showdown was declared, and stuck it inside the helper method. Until then, it couldn't find Showdown; I think it may have been trying to load the entity before the JS file was reached? Or something? Anyway, this works!
