2023-02-04
		1505
		
	

		Started assignment 2
		
	

		Created on MVC Application with the dotnet 3.1 (Out of support)
		

		Then I selected individual accounts

		And created the application 
		
	

		Then add a readme.txt

		I modified startup.cs
		After that I create the repository on github
		Then I test the application
	
		Edit ther welcome page and add a name of book store along with my name
	
		push the application to github
		create the Readme.md file then pull it
		

		Select a Vapor theme of the bootstrap and the copy the code of NavBar and also download the bootstrap.min.css
		Then change the name of bootstrap.css to bootstrap.bk.css, then add a download file bootstrap.min.css to wwwroot < lib < bootstrap < dist < css
		After then paste the code into bootstrap.min.css.

		Then test the application

		Then update it on github
		First copy the code of navigation bar for dropdown from the bootstrap which we select.
		Add a code in _Layout.cshtml for dropdown menu in navigation bar 
		Then test the application and it work smoothly
		Then update it on github

		Make a change in _Layout.cshtml and add @await RenderSectionAsync("Scripts", required: false)
		


		Then test the application
		

		Then write a proper Readme for the last 3 steps
		

		Then update it on github
		
	

		3-10-23
		3:35
		
	

		Add a css to footer
		Test the app and it runs perfectly
		then update it on github
		
	

		24-3-23
		
	

		3.20
		Add a new project through solution file and named as ShivangBookStore.DataAccess
		and now commit it on github
		
	

		3.23
		Add a new project through solution file and named as ShivangBookStore.Models
		and now commit it on github
		
	

		3.26
		Add a new project through solution file and named as ShivangBookStore.Utility
		and now commit it on github
		
	

		
	

		4.00
		Delete the whole repository because of an error and then open the zip which I already have.
		And then create new repository and clone it with my zip 
		
	

		4.07
		delete the .DataAccess , .Utility, .Models and then added them again with different name and then rename it and then change the namespace
		
	

		4.15
		install nuget packages
		then delete the class1 from the .DataAccess , .Utility, .Models
	  
	  4:50 
	  There was an major error in the name of directory so I started the whole assignment again
	

	  4:55
	  Started the bootsrtap with the same theme and also add the footer and nav bar in _layout.cshtml file
	

	  5:12
	  Upload it on github with single commit
	

	  5:45
	  Create ReadMe.md
	

	  Create 3 new projects in class library by right clicking on Solution
	  ShivangBookStore.DataAccess, ShivangBookStore.Models, ShivangBookStore.Utility
	

	  7:15
	  Copy the data folder and paste it to the .DataAccess
	

	

	  7:25
	  Then install the Microsoft.EntityFrameworkCore.Relational and Core.SqlServer packages
	

	  Then delete migrations folder
	

	  7:55
	  Install nuget package
	  then modify the namespace
	

	  8.15
	  Delete the Class1.cs files
	  Then build the project and it shows me few error
	

	

	  8:30
	  Move models to .models
	  then add project referencen to DataAccess and Models
	

	

	  8:45
	  Rename the Model folder to ViewModels after then change the namespace 
	  then modify the startup.cs and then try to run it and then it shows me error then I solve it 
	

	

	  8:55
	  Correct any default reference to ErrorViewModel to the new .Models.ViewModels.ErrorViewModels
	

	  9:00
	  Run the application and it runs smoothly
	

	  9:09
	  Add SD.cs in .Utility
	  Add a ‘Customers’ area to
	  Areas - Change the routes in Startup.cs like the one outlined in the ScaffoldingReadMe.txt
	

	  9:32
	  Then Move the HomeController.cs to the Area > Customer > Controller folder and delete Data and Models.
	 
	  9:40
	  Edit the HomeController.cs to explicitly define that the controller is in the Customer Area
	

	  9:43
	  Move Views > Home and modify the HomeController namespace
	

	

	  Take break of 30 mins (dinner time)
	

	  10:15
	  Views are now in Areas, but master page is defined in _ViewStart
	  Then Copy _ViewImport and _ViewStart to Customer Area Modify the _ViewStart.cshtml to reflect the new path.
	

	

	  10:30
	  Add a new Admin area in Areas
	  Then Add the proper view files and delete the Data and Models folder
	  then Delete the Controllers folder
	

	

	  11:00
	  While doing migration I got an error. And I follow your steps only, still it gives me this error
	  The entity type 'Category' requires a primary key to be defined. If you intended to use a keyless entity type call 'HasNoKey()'.
	  I tried so hard to solve this but still it shows error.
	

	  1:00
	  I just start the next step and started building repo and DataAccess
	  I created a file repository in DataAccess And in Repository I created I repository.
	  And then add a class name ICategoryRepository.cs, IRepository.cs, ISP_Call.cs in IRepository
	  And Created CategoryRepository.cs and Repository.cs
      I take the code from the file which you provided 



	  12-4-23
	  Redoing the whole assignment from start

	  2:50
	  Completed the bootsrtap and then push it on github

	  3:10
	  Create 3 new projects in class library by right clicking on Solution
	  ShivangBookStore.DataAccess, ShivangBookStore.Models, ShivangBookStore.Utility
	  Copy the data folder and paste it to the .DataAccess
	  Then install the Microsoft.EntityFrameworkCore.Relational and Core.SqlServer packages
	  Then delete migrations folder
	  Install nuget package
	  then modify the namespace
	  Delete the Class1.cs files
	  Then build the project and it shows me few error
	  Move models to .models
	  then add project referencen to DataAccess and Models
	  Rename the Model folder to ViewModels after then change the namespace 
	  then modify the startup.cs and then try to run it and then it shows me error then I solve it 
	  Correct any default reference to ErrorViewModel to the new .Models.ViewModels.ErrorViewModels
	  Run the application and it runs smoothly


	  4:45
	  Add SD.cs in .Utility
	  Add a ‘Customers’ area to
	  Areas - Change the routes in Startup.cs like the one outlined in the ScaffoldingReadMe.txt
	  Then Move the HomeController.cs to the Area > Customer > Controller folder and delete Data and Models.
	  Edit the HomeController.cs to explicitly define that the controller is in the Customer Area
	  Move Views > Home and modify the HomeController namespace
      Views are now in Areas, but master page is defined in _ViewStart
	  Then Copy _ViewImport and _ViewStart to Customer Area Modify the _ViewStart.cshtml to reflect the new path.
	  Add a new Admin area in Areas
	  Then Add the proper view files and delete the Data and Models folder
	  then Delete the Controllers folder
	  Then update it on Github

	  4:48
	  Add a ReadMe.md

	  4:50
	  To prepare for the next part, ‘build’ the application and confirm there are no errors
	  Review appsettings.json - Create the migrations (using code-first, where changes are “pushed” to the database), modify the database name and save.
	  Use the NuGet Package Manager Console to add the migration (with a meaningful name).
	  Note what happens if the wrong default project is selected.
	  Change to the correct default project (.DataAccess) and run again.
	  Migration Stamp- 2023412215944
	  Connection string to the localdb that is automatically selected
	  Review the file for the SQLlike syntax, statements, columns and primary key constraints.
	  Note tables related the ASP.NET Identity.
	  Once the migration is complete, the database needs to be updated.
	  In the PM console, update the database now.
	  Review the updated database in the SQL Server Object Explorer.
	  Check for errors, run the application
	  Add a new table to the DB by creating a Category model and push it to the DB
	  Add a new class file to the .Models project and modify
	  Add the migration via the PM Console
	  The new migration file will be empty because it hasn’t been added to the Application DB Context
	  Update this and note the added using statement
	  Re-run the add-migration and review the changes to the AddCategoryToDb (resolve the duplication error that will occur).
	  Update the database, confirm the new Categories table via the SQL SOE and
 
	  5:30
	  Update it on github


	  6:00
	  After creating the Category.cs and adding it to the ApplicationDbContext it’s time to implement the Repository, a generic way of accessing common
	  functionality (e.g. getting a record), in the .DataAccess project.
	  Add a new folder name it ‘Repository’ (for class implementations of interfaces) and add an IRepository (for the interfaces) folder inside it.
	  Add a new item of type interface to the folder and name it IRepository.cs
	  Modify so it can be used on the Category class to do all the CRUD operations (note using statements).
	  Create Crude files
	  Create individual repos for category and all potential models to be added in the future
	  CategoryRepository.cs
	  ICategoryRepository.cs
	  Modify CategoryRepository (note the using statements and the message for formal parameters – review in Repository.cs the method pointing to the
	  ApplicationDBContext)
	  Modify ICategoryRepository interface
	  Review and modify the error now in CategoryRepository.cs (implement the interface to update)
	  Complete the remaining modifications (note the comments)
      Build, fix any error and push commits to GitHub
	  Implement a stored procedure repository and map multiple repositories in a Unit of Work
	  Add a new interface in the IRepository folder -
	  ISP_Call.cs – that extends
	  IDisposable
	  Include the methods shown (note the comments) and install the NuGet package for Dapper
	  Now implement this with a new class in the Repository folder.
	  Add a new class (SP_Call.cs) in the Repository folder, select the appropriate using statement and implement the ISP_Call interface
	  Add a connection to the database, note the additional using statements
	  Update the implementation of the ISP_Call interface
	  Now add the wrapper for Unit of Work
	  Add a new interface (IUnitOfWork) to the IRepository folder and update the code.
	  Now implement this inside the UnitOfWork (Hint: Add a class)
	  Modify the code (make sure the public class implements the interface - UnitOfWork : IUnitOfWork)
	  To make it accessible by the project, register it Startup.cs in the ConfigureServices method (don’t forget the using statements)

	  12:40
	  Build and correct any errors,
	  At last commit it on github


	  12:50
	  With the addition of UnitOfWork in Startup.cs, it will be accessible with DI by any Controller.
	  Close all currently opened tabs.
	  Add a new MVC Controller - Empty inside Areas/Admin
	  Name it CategoryController.cs
	  Modify the code to use the IUnitOfWork from the .DataAccess project and the IRepository folder (Hint: using statement)
	  Add a new folder in the Areas/View with the same name as the Controller
	  Add a new ‘Index’ view to the folder (note the template) and modify with the generic HTML code from the Category Index View.txt file found in the Assignment 2 - Files folder
	  Save and run the application and it runs smoothly
	  In _Layout.cshtml, move the ‘Category’ link to the Content Management drop-down (note the code changes).
	  Review the changes to the navigation
	  Modify the Index.cshtml to add the icons in the Category section from Font Awesome and confirm
	  Delete it and add the JavaScript from the Assignment 2 files folder in to the wwwroot/js folder (note the ‘div’ is now in the return portion of the category.js file
	  In Index.cshtml add the @section call to the category.js script and run the project.
	  Time to apply the code to activate the ‘Edit’ and ‘Delete’ buttons and ‘Create New Category’ using the Upsert action
	  Add the IAction result to the controller and add a View (as we did w/ Index)
	  Copy and add the html from the Category Upsert View.txt
	  Create a partial view for the
	  In the general Views > Shared folder, add the partial view for _CreateAndBackToListButton.cshtml and add the asp-action
	  Create another parital view for _EditAndBackToListButton and note the code addition of the @model razor statement Add category
	  Modify the Upsert.cshtml (note the @model statement)
	  Add the asp-action to the Index.cshtml page and run the application
	  Navigate to Category > Create New Category
	  Modify Upsert.cshtml so TITLE now uses the @title variable and refresh the application.
	  Add the @section call to Scripts to validate input (or lack of) on the client-side and test.

	  1:25
	  Now create an Upsert POST action method in the CategoryController.cs
	  Note the Save method is not available, now add the void Save() method to the IUnitOfWork interface (this will now allow the Savemethod to be added).
	  Remove the _db.SaveChanges() method in the CategoryRepository.cs and move the _unitOfWork.Save() method with the return RedirectToaction method.
	  Check for errors and test whether the application can update and create a category.
	  Add the API (Application Programming Interface) call for HTTPDelete in the CategoryController.cs
	  Then implement the HTTPDelete with a delete method in category.js to add functionality to the application and call the API
	  Add the delete functionality in category.js with including the onclick event to the Delete function
	  Add the Delete(url) function code (see next slide).

	  1:55
	  Commit it on github
