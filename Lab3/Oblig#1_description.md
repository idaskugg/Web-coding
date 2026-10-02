Oblig#1
Write your personal page
Due date: check Canvas
IDG1292-FALL2026
Table of Contents
Preface ........................................................................................................... 3
Context .......................................................................................................... 4
Task description ............................................................................................ 5
Required ........................................................................................................ 7
Tips ................................................................................................................ 9
Other resources ............................................................................................ 10
Deliverables .................................................................................................. 11
3
Preface
This document describes the course's first compulsory task (oblig#1). The task
focuses on creating a coherent HTML structure and reflecting on the choices made
during the design and implementation phases. CSS is allowed, and you are encouraged
to use anything learnt between lectures 1 and 4. Therefore, you are not allowed to use
Flexbox, Grid Layout, tables, etc.
These are all rather simple tasks. So we expect you to deliver high-quality work.
The best thing you can do for quality assurance is to:
a) validate all your HTML and CSS code.
b) find a buddy so you can look through each other's code and give feedback.
Please do not forget this is an individual task; copying or letting others copy
your code can be considered plagiarism. If you use fragments of code from the
internet (Stack Overflow, W3C, etc.), make sure they are properly referred to in the
code as a comment with the link to the resource you have used.
Finally, also notice it is expected that you write your code from scratch. Therefore,
downloading HTML templates or using CSS frameworks such as Tailwind CSS or
Bootstrap is not allowed.
4
Context
You have just finished your fall semester at the university, and you are excited about
the idea of getting a part-time job to get some hands-on experience working as a web
designer. Unfortunately, your work experience is scant, and you need to figure out a
way to promote yourself. Then, the idea of building a website that talks about you
comes to mind.
Notice that a personal website is not a resume. Resumes are boring. Personal
Websites allow us to differentiate ourselves from the rest. Some advantages of having
a personal website are the following:
• You can emphasise your strengths by drawing the user’s attention to
remarkable things about you.
• It makes you more findable.
• It allows you to build a personal brand.
• It gives you a differentiating factor from the rest of the people.
This compulsory activity is delivered individually. Feel free to create your real
portfolio or create a fictional persona if you do not want to make the website about you.
Avoid lorem ipsum text by all possible means. Semantic tags carry meaning, and
the context of their content is important to understand whether they are used correctly
or not.
5
Task description
Design and implement your personal portfolio page.
Your personal website must contain five different pages:
¨ Home page: this is the first page users will see. You can decide the contents
that will be shown to the user on this page. However, it must contain at
least the following:
o image and description about you (make sure you use proper
semantic tags);
o text introducing yourself;
o list of hobbies;
o a quotation from a book, song, or movie you like.
¨ Resume/CV page1 presents your academic credentials, skills, and
qualifications. It must contain at least the following:
o academic background;
o work experience;
o list of languages you speak (e.g., English, Norwegian, etc.);
o list of skills.
¨ Portfolio page: Use this page to show to the world your best works or
projects. A portfolio project can be anything you want, such as a picture, a
drawing, a piece of art, a website, etc. You can also use assignments from
other courses, such as, for example, IDG1000. You must include at least
three different projects. All the projects in your portfolio must have a title,
a description explaining what the project is about (5 or 6 lines) and an
image. Example below (text from Wikipedia):
o Title: Guernica
o Short description: Guernica is a large 1937 oil painting on canvas
by Spanish artist Pablo Picasso. It is one of his best-known works,
regarded by many art critics as the most moving and powerful anti-
war painting in history.
1 Look at LinkedIn to get some inspiration about things you can include in your
curriculum
6
o Image:
¨ About page: this page must contain a short report of the preparations you
did beforehand to ensure you would use different semantic tags. Explain
why you decided to include the different parts of your content and discuss
why the HTML elements you used to annotate them were the best option.
Create a sketch of the main layout of the pages (box model) and show it in
this page together with the explanations.
¨ Contact page: It will show all your contact information as well as links to
your social websites (e.g., Facebook, Twitter, LinkedIn, Instagram, etc.).
You must include at least three different social networks. The links must
work properly. However, you don’t need to link them to your real social
networks if you don’t want to do so. A link to the main page of the social
platform would suffice. Do not forget to include an email address and
phone number2.
2 Use the proper elements so that the user can actually call you or send an email you
7
Required
This assignment is going to be graded based on all the concepts introduced from
lecture 1 to lecture 4, but you can also use concepts from lecture 5 (reading list on
Canvas) to improve the readability and aesthetics of your site. The most important part
of this oblig is to show that you understand how to structure your content and your
projects.
Here you can find a list of considerations you need to check before delivering this
assignment.
¨ Make sure you use structural and semantic tags (as many as possible). Don’t
forget about acronyms or abbreviations.
¨ Elements must be properly used (what is this element used for? Is used as
it was defined according to the standards?).
¨ Make sure you use lists and nested lists.
¨ Use proper naming conventions for files (i.e., HTML, CSS, images, folders,
etc.). Check google recommendations and Filenames and file types3. How
to Name HTML Files is another interesting article about this topic with
regard to SEO.
¨ Scaffold the project following a readable and well-structured hierarchy of
folders (check the different articles available on Cavas and lecture slides).
¨ Write readable code (clean, clear, commented and well formatted).
¨ Use CSS for the presentation layer (remember to avoid inline styles).
¨ CSS rules must be efficient. Don’t Repeat Yourself (DRY).
o Use separate files.
o Use selectors, classes, and ids.
o Use colours, background colours, padding, and margins to
improve the readability of the contents presented to the user.
o REMEMBER THAT ELEMETNS MUST NEVER
OVERFLOW THEIR PARENT CONTAINER4.
¨ Make sure that all the elements of the webpage are coherent (e.g.: all h1
elements has the same colour and size, etc.).
3 Notice that these are guidelines. You need to be critic with your decisions. For
example, google recommends omitting optional tags but - as explained during the lectures
- this might not be a good idea.
4 There are many ways of creating responsive layouts. In lecture 4, some recommendations
were discussed to create responsive layouts with little effort (e.g.: max-width + box-
sizing). In this assignment your goal is to prevent elements to overflow their parent
container. Media queris must not be used.
8
¨ All the pages must be linked using a <nav> top menu.
¨ Use English for writing both code and content.
¨ Do not use lorem ipsum text.
Try to be as creative as you can using all the elements and concepts explained so
far. You can learn and use CSS attributes on your own, but try to avoid using elements
not explained in previous lectures because they will not be evaluated (e.g., JavaScript,
animations, tables, etc).
Remember, DO NOT just grab a template from the internet; this is an introductory
assignment, and therefore you must start the project from scratch (i.e., no templates,
no Bootstrap, no flexbox, no grid, etc.). Should you need to clarify any of your
decisions, please include them in a README.txt file, in your zip file, beside your
HTML files.
9
Tips
You do not know how to include semantic tags in your site? You can, for example,
start the resume page by talking about your goals and motivations and then use
semantic tags to emphasise your strengths.
Does your CV contain abbreviations or technologies/skills that need to be defined?
You do not need to share sensitive data in your portfolio (e.g., your real phone
number), but writing about you and taking advantage of this assignment for a “real”
portfolio is a good idea and something that you might reuse in the future.
Be as creative as you can with the “scant” knowledge given so far. Try to be
imaginative and make an appealing and readable site with the tools you have.
The Google Style Guide for HTML recommends omitting all optional tags.
However, this practice has not been widely adopted and, taken out of context, it can
be a bit misleading. Therefore, always close your tags, even if they are optional.
Use the about page (and README.txt if you like) to explain relevant decisions.
For example, if all your pages stand inside the root folder, explain why, and reflect
about the pros and cons. Or the opposite if you have different folders per page, also
explain why, etc.
10
Other resources
Do not forget all the slides and course materials have links to external articles and
interesting resources. Here you have a list of other articles that might be useful for you
for this task.
¨ https://developer.mozilla.org/en-
US/docs/Learn/Getting_started_with_the_web/Dealing_with_files
¨ http://www.htmlquick.com/tutorials/organizing-website.html
¨ https://webstyleguide.com/wsg3/5-site-structure/3-site-file-
structure.html
¨ https://www.w3schools.com/Tags/tag_nav.asp
¨ https://www.w3schools.com/html/html_css.asp
¨ https://www.w3schools.com/css/css_howto.asp
¨ https://css-tricks.com/one-two-three/
¨ https://www.toptal.com/css/css-cheat-sheet
¨ https://www.themelocation.com/best-html5-practices/
¨ https://moz.com/blog/seo-meta-tags
¨ https://cssauthor.com/creative-resume-design-inspiration/
Please, read all the resources carefully and notice that some of the articles fall into
the field of subjectivity, which means that there is no absolute truth and you need to
reflect on what you are doing. The most important thing is to be consistent. For
example, if you “indent” your code using 4 spaces, that is the indentation that you
should use in all your files, etc.
11
Deliverables
The default number of attempts per oblig in our department is 1. However, this is
micromanaged by the course responsible, who can modify the number of attempts if
they like.
In this course, the number of attempts you have varies depending on the
compulsory activity. For oblig#1, you have 2 attempts. However, the second attempt
is only granted if you meet the following conditions:
• The first attempt must be delivered within the deadline (never after)
• The oblig must be a significant piece of work (i.e., do not deliver an empty
assignment)
• The first attempt is graded as “not approved”
The deadline is on Blackboard, and the assignment will be delivered there. Further
instructions will also be published on Blackboard if needed. The delivery consists of
two parts:
¨ The zip file, containing the complete website (i.e. you need to zip your root
folder).
o The zip file must be named as “studentcode-o1-idg1292-2025” (for
example, if your student code is 1357246, then the name of the zip
file must be “1357246-o1-idg1292-2025”.
o The zip will contain your whole project (i.e.: html pages, folders,
assets, images, etc.).
o The readme.txt file must contain the “URL” of the live version
of your site (i.e., the folk site).
¨ The live version of your site: the exact same website must be published on
your personal website (folk site) via FTP.
o To avoid plagiarism issues, I recommend you upload the project,
naming the root folder of your oblig using a random name
(https://randomwordgenerator.com/). Check the screenshot
below.
Get to work as soon as possible and do not leave this for the last minute. Also,
there is nothing new about this assignment, which we have not already done in the
previous lectures or labs, so do not be scared of the long description.
12
Should you have questions or need help, do not forget to use the forum (or the
email as a fallback option when needed). Don’t forget the student assistants.
Good luck!