
<h3>Create Django Project</h3>
  <ol>
    <li><b>Create a directory which include all django projects</b>
      <ul>
        <li><code>$  mkdir ~/<i>django-folder</i></code></li>
        <li><code>$  cd <i>django-folder</i></code></li>  
      </ul>
    </li>
    <li>Install Django: <code>$ pip install django </code></li>
    <li>Create Folder Project: <code>$  django-admin startproject your-project</code></li>
    <li>Next, create a virtual environment within the project directory: <code>$ virtualenv "my_env"</code></li>
    <li>To install packages into the isolated environment, activate it by typing: 
      <code>$ source my_env/bin/activate</code></li>
    <li>Check version Django: <code><i>(my_venv)</i> $ django-admin --version</code></li>
    <li>Migrate the database: <code>$ python manage.py migrate</code></li>
    <li>Finally, let’s create an administrative user so that you can use the Djano admin interface. Let’s do this with the createsuperuser command
      <code>python manage.py createsuperuser</code>
    </li>
 </ol> 
 
 <h5>Testing the Development Server</h5>
 <ol>
    <li>Run server: <code>$   python manage.py runserver</code></li>
    <p> If you want to change port:  <code>$   python manage.py runserver <i>8888</i></code>
    <li>Visit your server’s IP address followed by :8000 in your web browser. For example: <i>http://127.0.0.1:8000/</i></li>
    <p>You should see something that looks like this:</p>
    <img src="https://user-images.githubusercontent.com/85974492/125220336-b9132480-e2f0-11eb-9074-364f85a7447b.png">
    <li>To access the admin interface, add /admin/ to the end of your URL:<code>http://your_server_ip:8000/admin/</code></li><br>
    <img src="https://assets.digitalocean.com/articles/eng_python/django/django-admin-login.png">
    <p>If you enter the admin username and password that you just created, you will have access to the main admin section of the site</p>
    <li>When you are finished looking through the default site, you can stop the development server by typing <i>CTRL-C</i> in your terminal.</li>
 </ol> 
 
<h3> Install PostgreSQL, DBeaver(already have in Ubuntu Software)</h3>
<p>Refer two links to install: </p>
<a href = "https://phoenixnap.com/kb/how-to-install-postgresql-on-ubuntu">PostgreSQL</a>
<ul>
  <li><code> python3 -m pip install --upgrade pip </code></li>  
  <li><code> pip install psycopg2-binary </code></li>
</ul>


sudo apt install libpq-dev python3-dev
pip3 install psycopg2








