![sympy_logo](https://user-images.githubusercontent.com/50987933/161259317-5b4494d9-4a09-4751-a846-199765d2a776.png)
![gsoc_logo](https://user-images.githubusercontent.com/50987933/161259326-bddd6679-50b5-40ea-9614-5799b8819102.png)


**GSoC 2020 @SymPy**
This repository showcases my proposal, and the work done (final report) during Google Summer of Code 2020 with the SymPy project. SymPy is a computer algebra system written in pure python.

It all started here:

The SymPy community is very welcoming and supportive. I sent an email to the SymPy mailing list around Feb 3rd, 2020, asking the community about the scope of adding a new Control Systems engineering package. Initially, their opinions were against this, and students were advised to focus on improving existing SymPy packages, instead of adding new packages (core or not).

I continued to show my interest in this project and guess what?? Here is the response I got finally (Thanks, Jason):


Project: Control Theory - Implement a control systems package
Student: Naman Gera (namannimmo10)

Official No Mentors:

Since this was a big project and I had to develop a package from scratch, I did not get a lot of help from other members of the SymPy development team and even Control theory experts. .

Work done:
My main focus was to implement in SymPy, a basic Control Systems functionality from scratch. This can be used by Control engineers or professors/students to solve various control theory related problems. Being a part of SymPy, this is purely symbolic in nature. The advantage of this package over other packages/libraries (which are great, btw!) like harold and python-control is that the solutions obtained from it are highly accurate and do not rely on numerical methods to approximate the solutions. The solutions obtained are in a compact form that can be used for further analysis. Documentation is available at Control API and Control Intro.

PULL REQUESTS -

Major additions:

(Merged) sympy/sympy#22376 - Making the Laplace Transform Rule-Based 

(Merged) sympy/sympy#23215 - Inconsistencies in float + int 

(Merged) sympy/sympy#22873 - Printing error fixed.

(Merged) sympy/sympy#22889  - functions : Improved floor and ceiling results 

Miscellaneous PRs opened in the summer:

(Merged) sympy/sympy-
(Merged) sympy/sympy


Future Work:






 
 
My GSoC Experience and Learnings:
I've been writing weekly blog-posts documenting my journey during GSoC. The blog is hosted at namannimmo.me/emerald. This experience was so amazing and complete and I learned lots of different things; I can't write them all in here.

But, here are a few:

Having to adjust to my team members' different timezones was definitely a challenge. I also loved the challenge of working with a remote team and leaving my comfort zone of talking in person to work on something
I also learned written communication. Writing accurately is difficult, so I had to learn how to convey my thoughts well enough, because we were working remotely, right?
I had not implemented any package from scratch before, so this was a challenge in itself. But the mentors were helpful enough and discussed everything with me - they were readily available for discussions
If could repeat this again, I would do so. This community is so welcoming, even if you come up with a naïve approach of solving a particular problem, they will help you to improve the code even further because we had to adhere to the SymPy standards
Since a lot of people get confused in the beginning, I've written a detailed answer on Quora for students preparing for GSoC. Here's my answer to "How can I apply and prepare for Google Summer of Code?" - hope this helps!
Edit: I'm mentoring for SymPy in GSoC 2021.

:wq for now.

Naman Gera (namannimmo)

Email | GSoC blog | StackOverflow | Quora
