<h1>For more details anlyze the route section </h1>
<h1>Used Postman to perform any action</h1>
<h2>User role based login system </h2>
<h3>users are:patient,doctor,admin</h3>
<h3>patient can update his profile and read his profile only</h3>
<p>
- To read the profile of any patient run this project in local system:<br>
- npm install<br>
- npm start<br>
System will start localy at port:3000<br>
Go to postman and used url <h1>localhost:3000/signup</h1>
keep method as Post:<br>
provide your email,password,role as key and hit send:<br>
<img src="https://github.com/devil-cyber/role_based_login/blob/master/Screenshot%20(61).png"/>
To get the user used <h1>localhost:3000/users</h1>
Provide x-acess-token that you will get after login as a admin/doctor:<br>
<img src="https://github.com/devil-cyber/role_based_login/blob/master/Screenshot%20(62).png" />
Doctor can update the user and extend <br>
But an admin can delete the user by using the x-acess-token<br>
<img src="https://github.com/devil-cyber/role_based_login/blob/master/Screenshot%20(63).png" />
