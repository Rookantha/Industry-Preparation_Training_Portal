# Industry Preparation Training Portal

<h3>Reliable and Secured Communication platform for both computing students and industry experts.HTML / CSS / JavaScript / C# /ASP.NET Web API </h3>
<h5 style="color:red">This repository provides software documentation and user guide only. If you need source code for this project contact me.</h5>


<h3>Introduction.</h3>

<p>IPT stands for industry preparation training which is a program conducted by NSBM to provide a smooth and easy transition of undergraduates of the school of computing to the industrial life. This program allows computing students to showcase their talents and skills to the industry experts. This platform will enable the industry people to identify key personalities within the undergraduates and recruit them if necessary. At the same time, undergraduates will have a firsthand experience about the industrial life, where they need to work during their carrier.<p>
<p>IPT management has decided to expand this process by conducting an online communication platform between students and experts under the supervision of the IPT manager (Admin). The best solution is to have a website which is accessible anywhere in the world. We have developed a website along with windows form application (Admin portal) to meet the criteria defined by the management staff. This system allows users to create free membership accounts. But users cannot access their accounts until the IPT manager decides to approve. At the same time, the IPT manager can remove any user if they found fake or inappropriate. Admin accounts can only be created programmatically with the request of IPT manager.<p>
<p>The project consists of two major components, <p>
  <ul>
    <li>A web platform for all the users including Admin(s)</li>
    <li>Windows form application only for Admin(s)</li>
  </ul>  
  
<p>RESTful API – acts as a middleware coordinating databases and two applications.<p>
<p>Database<p>
  <ul>
    <li>MySQL Database – running on SQL Server.</li>
  </ul>  

<h3>Project Scope, Objectives, and Goals.</h3>
  
<p>The end goal of this project is to develop a reliable and secured communication platform for both computing students and industry experts. And the IPT manager should have to have the facilities to access all the transactions including messages. Several sub-objectives need to be satisfied to achieve the main goal as defined below.<p>
  
  <ul>
  <li>Any computing student and/or industrial experts can get registered with the system for free through online registration.</li>
  <li>All the registered users need admin’s approval for login into the system.Only the admin can approve.</li>
  <li>Once approved by the admin, users are given the freedom to change their profile details including Job category and the qualifications except for email address, NIC, user type and the name.</li>
  <li>Users can change their password at any time.</li>
  <li>No one can access the restricted pages unless login credentials are correct (cannot access using URL address).</li>
  <li>Industry experts can filter the students by their interested job category and communicate with them.</li>
  <li>Students can also communicate with industry experts regarding industry matters.</li>
  <li>Admin can remove accounts and messages within the admin’s portal.</li>
</ul>

<h3>Project Requirements</h3>
<p>Creating a secured website using API is not trivial. It requires a lot of efforts to identify possible threats and secure it, document it and to make it easy to use. This will result in a more complex situation than initially planned. However, to overcome this at the very initial stage we need to identify the exact requirements of the system.<p>
<h4>3.1. Functional Requirements.</h4>
  
<ul>
  <li>Use RESTful architecture to develop API.li>
  <li>Validate and verify all user registrations.</li>
  <li>Handled HTTP requests and responses in both JSON and XML formats.</li>
  <li>Both applications should support JSON and XML data types in transactions.</li>
  <li>Allow users to create, view, edit and delete their accounts within limits.</li>
  <li>Allow uses to create new projects and add members to that project.</li>
  <li>Allow admin to manage all accounts and message details.</li>
</ul>

<h4>3.2. Non-Functional Requirements</h4>
<h5>Reliability</h5>
<p>This system should contain only very reliable information. That is why we need to permit the admins to inspect all user accounts and their messages. And admins have the facility to remove any user at any time if found inappropriate and to remove unnecessary messages shared through this system.<p>
  
<h5>Scalability</h5>
<p>In terms of future, we may have to expand the resources and facilities provided by this IPT system. Therefore, we need to think ahead and make the pitch for future players. That is why we have designed these web application and windows form application using MVC patterns. And the API is developed using REST architecture.<p>
  
<h5>Security</h5>
<p>System security is the crucial factor that needs to be at the very highest point in the requirements analysis. Because if a security breach occurs that means the trust between users and the system will fall causing maybe to leave us even. Therefore we have decided to use Https than Http which encrypts data when transferring.<p>
