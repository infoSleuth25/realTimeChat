# Real Time Chat Application

Build a simple chat applications using raw websockets in Node.js that supports the following features :
- Allow an admin to create a new chat session/room. Admin should be allowed to set the following properties on the room.
- Name
- start_time
- is_open
- cool_down_time : People cant do spam messages
- Allow a users to join the room and send messages
- Allow users to upvote chat messages.
- If chat messages reach more than 3 upvotes, move them over to a saparate section.
- If chat messages reach more than 10 upvotes, alert the admin to answer.


- People are rate limiting : 30s - 1 msg per 30 seconds.
- Upvoting : Filter out questions.
- 10000 or greater subs : We tend to do distributed web socket server.
- In our case it is less than 10000, we will make simple web socket server.

