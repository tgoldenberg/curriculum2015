#Project 4 - Rails website
![Imgur](http://guides.rubyonrails.org/images/getting_started/rails_welcome.png)

##Do Now 
Begin this session by completing the [Do Now](doNow.md) activity.

##Scope
One thing that should be in everyone's portfolio is a personal website / blog. Writing about technical issues shows that you are interested in the work that you do, and that you believe that passing along that information to others is important to you. Github itself is built around the idea of Open Source software - or code that usable by anyone without payment or copyright. Therefore, when you learn something cool, write about it! This exercise will show you how to start your own blog with minimum effort and pain :). 

##Project Criteria
For this project, you should: 
- style the basic template to make it look nice with CSS 
- Write some blog content for others to see 
- Host it on the web!

##References/Tools
* [official Rails site](http://rubyonrails.org/)
* [ruby docs](http://ruby-doc.org/)
* [rails tutorial](https://www.railstutorial.org/)

 
##Vocabulary

* Gem
* Heroku
* Rails
* Ruby 
* Forms
* MVC

***
##Instructions

- type in the command `rails generate scaffold posts title:string author:string content:string` 
- then type the command `rake db:migrate`
- finally, change the `routes.rb` file to the following: 
  `root 'posts#index'`
- run the command to run the app and check it out - ` rails s -b $IP -p $PORT`
- Last, write some posts and style the stylesheet - located in `app/assets/stylesheets/posts.scss` 
- Hint: use the Chrome inspector to examine the HTML elements and assign new styles to them - use wireframing to help!

## Hosting 

Next, use git and `Github` to save your project to your Github account. 
To publish the website online, do the following: 
- create an account on heroku, then
- `heroku create MY_BLOG_NAME` 
- `git push heroku master` 
- `heroku run rake db:migrate` 

##Homework
Instructor will assign homework based on progress in class.



