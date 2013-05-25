#Filename: Testing == Hello_world rails app

> *11.25-11.30
>looking at rails new
>aim:
>1. add a url for /home/index
>2. add a controller
>3. add html index file
>
>rails generate controller home index
>
>
>11,40
>app > views > home = index page
command+T, “routes.rb”
>  root :to => “home#index”      tell rails to root to index page located at app/views/home
>  delete the public > index.html page   this will route our home#index as the default
>
>
>
>12.00
create another page called dashboard with index page
>  rails generate controller dashboard index
>
><%= link_to “folder”, root_path %>    rails quick link
>root :to => “dashboard#index”   change the index root from home/index to dashboard/index
