# WEB APPLICATION LARAVEL API
Laravel Web API Project is an API with authentication project that can be used in real-world applications v11 
 - User
 - Task
 - Project
 - Role
 - Members
 - Comments

<h3>Project information:</h3> 

<p>This API Laravel project v11 is an real-world platform laravel project </p>
 
 - <strong>A#</strong> The platform has Many Groups/Companies
 - <strong>B#</strong> Group/Company has One Admin/User
 - <strong>C#</strong> Company Admin has Many Roles
    
 - <strong>D#</strong> Roles has Many Members
 - <strong>E#</strong> Member has Many Roles 
 - <strong>F#</strong> Members has Many Projects
   - <strong>F1#</strong> Project has Many Task
   - <strong>F2#</strong> Project has Many members

 - <strong>G#</strong> Members has Many Tasks 
    - <strong>G1#</strong> Task has Many members   
    - <strong>G2#</strong> Task has Many comments

<hr />

 - <h4>A# The platform has Many Groups/Companies</h4>
  <p>Platform having a single organization and company, or a company having many groups and accounts inside the platform depends on the plan offered to clients subscribed.</p>
  <p>This web application or platform API is designed to handle tasks, and projects.</p>
  <h4>B# Group/Company has One Admin/User</h4>
  <p>Each company or group of the organization must own a single user account administrator, this role can create multiple members under itself. </p>
  <p>It also handles multiple duties such as assigning and creating projects, tasks, members, comments, and roles under its group or company account.</p>
  <h4>C# Company Admin has Many Roles</h4>
   <p>Each Organization or Company has features to create custom roles under on their accounts, like editing projects, editing tasks, editing others' tasks and other projects and assigning tasks to other members, etc...</p>
  <h4>D# Roles has Many Members</h4>
   <p>Each role can assign many members only with an administrator account.</p>
  <h4>E# Member has Many Roles</h4>
   <p>Each member can be another administrator account manager, editor, and regular member.</p>
  <h4>F# Members has Many Projects</h4>
   <p>Each member can have many projects assigned by himself or from an administrator or from another member. </p>
  <h4>F1# Project has Many Task</h4>
    <p>Each Project can create many tasks and assign them to different members. </p>
  <h4>F2# Project has Many members</h4>
    <p>Each Project can have many members to assigned by the project creator or administrator.</p>   
  <h4>G# Members has Many Tasks</h4>
      <p>Each Member can receive many tasks from other members or administrators.</p>   
      <h4>G1# Task has Many members</h4> 
      <p>Each Task can assigned to multiple or different members.</p>
     <h4>G2# Task has Many comments.</h4>
      <p>Each Task can have many comments from members or from the administrator.</p>
