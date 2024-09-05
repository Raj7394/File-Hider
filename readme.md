<h2><b>File Hider Project</b></h2>
<h3>Overview</h3>
This File Hider project is a Java-based application that allows users to securely hide files on their system. It is designed with essential security features like email authentication, user login, and encryption, making it a great project for both beginner and advanced Java programmers. By implementing these features, you will gain hands-on experience in building security mechanisms within applications.

This project is ideal for college students looking to enhance their programming skills and learn about practical implementations of Java and MySQL. Whether you want to protect your personal files or understand how to add security layers to your software, this project is a great starting point.

<h3>Features</h3>
<ul>
<li><b>File Encryption and Hiding:</b> Securely hide and encrypt files using Java’s encryption techniques.</li>
<li>User Authentication: Implement a user login system with secure password storage using MySQL as the backend database</li>
<li>Email Verification: Send verification emails to authenticate users during registration.</li>
<li>MySQL Database Integration: Store user credentials and file information securely in a MySQL database.</li>
<li>Java Swing GUI: User-friendly graphical interface to make the app easy to use.</li>
</ul>

<h2><b>Technologies Used</b></h2>
<ul>
<li><b>Java:</b> Core programming language for the project.</li>
<li><b>MySQL:</b> Database management system for storing user data.</li>
<li><b>Java Swing:</b> For building the graphical user interface (GUI).</li>
<li><b>Java Cryptography Extension (JCE):</b> For encrypting and decrypting files.</li>
<li><b>JavaMail API:</b> For sending email authentication to users.</li>
</ul>

<h2>Setup Instructions</h2>
<h3>Prerequisites</h3>
<ul>
    <li>Java Development Kit (JDK) installed</li>
    <li>MySQL database server installed</li>
    <li>Any Java IDE (like Eclipse or IntelliJ IDEA)</li>
    <li>Internet connection for email services</li>
</ul>

<h3>Steps to Set Up the Project</h3>

<h4>Clone the Repository</h4>
<p>1. git clone <a href="https://github.com/Raj7394/File-Hider.git">https://github.com/Raj7394/File-Hider.git</a></p>

<h4>Set Up the MySQL Database</h4>
<li>Create a new database in MySQL for the project.</li>
<li>Run the provided SQL script (database.sql) to create the necessary tables.</li>

<h4>Configure Database Connection</h4>
<li>In the project’s code, locate the database configuration file.</li>
<li>Update the MySQL credentials (username, password, and database name).</li>

<h4>Run the Project</h4>
<li>Open the project in your preferred IDE.</li>
<li>Compile and run the main class to launch the file hider application.</li>
<h2>How It Works</h2>
 <b>1. User Registration</b>
        <p>New users can register by providing their email and password. A verification email will be sent for authentication.</p>
 <b>2. Login</b>
        <p>Once authenticated, users can log in using their credentials.</p>
 <b>3. File Hiding and Encryption</b>
        <p>After logging in, users can select files to hide, which will be encrypted and hidden from view.</p>
 <b>4. File Recovery</b>
        <p>Users can retrieve hidden files by providing the correct credentials.</p>
    


<h2>Learning Outcomes</h2>
<ul>
    <li>Build a Java application with database integration.</li>
    <li>Use Java’s encryption libraries to secure sensitive information.</li>
    <li>Implement secure login and email verification systems.</li>
    <li>Develop GUI applications using Java Swing.</li>
</ul>