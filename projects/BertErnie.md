---
layout: project
type: project
image: img/download.jpg
title: "BertErnie"
date: 2023-08-23
published: true
labels:
  - Educational Technology
  - Javascript
  - React
summary: "Discussion of the firs WOD"
---
For this "Workout of the Day", we were assigned a relatively easy task, to find multiples of specific integers and return "Bert", "Ernie", or "BertErnie". I was confident in my four inf statemets and two for loops, but once I turned it in, I looked at my neighboors solution, which was much less redundant than mine. I realized that although my solution was correct, her solution was much more efficient. 

The more efficient solution is provided below.
function BertErnie(int){
  	if (int % 4 === 0 && int % 6 === 0){
    	return "BertErnie";
    }if (int % 4 === 0){
    	return "Bert"
    }if(int % 6 === 0){
			return "Ernie";
    }else{
    return int;
    }
  }
 }
 	for (let i = 1; i <= 15; i++){
		console.log(BertErnie(i));
   }
