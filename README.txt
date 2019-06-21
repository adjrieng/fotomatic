Hello to whomever will be analyzing my work.

The project "SOLUTION" itself was broken. With that said, I sorted things out. 

Asides from the obivious trip ups (I really liked the missing "."... that kinda frustration makes you remember.)
Anyhoot, the primary issue with the exercise is that @media queries were not functioning sans a <meta>.
That said, I also spruced things up with some min/max's and the like. Enjoy ;-) 


*update - commit 3
- cleaned up <head>
- added a favicon


*update - commit 4
Noticed on my jumbo-tron the the #filters-section .images-container was not centering soooooo...

- added "justify-content: center;" to the Rule Set.. I feel better now. ;-)


*update - commit 5
Noticed one last problem on the jumbo-vision... certain elements were not playing nice on stupid resolutions...

- changes marked with *

.image-container {
    overflow: hidden;
   *max-width: 680px;
}


.feature {
    flex: 1;
    padding: 2rem;
    margin: 0px 1.25rem;
    background-color: white;
   *max-width: fit-content;
}



#features-section {
    display: flex;
   *justify-content: center;
    padding: 4rem 5%;
    background-color: #f3f3f3;
}


Thanks
