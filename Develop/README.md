# Homework1
Homework1 - Columbia Coding Bootcamp

# 01 HTML CSS Git: Code Refactor

I was going to reset the assumptions before starting anything else
    <link rel="stylesheet" href="./assets/css/reset.css"> 
BUT IT THREW OFF SOME FONT-SIZE IN HEADER/BODY AND PULLED ASIDE BOX DOWN.  SO I TOOK THE RESET OUT AGAIN 

HTML --- title changed from 'website' to 'Horiseon'

HTML --- Link for "Search Engine Optimization" doesn't go anywhere.  Other two go to sections below.    
Changed "Search Engine Optimization" to id and class, matching others. 

*** HERO Div doesn't enclose anything --- IT IS PLACEHOLDER FOR BACKGROUND IMAGE AT TOP.
MOVED IMAGE TO HTML TO ALLOW ALT TEXT.  ADDED TITLE FOR IMAGE.

ADDED ALT TEXT AND TITLE FOR ALL IMAGES.

Within HTML paragraphs, put them on separate lines so easier to read code.

HTML - changed to header, footer, aside, and article.  In CSS, removed . from .header, .footer

In CSS, .benefits changed to aside.

In CSS, .benefit-lead, .benefit-brand, .benefit-cost were combined. Simplified to aside div.  

In CSS, .benefit-lead h3, .benefit-brand h3, .benefit-cost h3 were combined.  Simplified to aside h3

In CSS, .benefit-lead img, .benefit-brand img, .benefit-cost img were combined.  Simplified to aside img

In CSS, .search-engine-optimization, .online-reputation-management, .social-media-marketing were combined. Simplified to article.  In HTML removed classes for these three.

In CSS, .search-engine-optimization img, .online-reputation-management img, .social-media-marketing img were combined.  Simplified to article img

In CSS, .search-engine-optimization h2, .online-reputation-management h2, .social-media-marketing h2 were combined.  

In CSS, added color:#fffff to body; removed from header, aside, and article.  Left color for a; put black as color in footer.