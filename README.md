For the Anubis interviews we are giving out a little assignment to everyone so that you can flex
your proverbial programming muscles. You can make this as simple or as complicated as you
would like. Take a few days to work on this, and we can schedule an interview when you are ready.

# Project Proposal

We want you to create an http server that you can upload, list and download files from. You
don’t need to worry about authentication or anything like that. You also don’t need to worry
about dressing up the website with any fancy react/css elements. *Really what we want to see is
how you approach and solve the problem.*

This is purposefully open ended. You can use whatever framework or language you are
comfortable in. If you do not have a preferred framework, flask is a pretty reasonable choice.
You can use docker to break your system down into microservices if that is your speed. You can
even use kubernetes to get really fancy if you would like.

> Use whatever tutorials, quickstarts, stackoverflow stuff you need. There is pretty much no part of
> this project that you could not find some example or forum post online for.

_Do not worry about deploying this application anywhere._

# But wait, there is a catch!

**The only hard requirement for this project is that you store the files in a database or object store, 
not in a filesystem.** This is a pretty standard practice when making files available in a distributed system.
For your database you can use something simple like sqlite, or use a database server like
postgresql or mysql. Pretty much every database system has something along the lines of a
BLOB or LARGEBINARY type where you can store binary data. Just make sure it can handle
reasonably large files (let’s say at least a couple MiB).

For your database you can write the raw sql, or use something more complicated like
sqlalchemy. We would even accept an application that uses the google sheets api as a
database! (that is a joke, plz don’t do that)

> Don’t overthink it!

**Please do not feel obligated to learn systems or technologies that are more complicated
than you are comfortable with.** You could fulfill the requirements for the project with a single
page of php.

If you cannot solve the problem in a reasonable amount of time, it is ok to reduce the
requirements. *This is not meant to stress you out.* If you can’t make it happen, that is OK! Just
do whatever you can.

# The Repo

Create a repo on either github or gitlab to put your work on. If it is public or private, it does not
matter too much. If you do make it private, please share it with `wabscale`,
`synoet`, and `GusSand` when you are ready to share your work. Those github usernames are for John
Cunniff, Teo Nys, and Gustavo Sandoval.

Thanks for your interest in working with us!! We are really excited that you can join us!!
