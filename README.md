Hellow world! 

So I guess I finally decided what to do with this blog. This is going to be only for me to kind of clear out my thoughts and journal what I am doing.

Since the start of the year I decided to get involved in bug bounty hunting (more serious this time, not like the script kiddie I was), and I want to document everything as much as possible here.

As with any good bug hunter, I want to develop my own set of tools that can help me get closer to my goals. First stop is a recon database.

I want to store my recon data nice and clean into a database that I will have access to anywhere anytime, and update it on a regular basis. For this I am going with MongoDB and later down the road I will be deploying my own API on top of it for ease of access and a lil swag lol :)

For now I will document the steps I've gone through to start with the database. (Btw I will be using "booking.com" in my recon which is a public program at HackerOne)

<h1>Start</h1>
<li>Created a mongodb cluster in mongoAtlas </li>
<li>Created a database named `assets` and the first collection as `booking`</li>
<li>Created an admin user with a password, gave it an atlasAdmin role for highest permission</li>
<li>Under the “Network Access” added IP address of “0.0.0.0/0”  </li>
<h1>Connection</h1>
