Mosaic
======

Mosaic

--Removed from show page <%= render '/refinery/content_page' %>
--Start run: rails server
--Override a page rake refinery:override view=refinery/pages/show
--adding events:
    rails generate refinery:engine event title:string date:datetime photo:image blurb:text
--engines
    rails generate refinery:inquiries