Frontend Task (1)
===================

Task
------
Create a responsive layout for both mobile and desktop similar to the design in the final_layout folder.

prerequisites
-------------
1. Git [Download](https://git-scm.com/download/win)
2. Ruby [Download](http://rubyinstaller.org/)
3. RubyGems [Download](https://rubygems.org/pages/download)
4. Compass, install from your terminal

		gem install compass

Using
-------------
#### Clone
Fork this repository https://github.com/goodsensejp/frontend-task-sass then run the following commands from your terminal

    git clone https://github.com/<your-username>/frontend-task-sass <your-path>

#### Develop
Run the following from your path

    cd <your-path>
    compass watch

Open index.html in your browser and start coding!

#### Deploy
After you finish the task push to your repository then make a pull request

		git add --all
		git commit -m "<your-commit-message>"
		git push origin master

Considerations
--------------
1. Use flexbox to make a responsive design.
2. Use mixins, variables, inheritance when they make sense.
3. Put files in their corresponding folders.
4. Use global variables to control theme colors.

The main goal is to organize your code so it can be easily customized later in the project lifetime and by any member of the team.

Resources
-------------
http://thesassway.com

https://scotch.io/tutorials/aesthetic-sass-1-architecture-and-style-organization
