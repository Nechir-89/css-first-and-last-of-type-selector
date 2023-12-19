:first-child selector means

Select the first child of its parent if and only if it's first element in the container.

CSS3's :first-of-type selector, referes first of it's kind in a container.

element:first-of-type
{
    color: blue;
} 

With browser compatibility, it's better off giving the first element a class, then targeting that class:

classname.first-of-type
{
    color: blue;
}