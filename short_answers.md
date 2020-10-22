# Short Answer Questions

Paolo Penaflor
A00964723
midterm for 1620 October 2020
BCIT

## Q1. Explain what Git and GitHub are. How are they different? 

        Git is one of many version control systems (VCS). It allows multiple users to work on the same project and track any changes to the said project.

        GitHub is a git hosting service. This is the platform where users share and store their projects and also where they can track changes to their files.

        Git is the tool that a user needs to install in their system while GitHub is the online platform that is built around using the Git tool.

## Q2. What is a 'Branch' in Git? How could you create a new branch and what would you commonly use a branch for? 
        Branches are lines of development for the project. Using branches, different users can work on the same project without affecting each other. You can create a new branch using "git branch (branch_name)".

        Branches are used usually to test features and changes to a project without affecting anyone else's work.

## Q3. What is the http status code you get when a resource is not found? What category of status code does this belong to (other status codes that start with the same number)? Does this status code indicate if the representation is permanent?

        The http status code you get is "404 Not Found". It belongs in the Client Error category where all status codes start with a 4. the 404 Not Found status code doesn't necessarily indicate that the representation is permanent or temporary. A "410 Gone" status code will be displayed if the requested content is permanently deleted.

## Q4. What is not correct about styling of the given h2 element in the code below? Which color will the h2 be and why? 

        Since there is a style in the opening h2 tag, the h2 styling that has previously been put in the head area. h2 will be red instead of green.

## Q5. List and briefly describe the parts of a URL.

        https://www.google.com/maps

        1. "https:" - Protocol - Tells the browser which protocol to use in order to communicate with a web server.

        2. "//www"  - Subdomain - Basically a folder where content is held in a web server. Allows servers to identify unique sites.

        3. ".google" - Domain Name - Provides a human-readable address for any web server. Domain names are translated into IP addresses to find a specific website.

        4. ".com"  - Top-level Domain - The name server browsers use to locate the site requested.

        5. "/maps" - Subdirectory - Shows which section of a webpage a user is on.


## Q6. What is an http header? Provide examples of three http header fields and briefly describe what each does. 

        An http header is a human readable name value pair separated by a colon. It is added to the HTTP request or response and can be used to pass a variety of information between client and server.

        - Host: States what resource is being requested using a URL.

        - User-Agent: This is how a client identifies itself.
        
        - Accept: Lists what file types the client accepts.

## Q7. Describe the CSS box model? From inside to outside what are the different parts of the box model? 

        The css box model is how every element in a document is represented by the client engine. From inside to outside, the parts are content, padding, border, and margin.

## Q8. Briefly describe the 4 CSS Combinator selectors that we looked at in class. Provide an example of each.
        Descendant selector (space) - Matches all elements that are descendants of a specified element.
        
        div p {
                color: red;
        }

        Child selector (>) - Selects all elements that are the children of a specified element.

        div > p {
                color: red;
        }

        Adjacent sibling selector (+) - Selects all elemnts that are adjacent siblings of a specified element.

        div + p {
                color: red;
        }

        General sibling selector (~) - Selects all elements siblings of a specified element.

        div ~ p {
                color: red;
        }


## Q9. Will these two paragraphs appear on two separate lines? Why? 

        These two paragraphs will appear on two seperate lines. They have paragraph tags on them and paragraphs are block level elements.

## Q10. Identify and explain two of the errors that exist in the code snippet below.

        Closing tag of the anchor element has "title" parameter on it. Also, alt attribute is not given.