<h1>Parallel Browser Automation - OrangeHRM Login Testing</h1>

<h2>Description</h2>
This project runs automated login tests for the OrangeHRM web application, covering both the standard user and the admin user accounts. The tests execute in parallel across three browsers, Chrome, Edge, and Firefox, using Selenium WebDriver. Each run validates successful authentication, verifies the landing dashboard for the logged-in account, and confirms consistent behavior across every browser. The full environment is hosted on an AWS EC2 instance that I provisioned myself, demonstrating cross-browser test execution in a cloud setup.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Python</b>
- <b>Selenium WebDriver</b>
- <b>pytest</b>
- <b>pytest-xdist (parallel execution)</b>
- <b>WebDriver Manager</b>

<h2>Environments Used</h2>

- <b>AWS EC2 Instance</b>
- <b>PyCharm</b>
- <b>Google Chrome / Microsoft Edge / Mozilla Firefox</b>
- <b>OrangeHRM (application under test)</b>

<h2>Program walk-through:</h2>

<p align="center">
Launch the EC2 instance and connect: <br/>
<img src="https://i.imgur.com/REPLACE.png" height="80%" width="80%" alt="EC2 Connect"/>
<br />
<br />
Open the project in PyCharm: <br/>
<img src="https://i.imgur.com/REPLACE.png" height="80%" width="80%" alt="PyCharm Project"/>
<br />
<br />
Run the parallel suite across Chrome, Edge, and Firefox: <br/>
<img src="https://i.imgur.com/REPLACE.png" height="80%" width="80%" alt="Parallel Run"/>
<br />
<br />
Standard user login test passes: <br/>
<img src="https://i.imgur.com/REPLACE.png" height="80%" width="80%" alt="Standard User"/>
<br />
<br />
Admin user login test passes: <br/>
<img src="https://i.imgur.com/REPLACE.png" height="80%" width="80%" alt="Admin User"/>
<br />
<br />
All tests complete across the three browsers: <br/>
<img src="https://i.imgur.com/REPLACE.png" height="80%" width="80%" alt="Results"/>
</p>
