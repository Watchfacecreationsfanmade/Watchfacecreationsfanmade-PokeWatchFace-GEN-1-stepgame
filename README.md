# Pokemon Watchface Daily FireRed/LeafGreen simulation
Pokémon FireRed/LeafGreen watchface for Wear OS. Your Pokémon party changes daily, and you level up your Pokémon by taking steps. Every 200 steps is 1 level. 50 Generation 1 Pokémon, including their levels and evolutions, are in the watchface as your possible party. Every night at 00:00 your story resets, and you will start over with a new team. As your time and level progress, your story through Kanto will too. It brings you back to the Game Boy; all the gym leaders, rival battles, and the Elite Four are in the story.
- Shinies are included as well. A few times a year, one of your Pokémon will be shiny for the whole day.
- Legendary Pokémon and fan-made post-story content unlock after 12.5k steps.

Pokémon sprites and pokemon battlefield with realistic elements, without giving up watch face functions. A glance at the watch face will give you the following information:

<img width="462" height="1000" alt="image" src="https://github.com/user-attachments/assets/3780e3c7-c4d3-42b4-b815-a8bc6309a06b" />

- Time in digital
- Battery status is represented by the enemy Pokémon's HP bar.
- Your Pokémon's level is determined by your step counter ($200\text{ steps} = 1\text{ level}$, e.g., Level 16 = 3,000 to 3,200 steps). The experience bar shows your progress between levels (e.g., at 3,100 steps, the bar is half full toward Level 16).
- Heart rate 
- Date is shown as your Pokémon's HP numbers (formatted as MM/DD).
- Your Pokémon's HP bar slowly decreases over time and can only be restored by taking steps. This encourages you to stay active throughout the day! If your activity level is too low for that time of day, you will "faint" and end up in the Pokémon Center with Nurse Joy!
- Real-time temperature changes your Pokémon's status condition (e.g., "BRN" (Burn) appears if the temperature rises above 23°C).
- The battle weather changes dynamically based on your local, real-time weather (supporting rain, sunny days, and more).
- Background of the battlefield changes with the story (e.g. water battlefield in Misty Fight) so the watchface wont bore out as fast.

The Always-On Display (AOD) shows your progression for the day. It does this by showing the gym badges you have earned that day. Roughly 1,000 steps per badge means 8 badges earned equals 8,000 steps, perfectly aligning with your daily activity. Going for a good walk that day will allow you to reach the Elite Four. After earning all eight badges and beating the Elite Four, the AOD will showcase your daily team, just like in the Hall of Fame!


<img width="462" height="1000" alt="image" src="https://github.com/user-attachments/assets/3f2b8444-3002-4ce5-b1b6-7a59772ab832" />

I have also designed post-game content for after you beat the Elite Four. You will battle the Legendary Pokémon of Kanto, which will appear as small sprites on your AOD once defeated. After the Legendaries, I have added some logical, fan-made post-story content. I don't want to give everything away—you will have to go for a good walk to see it for yourself!

I have put the download link for the APK file on this page. I hope you will enjoy it as much as I enjoyed making it!
Please feel free to give feedback on this project—I would really love to hear about your experience with the watch face in general! Leave a message in the Discussions tab!


## DOWNLOAD LINK:
com.watchfacestudio.RPGwalkthrough.apk



Because I made this in Samsung's Watch Face Studio, you will need to sideload it onto your watch. Here is a quick guide made by AI:

## 📥 How to Sideload (Quick Guide)

Step 1: Connect your phone and your watch to the same secure and trusted Wi-Fi network 

Step 2: Depending on the brand of your watch, the steps may vary slightly. 

If these steps do not match your specific watch type exactly, look up instructions for your model on Google.

Put your watch in Developer options.

Samsung: Go to the watch’s Settings > About watch > Software information and tap 7 times on 'Software version'. The watch is now in Developer options. 

- Go back to Settings, and Developer options should be the lowest option.
- A. Enable ADB debugging.
- B. Enable Debug over Wi-Fi.

Step 3: Your watch should automaticly connect to your WII network. That could take a few minutes. 
if not connected to wifi yet:
For Samsung: Go to Settings > Connections > Wi-Fi and enable it and connect with your WIFI.

Step 4: Download the watchface as APK file from this GiTHub and download the app Bugjaeger on your phone.

Step 5: On your watch, go to Developer options > Wireless debugging and select Pair new device. You will see a screen showing a Pairing Code, an IP address, and a Port number.
On my pixel watch it looks like this:

<img width="473" height="1024" alt="image" src="https://github.com/user-attachments/assets/9d9e4a4d-2d36-4bbc-95d0-58bab487262f" />




Step 6: In the Bugjaeger app on your phone,  tap the plug icon with the plus sign (+) in the top right corner and select Pair.


<img width="235" height="488" alt="image" src="https://github.com/user-attachments/assets/f27cfff9-26d9-42e8-a0a6-d14c32434f89" />

and select Pair:

<img width="459" height="713" alt="image" src="https://github.com/user-attachments/assets/e143afea-63e3-49b3-966d-82532bdd690e" />

Fill in the fields exactly as shown on your watch screen:

<img width="459" height="838" alt="image" src="https://github.com/user-attachments/assets/e880ebb8-2109-4e37-a9e9-43fe4410a920" />

Step 8: Next enter the details from your smartwatch.
Using the example photos, that would be:

IP address: 192.168.1.45

Port: 41235

Pairing Code: 482091

Your watch should now be successfully paired with your phone.

Step 7: A second box should pop up with filled in IP Adress and portnumber. simply press 'connect'

IF that box doens't show automaticly follow these steps:

Tap the plug icon in the top right corner once again, but this do not tap tap pair but fill this screen the IP adress (should be unchanged) and Port number..

<img width="462" height="1000" alt="image" src="https://github.com/user-attachments/assets/204e336e-9505-4c9a-8bbe-7b34c2a797b5" />

On your watch's Wireless debugging screen, an IP address and Port should be visible. Enter these numbers into the connect prompt. Do not go back to the "Pair new device" screen; if you use the pairing codes page for this step, it will not connect.

Your watch should no be succesfully connected to you phone!

step 8: Tap the plus sign (+) at the top of the Bugjaeger app, as circled in the photo. 

<img width="238" height="496" alt="image" src="https://github.com/user-attachments/assets/9e5c3b41-f5e9-4cb6-8805-adeeac683dd0" />

Tap Select APK file and choose the APK file downloaded from this GitHub link. The watch face will now be installed on your watch.

Once this process is successfully completed, the watch face will be on your watch!

step 9: close developer mode on your watch. it drains energy. Go to settings, developer mode . turn it off. (wifi will turn off aswell)


For me, it shows up directly in the list of watch faces. However, it is possible that you will need to go to your watch faces, select "Add extra," and you will find it listed there.

Have fun with the watch face! May you make it into the Hall of Fame as often as possible. Let me know what your experiences are!
