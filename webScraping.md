<h1>Data Science at UCSB</h1>
<h2>Spring Novice Group -- </h2>

<h3>About the Project</h3>
<p>
	Web scraping is the process of programmatically reading and storing information from the internet. Web scraping (a.k.a. web crawling) is often a first step in a data analysis project--how can you analyze data if you do not have data to begin with?! It is a pretty fun topic for a personal programming project, because you can scrape things that are of personal interest to you. 
</p>
<br>
<p>
	This project will be done in Python because it is the de facto tool for web scraping thanks to popular modules like <a href="https://www.crummy.com/software/BeautifulSoup/bs4/doc/">Beautiful Soup</a> and <a href="http://docs.python-requests.org/en/master/">requests</a>. Your first couple weeks will be spent learning about the fundamentals of Python (and object oriented programming in general), regular expressions, and the two libraries mentioned earlier. Once you have laid that groundwork, you can <em>really</em> start scraping!
</p>
<br>
<p>
	Remember that this is an <em>guided outline</em> of a project, it is <strong>not</strong> an instruction manual. Later in the project, I may ask you to "using the <a href="http://docs.python-requests.org/en/master/">requests</a> library, make a GET request to http://swapi.co/api/people/1/ and print the result". That instruction is going to require you to read the linked documentation, try it, fail, and try again. Remember... if this was easy, everyone would do it!
</p>

<h3>Project Outline</h3>
<ul>
	<li>
		Work through the entirety of Codecademy's <a href="https://www.codecademy.com/learn/python">Python course</a>
		<ul>
			<li>
				Pay special attention to the exercises on Functions, Lists, and Loops
			</li>
			<li>
				It goes by pretty quickly, it might be a good idea to meet up just to work through the exercises together!
			</li>
		</ul>
	</li>
	<li>
		<em>Learning Check</em>
		<ul>
			<li>
				What is a class? How does a class relate to an object?
			</li>
			<li>
				Try doing a list comprehension. Then try doing one with an <code>if</code> statement.
			</li>
		</ul>
	</li>
	<li>
		Download and install Python <a href="https://www.python.org/downloads/">here</a> and a text editor like <a href="https://www.sublimetext.com">Sublime Text</a> or <a href="https://atom.io">Atom</a>
		<ul>
			<li>
				Make a new script, <code>scratchpaper.py</code> and try messing around with the topics you learned from the Codecademy course.
			</li>
			<li>
				To run your script: go to your terminal, change directories to where <code>scratchpaper.py</code> is saved, enter the command <code>python scratchpaper.py</code>
			</li>
			<li>
				Python is an interpreted language, meaning that you do <strong>not</strong> have to compile your code before running.
			</li>
			<li>
				Using <a href="">pip</a>, install BeautifulSoup and requests
			</li>
		</ul>
	</li>
	<li>
		<em>Learning Check:</em>
		<ul>
			<li>
				What is a module?
			</li>
			<li>
				What does pip do?
			</li>
		</ul>
	</li>
	<li>
		Let's make a request to a website, swapi.co, the Star Wars API. The site contains tons of information on the planets, people, and vehicles of the Star Wars universe. You are going to try making requests to the website to get information.
		<ul>
			<li>
				Make a script called "firstRequests.py" and import the requests module
			</li>
		</ul>
	</li>
</ul>
