#### Domain Modeling
Domain Modeling: A Conceptual Map of a Problem Space

It involves creating a visual representation, often a diagram, that captures and organizes key concepts and relationships within a specific domain or problem area.
It serves as a shared understanding among stakeholders, enabling effective communication and collaboration.

Explain why we need domain modeling.
HTML Table Basics.

<table> element: This element defines the start of the table. You'll also need a closing </table> tag.
<tr> element: This element defines a table row. Each row should have an opening <tr> tag and a closing </tr> tag.
<td> element: This element defines a table cell. Each cell within a row needs an opening <td> tag and a closing </td> tag.

Use semantic markup: Ensure your table structure reflects the actual data organization.
Keep it simple: Avoid excessive nesting and focus on clarity.
Consider accessibility: Use captions and proper row/column structure for screen readers.
Why should tables not be used for page layouts?
List and describe 3 different semantic HTML elements used in an HTML <table>.
Introducing Constructors

What is a constructor and what are some advantages to using it?
Initialization:

Explicitly assign initial values to the object's members. This avoids relying on default values, which can sometimes be unexpected or undesirable.
Perform complex initialization tasks, such as opening files, setting up connections, or allocating memory.
2. Encapsulation:

Control how objects are created and initialized. You can define specific rules and ensure all instances of the class are created in a consistent way.
Hide internal implementation details from the outside world, improving code maintainability and security.
3. Overloading:

Define multiple constructors with different parameters for different use cases. This allows users to create objects with various initial states or configurations.
Improve code flexibility and cater to different scenarios without creating separate classes.
4. Error Handling:

Validate input parameters during object creation and throw exceptions if invalid values are provided. This helps prevent potential errors and unexpected behavior later in the program.
5. Clarity and Readability:

Make the intent of object creation explicit by grouping initialization logic in a dedicated constructor. This improves code readability and understanding for future developers.
Overall, constructors are essential tools for creating and initializing objects in a controlled and well-defined manner. They provide significant benefits for code organization, clarity, and reliability.


How does the term this differ when used in an object literal versus when used in a constructor?
When you create an object using literal notation (curly braces with key-value pairs), this inside the object doesn't refer to the newly created object itself. It actually refers to the global object in the current execution context. This can be surprising and lead to unexpected behavior if not understood.

Object Prototypes Using A Constructor
Code Reuse: Define common functionalities once on the prototype and share them across all objects.
Maintainability: Easier to update functionality for all objects by modifying the prototype.
Inheritance: Enable inheritance between classes by setting child constructor's prototype to the parent class's prototype.
Inside the constructor function, you can define methods and properties on the prototype property. These become shared by all objects created from that constructor.
This promotes code reuse and avoids redundantly defining the same functionalities for each object.

Explain prototypes and inheritance via an analogy from your previous work experience.
NOTE: This is a very common front end developer interview question

Inside the constructor function, you can define methods and properties on the prototype property. These become shared by all objects created from that constructor.
This promotes code reuse and avoids redundantly defining the same functionalities for each object.

#### "Things I want to know more about" ... Q'A & A's List..

Anytime a question arises in your mind, or something catches your curiosity, note it under this heading.

If you utilize any content directly from the reading sources, be sure to identify what you are quoting, and cite the source.