# ece568-lab-3--web-application-security-solved
**TO GET THIS SOLUTION VISIT:** [ECE568 Lab 3- Web Application Security Solved](https://www.ankitcodinghub.com/product/ece568-lab-3-web-application-security-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119788&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE568  Lab 3- Web Application Security Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
ECE568 – Computer Security Lab #3: Web Application Security Overview

The purpose of this lab is to familiarize yourself with a number of the most common web application vulnerabilities. You will need to spend some time reading and understanding some material on JavaScript, the HTTP DOM model and SQL.

README format:

We have provided a submission checking script to help ensure that the automarker will process your files correctly:

Your solutions will be tested using the Firefox browser on the ECF machines. Please make sure to test your solutions on these machines prior to submission.

Background

For this lab, we will be using the WebGoat environment; it is an open-source tool that allows you to explore a variety of web vulnerabilities, several of which we will be using in this lab. Begin by creating a local working directory, and copy the webgoat.jar file provided from Quercus into the directory. The file webgoat.jar can also be found in /share/copy/ece568f/lab3 on ECF machines.

The WebGoat application creates a private web server and database for you to experiment with. When it runs, the application starts listening on a local port; you will need to pick a unique value for your use. Make sure to check your Java SDK version is

1.7. The following commands use port 8090 as an example:

If you are working on this lab remotely and running this on ECF, then you will need to use SSH to create a tunnel; this will allow you to access the local web service from your own computer:

(If you are using Windows, then a program like putty can perform the same port-forwarding.) You can then connect to the service from your local web browser by connecting to:

and then logging in as a username of “webgoat” with a password of “webgoat”.

Getting Started

To get oriented to WebGoat, start by going to the Discover Clues in the HTML lesson under “Code Quality”:

Select either “Inspect Element” or “Show Page Source” (depending on your web browser) to view the source of the web page.

You can find the developer’s comments, with the solution for this first exercise, within the code:

You need to now complete the following eight exercises to complete this lab:

Part 1: Phishing with XSS

Navigate to the “Cross-Site Scripting (XSS)” lessons and select “Phishing with XSS”. Read the description and complete this exercise.

Your goal is to generate a fake “login” form, use XSS to display it, and then submit its contents to the URL provided in the exercise description (substituting the port number you selected):

If you are successful, a green checkmark will appear.

Hints:

In particular, look at the DOM reference for how to access HTML form data from within JavaScript (“document.forms[0].____.value”).

What to submit:

Submit the full code you create in part1.txt. Your explanation should provide a brief description of the code and the vulnerability you used, and how you phished the victim. For ease of marking, when creating your “login” form, please use the following HTML id values for your form fields:

Part 2: Reflected XSS Attacks

Navigate to the “Cross-Site Scripting (XSS)” lessons and select “Reflected XSS Attacks” (not the “LAB…” lessons).

In this section, you need to determine which form element is vulnerable to script injection. Using this information, you will then craft a URL that injects JavaScript into the page such that when a victim visits the URL, their credit card number is sent to the attacker at the following URL.

You can assume that the user is logged in before visiting your URL, and that they will enter your URL directly into the address bar. In order to obtain the user’s actual credit card number (and not the default number), you should steal the user’s information after they have clicked the “Buy” button. You can verify the credit card number sent to the attacker in the WebGoat server logs.

For stealthiness, you should also make sure that the page with the injected script looks as close as possible to the original page for “Reflected XSS Attacks”.

Hints:

What to submit:

You should provide your attack URL in part2.txt. Your explanation should indicate the field that’s exploitable and a readable, unencoded version of your URL. It should also include an explanation of how/why the attacker was able to obtain the credit card number.

Part 3: Cross Site Request Forgery (CSRF)

Navigate to the “Cross-Site Scripting (XSS)” lessons and select “Cross Site Request Forgery (CSRF)”. In this section, you need to successfully complete the “transfer” action to steal money from the victim/user’s account.

What to submit:

Your explanation should indicate the field that’s exploitable and you should provide the exploit you craft in part3.txt.

Part 4: CSRF Prompt By-Pass

Navigate to the “Cross-Site Scripting (XSS)” lessons and select “CSRF Prompt By-Pass”. In this section, you need to successfully complete the “transfer” action, but it is slightly more complicated than in Part 3. The “transfer” action has two steps, requiring you to start the transfer and then confirm it by fetching a second URL.

You should provide the exploit you craft in part4.txt, and your explanation should indicate the field that’s exploitable and how/why you were able to defeat the prompt by-pass.

Part 5: CSRF Token By-Pass

Navigate to the “Cross-Site Scripting (XSS)” lessons and select “CSRF Token By-Pass”. In this section, you need to successfully complete the “transfer” action, but it is significantly more complicated than in Parts 3 or 4. The “transfer” action has two steps and now requires you to start the transfer, receive a token value and then provide that random value while fetching the second URL.

You should provide the exploit you craft in part5.txt, and your explanation should indicate the field that’s exploitable and how/why you were able to defeat the token by-pass.

Part 6: String SQL Injection

http://hsqldb.org/doc/1.8/guide/ch09.html (http://hsqldb.org/doc/1.8/guide/ch09.html)

http://www.sqlinjection.net/ (http://www.sqlinjection.net/)

This exploit should be fairly simple. You should include the full contents of the field that you entered in part6.txt.

Part 7: Database Backdoors

Navigate to the “Injection Flaws” lessons and select “Database Backdoors”. This section has two parts.

For the first part, you must find an exploit that will change the salary of user 101 to $555000. As a hint, you should look at the “update” SQL command.

For the second part, you must find an exploit that will insert a database “trigger”. This trigger will stay resident inside the database, and will automatically alter the database for you. Create a trigger that will automatically change the email of any new user entry to “ece568-2020f@utoronto.ca (mailto:ece568@utoronto.ca) ”. The WebGoat lesson plan will present you with the proper format for the trigger once you complete the first part.

Your answer should include the full contents of what you entered in both parts. The first line in part7.txt should be your answer for the first part, and the second line for the second part.

Part 8: Blind Numeric SQL Injection

Navigate to the “Injection Flaws” lessons and select “Blind Numeric SQL Injection”. You will need to find a SQL injection vulnerability that allows you to find the PIN for credit card 1234123412341234.

You should provide the value of the PIN in part8.txt. Your explanation should include the SQL injection you used and a brief description of how you found the PIN.

The remainder of this package covers examples of dozens of other frequently-encountered web exploits. While it is beyond the scope of this assignment, my hope is that you will find some of them interesting to explore at some later time. WebGoat has had active development for the past few years, and is constantly expanding to include new tutorials; you can always download the latest version here:

https://github.com/WebGoat/WebGoat (https://github.com/WebGoat/WebGoat)
