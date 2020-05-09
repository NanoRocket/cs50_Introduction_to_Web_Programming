<html>

    <head>

        <meta charset="utf-8"/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>

        <meta property="og:title" content="Project 0: Homepage"/>

        <title>Project 0: Homepage</title>

    </head>

    <body>
        <div class="container-lg px-3 my-3 markdown-body">
            <h1 id="project-0-homepage">Project 0: Homepage</h1>

<h2 id="objectives">Objectives</h2>

<ul>
  <li>Become more comfortable with HTML and CSS to design and style webpages.</li>
  <li>Learn to use SCSS to write more complex stylesheets for your webpages.</li>
</ul>

<h2 id="getting-started">Getting Started</h2>

<h3 id="your-first-webpage">Your First Webpage</h3>

<p>Download the distro code for this project from <a href="https://cdn.cs50.net/web/2020/x/projects/0/project0.zip">https://cdn.cs50.net/web/2020/x/projects/0/project0.zip</a> and unzip <code class="highlighter-rouge">project0.zip</code>, which should yield a directory called <code class="highlighter-rouge">project0</code>.</p>

<p>Then, in a terminal window (located in <code class="highlighter-rouge">/Applications/Utilities</code> on Mac or by typing
<code class="highlighter-rouge">cmd</code> in the Windows task bar), move to the directory where you extracted <code class="highlighter-rouge">project0</code>
(recall that the <code class="highlighter-rouge">cd</code> command can change your current directory), and run</p>

<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><code>cd project0
</code></pre></div></div>

<p>to enter the project directory. Now, run</p>

<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><code>touch index.html
</code></pre></div></div>

<p>to create a new <code class="highlighter-rouge">index.html</code> file in your repository. Open the file with your
favorite text editor: popular choices include <a href="https://atom.io/">Atom</a>,
<a href="https://www.sublimetext.com/">Sublime Text</a>, and <a href="https://code.visualstudio.com/">VS
Code</a>. Then, paste in the following contents:</p>

<div class="language-html highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="cp">&lt;!DOCTYPE html&gt;</span>
<span class="nt">&lt;html&gt;</span>
    <span class="nt">&lt;head&gt;</span>
        <span class="nt">&lt;title&gt;</span>My Webpage<span class="nt">&lt;/title&gt;</span>
    <span class="nt">&lt;/head&gt;</span>
    <span class="nt">&lt;body&gt;</span>
        Hello, world!
    <span class="nt">&lt;/body&gt;</span>
<span class="nt">&lt;/html&gt;</span>
</code></pre></div></div>

<p>Then, save your <code class="highlighter-rouge">index.html</code> file.</p>

<h2 id="requirements">Requirements</h2>

<p>Alright, now it’s time to make your website your own. Design a personal webpage
about yourself, one of your interests, or any other topic of your choice. The
subject matter, look and feel, and design of the site are entirely up to you,
subject to the following requirements:</p>

<ul>
  <li>Your website must contain at least four different <code class="highlighter-rouge">.html</code> pages, and it
should be possible to get from any page on your website to any other page by
following one or more hyperlinks.</li>
  <li>Your website must include at least one list (ordered or unordered), at least
one table, and at least one image.</li>
  <li>Your website must have at least one stylesheet file.</li>
  <li>Your stylesheet(s) must use at least five different CSS properties, and at
least five different types of CSS selectors. You must use the <code class="highlighter-rouge">#id</code> selector
at least once, and the <code class="highlighter-rouge">.class</code> selector at least once.</li>
  <li>Your stylesheet(s) must include at least one mobile-responsive <code class="highlighter-rouge">@media</code> query,
such that something about the styling changes for smaller screens.</li>
  <li>You must use Bootstrap 4 on your website, taking advantage of at least one
Bootstrap <a href="https://getbootstrap.com/docs/4.3/components/">component</a>,
and using at least two Bootstrap columns for layout purposes using
Bootstrap’s <a href="https://getbootstrap.com/docs/4.3/layout/grid/">grid model</a>.</li>
  <li>Your stylesheets must use at least one SCSS variable, at least one example of
SCSS nesting, and at least one use of SCSS inheritance.</li>
  <li>In <code class="highlighter-rouge">README.md</code>, include a short writeup describing your project, what’s
contained in each file, and (optionally) any other additional information the
staff should know about your project.</li>
</ul>

<p>Note that not all of the above requirements are covered in Lecture 0, some will
be introduced in Lecture 1.</p>

<h2 id="how-to-submit">How to Submit</h2>

<p><strong>IMPORTANT</strong>: <em>On 1 July 2020, CS50W will update to a new version and this version of this project will no longer be accepted for credit. If you haven’t completed the entire course by that date, that’s okay! If you ultimately receive a passing grade on this project, we will consider it equivalent in scope and content to Project 0 in the new version of the course, and within two weeks after 1 July 2020 your gradebook at <a href="https://cs50.me/cs50w">https://cs50.me/cs50w</a> will update to reflect that you have received credit for having completed Project 0.</em></p>

<ol>
  <li>Visit <a href="https://submit.cs50.io/invites/89679428401548238ceb022f141b9947">this link</a>, log in with your GitHub account, and click <strong>Authorize cs50</strong>. Then, check the box indicating that you’d like to grant course staff access to your submissions, and click <strong>Join course</strong>.</li>
  <li><a href="https://git-scm.com/downloads">Install Git</a> and, optionally, <a href="https://cs50.readthedocs.io/submit50/">install <code class="highlighter-rouge">submit50</code></a>.</li>
  <li>If you’ve installed <code class="highlighter-rouge">submit50</code>, execute
    <div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><code>submit50 web50/projects/2020/x/0
</code></pre></div>    </div>
    <p>Otherwise, using Git, push your work to <code class="highlighter-rouge">https://github.com/me50/USERNAME.git</code>, where <code class="highlighter-rouge">USERNAME</code> is your GitHub username, on a branch called <code class="highlighter-rouge">web50/projects/2020/x/0</code>.</p>
  </li>
  <li><a href="https://www.howtogeek.com/205742/how-to-record-your-windows-mac-linux-android-or-ios-screen/">Record a 1- to 5-minute screencast</a> in which you demonstrate your app’s functionality</li>
  <li><a href="https://forms.cs50.io/5cae6982-7dea-48f3-8171-3916bfdb9382">Submit this form</a>.</li>
</ol>

<p>You can then go to <a href="https://cs50.me/cs50w">https://cs50.me/cs50w</a> to view your current progress!</p>

        </div>
    </body>

</html>