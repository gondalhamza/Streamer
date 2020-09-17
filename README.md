# Streamer

> A dashboard for watching out real time tweets for end user.

> This is my first Rails 6 project.

**Considering it an `MVP` Minimun Viable Product the main features selected for this phase are:**

- User login through Twitter account.
- The Dashboard contains User timeline tweets(tweeted by end user).
- The Home(wall) tweets (tweeted by friends of user).
- Bootstrap 4 framework is adopted with custom styling to make it more visually attractive.

---

## Installation


### Clone

- Clone this repo to your local machine using `https://github.com/gondalhamza/Streamer.git`

### Setup

- Follow the steps to setup project on local your machine

> Create gemset and install bundler

```shell
$ gem install bundler
$ bundle install
```

> Install yarn packages

```shell
$ yarn install
```

- Setup environment variables `TWITTER_CONSUMER_KEY`, `TWITTER_CONSUMER_SECRET`, `TWITTER_ACCESS_TOKEN`, `TWITTER_ACCESS_TOKEN_SECRET` 

> Copy .env.example file to .env (configure twitter credentials from twitter developer account)

```shell
$ cp .env.example .env
```

> Setup your database

```shell
$ rake db:create
$ rake db:migrate
```

> Run server at localhost

```shell
$ rails s
```

- Point your browser to `localhost:3000`

---


## Usage
- On homepage click on Login button
- Enter Twitter credentials on pop up window
- You will be landed to dashboard where user info is displayed

```shell
Follows
```
```shell
Followed
```
```shell
Username
```
```shell
Profile picture
```
```shell
Full Name
```

- To see Timeline tweets click on `Timeline` button from left sidebar.
- To see Home(Wall) tweets click on `Wall` button from sidebar.

---

## Tests 
TODO:
- Unit Tests and Integration Tests

During the last week I got sick, had to take rest from all my duties. In that time Test casses were part of Initial Plan.

---
## Timeline
> In the start I planned to complete this work in 4 weeks along with my other commitments. 
> Getting the twitter developer approved took almost 2 weeks.
> After that I did my initial commit.

---
## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)
MIT License

Copyright (c) 2020 Hamza Zubair

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
