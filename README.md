resume
======

A LaTex resume! I've tried to make it as easy to use as possible

I've defined several Commands and Environments

Commands
--------
resname: Formats the Name, Address, Phone Number, and Email in the header (also provided name,addr,phone, and email commands so all that information is in one piece)

reseducation: a shortcut for an information ressection:
	      Requires: Name of school
	      		Date of Graduation
			GPA
			Major(s)
			Minor(s) {Will need to change if only one/no minors}

skills: prepends and '\item[]  skills' in italics to a list of skills, 


Environments
------------

Ressection: Given the name of the section: (ex, Experience, Volunteering, Etc.) formats a header for a new section in the resume and sets up the environment to add resitem for individual elements in the section

resitem: Given name of item, location, time period, job title
Formats the header for an individual item in a ressection (e.g. \begin{resitem}{B-Line Medical}{Washington, D.C.}{June 2013-August 2013}{Software Development Intern})
inside of this environment you can add details with the regular \item command

classes- Shortcut to list relevant classes. Just an \item command for each Class