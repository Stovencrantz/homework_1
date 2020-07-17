<HTML Changes>

1) Line 7 --> Adjusted the title content to better represent the website.
2) Line 11 -->Replaces the <div class = header> with HTML5 tag of <header>
3) Line 15 --> Replaced the <div> tag with a <nav> tag to better identify the nav bar
4) Line 32 - line 57 --> Replaced <div> elements with <article> elements to represent the self contained data in each class.
5) Line 32 - line 57 --> Removed the <id> elements from each article as it was creating unnecessary redundancy and no callouts were used in our CSS.
6)  Line 87 --> Refactored the <div class = "footer"> to a <footer> tag


<CSS Changes>

1) Line 11 - Line 39 --> Adjusted the selecters to replace <.header{}> with <header{}> and <div{}> with <section{}>
2) Line 66 --> removed the style attributes for .float-left and 
.float-right as their styling was never called in our html.
3) Re-orgonized our .benefits supporting classes to be listed below our .content supporting classes.
4) Line 77 - line 105 --> Consolodated 3 seperate instances of extra syntax into one instance for the classes contained in our .contents class, as well as for <img> tags and <h2> tags within these subclasses.
5) Line 77 - line 105 --> Consolodated 3 seperate instances of extra syntax into one instance for the classes contained in our .benefits class, as well as for <h3> tags and <img> tags within these subclasses.
6) Line 148 - line 157 --> Replaced .footer class selector with a <footer> tag selector for styling.