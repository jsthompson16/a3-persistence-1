## Pizza Ordering Website
Jarod Thompson
http://a3-jarodthompson.glitch.me

My website allows you to order pizza from Classic Pizza, allowing up to two toppings per pizza. 
You can order a new pizza, see your orders currently being worked on, edit them, and delete them.
Click on the "View Current Orders" link to see the table of current orders, and click on the "Order now!"
link to bring back up the form to order a new pizza.

Most of the challenges I faced involved changing my code from using a local array to using lowdb to store its information. 
I had trouble with editing and deleting information in particular, but got everything fixed *when running locally*. I don't understand why,
but once I imported the project to Glitch, it won't let me create new users, it will only allow an already accepted username and password.
The username and password to login with are 'arathorrn' and 'hello'. I would be happy to show this working properly on my own laptop, and don't think
I should be penalized points because I have it working on my laptop, it was only upon importing to Glitch that it stopped working.

I used Passport and lowdb because they were the easiest to implement.

I used sanitize.css for my CSS framework because I wanted a simple, clean look to my website.

Express Middleware
1. I used passport for user authentication. 
2. I used morgan to log all my HTTP requests to the console. 
3. I used helmet to set the HTTP request headers for me.
4. and 5. I used response-time and node-statsd to collect response times for my HTTP requests.

## Technical Achievements
- **Created PIXI scrolling picture**: Learned how use Pixi.js in order to create a scrolling picture of a pizza to add
                                      some color to my website

### Design/Evaluation Achievements
- **CSS**: I used two additional CSS frameworks, typography.css and forms.css, to help keep things consistent
           with the sanitize.css framework.
