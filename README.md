# 14-Model-View-Controller-MVC
# Tech Blog

This application is a blog that allows users to create accounts, posts, and comments on posts. Users are able to delete/update their existing posts. Users are automatically logged out after 15 minutes of inactivity.

The deployed application can be found [here](https://esd-14-tech-blog.herokuapp.com/). The application's GitHub repository can be found [here](https://github.com/elisesamanthadaly/14-Model-View-Controller-MVC).


## Usage

Existing posts can be viewed on the homepage.

Click the "Login" link in the navigation bar to login or signup.

After logging in/signing up, new posts can be created on the "Dashboard" screen. Click one of your existing posts on the Dashboard screen to update or delete it.

On the homepage (click the "Home" link in the navigation bar), click an individual post to view or add comments to it.

![alt text](./assets/images/screencast.gif)


## Credits

Starter code provided by the UNC Coding Bootcamp.

This application relies on the following npm packages:
* [bcrypt](https://www.npmjs.com/package/bcrypt)
* [connect-session-sequelize](https://www.npmjs.com/package/connect-session-sequelize)
* [dotenv](https://www.npmjs.com/package/dotenv)
* [express](https://www.npmjs.com/package/express)
* [express-handlebars](https://www.npmjs.com/package/express-handlebars)
* [express-session](https://www.npmjs.com/package/express-session)
* [mysql2](https://www.npmjs.com/package/mysql2)
* [sequelize](https://www.npmjs.com/package/sequelize)


## License

MIT License

Copyright (c) 2021 Elise Daly

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.