# Short Answer Questions

Adrian Lee
A01235958
midterm for 1620 October 2020
BCIT

## Q1
Git is software that allows the user to track and edit code through branches without changing the main code (master branch). Git is also useful for working on projects with groups/teams. Git also allows users to track the date of modification to any of the files. 
GitHub is a cloud service that allows you to store work. Useful for showing business' previous work that has been done when applying to jobs. Github uses Git to manage and control work.

## Q2
Branches are a way to test code. Instead of making commits to the master branch you create a different branch that edits can be made on. If what the user did on the new branch is successful they can just merge the branches. 
writting git branch will show the list of branches.
to create a branch you write git branch (name)

## Q3
the status message will return 404 not found. This belongs in the 400 client error status messages. 
Other messages within this category are:
400 bad request - the request is to large or malformed.
401 unauthorized - client lacks authorizaiton to access the resource
403 forbidden - access is refused by the server. Either the user does not have permissions or are not logged in.
404 not found - means that whatever the user is trying to access does not exist.
405 method not allowed- if you try to use a http verse that is not allowed whatever the user is working with.

## Q4
inline css styling will take priority over the style sheet. Or styling placed into the head section. The element will be red instead of green. 

## Q5
the http: is the protocol (hypertext transfer protocol). (Https - hypertext transfer protocol secure)
//www subdomain stands for the world wide web.
the domain name is the part after the www it is the .google or .notion
.com, .ca top level domain the name server that the browser will use to locate the requested site. 
the //www.notion.so is the resource name.

## Q6
Http headers allow information to be passed between the user device and the server. There can be multiple headers per request and the name is separated from the request or response by a colon. There are cookie headers which can be sent from the server requesting that the user's browser store information in some cookies to be sent back to the server. There are language headers, host, connection, and many more. The client-date header requests the date time and timezone of the clients computer. The Keep-Alive header hints about the ability to set a timeout and maximum number of requests. The Connection header is what controls whether or not the connection to the network will stay open after the request is finished. 

## Q7
The box model sets the size of elements, the space it takes up, and the position they are in relation to each other. The box model is (from inside to outside) content, padding, border, margin. The content box contains text or an image, the padding area surrounds the content area which is still part of the elemen, then the border surrounds the padding and the margin surrounds the element. There are different properties; for the content there are width and height properties. padding adds or removes within the element margin adds or removes around the element and the border is inbetween.

## Q8
The descendant selector picks all of the elements that are of a specific element. 
 div p{
     color:purple;
 }

The child selector selects an element that is a child of the selected element. 
if the DOM shows an aside tag that contains a header within it then the header would be the child of the aside tag.
aside > h1{
    color: cyan;
}

sibling selectors will select elements on the same heiarchy level. if there is a div tag that contains a h1,  p, h2, p. The adjacent selector '+' will pick something right beside them.
div h1+p{
    background-color: green;
}
if you write:
div h1~p{
    color:orange;
}
all of the paragraph tags that are within that div tag will now be orange.


## Q9
the paragraph tag always starts on a new line.

## Q10
1 the img tag requires an alt tag.
2 what is a title attriute doing in the closing a tag... if you want a title attribute it goes IN the opening a tag. It is what appears when the mouse is hovered over the link.