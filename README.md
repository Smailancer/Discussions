# Discussions Platform
I have been thinking for a long time about creating a platform that specializes in sharing personal experiences only, away from any theoretical discussions that make the user absent from his reality living in a fake virtual world.
I am currently thinking of naming the platform and the most important characteristics that I would like to put in it.


## Screen shots from the app:

### Home Page:

![a pic from the home page](https://i.suar.me/mwJZN/l)

### Discussion Show Page:

![a pic from the show page](https://i.suar.me/lwV95/l)

### Admin privilege to manage channels
![admin channels](https://i.suar.me/QrAPK/l)

## Platform features:
- You can register as a member, create discussions, and comment on others' discussions
- Each channel contains many discussions
- Only the administrator can create channels
- Administrator can edit discussions and comments
- The platform's text editor is equipped with a Markdown reading feature

## Used Gems :

- bulma-rails
- simple_form
- devise
- gravatar_image_tag
- jquery-rails
- rolify
- cancancan
- friendly_id
- redcarpet
- coderay

## Ruby and Rails versions used :

- `Ruby 2.7.5`
- `Rails 5.2.7`

## How to use the platform :

Clone the project to your computer using the command:

````bash
git clone git@github.com:smaily1/discussions.git
````
- Enter the project folder using the command `cd discussions`, Then to install the Gems in the project, run the command:

````bash
bundle install
````

- Build the tables in the database using :

````bash
rails db:migrate
````

- Finally, to run the application, type the command:

````bash
rails server 
````

- Then you will find that the application works for you at the link `http://localhost:3000`
