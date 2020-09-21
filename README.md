# SMS-BirthdayWisher
<p> This python program will wish your friends at 12 am on their birthday by sending a SMS. </p>

# Developed Using:
<ul>
  <li> python 3.8.4 </li>
  <li> openpyxl module </li>
  <li> twilio module </li>
  <li> time module </li>
  <li> datetime module </li>
</ul>

# 1. Installing & Requirements:
<p> Clone the tool if you have git installed. </p>
<b> <ul> Git Installation Guide: </b>
  <li>Windows - https://git-scm.com/download/win </li>
  <li>Linux - https://git-scm.com/download/linux </li>
  </ul>
Then run these command in the Command Prompt or Terminal.

```
git clone https://github.com/satya-root/SMS-BirthdayWisher/
cd SMS-BirthdayWisher
pip install -r requirements.txt
```
<p> <b>        OR </b> </p>
<p> Download from the link: <p>
Then, run these command in the Command Prompt or Terminal.

```
cd SMS-BirthdayWisher
pip install -r requirements.txt
```
# 2. Configure the excel file (DB.xlsx) for the birthdays.

# 3. Create your account in Twilio: 
<p> Follow This: https://www.twilio.com/docs/usage/tutorials/how-to-use-your-free-trial-account </p>
<p> Add the numbers to which you want to send SMS (Phone Numbers Used In DB.xlsx): https://www.twilio.com/console/phone-numbers/verified </p>

# 4. Usage:
<p> i.   Add your Account SID and Auth Token to main.py from: https://www.twilio.com/console </p>
<p> ii.  Give the path of DB.xlsx in main.py </p>
<p> iii. Run the python file (main.py) </p>
  
<p> Or type the command in terminal/command prompt: </p>

```
python main.py
```
