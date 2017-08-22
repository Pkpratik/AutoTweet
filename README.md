# AutoTweet

AutoTweet is a Twitter bot that helps with tweeting at a scheduled time.  




<h1> Quick start </h1>

<b> Tools needed to set up AutoTweet: </b> 


<li> <a href="https://nodejs.org/en/">Node.js</a>  installed on your machine. </li>

<li> A registered Twitter account. </li> 

<li> A Twitter App - Create one for your Twitter account <a href="https://apps.twitter.com/app/new"> here </a> </li> 


<p><i> Note: The following processes below assumes you have set up all the tools above</i> </p>   
   
<h3> Setting up on your local machine. </h3> 



<p> <li> Open your Terminal, <code> cd </code> to the directory where you want to install the script.</li> </p>

<p><li> <code> git clone https://github.com/Adetona/AutoTweet.git </code> to download the script to your machine.</li> </p>

<p> <li>Open the <code> config.js </code> file. You will find the following in the file: </p> 

<code> consumer_key:         '65EmpGTOKXXkjHR9tI5Jiio01',</br> </code>

<code> consumer_secret:     'FZ0lYU5dUJA4YTuqPtZ4q5NfXLbXFuz4E9xgA49ij6Tc8YAcol', </br> </code>

<code> access_token:         '2963547257-9N7VF9O9gLjQQTtJhRVjk8chJQivg0zTMV2dy9E', </br> </code>

<code> access_token_secret:  'QMnRuSd0zbh3HbZ09wcVUohOEAol5W6HrABPyNF0gf0fY' </code> 

</code>  


Change the values to the keys to your own. </li> 


<h3> Scheduling your tweet. </h3> 

<p> <li> Open the <code> server.js </code> file. </li> </p>

<p><li> Set the value of <code> var tweet </code> to the tweet you want to schedule. </li></p> 

<code> 	var tweet = ['12:22 AM']; </code> 



<p> <li> Set the value of <code>cycle</code> to the time you want to post the tweet. The current time in the script is 12:22 AM.</li></p>

<p>Learn more about setting the right time <a href="https://www.npmjs.com/package/ontime"> here </a>  </p> 
		
<code> cycle: '12:22:00' </code> 



<h3> Test the script. </h3>

<li> After the configuration, you should  <code> cd </code>  to the directory where the script is located, then type <code> node server.js </code> in your terminal and run it </li>


<p> If your configuration is complete a tweet will be posted on your account at the scheduled time. </p> 







  
