# How would you break a mock into a component heirarchy?
draw boxes around every component (and subcomponent) in the mock and give them all names
# What is the single responsibility principle and how does it apply to components?
Means that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

# What does it mean to build a ‘static’ version of your application?
enders your data model, you’ll want to build components that reuse other components and pass data using props.

# Once you have a static application, what do you need to add?
 - Add Your New Site. ...
- link to Your GitHub (or supported version-control tool of choice) ...
- Authorize Netlify. ...
-  Select Your Repo. ...
- Configure Your Settings. ...
- Build Your Site. ...
- All Done.
# How can you identify where state needs to live?
Identify every component that renders something based on that state.
