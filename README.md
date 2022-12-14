# CMPG-323-32737742-

<h1>CMPG 323</h1>

<p>Repository for CMPG 323 for myself 32737742 in which I will add various items such as milestones, labels, a readME file that will be continuously updated throughout the semester, charts and projects related to CMPG 323 etc...</p>

<p>I will be seperating all my projects into their own respective repositories and use anchor elements in this README.md file to link all the relevant projects:</p>
<h2>Repositories to be used (with links): </h2>
<ul>
  <li><a href=https://github.com/BrendanV11/CMPG-323-Overview-32737742>Project 1 - Agile & Scrum</a></li>
  <li><a href="https://github.com/BrendanV11/Project-2---API-Development">Project 2 - API Development</a></li>
  <li><a href="https://github.com/BrendanV11/Project-3---Standards-Patterns">Project 3 - Standards & Patterns</a></li>
  <li><a href="https://github.com/BrendanV11/Project-4---Testing-RPA">Project 4 - Testing & RPA</a></li>
  <li><a href="https://github.com/BrendanV11/Project-5---Reporting-Monitoring">Project 5 - Reporting & Monitoring</a></li>
 </ul>
 
 <h2>Branching strategy to be used: </h2>
 <p>After the intitial setup of all the comonents (when everything is in order after project 1), the way I will implement branches to my repositories is as follow.</p>
 
 <p>I will create a branch off of the main/default branch and implement all my changes within the secondary branch I have created. Anything that I do on the secondary branch I will then commit and merge into the main branch once I feel that it is neccessary. However, if there are any errors that I encounter after committing and merging the branches, I will create another branch named hot-fix and assign a version to the branch in order to keep track of updates. In this hot-fix branch I will simply fix the error, update the version number, and merge this branch into the main/default branch.</p>
 
 <h2>Use of .gitignore</h2>
 <p>When.gitignore is used it essentially tells Git whether there are files that should be ignored when committing a project to your repository. Throughout the semester I will determine what data need not be added when committing to the repository and add it to the .gitignore folder. and then update the README.md file accordingly.</p>
 
<h2>My use of .gitignore</h2>
<h3>Project 1</h3>
<p>Explanation of how it works and can be implemented</p>

<h3>Project 2</h3>
<p>Using a website that enables us to get all the instances that we might want to ignore when uploading to github, I added these to the .gitignore file:</p>
  <uL>
  <li>C#</li>
  <li>ASP</li>
  <li>connection.udl</li>
  <li>appsettings.json</li>
  </ul>
  
  <h3>Project 3</h3>
<p>Implemeneted standards and patterns to make the program more efficient and reduce duplicate/redundant code.</p>
  <uL>
  <li>Implemented repository classes</li>
  <li>Implemented Interfaces</li>
  <li>Removed all references to _context in the repository classes.</li>
  <li>.gitignore appsettings.json to hide cridentials</li>
  </ul>
  
  <h3>Project 4</h3>
    <li>No use of .gitignore</li>
    <li>Used Orchestrator to store credentials using assets.</li>
 
 <h2>Storage of credentials and sensitive information</h2>
 <p>This type of information should never be stored in git repositories. We should rather add these sensitive files to gitignore thus excluding these files from being pushed into the repositories. Furthermore, simply creating a private repository will not be enough as these type of repositories are seen as "High value" targets in which others may gain some valuable information (Simon Maple, 2018).</p>
 
<h3>Method I will use to protect sensitive information:</h3>
<p>Any files/folders that appear in the repossitory that I would rather ignore when commiting in Git/GitHub I will simply add these documents to the .gitignore in order to protect the information. I will be looking at various methods such as adding repository secrets with the use of gh secret set "secret-name", and evaluate if it delivers the desired outcome. I will research various methods on what is the best way to store sensitive data and plan accordingly to keep this information guarded (Johnson, 2020). I have used Orchestrator to store sensitive data by making use of assets.</p>

<h2>Diagram explaining project and repository context and how they are integrated:</h2>

<p>
  Diagram Link:(https://user-images.githubusercontent.com/88327992/184868034-ffde6d54-284d-43f3-9567-a790f4b1330d.png)
</p>


<h2>KANBAN charts</h2>
<ul>
  <li>Number of items by label: (https://user-images.githubusercontent.com/88327992/184931764-17ee89f1-201a-4584-bb54-4788c35541ec.png)</li>
  <li>Number of items by sprint: (https://user-images.githubusercontent.com/88327992/184931938-8ed395a7-b25b-41e8-9e19-0c29756dd43b.png)</li>
  <li>Number of items by status: (https://user-images.githubusercontent.com/88327992/184932149-3733267c-d4ca-4a8a-84c3-7e7c47eaf8c6.png)</li>
  <li>Burdown Chart: (https://user-images.githubusercontent.com/88327992/185185018-f077f95b-4959-41c9-b28f-9fe074cc7415.png)</li>
</ul>

<h2>Reference List:</h2>
<p>
(https://github.com/BrendanV11/CMPG-323-Overview-32737742/files/9673079/References.pdf)
</p>

