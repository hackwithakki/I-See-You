# I-See-You

ISeeYou is a Bash and Javascript tool to find the exact location of the users during social engineering or phishing engagements. Using exact location coordinates an attacker can perform preliminary reconnaissance which will help them in performing further targeted attacks. 

<B>Note:</B><Br>
- This tool does not require any additional software to perform phishing attacks.
- Users can expose their local servers to the Internet and decode the location coordinates by looking at the log file.
  
<B><I>This project must not be used for illegal purposes for stalking people or hacking into system where you do not have permission, it is strictly for educational purposes and for people to experiment with.</I></B>
  
Any suggestions or ideas for this tool are welcome - just tweet me on [@hackwithakki](https://twitter.com/hackwithakki)

![image](https://user-images.githubusercontent.com/3501170/55272562-2d894b80-5312-11e9-8fec-0be64a00c317.png)

# How to install?![terminal]


<pre>
git clone https://github.com/hackwithakki/I-See-You.git
cd I-See-You
chmod u+x ISeeYou.sh
./ISeeYou.sh
</pre>
![image](https://github.com/user-attachments/assets/8cf0118b-4833-4781-b023-9b881f9abe0f)

# Screenshots

Once the `ISeeYou.sh` is ran user sees the below screen:

![image](https://github.com/user-attachments/assets/c07c6a0e-7552-4488-abfb-98311895c32b)


Enter the highlighted url on the main screen where it asks for `Enter the URL generated by Serveo` and hit `Enter`:

![image](https://github.com/user-attachments/assets/8bdae5be-cf2d-4fda-b330-0df78622e2ee)
This URL is generated randomly for different users. However, it will be a subdomain for the serveo.net domain. Send this URL to your victim as part of the phishing campaign via email or any other medium. Victim will see the site as below:

![image](https://user-images.githubusercontent.com/3501170/55271752-34aa5c80-5306-11e9-87b2-fa4f54321fe3.png)

Note: You can be creative and modify the look and feel of the page as per your requirement.

Once the targeted users allows location permission, malicious user will receive exact location of the victim in the tail screen. These numbers are `longitude and latitude` of the user.

![image](https://user-images.githubusercontent.com/3501170/55271965-cbc4e380-5309-11e9-8dca-5a1f5933c1c7.png)

Using `https://maps.google.com` you can convert the `longitude and latitude` to an exact location:

![image](https://user-images.githubusercontent.com/3501170/55271991-4e4da300-530a-11e9-91ec-2fb83ef46461.png)

# Copying Longitude and Latitude numbers from Xterm screens

To copy between xterm and other programs - This would allow user to select numbers to be copied to the clipboard.
1. Add to the file ~/.Xresources (or create)

2.
<pre>
XTerm*selectToClipboard: true
</pre>
3. Then run the command:
<pre>
xrdb -merge ~/.Xresources
</pre>
4. Restart xterm.

# Questions?

Twitter: https://twitter.com/hackwithakki <br>
LinkedIn: https://www.linkedin.com/in/hackwithakki

# Contribution & License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.</br>
Want to contribute? Please fork it and hit up with a pull request.

Any suggestions or ideas for this tool are welcome - just tweet me on [@hackwithakki](https://twitter.com/hackwithakki)

# Thanks

Special thanks to cryptomarauder aka voidengineer
