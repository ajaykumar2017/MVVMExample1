# MVVMExample1
MVVM - Model View View-Model Example 1

DESCRIPTION OF MODEL :
1. MODEL: ( Reusable Code – DATA ) Business Objects that encapsulate data and behavior of application domain, Simply holds the data.
2. VIEW: ( Platform Specific Code – USER INTERFACE ) What the user sees, The Formatted data.
3. VIEWMODEL: ( Reusable Code – LOGIC ) Link bewteen Model and View OR It Retrieves data from Model and exposes it to the View. This is the               model specifically designed for the View.

FEATURES:

Life Cycle state of Application will be maintained.
  - The application will be in the same position as to where the user left it.
  - UI Components are kept away from Business Logic.
  - Business Logic is kept away from Database operations.
  - Easy to understand and read.

ADVANTAGES:

1. Maintainability – Can remain agile and keep releasing successive versions quickly.
2. Extensibility – Have the ability to replace or add new pieces of code.
3. Testability – Easier to write unit tests against a core logic.
4. Transparent Communication – The view model provides a transparent interface to the view controller, which it uses to populate the      view layer and interact with the model layer, which results in a transparent communication between the layers of your application.

DISADVANTAGES:

1. Some people think that for simple UIs, MVVM can be overkill.
2. In bigger cases, it can be hard to design the ViewModel.
3. Debugging would be a bit difficult when we have complex data bindings.
