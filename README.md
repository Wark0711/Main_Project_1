# Main_Project_1
In this, there is a JSON file of fake data of 1000 users consisting of id,username, country, age, occupation, car details, etc.

Due to some reason which I don't know, faker.js and react virtualised didn't installed on react app. So I actually divided the project in 2 parts.

In first part, first I used script as module type to create fake data using import statement of faker.js.
Then I used reduce() function to create a date where I arranged users on the basis of the country they live in.
Used same function to arrange for other 2 parameters.

Then there is a bar chart of users where users live. To make sure that bar chart looks okay, I restricted the amount of countries to 20 only.
Further, 2 pie charts in which we can vary those charts on basis of users' age range. This means we can adjust the data of charts for users of age shown in given options.

Now on second part, I created a list of 1000 users with id and username using React Virtualised. On clicking these list items, we can obtain full information of the user.
Then I made a list of Car Manufacturers and their models. On clicking them we obtain a list of all users using that car manufacturer and its model resp.

I tried to obtain data of 100000 users but neither any online compiler allowed to copy that data to create json file, nor NodeJS allwoed to run faker.js module to obtain fake data of that many users

Hope that the project is good

Thank You
