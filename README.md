# Using-Playbook-for-phishing-email

<h2>Directions:</h2>
In this activity, you will respond to a phishing incident that involves a malicious file hash. 
<h2>Scenario</h2>
<img width="894" alt="Screen Shot 2025-01-03 at 4 18 30 PM" src="https://github.com/user-attachments/assets/d5d549ca-b2ed-457e-bafa-839943def059" />
<h2>Steps</h2>
Before you begin investigating the alert, take a moment to review the playbook and flowchart because you'll be using them throughout the investigation.
<h2></h2>
Step 1) The Phishing Playbook instructions provide detailed, written instructions about each step represented in the flowchart.

The Phishing Flowchart provides a high-level overview and visual representation of the sequence of steps and substeps you'll take to respond to a phishing alert.

Note: The steps in this playbook are not a definitive guide to responding to a phishing incident. Organizations have their own sets of policies, standards, and procedures that determine the expected response actions to incidents.

Step 2) In the Alert ticket template, begin the investigation by updating the Ticket status dropdown list to Investigating.
<img width="590" alt="Screen Shot 2025-01-03 at 4 35 20 PM" src="https://github.com/user-attachments/assets/1043a978-8a00-435a-8c90-8fb5bd556dd4" />

Step 3) As a security analyst, you'll want to gain a complete understanding of why the alert was triggered. Create a new entry in your incident handler's journal to record the details of this security incident and gather your thoughts. You'll refer to these notes as you progress through the steps in the playbook. 
<img width="682" alt="Screen Shot 2025-01-03 at 5 20 02 PM" src="https://github.com/user-attachments/assets/5e5b8530-4f48-4064-9873-ec1901286185" />

Then, evaluate the contents of the Alert ticket, including the content in the Additional information section. Here are some examples of elements to examine when you are evaluating the alert ticket details:

Alert severity: According to the playbook instructions, an alert severity of Medium or High is a good indication that a ticket might require escalation.

Sender details: Analyzing the sender details of an email is important because it can reveal inconsistencies that can indicate a phishing attempt. Often, phishing emails try to impersonate trusted entities. For example, if there is a mismatch between the sender's email address and the sender's name, this is a good indication that the email might be a phishing email.

Message body: It's important to analyze the message body (and subject line) of an email because phishing emails often contain grammatical errors, which can be an indication of a phishing attempt.

Attachments or links: Phishing emails contain malicious links or attachments that are used to steal sensitive information or download malicious software or code on the recipient's device. Check to see whether a file has been attached to this email.

Step 4) After evaluating the alert details, use the Phishing Playbook's Step 3.0 and Step 3.1 to determine whether the email contains links or attachments and whether these links or attachments are malicious. Remember you've already determined that the email contains an attachment that has been verified as malicious through its file hash. 

Proceed to the Phishing Playbook's Step 3.2 if you've determined that the alert should be escalated. If you've determined that the alert should not be escalated, proceed to the Phishing Playbook's Step 4.
<img width="742" alt="Screen Shot 2025-01-03 at 5 04 32 PM" src="https://github.com/user-attachments/assets/c7e6fb93-5794-4168-8b58-01872dcfca3d" />
<img width="619" alt="Screen Shot 2025-01-03 at 4 52 37 PM" src="https://github.com/user-attachments/assets/f4b560ce-c489-43a8-b6d2-a731c7253e2b" />
