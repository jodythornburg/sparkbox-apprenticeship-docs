# Leveling Up Your Frontend Development Environment
So you’ve decided to take the next step in your internet-making education—congratulations. Give yourself a well-deserved pat on the back. As a fellow [student of the internet](http://apprentices.seesparkbox.com/), I know what it’s like to [carve](https://www.codeschool.com/) out an [education](http://teamtreehouse.com/) in all [things](http://www.codecademy.com/) [web](https://the-pastry-box-project.net/ben-callahan/2015-january-22), and what a challenge it can be. The road ahead is going to be tough, but seriously rewarding.

For me, one of the most important steps in taking my internetting to the next level was getting my development environment in shape. It allowed me go from fighting against my computer to using tools to my advantage, so I could focus on just writing code. I’ve had the benefit of being around [some great people](http://seesparkbox.com/team) who have helped me make some good decisions through this process. In case you don’t have that advantage, what follows is some highly opinionated advice on the next steps you should take.

## Some Assumptions
But, before that, let’s get some basic assumptions out of the way. I’m assuming that you’ll mainly be writing HTML, CSS, and a little JavaScript for now. I’m also assuming that you’re doing all that on a Mac (if you’re on another platform, I’m the wrong guy to help you). And finally, I’m assuming that you’ve hit a roadblock with your current tools, you’re pulling out your hair, typing way too much, and doing a lot of unnecessary repetition. With that said, it’s time to level up.

## Software Recommendations
First things first, stop reading and install all the software in this section. Trust me, you’ll be happy you did. These apps are mostly free, and where they’re not, there are options to try before you buy—or use a less feature-filled version.

**[Google Chrome](http://www.google.com/chrome/):** In my humble opinion, it’s the best browser out there. And while you should definitely have copies of all the latest browsers on your machine for testing (and plan to test on some older versions too), it’s the one to use for development purposes (though some would disagree).

**[Sublime Text](http://www.sublimetext.com/):** I’ve used my fair share of text editors—many of which I’ve liked. But none of them so far have matched the ease-of-use, keyboard shortcuts, and extensive assortment of plugins available you get with Sublime (although some would argue Vim is superior). 

**[iTerm](http://iterm2.com/):** While the default Mac terminal is fine, iTerm is just so much better. Split panes, easy tabs, hotkey support, and lots of configuration options are just a few of the reasons it’ll make your life easier.

**[Dash](http://kapeli.com/dash):** Having API documentation readily available can be the difference between hours spent googling, and actually shipping a new feature. It’s searchable, keeps everything in one place, and has docs for just about every language imaginable.

**[Alfred](http://www.alfredapp.com/):** While not exactly a development app, Alfred will make you so productive on your Mac that you’ll wonder how you ever got by without it. It does app launching, makes finding files easier, allows nearly endless customization with workflows, and reduces your dependence on using your trackpad. And while you’re at it, seriously consider shelling out the extra money for the [Powerpack](http://www.alfredapp.com/powerpack/)—you won’t be sorry you did.

**[Moom](http://manytricks.com/moom/):** With all those new apps, things are undoubtedly starting to get a bit messy on your screen (even if you’re fortunate enough to have a great big display). So wrangle all those windows with Moom, the app that lets you easily move and zoom things on your screen.

## Leveling Up
Alright, now that all that’s out of the way, it’s time to really dig in and get things going.

If you haven’t already done so, go ahead and enable [developer tools](https://developer.chrome.com/devtools) in your installation of Chrome. While I could hardly explain their benefit in just one paragraph, [there are some pretty amazing things you can do with them](https://www.codeschool.com/courses/discover-devtools)—from debugging your code, to spying on how others implement a feature on their site. Once you get them running, I’m pretty sure you’ll be hitting "inspect element" on every nice-looking site you visit from here on out.

From there, it’s time to start [customizing Sublime Text](http://sublime-text-unofficial-documentation.readthedocs.org/en/latest/index.html). Go ahead and tinker with the settings, get familiar with some keyboard shortcuts, and then install [Package Control](https://packagecontrol.io/). Once you’ve got that, it’s dead simple to install color schemes, themes, and plugins. When evaluating what to add on to Sublime, try to find stuff that solves a persistent problem. 
* Hard to read text? Grab a [color scheme](https://packagecontrol.io/packages/1337%20Color%20Scheme). 
* Don’t like the UI? Add a new [theme](https://packagecontrol.io/packages/Devastate). 
* Typing too much HTML? Grab [Emmet](https://packagecontrol.io/packages/Emmet). 
* Making code mistakes? Time for a [linter](https://packagecontrol.io/packages/SublimeLinter). 

You get the idea. The best thing about Sublime is, if you’ve had an issue, chances are someone else has too, and they’ve made a plugin to solve it.

Now that you have your browser set up and your text editor configured, it’s time to think about source control. Speaking from experience, [Git](link) can be intimidating—as can just about anything in the command line—[but once you get past that initial fear](https://try.github.io), it empowers you to build great stuff. Whether you’re collaborating on a team, contributing to an [open-source project](https://guides.github.com/), or just mitigating risk, Git (and its buddy [GitHub](link)) will change the way you work for the better.

And since you’re going to be spending a lot of time in the command line, you should probably get comfortable and [make yourself a little more at home there](http://computers.tutsplus.com/tutorials/40-terminal-tips-and-tricks-you-never-thought-you-needed--mac-51192). Once you spend some time in the command line, you’re going to start wanting to customize some things—and that’s where [dotfiles](https://dotfiles.github.io/) come in. Think of them as the settings for your shell and everything you do in the terminal. Whether you want to customize your prompt, add a color scheme, or create aliases for commonly used commands, it all happens in your dotfiles. Once you have them set up, move them into a dotfiles directory, symlink them, and track them with Git—this’ll make life a lot easier if you want to change them or set up a new machine.

## That’s All For Now
While this is far from an exhaustive list, and is certainly opinionated at best—you may prefer VIM over Sublime, Terminal over iTerm, Subversion over Git—it’s helped me make some real progress in becoming a better web developer. No matter your preference, what’s important is that your development environment helps you focus on writing code, and not fighting against technology. Find solutions that solve problems, not create new ones. Making those changes to your environment and workflow will open you up to new opportunities and the introduction of new technology. When your development environment is comfortable, change and growth comes naturally.
