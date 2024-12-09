<h1>FoodOnline</h1>

<h3>Overview</h3>
FoodOnline is a multi-user food ordering platform designed to streamline the process of ordering and managing food. With roles for <b>Users</b>, <b>Vendors</b>, and an <b>Admin</b>, the platform ensures seamless interaction between customers and restaurant vendors while providing administrative control. Built with Django, PostgreSQL, and modern front-end technologies, FoodOnline simplifies food order management for everyone involved.

<br>

<h3>Features</h3>
<h4>1) User Features:</h4>
<ul>
    <li>Users can register, log in, and log out.</li>
    <li>View and manage their own order history and details.</li>
</ul>

<h4>2) Vendor Features:</h4>
<ul>
    <li>Vendors have access to a dashboard to view incoming orders and manage them efficiently.</li>
    <li>Vendors can track user-specific order details to ensure prompt service.</li>
</ul>

<h4>3) Admin Features:</h4>
<ul>
    <li>Admins have full control over the platform.</li>
    <li>Manage users, vendors, and orders seamlessly from a centralized dashboard.</li>
</ul>

<h4>4) Secure Authentication:</h4>
Role-based authentication ensures that users, vendors, and admins have access only to the features relevant to their role.

<br>

<h3>Technologies Used</h3>
1) Backend: Python, Django<br>
2) Database: PostgreSQL<br>
3) Frontend: HTML, CSS, JavaScript, Bootstrap<br>

<br>

<h3>Usage Instructions</h3>
<ol>
    <li>
        <b>Setup:</b><br>
        Clone the repository:<br>
        <code>git clone &lt;repository-url&gt;</code><br>
        Navigate to the project folder:<br>
        <code>cd &lt;project-folder&gt;</code><br>
        Install dependencies:<br>
        <code>pip install -r requirements.txt</code>
    </li>
    <br>
    <li>
        <b>Configuration:</b><br>
        Update database settings in <code>settings.py</code> for your PostgreSQL instance.<br>
        Run migrations to set up the database:<br>
        <code>python manage.py makemigrations</code><br>
        <code>python manage.py migrate</code>
    </li>
    <br>
    <li>
        <b>Run the Application:</b><br>
        Start the Django development server:<br>
        <code>python manage.py runserver</code><br>
        Access the application at <code>http://127.0.0.1:8000/</code>.
    </li>
    <br>
    <li>
        <b>User Roles:</b><br>
        <ul>
            <li><b>Users:</b> Register and log in to place food orders and view their order history.</li>
            <li><b>Vendors:</b> Log in to the vendor dashboard to track and manage incoming orders.</li>
            <li><b>Admin:</b> Access the admin panel to manage all aspects of the platform.</li>
        </ul>
    </li>
</ol>

<br>

<h3>Important Notes</h3>
<ul>
    <li>This project uses Django’s built-in authentication for role-based access control.</li>
    <li>Orders and user data are stored securely in a PostgreSQL database.</li>
    <li>The platform ensures a smooth and efficient experience for all users, vendors, and administrators.</li>
</ul>
