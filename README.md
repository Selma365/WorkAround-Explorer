# WorkAround-Explorer
This is project about Modules,how to import and export.
First: Export the four functions from salaryData.js using ES6 named export syntax and then Export the salaryData array as the default export.
Second:  We use ES6 named import syntax to import getRoles and getCompanies from salaryData.js.
Then: In index.html, add attribute to <script type="module" src='main.js' defer ></script>

In workAroundModule.js Import the functions getDataByRole() and getDataByCompany() from salaryData.js using named import syntax and Import salaryData from salaryData.js using the default import syntax.
To make these functions available to main.js, export the four functions using named export syntax.

In main.js, import the four functions from workAroundModule.js.
