------------
Philosophies
------------

The design of Kaizen embraces the following design philosophies.  They are the principles used to 
made design decisions.  The reasons one solution is chosen over its peers.  The basis to resolve 
design conflict peacefully.  The beliefs that give Kaizen its nature and its personality.

#.  Shape of the problem equals shape of the solution.

	Meaning the design/approach/implementation of a solution must match the nature/size/importance 
	of the problem.  A round hole needs a round peg.  A solution that does not match the problem 
	it is trying to solve, is the same as forcing a “square peg into a round hole”.  It simply 
	does not fit.  The solution will not solve the problem.  It will never be satisfactory solution.  
	Even if it is somehow forced to fit, the solution will not add to the greater good, instead 
	will detract.

#.  Size & Performance matters.

	Kaizen is a 'big-data' application, meaning it must handle large volumes of data.  All design 
	choices must be able to scale, and to operate at scale.  Solutions that are perfectly valid 
	“in-the-small”, often fail when encountering “the large”.  Knowing in advance that the system 
	will be faced with thousands, millions, or billions of items allows quicker, more knowledgeable 
	selection of possible solutions.

#.  Simple is better than complex.
    Complex is better than complicated.
    Complicated is just wrong.

	Many people will use, add to, and maintain Kaizen over its lifetime.  Those people need to 
	understand the system and how it works.  It is easier to understand a complex system built 
	of many simple parts, than a complicated system built of many complex parts.  Complexity 
	naturally results when dealing with complex problems.  But complicated is not natural.  
	It is the result of a poor understanding of the problem, followed by poor problem deconstruction, 
	resulting in poor design.  There is no excuse for poor design.

#.  Results are Pushed.  Users shouldn't need to Pull information.

	Building Operators & Facility Managers are awash in data.  There is no end of data coming from 
	their buildings.  The BAS system generates more data, more alarms, more noise - than any person 
	can hope to process.  What these people (our target audience) need is more concentrated 
	information not more data.  They need insights (actionable knowledge), not another tool 
	regurgitating realms of meaningless BAS data. Kaizen shall deliver concise knowledge to its 
	users where they are, when they need it.  Users shouldn't have to login looking for this information.

#.  Soon is better than never.  *Right now* is seldom required.

	Technology has created the false expectation that “everything is needed, and is needed right now”.  
	This falsehood has lead to many poor design choices, incomplete & unwieldy implementations, 
	and premature solution optimizations.  “You aren't gonna need it (YAGNI)”, 
	and KISS (keep it simple stupid) Principle - are other ideas supporting push-back to this falsehood.  
	Only a proper understanding of the problem clarifies “how much” of a solution is needed and when.  
	It is better to provide a good solution soon, than either the prefect solution never, 
	or a bad solution now.

#.  Beautiful is better than ugly.

	Real Life is messy, but that is no excuse for ugly.
	Real life, meaning real world data, is full of special cases, bad values, holes, and surprises.  
	The design must expect and deal with these realities.  However, just because the data is ugly 
	does not mean the solution(s) must be ugly.  Ugly results from poor design, not ugly data.  
	A good solution gracefully handles real life, and is beautiful.

#.  Be thankful for “The law of Large Numbers”.

	When dealing with large volumes of data, the effects (and importance) of individual values 
	diminishes.  This allows certain constraints to be relaxed in many parts of the system.  
	Provided the outliers (minimums, maximums, steep changes, etc) are preserved, many items and 
	be suppressed, aggregated, ignored without affecting the results.  Careful application of this 
	principle can yield useful solutions where none seemed possible.
