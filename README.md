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
<pre>
  <ol>
    <li>mkdir django-project</li>
    <li>cd django-project</li>
    <li>python3.8 -m venv my_env</li>
    <li>source my_env/bin/activate</li>
    <li>pip install django</li>
    <li>django-admin --version</li>
    <li>django-admin startproject crm_project</li>
    <li> <p>Run server: <code> python manage.py runserver</code></li>
</ol>
</pre>








