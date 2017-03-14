# Front End Hand-ons Test

##Instruction
You've provided with 2 source code:

1. fe_01.html
2. fe_01_style.css

*fe_o1.html is not complete code where you'll complete it for this hands-on test*

*all ajax url is not working, it just dummy url*

##Introduction
From the **Table** you can see a list with 5 column id, name, gender, sex and action columns.
In the **action** column there a 2 links which are view and remove links.

You were provided with predefine javascript and css in the **html** files where the already a few method
inside the **App** class:
1. view method
2. remove method

###Question
1. Please make all action buttons (view and remove works) respectively
    1. when view is click it will stub / call method **view** in **App** class
    
    2. when remove is click it will stub / call method **remove** in **App** class
    
    3. For each method (view, remove), for ajax url it need an id to identify which person is being used as 
    parameters. you can check in the table in the html element what is the id for each person
    which is display in column ID.
        1. please identify the respectively id by replace the ?? in each method with your single line code.

2. Make the UI flow "live".
By default in the html there is element with id "response-message" which by default is not hidden.

    1. Please make it hidden once the page is loaded, so by default user will not see this message when the page is
    loaded. You can hide it with css or javascript.
    
    2. Lets assume the all the ajax request will return either *true* or *false* for success and 
    failed respectively. foreach type of there is a predefined css style in **css** file which are
    *.success* and *.failed* respectively.
        1. Please complete **view** method on result *true* SHOW the *response-message* and the
        elements should apply *.success* provided in css and show message "Request has been done" within the element
        
        2. Please complete **view** method on result *false* SHOW the *response-message* and the element should
        apply *.failed* provided in the css and show message "Request is failed!" within the element.
    
        3. For each message is display in the page, either *success* or *failed* it will just show to user in 5 seconds, then it
        should hide it the message automatically.
        
        4. Please complete **delete** method on result *success* it will remove which rows it was intended to remove.
        for e.g if user click remove in row of John Smith please remove the table row after *success*
        
3. Sass / Scss conversion
From the given css file (fe_01_style.css), please add a file of sass / scss file which will having same result as the 
css. 
p/s Try utilize as many sass / scss feature when you converting the scss.
    

