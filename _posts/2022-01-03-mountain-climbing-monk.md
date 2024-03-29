---
title: "Mountain Climbing Monk"
tags: puzzle
---


<p>
  <!-- <a href="MY WEBSITE LINK" target="_blank"> -->
    <img src="/img/monk.jpg" style='width:60%; display:block; margin-left:auto;margin-right:auto' border="0" alt="Null">
  <!-- </a> -->
</p>

##  Question 

Beginning at sunrise, a Buddhist monk threads the 2-ft wide paths of Kathmandu to reach a temple at the mountain's peak. The monk doesn't travel continuously, in fact, he makes regular breaks and seldom walks the same speed. Eventually, he reaches the temple by sunset.

After meditating and praying for days at the temple, he decides to return down the mountain using the same path. Similar to his upwards journey, he begins at sunrise. The walk was (also) discontinuous and at varying speeds. However, since the trek is downhill, the average speed of him returning down is higher than that of him going up.

> Show that there is a spot along the path that the monk occupies at precisely the same time of day on both trips.

## Thoughts

If I'm not mistakened, this problem was used as an introductory problem in one editions of Polya's book, "How To Solve It". This problem is a great demonstration of how the WRONG perspective can influence the difficulty of the problem. If you are trained in applied science, you'd likely think about average speed. If you did mechanics, perhaps you'd even go as far as to consider using the equations of motion, e.g. `s=ut+(1/2) at^2`. And yet, statements such as 'beginning at sunrise' make you wonder if the writer meant that the monk left at the same time at dawn on each day.

## Solution 

The key here is to: 1) Understand the question 2) Draw a diagram. Unsurprisingly, it is 2 of the many recommended rules by Polya when thinking about _How to Solve it_. 

Firstly, this question is asking of existence -- not more. We are not trying to find what time of day, nor are we trying to find which point. To find those are impossible. This should give a clue already that any calculations should be excluded.

Secondly, draw a picture!

Here is a picture of the monk denoted by 'o' and the hill.

        o
        /\
       /  \
      /    \
     /      \
    /        \


        /\
       /  \
      /    \ o
     /      \
    /        \    
  

        /\      
       /  \
      /    \   
     /      \  
    /        \ o


Although a single monk takes a journey up and down on separate days, there is no reason why we cannot imagine them  moving on a single day. 'o' now denotes the monks movement down the hill whereas 'x' denotes the monks movement up the hill; this is the same as imagining two different monks starting the journey at the same time.

        o
        /\
       /  \
      /    \
     /      \
    /        \ x


        /\
       /  \
      /    \ ox
     /      \
    /        \    
  
        x
        /\      
       /  \
      /    \   
     /      \  
    /        \ o

Obviously, if there exists only one path up and down, regardless of how the speed of each of their journey changes, the monks have to cross paths -- at some time and some place. 

## Conclusion 
    
Although not the most difficult puzzle of all time, this is by far my favorite puzzle. It's solution is imaginative and questions the constant need of people to make problems harder than they already are. This puzzle also highlights the two most important tools of puzzling which is to always draw a diagram, and, restate the problem (if possible).