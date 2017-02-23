# ```iOS``` Interview Dry Run

**What have you learned about building ```iOS``` apps?**

In the past year, I have learned a lot. Importantly, one of the best parts about being an ```iOS``` Developer is that you can utilize the ```Swift``` programming language to fit your needs by using different methods of code. This gives you plenty of freedom in order to reach your creative goals. 

Learning how to use ```Git``` and ```GitHub``` has complimented my role as a developer. Often I make commits, generate pull requests and revert commits in order to add better value to my projects. This has not only made it more efficient for me to succeed at any project I undertake, but it has helped projects run more efficiently when working in group settings.

**Can you talk about a framework that you've used recently (Apple or third-party)? What did you like/dislike about the framework?**

Recently, I’ve used the framework ```MapKit```. I learned this by studying the documentation, video tutorials and self-practice. 

The thing that draws me the most about this framework is that there are numerous capabilities of reaching information and content. Instead of getting one piece of information, you’re essentially sending or receiving information that goes beyond an ```iOS``` device. I do dislike how this framework may need third party dependencies in order to innovate with your project. It’s not necessarily an easy framework to use if you plan on innovating with ```MapKit```.

**Describe how you would construct a Twitter feed application that at minimum can display a company's Twitter page. Please include information about any ```classes/structs``` that you would use in the app. Which ```classes/structs``` would be the model(s), the controller(s), and the view(s)?**

In order to create a Twitter feed application for a company’s Twitter page I would use ```Twitter’s API```, ```Core Data```, ```Collection Cell```, ```Outlets``` and ```Image Views```. 

Overall, I would set up a ```Table View Controller``` that has a ```Table View Cell``` embedded. This would store Tweets sent out by the company. I would also have a refresh button in order to update any tweets by the company. Additionally, I would create labels that would represent the tweet and an image, if applicable. I would also create functions that represent showing a Tweet, ```Parsing``` the data and refreshing the information when necessary. 

**Describe some techniques that can be used to ensure that a UITableView containing many UITableViewCell is displayed at 60 frames per second.**

By implementing delegate and data source methods to our Table View Cell, we can use ‘numberOfRowsInSection” in order to customize our information when a Table Cell is demonstrated. This can display how many cells of information appear at once. I would also implement “cellForRowAt indexPath” and “didSelectRowAt indexPath” in order to store any additional information as an Array in the view. Doing these methods, would help execute of viewing cells at 60 frames per second. 

For example, when specifying code in “numberOfRowsInSection”, this would indicate how many rows you’d like to appear. For example, in my project ‘OnTheMap’, I wrote:

```if UsersInfo.UsersArray.count>100 {
return UsersInfo.UsersArray.count
}
else {
return 100
}
}```

This would appear no more than 100 rows in the ```Table View Cell```. Depending on the information you’d like to provide with it and how you would like to customize it, you could also implement ```didSelectRowAt indexPath``` or even ```cellForRowAt indexPath```.  

**Imagine that you have been given a project that has this ```ActorViewController```. The ```ActorViewController``` should be used to display information about an actor. However, to send information to other ```ViewControllers```, it uses ```NSUserDefaults```. Does this make sense to you? How would you send information from one ```ViewController``` to another one?**

This does not make sense for the fact that ```UserDefualts``` is only best when used to store simple user settings. For example, it would be used best when storing names, addresses or other information that doesn’t require a lot of storage. 

Considering the information being sent between ```View Controllers``` contains lots of information about an Actor, I would use ```CoreData``` instead. By using ```NSManagedObject```, I can store majority of all the data for the project. Afterwards, I would create a segue in code using an identifier to transfer the data between ```View Controllers```.  

**Imagine that you have been given a project that has this ```GithubProjectViewController```. The ```GithubProjectViewController``` should be used to display high-level information about a ```GitHub``` project. However, it’s also responsible for finding out if there’s network connectivity, connecting to GitHub, parsing the responses and persisting information to disk. It is also one of the biggest classes in the project. Follow-up question:: How might you improve the design of this ```View Controller```?**

In order to improve the design of the ```View Controller```, I would add a ```Table View``` with ```Table View Cells```. Inside the ```Table View Cell```, I would insert four labels. These labels would represent the title of the project, the ```GitHub``` repo web link, an error/connected message and a complete button that allows users to know the information persisted to the disk. 

In addition, I would create a new ```.Swift``` file that strictly contains the networking information for the project. This would help separate the outlets and actions within the actual ```View Controller```, while keeping the ```networking/API``` code separate. This would make things easier to read and more organized. 

**If you were to start your ```iOS``` developer position today, what would be your goals a year from now?**

In a year from now, I hope to contribute to projects that support innovation and helping others. In order to achieve this, I would continue to learn new strategies in order to compliment the knowledge I already am aware of. I’m a big believer in practice makes perfect and I know as long as I keep an open mind to new information, while I continue to practice, that I’ll be able to meet goals and apply creative decisions to any project I undertake. 

In order to be a great asset to any company or project, I strongly encourage anybody to involve themselves in whatever they are passionate about and the values they share. Indefinitely, I will be working for someone who compliments these things when it comes to my personal passions and values. This will not only allow me to succeed, but exceed expectations within myself as well as with the client. 





