# User Journey Map: BeReal Behavioral Matrix
**Date:** May 30, 2026  
**Author:** Zipphora Platania <br>
**Role:** Product Management Extern (Product Quality & UX Focus)  

## Executive Summary
This matrix maps out the user behavioral lifecycle across BeReal's core journey stages. By documenting exactly what a user does, thinks, and feels, we can anticipate user friction points, isolate potential edge cases, and design highly targeted manual test cases.

---

## 🗺️ The Behavioral Matrix

<table border="1">
  <thead>
    <tr>
      <th style="width: 20%;">Stage</th>
      <th style="width: 30%;">What does the user do?</th>
      <th style="width: 30%;">What does the user think?</th>
      <th style="width: 20%;">What does the user feel?</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Stage 1: Core Onboarding & Activation</b></td>
      <td>
        1. Downloads BeReal from the app store.<br><br>
        2. Inputs phone number and submits the SMS verification code.<br><br>
        3. Creates a username, syncs contacts to find friends, and approves Camera/Push Notification permissions.
      </td>
      <td>
        1. "I hope my friends are actually active on here, otherwise this is pointless."<br><br>
        2. "Do I really need to sync my whole contact list right now?"<br><br>
        3. "I definitely need to make sure notifications are turned on or I’ll miss the daily window."
      </td>
      <td>Curious, slightly annoyed if the verification text takes a second to send, but excited to see who pops up on the app.</td>
    </tr>
    <tr>
      <td><b>Stage 2: The Trigger Event (Notification Retrieval)</b></td>
      <td>
        1. Engages in daily routines (studying, working, relaxing) with phone nearby.<br><br>
        2. Receives the "It's Time to BeReal." push notification.<br><br>
        3. Taps the alert immediately to open the app within the 2-minute window.
      </td>
      <td>
        1. "Alright, it's time. What am I even doing right now? Is it boring?"<br><br>
        2. "Let me hurry up and open this before the timer runs out."<br><br>
        3. "Hopefully the app doesn't lag or crash with everyone jumping on at the exact same time."
      </td>
      <td>A sudden rush of urgency, a little bit of FOMO, and a quick spark of curiosity to see what everyone else is up to.</td>
    </tr>
    <tr>
      <td><b>Stage 3: Content Capture & Creation</b></td>
      <td>
        1. Monitors the 2-minute countdown timer ticking on screen.<br><br>
        2. Utilizes the dual-camera interface to capture a simultaneous front/back unedited photo.<br><br>
        3. Reviews the capture and submits the post (or uploads late, triggering the late timestamp).
      </td>
      <td>
        1. "The clock is literally ticking, let me just snap this."<br><br>
        2. "I look kind of messy right now, but whatever, that’s literally the point of this app."<br><br>
        3. "Did the back camera actually capture what I wanted? Let me double-check before hitting post."
      </td>
      <td>A little pressured by the countdown, slightly self-conscious since there are zero filters, but relieved once it successfully uploads.</td>
    </tr>
    <tr>
      <td><b>Stage 4: Social Discovery & Engagement</b></td>
      <td>
        1. Scrolls through the newly unlocked feed to view friends' real-time updates.<br><br>
        2. Captures a custom "RealMoji" selfie reaction to a friend's post.<br><br>
        3. Drops a text comment on a friend's timeline to start a conversation.
      </td>
      <td>
        1. "Oh nice, Alex is just sitting on the couch doing nothing too. Good to know I'm not the only boring one today."<br><br>
        2. "Let me leave a funny face reaction on this."<br><br>
        3. "This is actually refreshing compared to Instagram where everything looks fake and over-edited."
      </td>
      <td>Connected, amused, and totally relaxed because there's no pressure to look perfect.</td>
    </tr>
    <tr>
      <td><b>Stage 5: Session Termination & Retention</b></td>
      <td>
        1. Reaches the end of the activity feed after consuming all updates.<br><br>
        2. Exits the application or locks the mobile device screen.<br><br>
        3. Resumes daily routines, bypassing the application until the next notification cycle.
      </td>
      <td>
        1. "Alright, I'm caught up for the day."<br><br>
        2. "I love that I can't doom-scroll this for three hours. There’s nothing else to see."<br><br>
        3. "Wonder when the notification is gonna hit tomorrow."
      </td>
      <td>Satisfied, unplugged, and ready to get back to real life.</td>
    </tr>
  </tbody>
</table>
