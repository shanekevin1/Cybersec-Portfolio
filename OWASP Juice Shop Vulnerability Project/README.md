Worked in a collaborative student group to investigate, identify, and exploit real-world web application vulnerabilities using OWASP Juice Shop

The objective was not just to solve the challenges, but to analyze, document, and explain the security weaknesses in each vulnerability

<img width="600" height="343" alt="image" src="https://github.com/user-attachments/assets/0fbb5054-655d-4a8d-9f48-f5519e668436" />

I launched OWASP Juice Shop through Kali Linux when it was running in my Oracle VirtualBox VM

An example of an exploit I tested was called 'Login Amy' as a challenge in Juice Shop. 

I identified a significant flaw in the "Sensitive Data Exposure" feature. This vulnerability feature is just basically about the app didn't do enough to protect Amy’s private login info

The root cause of this specific vulnerability is just bad password management. The system didn't force the person to pick a strong password


  1. Using clues from the challenge description, I researched Gibson Research’s 'Password Haystacks' article and found the example password pattern 'D0g.............'

<img width="602" height="555" alt="image" src="https://github.com/user-attachments/assets/8b944b9a-332e-4194-b169-1bffa67962e4" />
<img width="601" height="162" alt="image" src="https://github.com/user-attachments/assets/e2e070e2-cba0-47cf-b66e-f03940494a49" />


  2. With the 'D0g..........' clue and Amy's email, it was invalid at first but Juice Shop provided another clue, saying "Did you know that Amy is married to an alien named K1f?". I then wrote K1f instead of D0g

  <img width="601" height="351" alt="image" src="https://github.com/user-attachments/assets/7ccc4ff4-97cb-4571-98a0-bf9e56d2e267" />
  <img width="281" height="311" alt="image" src="https://github.com/user-attachments/assets/a30996de-d54c-4a71-b3f7-fca772f04c35" />

  3. Entering Amy's email alongside this password was correct and I am signed into Amy’s account.

The image below shows the completed vulnerability challenges I completed for this project
<img width="597" height="286" alt="image" src="https://github.com/user-attachments/assets/ae522310-3264-4323-96f7-73bfcaaae3a3" />
