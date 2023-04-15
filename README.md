My app is using React as a front-end and i have my server.js file as a back-end from previous assigment.

My app is in 4 components and main component App.js, delete component is build in getall.js and search.js, when you get the data, app will create delete component for each datapoint.

I have a "show all data" button, which will get all data from the mongodp database, with data and ID:s

I have a search bar, where you can use id to find spesific data.

I also have create data component, where its easy to add new data to database.

And update data, where you can update data using the ID of the data you want to update.

I used CSS in Default.CSS file and imported Default.css in each component, so it was easy to use same styling in all components.

Everything works perfectly locally, front-end, back-end and mongodp. Zero errors or problems.

Render deployment backend only works if i put the server on with command "node Server.js".
I tryied close to 10 different solutions for this problem, but nothing worked, 
i even tryied new builds entirely and different github repositories. I just have to start locally the server and the depoyment works.

I deployed the app in Render, here is the link: https://api-react-dtq8.onrender.com 
