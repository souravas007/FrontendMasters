!+ENTER = html structure
span+ENTER 
a+ENTER
span.purple
span#id
div.class-1.class-2#id-1
.class -> generates div automatically
#id -> generates div automatically
link+ENTER
button[type="button"]
[data-selected] ->attribute generation
[data-selected].active  ->attribute + class -> use tab to move
div.purple>span.cyan -> child creation.
header>nav>ul
header>nav>ul>li*3 -> use tab to move
header>nav>ul>li*3{text to be placed inside}
header>nav>ul>li*3{List Item $} -> generates number from 1 to n.
header>nav>ul>li*3{List Item $} -> generates 2 digit number
header>nav>ul>li*3.class-${List Item $} -> generates class1, class2, classn
header+main+footer -> 3 siblings
header>nav^main+foot -> ^ -> climb up. nav is child of header. main & foot are siblings.
(header>nav)+main+footer  -> same as above. nav is child of header. main & foot are siblings.
form:post>.group>input:text
form:post>(.group>label+input:text)+(.group>label+input:number)

css 
bgc-> background-color
selectors has shortcuts in css.