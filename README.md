# Customer_Management_Django


<h3>Install Django <a href="https://www.digitalocean.com/community/tutorials/how-to-install-the-django-web-framework-on-ubuntu-18-04"></a>Link</h3>
<h5>Development Version Install with Git</h5>
<p>If you need a development version of Django, you can download and install Django from its Git repository. Let’s do this from within a virtual environment.></p>
<p>First, let’s update the local package index:</p>
<pre>sudo apt update</pre>
<p>Check the version of Python you have installed:</p>
<pre>python3 --version</pre>
<pre><p color="grey">Output</p> Python 3.8.0</pre>
<p>Next, install pip from the official repositories:</p>
<pre>sudo apt install python3-pip</pre>
<p>Install the venv package to create your virtual environment:</p>
<pre color="grey">sudo apt-get install python3.8-venv</pre>
... 
<h5>Create Project</h5>
<code>mkdir django-project</code></n>
<code>cd django-project</code></n>
<code>python3.8 -m venv my_env</code></n>
<code>source my_env/bin/activate</code></n>
<code>pip install django</code></n>
<code>django-admin --version</code></n>
<code>django-admin startproject crm_project</code></n>
Run server: <code> python manage.py runserver</code></n>









