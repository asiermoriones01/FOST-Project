
## Summary (Summarize the bug encountered concisely)

In the creation of a new Blank Project, there is a bad written word. Instead of 'black' should be 'blank'.

[Link to New Project](https://gitlab.com/projects/new)
![Image info](../Image/Bug_Project_create_blank.png)

## Steps to reproduce     

1.  Logged User in GitLab
2.  Go to [Create New Project](https://gitlab.com/projects/new)
3.  Bad written word in the up-left box

## What is the current bug behavior?

There is bad written word in the up-left box. 'Create black project'

## What is the expected correct behavior?

The up-left box should show 'Create blank project'
     
## Relevant logs and/or screenshots

Page with the bug

![Image info](../Image/Bug_Project_create_blank.png)

Page without the bug 

![Image info](../Image/Bug_Screenshot.png)

## Possible fixes

Change the word in the line of code of html

from
```html
<h3 class="gl-font-size-h2 gl-reset-color">Create black project</h3>
```
to 
```html
<h3 class="gl-font-size-h2 gl-reset-color">Create blank project</h3>
```

## Whom do you report/ Assign To/ Tags

    /label ~bug ~reproduced ~needs-investigation 
    /cc @project-manager 
    /assign @qa-tester

## Priority

Trivial
      
