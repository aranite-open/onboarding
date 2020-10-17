## Training Material

### Learning Path

**REST API**
1. Watch the first 10 minutes of this video to learn about REST API, and HTTP methods:
- [REST API](https://www.youtube.com/watch?v=Q-BpqyOT3a8")

2. This is a complementary resource for HTTP methods:
- [HTTP Methods](https://restfulapi.net/http-methods/")

**You should activate the virtual environment each time when starting to work on the project and deactivate it after your work is finished**
 
 - create the virtual environment: 
  1. py -m pip install virtualenv
  2. py -m venv foldername(e.g env)
 - Activate and deactivate:
  3. activate: .\env\Scripts\activate
  4. deactivate: deactivate
  
 - You may use Conda virtual environment as an alternative:
 - [Conda Virtual Environment](https://docs.conda.io/projects/conda/en/latest/user-guide/concepts/environments.html)

**Django**
 - Through the following video learn thsese concepts in Django: [Python Django Web Framework - Full Course for Beginners](https://www.youtube.com/watch?v=F5mRW0jo-U4)
   - **Note that Since we use React for Front-End, which you will learn more about later, we do not use forms.**
   - **Watch the first hour of the video**
   - Installing. Virtual environment 
   - Django settings
   - Built-In components
   - New model fields 
   - Custom homepage 
   - URL routing
   
- The result for our project in admin page looks like this:
- ![image](https://github.com/yaldaafshar/research/blob/master/Training%20Material/admin.jpg)

2. Whenever you face a problem with implementation of Django syntax and structure search it in Django documentation:
- [Django Documentation](https://docs.djangoproject.com/en/3.1/)
  - In Django Documentation:
    - Learn about Field Types: [Field Types](https://docs.djangoproject.com/en/3.1/topics/forms/modelforms/#topics-forms-modelforms)
    
3. Underestanding Django models relationships( One-To-Many, Many-to-Many, One-to-One):
- [Django Model Relationships](https://www.youtube.com/watch?v=2KqhBkMv7aM)

3. What are Meta classes: [Meta classes](https://stackoverflow.com/questions/100003/what-are-metaclasses-in-python)

4. Start working with Django Rest Framework through using its Serializers, views and URLs features in your project and show the information in JSON:
- [Django-REST-Framework](https://www.django-rest-framework.org/tutorial/quickstart/)
- The Result for our course-outline project looks like this:
- ![image](https://github.com/yaldaafshar/research/blob/master/Training%20Material/Rest-Framework.jpg)
- Use [Serializer](https://www.django-rest-framework.org/api-guide/serializers/) to translate Django models into other formats so you will be able to send data over network or store in files.
- [Difference between Model Serializer and Hyperlinked serializer](https://stackoverflow.com/questions/33421147/what-is-the-benefit-of-using-a-hyperlinkedmodelserializer-in-drf)
- Use [Routers](https://www.django-rest-framework.org/api-guide/routers/) to map the incoming request to proper viewset action based on the request method type (i.e GET, POST,etc)
- Use [class-based views](https://www.django-rest-framework.org/tutorial/3-class-based-views/) to take Web Requests and return Web response.

**React and JavaScript**
1. Become familiar with HTML DOM(Document Object Model),which is the logical structure of documents and the way a document is accessed and manipulated, element and attribute concepts:
- [HTML DOM](https://www.youtube.com/watch?v=RbQGn6vBlys")

2. How browser rendering works(behind the scenes)
- [Critical Rendering Path](https://blog.logrocket.com/how-browser-rendering-works-behind-the-scenes-6782b0e8fb10/)
- [Critical Rendering Path](https://developer.mozilla.org/en-US/docs/Web/Performance/Critical_rendering_path)

3. Create a React app:
- [create-react-app](https://github.com/facebook/create-react-app)

4. Basic React folder structure:
- [Folder Structure](https://www.freecodecamp.org/news/quick-guide-to-understanding-and-creating-reactjs-apps-8457ee8f7123/)

5. If you are not familiar with JavaScript syntax and data structure, learn:
   - Different types of variables: Var, Let, Const and their scopes
   - Escape quote in strings
   - work with Strings, Arrays, Functions, 
   - Work with Objects, properties, methods ( access properties, update properties, delete properties, manipulate complex objects)
   - Destructuring syntax in objects
   - Destructuring syntax in arrays
   - Copy objects
   - Copy arrays  
   - Ternary or inline if-else to write if conditional inside JSX elements -- **another resource** [Inline If-Else with Conditional Operator](https://reactjs.org/docs/conditional-rendering.html)
   - Learn Arrow Functions and where to use them to write shorter function syntax-- **another resource** [Arrow Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
   - template literals -- **another resource** [template literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)
  - from [Learn JavaScript - Full Course for Beginners](https://www.youtube.com/watch?v=PkZNo7MFNFg)
  - *Here is a complementory resource for JavaScript** and learn target Event Property and Onchange event from here:
- [JavaScript](https://www.w3schools.com/js/)

7. This is a step by step tutorial to learn about React, states and props:
- [React](https://reactjs.org/docs/hello-world.html)
- [state and props](https://reactjs.org/docs/faq-state.html)
- Example of sending and recieving props in functional components:
- [props in functional components](https://stackoverflow.com/questions/39963565/react-passing-down-props-to-functional-components)

8. Watch this video to learn about difference between class components and function components with hooks, useState and useEffect :
- [useState and useEffect](https://www.youtube.com/watch?v=iEVcCdbF1WQ")
- This is React documentation for hooks. Just skip “Hooks at a Glance” if you are not familiar with React Hooks :
- [React Hooks](https://reactjs.org/docs/hooks-intro.html)

9. You will need React Router, to navigate between the pages of a website. Watch the first 17 minutes of this video:
- [React Router](https://www.youtube.com/watch?v=Law7wfdg_ls&pbjreload=101")
- This is React Router documentation:
- [React Router Documentation](https://reactrouter.com/web/guides/quick-start")
- [React Router Match](https://reactrouter.com/web/api/match")
- How to pass props to a component in React Router:
- [Pass props to components](https://ui.dev/react-router-v4-pass-props-to-components/)
- "link" tag, Provides declarative, accessible navigation around your application
- [React Router Link](https://reactrouter.com/web/api/Link)
- you can send information to the next page through the "state" object of "Link":
- [Link - state](https://stackoverflow.com/questions/41736048/what-is-a-state-in-link-component-of-react-router)

10. Use spread syntax where zero or more arguments (for function calls) or elements (for array literals) or key-value pairs (for object literals)are expected:
- [Spread Syntax](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)
11. To connect front-end with back-end, you will need to send HTTP request using axios. "In axios API" section you will see how you can implement it:
- [Axios](https://github.com/axios/axios)

**Most common Errors you may face in this part:**
 - When sending HTTP request to the backend, you may face "Reason: CORS header 'Access-Control-Allow-Origin' missing" error. Read more why this error happens:
     - [Reason](https://stackoverflow.com/questions/31276220/%20%20%20%20cors-header-access-control-allow-origin-missing)
     - [Fix the Error](https://stackoverflow.com/questions/35760943/how-can-i-enable-cors-on-django-rest-framework)
     - to fix the error you need to write "ALLOWED_HOSTS = ['*']" in setting of your application as well.
     - Read more about Middleware functionality and find the reason why you changed it:
     - [Middleware](https://docs.djangoproject.com/en/3.1/topics/http/middleware/)
    
12. Notice where you can put javascripts expressions:
- [Embedding Expressions in JSX ](https://reactjs.org/docs/introducing-jsx.html)
13. You may not be able to use if-else conditions as well as for loop inside JSX, to implement them inside JSX you will need to learn about map function to implement for loop:
- [map function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
14. What do curly braces mean in JSX (React)?
[curly braces](https://stackoverflow.com/questions/43904825/what-do-curly-braces-mean-in-jsx-react)
15. Learn how to export parameters from modules:
[export](https://www.geeksforgeeks.org/reactjs-importing-exporting/)

## Styling:
1. Instead of CSS we use material ui, which is a user interface library for React:
[Install Material UI](https://material-ui.com/getting-started/installation/) 
- In Material UI go to component section, learn how to use "Container , paper, Grid, Button, Checkbox, Select, Text Field, Divider, Table" and their APIs( what are their inputs).

## Important Notes:
1. Difference between functions and functional component:
  - Functional components should always return a JSX element.
2. What does useEffect do? 
  - By using this Hook, you tell React that your component needs to do something after render. React will remember the function you passed (we'll refer to it as our “effect”), and call it later after performing the DOM updates.
3. Why does React have to use setState for state update?
  - The idea behind that is that in order to track changes in state and than re-render the component according to the changes, you have to use setState, because after setState, the render function is triggered.
  - [setState](https://stackoverflow.com/questions/53098873/why-does-react-have-to-use-setstate-for-state-update)
4. Note that each functional component can just be declared in another functional component.
5. If functional components are used inside JSX, their name should start with uppercase character

