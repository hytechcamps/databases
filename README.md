# Storing Information with Databases
In this workshop, students will explore the fundamental concepts behind databases, and then practice creating and updating a database of their own. They will learn about relational databases, SQL, NoSQL, and the importance and impact of databases in modern society. By the end of the workshop, each student will have access to their own database, and will be able to interact with it in multiple ways.

### Student Content
Student-facing content is available at [hytechcamps.github.io](https://hytechcamps.github.io/databases).

### Agenda
Here are some general guidelines for the overall flow of the camp:

| Activity | Time |
|-|-|
| Icebreaker | 30m |
| Presentation | 15m |
| Interactive Activity | 10m |
| Break | 10m |
| Follow-Along | 40m |
| Gimkit | 10m |
| Conclusion | 5m |

### Tips
Here are some tips to ensure a successful run:

- Before the camp, **read through this lesson plan thoroughly**
- During the camp, ask the students questions as often as possible
    - Ask for their names, hobbies, favorite things... anything!
    - Ask for suggestions about what to do next
    - Poll them to see what they know, or what they'd like to do
- Make sure to turn off notifications for Teams, Outlook, etc
- Make sure to zoom in properly on small parts of the screen
- Encourage students to make their own choices in the project
    - The more they personalize things, the more fun they tend to have!
- Take it slow at first, and always check to see how the students are progressing
    - Don't trust them to tell you; make sure to actually have an assistant look at their screens and give the go-ahead
    - Give students time to catch up before moving too far ahead, but...
    - Don't stall too long on any one part

## Camp Outline
The entirety of the camp flows through the [PowerPoint Presentation](Databases.pptx).

### Icebreaker
Have students submit movie reviews using a web application powered by MongoDB. Once all students have added reviews, they will introduce themselves.

#### Setup
The URL for the Movie Reviews site is [https://movie-reviews-62s1.onrender.com/](https://movie-reviews-62s1.onrender.com/) - students can access this by clicking the link from the [camp homepage](BOOKREADME.md). Make sure to visit the site _before_ the camp begins - it usually takes a minute to get up and running.

If there are reviews, you can delete them by clicking on the "Action" table header, entering "allowthis" into the prompt, and clicking the "Delete" button next to reviews. Add one or two reviews in there to start.

Additionally, log into [MongoDB](https://cloud.mongodb.com/account/login) using these credentials:

- Username: **techoutreachinstructor@gmail.com**
- Password: **Tech0utreach!**

Under the **Clusters** section, click the **Browse collections** box and select the **reviews** collection in the **movie_reviews** database. This is where all the reviews should appear, and they can be manually modified from here.

#### Facilitation
Start by directing the students to the [Movie Reviews Site](https://movie-reviews-62s1.onrender.com/). Have each of them submit a review, making sure they enter their full name as the reviewer. If they have never seen a movie, they are welcome to review anything else.

Once a good number of reviews have been added, go around the room and have each student introduce themselves with their name, grade, school, and which movie they reviewed.

After all of the students have been introduced, head to the Atlas UI to show what the data looks like behind the scenes - show how it can be [viewed, modified, and filtered](https://www.mongodb.com/docs/atlas/atlas-ui/documents/). Don't worry about explaining it too much - the presentation is next!

### Presentation
After students have warmed up with the icebreaker, it's time for the presentation portion of the [PowerPoint](Databases.pptx). These slides contain a brief introduction to data and databases, including SQL and NoSQL design approaches. There are notes with talking points in the slides.

### Interactive Activity: SQLBolt
Direct students to the [camp homepage](BOOKREADME.md) where they can find a link to [SQLBolt](https://sqlbolt.com). Encourage them to read through the guides, and attempt to complete as many lessons as possible before the break.

### Follow-Along
Walk through the [Follow-Along Activity](FollowAlong.md) with the students. They should create and deploy their own cluster in MongoDB Atlas, and then connect to it through a web application.

#### Starter Project: Web Application
[Click here to remix the web application project on Glitch.](https://glitch.com/edit/#!/remix/posts-db)

#### Back-up Connection String
If a student is _really_ struggling to follow along with the activity, this connection string can be shared with them. Replace `<username>` with `ezekieljohnson`, and `<password>` with `eM4OPS9FdgsAVLpV` in this string:

```
mongodb+srv://<username>:<password>@cluster0.6haikte.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
```

### Gimkit
[Gimkit](https://gimkit.com/) is a fun formative assessment tool that's similar to Blooket, but with some different game modes. Just like Blooket, there are a variety of modes where the students compete against each other in different ways. Answering questions correctly helps them achieve more success in each game.

An account is required to host the game; here are some credentials you can use:

- Username: **techoutreachinstructor@gmail.com**
- Password: **Tech0utreach!**

When setting up the game, try to time it so that it ends just a couple minutes before the camp ends. Note that it will likely take 2-3 minutes for all the students to join the game, so a game time limit of **7 minutes** might end up taking about **10 minutes**.

1. Go to the [Gimkit Login Page](https://gimkit.com/login)
1. Enter the credentials above
1. Find the [**Databases** question set](https://www.gimkit.com/view/66464769fa43d1810473acde)
    - If it appears in the list, click the green "Play Live" button
    - From the set page, click the "Play Live" link on the left side
1. Select one of the freely-available game modes
1. Adjust the time as needed, but keep everything else the default
1. Click the **Continue** button
1. Instruct students to go to **gimkit.com/join**, enter the code and a nickname, and join the game
1. Once all students have joined, click the **Start Game** button

From there, the students will work on their own, answering questions and trying to win the game!

## Conclusion
Make sure to close out the camp on a strong, positive note of encouragement. Here are some key points to hit:

- Thank the students for participating
- Encourage them to continue learning about databases on their own
- Tell them they can reach us at **techoutreach@hyland.com** if they have any questions or would like any guidance
- Send them on their way!
