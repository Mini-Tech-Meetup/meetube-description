# meetube-description
Junction X Seoul Project
![image](https://user-images.githubusercontent.com/10369528/95670230-8605fe00-0bc3-11eb-9b44-d950a4cbb9be.png)


Meetube is Meeting Record Manage System for Collaborate

## Why need meetube?
1. Check saved meetings

2. Automatic meeting analysis

3. Meeting Record Search


## Architecture
![image](https://user-images.githubusercontent.com/10369528/95670287-23f9c880-0bc4-11eb-9b7f-353639fda4fb.png)


## Descrption
#### Describe the problem it solves
Due to the Corona 19 this year, many companies are working at home. As a result, meetings are also being held online. However, it is difficult to record all the meetings and proceed with them. This is because active participation in meetings is not possible, such as talking while writing notes. It is also not easy to grasp and record everything if the meeting is prolonged, even if you actively participate in the meeting. Therefore, we wanted to record an online meeting and analyze and summarize the contents of the entire meeting based on this video.
#### What real-world impact it has
For the above reasons, when conducting an online meeting, each person takes turns to take charge of the minutes, and the person focuses only on the minutes. This project will reduce the burden of recording minutes and allow everyone to focus only on meetings. In addition, after the meeting, it will be easy to find out what you don't remember in detail or what you need to check again.
#### What technologies you used to make it
+ React
+ Spring boot
+ Postgresql
+ Azure Blob
+ Azure Video indexer
#### Future plans regarding the project
Although it was not implemented during this hackathon, we would like to search for content through speaker name or time as well as simply analyzing the entire contents in the meeting video. In addition, we want to recognize the faces of the participants in the meeting and search the contents through their faces. This will allow everyone to focus on meetings without worrying about records by creating a meeting record management program.


## QnA
### Where is the related repo?
[meetube-api-server](https://github.com/Mini-Tech-Meetup/meetube-api-server) : spring boot / kotlin

[meetube-react](https://github.com/Mini-Tech-Meetup/meetube-react) : react / JS

### Status
| Catagory | Action                   | Status     |
|----------|--------------------------|------------|
| UI       | Front End UI/UX          | almost...? but have some error |
| Logic    | File Upload              | O          |
|          | Search Video             | O          |
|          | View Detail Video        | O          |
|          | Play Video               | O          |
| Storage  | DB Save                  | O          |
|          | Azure Storage Save       | O          |
| AI       | Keyword Generate         | O          |
|          | Full Contents (Captions) | O          |
|          | Thumnail Generate        | Not Yet :( |
|          | Auto Summary             | Not Yet :( |

### Devloper
|                     | Front-End          | Back-End                     | Etc                 |
|---------------------|--------------------|------------------------------|---------------------|
| 고세원 (dream365)   |                    | DB Access Docker ServerLogic | Back-End Manager    |
| 백종현 (JHyunB)     |                    | AI                           | Video Indexer       |
| 장준영 (JunYoung7)  | View Search Detail |                              | Front-End Manager   |
| 이원준 (Lee-WonJun) | Upload File        | Server Logic                 | Azure/Video Indexer |
