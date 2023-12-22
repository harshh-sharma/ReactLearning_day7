# In this lecture I learn about useState(some imp points),useEffect,react-router-dom,outlet,Link and useRouteError hook


# Important points about useState() hook :-
    - Always calls useState() hook under the component if you called outside the component then they thrown an error.
    - Trying to call hook on the top of the component.
    - Never make useState() hook under the conditional statement.
    - Never create useState() under the loop or any other function except function component.


# React-Router-DOM :-
    React router dom is a npm package that enables you to implement dynamic routing in a web app.It allows you to display pages and allows users to navigate them.It is fully-featured client and server side routing library for react

# React-Router-DOM has many useful components and create fully functining routing :-
    - 1. Router(usually imported as browser router):-
        It is the parent component that is used to store all of the other component.Everything within this will be part of routing functionality.

    - 2. Switch :-
        Switch component is used to render only the first route that matches the location rather then rendering all matching routes.

    - 3. Route :-
        This components checks the current URL and displays the component associated with that exact path.All routes are placed within the switch components.

    - 4. Link :-
        Link component is used to create links to differnt routes.

    The routes components takes two argument:-
        - 1. The first one is path that will be in the url.
        - 2. The second is the component that will be displayed if the current URL matches the path in the first parameter.

# How to install react router dom 
    - npm install react-router-dom

# OutLet component :-
    - The react router <Outlet /> componet (from react-router-dom) is used within the parent route element to indicate where a child route element should be rendered.

# Link Componet :-
    - The <Link> helps the user navigate from one page to another in a SPA(single page application) without reloading the entire page

# Differnce between Link and anchor tag
    - The main differnce between link and anchor tag is Link can navigate from one page to another without reloading the entire but achor tag can navigate one page to another and reloading entire page