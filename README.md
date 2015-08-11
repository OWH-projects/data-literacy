# Data literacy
Brown-bag session on how to find, obtain, clean and use data on your beat.

## Finding data
<ul>
<li><b>Check annual/quarterly reports.</b> Reports like <a href="http://opd.ci.omaha.ne.us/images/crime-statistics-reports/quarterly/1st_Qtr_14_RPT1.pdf">this one</a> from the police department can be a huge key. How does the department know average 911 response time? Because they record it for every call. Similar logic can lead to all sorts of neat datasets.</li>
<li><b>Go up the food chain.</b> The National Center for Education Statistics requires data from the states, which requires data from the districts, which requires data from the schools. This happens in beats we can't even imagine. Find out what federal or state agencies require, and you'll find a local dataset at the end of the rainbow.</li>
<li><b>Read the rules.</b> Government is fantastic at creating data. It is not so good at following up. Ask Chris Burbach, who found that a city department was supposed to file a quarterly report about its hiring practices... but wasn't.</li>
<li><b>Request copies of blank forms.</b> To find out what data a department or agency has, see what they're collecting from users.</li>
<li><b>Chat up a frequent flier.</b> Find somebody whose job requires them to interact with a department frequently, and see what sort of information they have to give up. (E.g., what's it take to pull a building permit? Talk to a builder or electrician.)</li>
</ul>

## Getting data
<ul>
<li><b>Don't fear the formal request.</b> Most worker bees don't even realize they're filling in a database, much less have the power to give you complete data. A records request is a surefire way to cut through the crap and get your questions before a person who can actually help you. Be stern and cite the law.</li>
<li><b>But there's a catch</b>: It's hard to make a request without knowing what data is stored. Try talking to the people who actually work with the data to understand what's there and how it can be used. Requesting information that doesn't exist is a good way to drive yourself to drink.</li>
<li><b>A middle ground.</b> In my requests, I  admit when I have no idea if the data exist or not and ask for help. I don't know if it works.</li>
<li><b>Ask for a csv.</b> It's a universal format easily exported from any program. If they say otherwise, call the vendor. Some agencies will give you PDFs. <a href="http://blog.dataomaha.com/pdfs-data-nebraskas-public-records-law-and-why-you-should-care-about-file-formatting/">Try to talk them out of it</a>.</li>
<li><b>List the fields you want.</b> Some government databases are hugely complicated, with lots of tables that relate to each other. To get around their weirdness, specify exactly the records you're after. When possible, of course.</li>
<li><b>Dealing with known unknowns</b>. If you know there's a database, but you don't know exactly what's in it, you can request what is variously called a "record layout" or "data dictionary" &mdash; basically, a table of contents for your data file.</li>
<li><b>Use our handy records request generator</b>, which has sample language for Iowa, Nebraska and FOIA requests.</li>
</ul>

<img src="https://github.com/OWH-projects/data-literacy/blob/master/rr.png" style="max-width:100%; border:1px solid #ccc;" />

## Checking your data
Don't make any assumptions about your data. Unless your assumptions are that the file is dirty or incomplete or otherwise imperfect, in which case assume away!

Make sure you understand how your data is created. Is it input by humans? Expect typos. By machines? Expect machine dumbness. Understand why your data exists and what it's supposed to do. Motives are an indicator of biases, and can evolve your understanding of your data considerably.

Approach data the same way you'd approach an unknown source who wants to meet you in a bad part of town: With caution. Maybe you'll end up with a great story. Or maybe you'll end up with a screwdriver in your neck and an empty wallet. Or &mdash; worse &mdash; a correction.
<img src="http://media.giphy.com/media/4XL512RWMdtZK/giphy.gif" />

Point is, be paranoid. Run sanity checks on your data, then run them again. Sort, filter and Group By to look for outliers. Check datatypes using =isNAN() and other such functions.

If you find an outrageous value ("There's a home in Sarpy County worth $5 million?!"), check it out. Pick up the phone. Talk to the human who collects or analyzes the data. Sometimes, the outlier you find is a story. More often, it's a typo, or you don't understand the data yet. ("Oh. There's an entire subdivision in Sarpy County worth $5 million that, for tax purposes, is treated as a single parcel.")

## Links
<ul>
<li><a href="https://github.com/propublica/guides/blob/master/data-bulletproofing.md">ProPublica's guide to bulletproofing data</a></li>
<li>Book: <a href="https://books.google.com/books?id=oFtNBQAAQBAJ&lpg=PT85&dq=the%20art%20of%20access">The Art of Access</a></li>
<li><a href="http://ire.org">Join IRE/NICAR!</a></li>
<li>PDF: <a href="https://github.com/OWH-projects/data-literacy/blob/master/pdfs/finding-documents-and-data.pdf">Finding documents and data</a></li>
<li>PDF: <a href="https://github.com/OWH-projects/data-literacy/blob/master/pdfs/negotiating-tips.pdf">Negotiating for data</a></li>
<li>PDF: <a href="https://github.com/OWH-projects/data-literacy/blob/master/pdfs/data-resources.pdf">Roundup of data sources</a></li>
<li>PDF: <a href="https://github.com/OWH-projects/data-literacy/blob/master/pdfs/data-driven-story.pdf">Seeing a data-driven story through to the end</a></li>
</ul>
