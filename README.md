![](http://ForTheBadge.com/images/badges/made-with-python.svg)
![](https://forthebadge.com/images/badges/built-by-developers.svg)</br>
[![Prettier](https://img.shields.io/badge/Code%20Style-Prettier-red.svg)](https://github.com/prettier/prettier)
![Size](https://img.shields.io/github/repo-size/Iamtripathisatyam/Push_Notification_to_your_Phone?color=red&label=Repo%20Size%20)
![](https://img.shields.io/tokei/lines/github/Iamtripathisatyam/Push_Notification_to_your_Phone?color=red&label=Lines%20of%20Code)</br>
![sds](https://profile-counter.glitch.me/{Push_Notification_to_your_Phone}/count.svg)


Let's have a look at the step-by-step implementation:

- Set up a Pushbullet account on your PC and Phone
  - For PC
    - Go to [***Pushbullet.com***](https://www.pushbullet.com/)
    - Create an account
  - For Phone
    - Install the Pushbullet app on your phone.
    - Log in using the same email address that you used to log in to your PC.
- Let's begin applying this script once we've set up the account on both devices.
  - Install the following modules listed below
  
    ```python
    pip install pushbullet.py==0.9.1 # Used for sending the Push notifications.
    pip install pywebio # Used for the interface at the output window.
    ```
  - Import the following modules
    ```python
    from pushbullet import PushBullet  # pip install pushbullet.py==0.9.1
    from pywebio.input import *  # pip install pywebio
    from pywebio.output import *
    from pywebio.session import *
    import time
    ```
  - Go to [***Pushbullet***](https://www.pushbullet.com/#settings/account) and obtain the ***access token***.
  - Get your Access Token and use the PushBullet method to create an instance by providing the Access Token in the PushBullet function.
  - Use the ***push_note*** function to send data and text inside the function. push_note will take two arguments i.e. data and text. the first argument will work as a Heading in the notification where second argument is a text.

### Output #1: 
<p align="center"><img width="80%" src="https://user-images.githubusercontent.com/69134468/127794809-134071ad-f607-45c1-815e-301b0bb961f4.gif"></p>

### Output #2:
<p align="center"><img width="20%" src="https://user-images.githubusercontent.com/69134468/127794951-3a0aea84-2162-49e0-9387-8987e0bd35d9.jpg"> <img width="20%" src="https://user-images.githubusercontent.com/69134468/127794984-3305be55-c41b-46bd-9ee3-24acfbc002ed.png"></p>
