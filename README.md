# SQL
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>SQL – Structured Query Language</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        ul {
            margin-left: 20px;
        }
        code {
            background-color: #f4f4f4;
            padding: 2px 6px;
            border-radius: 4px;
        }
        .box {
            background-color: #f9f9f9;
            border-left: 5px solid #3498db;
            padding: 10px;
            margin: 15px 0;
        }
    </style>
</head>

<body>

<h1>SQL (Structured Query Language)</h1>

<div class="box">
    <p>
        SQL is a <strong>query language</strong>, not a programming language.  
        It acts as a <strong>mediator between the user and the database</strong>.
    </p>
</div>

<h2>What is a Database?</h2>
<p>
    A database is a place where all data is stored.  
    It is stored on a <strong>physical device</strong> such as servers.
</p>

<h2>What is a Data Warehouse?</h2>
<p>
    A data warehouse is a <strong>collection of databases</strong>.  
    Organizations maintain multiple databases together in a single location or building.
</p>

<h2>What is a Data Center?</h2>
<p>
    A data center is a <strong>collection of data warehouses</strong>.
    Data centers are built in different geographical directions and sometimes:
</p>
<ul>
    <li>Near oceans</li>
    <li>Under the sea</li>
</ul>
<p>
    This is done to maintain <strong>24/7 cooling</strong> using natural water resources.
</p>

<h2>Startup Example – Database Rental</h2>
<p>
    Suppose you have a startup company working on:
</p>
<ul>
    <li>Machine Learning (ML)</li>
    <li>Data Analytics (DA)</li>
</ul>

<p>
    ML and DA mainly use <strong>structured data</strong>.  
    Some companies that provide structured database services are:
</p>
<ul>
    <li>Oracle</li>
    <li>Sybase</li>
    <li>MySQL</li>
</ul>

<h3>Pricing Example</h3>
<ul>
    <li>Oracle: ₹10,000/month – 10 TB</li>
    <li>MySQL: ₹20,000/month – 10 TB</li>
    <li>Sybase: ₹15,000/month – 10 TB</li>
</ul>

<p>
    If you choose Oracle and pay ₹10,000, Oracle provides you with
    <strong>10 TB database storage</strong>.
</p>

<h2>Oracle’s Perspective</h2>
<p>
    Oracle owns:
</p>
<ul>
    <li>Databases</li>
    <li>Data Warehouses</li>
    <li>Data Centers</li>
</ul>

<p>
    Oracle stores data for multiple companies and earns profit through
    database rental charges.
</p>

<h2>Unstructured Data Example</h2>
<p>
    For projects like:
</p>
<ul>
    <li>Deep Learning (DL)</li>
    <li>Natural Language Processing (NLP)</li>
    <li>Images and Videos</li>
</ul>

<p>
    These require <strong>unstructured data</strong>.  
    Companies that provide unstructured databases include:
</p>
<ul>
    <li>MongoDB</li>
    <li>Redis</li>
</ul>

<h2>Limitations of Traditional Database Rental</h2>
<p>
    Example:
</p>
<ul>
    <li>You rent 10 TB from Dec 1 to Jan 1</li>
    <li>If you use only 1 TB, remaining 9 TB is wasted</li>
    <li>If you need 20 TB, extra space is not available</li>
</ul>

<h2>Solution – Cloud Computing</h2>
<p>
    Cloud platforms solve these problems.
</p>

<ul>
    <li>Amazon Web Services (AWS)</li>
    <li>Microsoft Azure</li>
    <li>Google Cloud Platform (GCP)</li>
    <li>Salesforce Heroku</li>
</ul>

<p>
    In cloud computing:
</p>
<ul>
    <li>You can increase storage anytime</li>
    <li>Billing is automatic</li>
    <li>You pay only for what you use</li>
</ul>

<h2>Role of SQL</h2>
<p>
    SQL is used to:
</p>
<ul>
    <li>Insert data</li>
    <li>Retrieve data</li>
    <li>Update data</li>
    <li>Delete data</li>
</ul>

<p>
    We cannot communicate directly with a database.  
    <strong>SQL is the medium language</strong> between the user and the database.
</p>

<p>
    A <strong>query</strong> means a question.  
    SQL works only with <strong>structured data</strong>, not unstructured data.
</p>

<h2>What is SSMS?</h2>
<p>
    <strong>SSMS (SQL Server Management Studio)</strong> is a platform used to write SQL queries.
</p>

<ul>
    <li>Developed by Microsoft</li>
    <li>Used to connect to databases</li>
    <li>Execute SQL commands</li>
</ul>

<h2>CMS Services in SQL Server</h2>
<p>
    A CMS provides multiple services:
</p>

<ul>
    <li><strong>Database Engine</strong> – Execute SQL commands</li>
    <li><strong>SQL Server Analysis Services</strong> – Convert 2D data into 3D format</li>
    <li><strong>SQL Server Reporting Services</strong> – Convert documents to PDF and vice versa</li>
    <li><strong>SQL Server Integration Services</strong> – Connect one database to another</li>
    <li><strong>Azure Cloud Integration</strong> – Perform CRUD operations in the cloud</li>
</ul>

<h2>CRUD Operations</h2>
<ul>
    <li>Create</li>
    <li>Read</li>
    <li>Update</li>
    <li>Delete</li>
</ul>

<p>
    Cloud data can also be used to <strong>train AI models</strong>.  
    However, the most commonly used service is the <strong>Database Engine</strong>.
</p>

</body>
</html>
