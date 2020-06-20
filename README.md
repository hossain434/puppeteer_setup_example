# puppeteer_setup_example

1.	What is the purpose to use  this tool?
https://blog.goodaudience.com/why-you-should-use-puppeteer-for-testing-a3b41dbce660


2.	Why this is better than other tool?
https://www.lucidchart.com/techblog/2018/08/08/why-puppeteer-is-better-than-selenium/
Having used both Selenium and Puppeteer, these would be my observations as to why it's currently being recommended so highly:

Puppeteer is really easy to configure and execute. No setting specific drivers required. Just write your test scripts, point node towards your scripts and watch it go. Everything even runs in parallel!

It's a zero setup framework in that it comes bundled with the version of Chromium which it runs best with.
Another benefit is speed. Puppeteer is really fast since it uses headless Chrome.

It integrates very nicely with other popular test frameworks such as jest and mocha.

Using Puppeteers API is really straightforward. Everything is simple to write, easy to understand and basically allows for simple user interactions to be automated using a single line of code.

It's really easy to debug your automation scripts. Simply set headless to false and turn slowMo up from 0 to, say, 250 and you can easily see what's going on and fix any problems you may have.

It's easy to pick up and use no matter what your previous experience levels: on the team I'm working on, everyone (even those with no real automation test script writing experience) has found working with Puppeteer a really nice and relaxed experience. Everyone is getting the grasp of it within a few minutes of basic research and getting scripts running quickly and with no hassle or stress.

It should be noted that Selenium does do everything that Puppeteer does (and vice versa) but that's not the point of Puppeteer. Puppeteer allows for a team to build a large library of automation scripts very quickly using an easy to use API and get tests running now rather than having to deal with building ultra-robust test frameworks which work cross browser and / or cross device.

If you really must have cross browser testing then Selenium or perhaps InternJS (a personal favourite of mine) are still the choices to make.

Puppeteer only supports executing tests on Chrome but, at the end of the day, it's much better to have a lot of tests running (even if it's just on Chrome) as opposed to having none.

3.	Why you're using this tool?
Same as #2

4. Usability:
a. Normal scripting using page object and with different browsers. and platform e.g Windows, MAC, Mobile
Page Object: Yes, http://dsheiko.com/weblog/end-to-end-testing-with-puppeteer
Support: Chrome, recently supports Firefox
Support Mac
Mobile: 

b. Parallel execution. Yes

c. Datadriven with Assertion (Yes) using csv or xlsx (Yes)

d. Jenkins build or execution in Docker (Yes)

e. Result Report Yes

f. Advantages and drawback

No support for cross-browser testing: One of the things that we’d like to be able to tap into in the future with true end-to-end testing is user behavior cross browser. It is currently not a concern for Puppeteer since it isn’t what the project was set out to achieve.

Immature community: Puppeteer is still a very young framework and the community is still growing, but it’s not mature, and hence it’s somewhat hard to find relevant resources for help across the web.

Puppeteer Setup:

Puppeteer

npm -y

npm install puppeteer --save-dev

To run: node newtest.js

https://flaviocopes.com/puppeteer/

https://pptr.dev/
