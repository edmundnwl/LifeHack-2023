# TryingOurBest | LifeHack 2023

## Problem Statement
### Theme: Revolutionizing the Workplace 
A mundane career can be both fulfilling and exciting in a virtual and innovative workplace setting. Design an application which allows employees to seek joy in their work and offers practical benefits.

## Product
Introducing Offun: Connecting People, Empowering Collaboration

At Offun, we're passionate about creating a vibrant and engaging work environment where employees can connect, collaborate, and have fun together. Our app is designed to revolutionize the way teams interact and socialize within the company, making work more enjoyable and productive. With a range of exciting features and a user-friendly interface, Offun empowers employees to build strong relationships, plan meetups, seek assistance, and collaborate seamlessly. Get ready to experience a whole new level of workplace engagement with Offun!

Key Features That Bring Joy and Productivity to Your Work:

Group Filtering: Offun allows you to tailor your experience by joining specific groups based on departments, projects, or shared interests. This ensures that you receive relevant updates, posts, and discussions that matter most to you. Connect with like-minded colleagues, share insights, and stay informed within your professional circles.

Socializing and Meetup Planning: We believe that fostering personal connections is essential for a thriving work environment. With Offun, you can easily organize social events, plan meetups, and create lasting memories with your co-workers. From after-work happy hours to team-building activities, our app makes socializing a breeze.

Collaborative Forums: Offun provides a dedicated space for collaboration, where you can tap into the collective knowledge and expertise of your colleagues. Seek advice, share ideas, and collaborate on projects through our interactive forums. Together, we can break down silos and unlock the full potential of teamwork.

Scam Awareness: In our commitment to creating a safe and secure environment, Offun incorporates a unique feature that raises awareness about workplace scams. Through carefully simulated pop-ups, we aim to educate and empower users to recognize potential scams. If you encounter a simulated scam, rest assured that it's a valuable lesson to help you stay vigilant and protect your account from real threats.

Join Offun today and unlock a world of connections, collaboration, and endless opportunities for growth. Let's make work not only productive but also enjoyable and fulfilling! Together, we'll create an Offun-filled workplace experience like never before.


## Testing
1) Download the folder "LifeHack 2023"
2) You may need to download packages used:
    - pip3 install flask
    - pip3 install flask_sessions
    - pip3 install cs50
3) In your terminal type: flask run
4) The terminal should prompt you that the app is now running, you can view the app by clicking on the link provided.


## Tech Stack
- Python Flask
- HTML
- CSS, Bootstrap
- JavaScript
- Jinja
- SQLite

Offun is a web app built on python flask. Its database of users, posts, and groups are stored in SQLite tables. The queries used to create the tables can be found in the folder under the file titled 'random.txt'.

## Plot Twist
As a form of plot twist, a random chance was given for a scam pop-up to appear on the user's screen when he is navigating between pages. The pop-up is obviously a scam due to its poor formatting and ridiculousness. A user that is aware of such scams will be able to identify it and safely close it by clicking the 'back' button. Else, if the user were to 'claim his prize' he will be immediately logged out and their account suspended as they are clearly not well versed in such scams and should promptly be blocked from using the app for the sake of cybersecurity of the user and the company.
