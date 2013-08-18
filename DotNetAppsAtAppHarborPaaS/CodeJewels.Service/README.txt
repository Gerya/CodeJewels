http://localhost:8826/api/codejewels -- Listing all Code Jewels
http://localhost:8826/api/codejewels?sourceCode={term} -- Searching for some code.
http://localhost:8826/api/codejewels?sourceCode={term}&category={name} -- Same as above but including category name.
http://localhost:8826/api/codejewels/upvote/{codejewelId} -- Upvoting some jewel.
http://localhost:8826/api/codejewels/downvote/{codejewelId} -- Obviously the opposite of the above description.
http://localhost:8826/api/codejewels/create -- Uploading new jewel

Code jewels with negative rating are automatically deleted.

Enjoy!