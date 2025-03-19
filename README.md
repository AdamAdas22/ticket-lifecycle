# ticket-lifecycle

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Step 1: Creating Tickets as End Users</h2>

<p>
In this lab, we will focus on creating tickets as end users, observing all ticket properties, and responding to them as help desk professionals.
</p>

<h3>Modifying Departments</h3>
<p>Log into the admin account and do the following:</p>
<ul>
  <li>Change the <strong>SysAdmins</strong> department to a <strong>Top Level Department</strong>.</li>
  <li>Delete the <strong>Maintenance</strong> department completely (do not archive).</li>
</ul>

<p>
This step ensures that SysAdmins are structured properly within the department hierarchy and removes unnecessary departments for a cleaner workflow.
</p>

<h2>Step 2: Creating and Observing a Ticket</h2>

<h3>Creating a Ticket as an End-User</h3>

<p>
As an end-user (Karen), create a new support ticket under the category <strong>"Report a Problem"</strong>.
</p>

<ul>
  <li><strong>Name:</strong> Karen</li>
  <li><strong>Email:</strong> karen@email.com</li>
  <li><strong>Issue:</strong> Entire mobile/online banking system is down</li>
  <li><strong>Summary:</strong> "My employees are reporting they are unable to access the banking system."</li>
</ul>

<h3>Observing the Ticket Properties as a Help Desk Agent (John)</h3>

<p>
As a Help Desk Agent (John), log in and navigate to the newly created ticket. Observe the following properties:
</p>

<ul>
  <li><strong>Priority:</strong> Check the assigned priority level.</li>
  <li><strong>Department:</strong> Verify which department the ticket is assigned to.</li>
  <li><strong>SLA:</strong> Review the Service Level Agreement associated with the ticket.</li>
  <li><strong>Assigned To:</strong> See if the ticket has been assigned to a specific agent or remains unassigned.</li>
</ul>

<p>
This step ensures that help desk agents understand ticket properties and how they are categorized within the support system.
</p>



<h2>Step 3: Managing and Updating a Ticket</h2>

<h3>Observing the Ticket Properties as a Help Desk Agent (John)</h3>

<p>
As a Help Desk Agent (John), log in and navigate to the newly created ticket. Observe the following properties:
</p>

<ul>
  <li><strong>Priority:</strong> Check the assigned priority level.</li>
  <li><strong>Department:</strong> Verify which department the ticket is assigned to.</li>
  <li><strong>SLA:</strong> Review the Service Level Agreement associated with the ticket.</li>
  <li><strong>Assigned To:</strong> See if the ticket has been assigned to a specific agent or remains unassigned.</li>
</ul>

<h3>Setting Ticket Properties</h3>

<p>
Now, update the ticket properties to reflect its urgency and ensure it is directed to the appropriate team:
</p>

<ul>
  <li><strong>Priority:</strong> Set to <strong>Sev-A (1 hour response time, 24/7 schedule)</strong>.</li>
  <li><strong>Department:</strong> Change to <strong>Online Banking Department</strong>.</li>
  <li><strong>Title:</strong> Tickets often have vague titles, so update the summary with additional details as needed.</li>
</ul>

<p>
This ensures the ticket is categorized correctly, assigned the proper SLA, and routed to the right department for resolution.
</p>


<h2>Step 4: Resolving the Ticket as Jane</h2>

<h3>Logging in as Jane</h3>

<p>
Now that the ticket has been categorized under the Online Banking Department, log out of John’s account and log in as Jane, who has the required permissions to resolve the issue.
</p>

<h3>Updating the Ticket in the Chat Log</h3>

<p>
Before resolving the ticket, communicate with your team by posting an update in the chat log. This ensures that all team members are aware of progress on the issue.
</p>

<p><strong>Example message:</strong></p>

<blockquote>
“We have identified the issue causing the mobile/online banking system outage. The server needed a reboot due to an unexpected overload. Rebooting now and monitoring system stability.”
</blockquote>

<p>
Posting this message allows all agents assigned to the ticket to see the update and collaborate effectively.
</p>

<h3>Resolving the Ticket</h3>

<p>
Once the issue is confirmed to be resolved, update the ticket status to <strong>Resolved</strong>. This marks the ticket as completed and removes it from the active queue.
</p>

<p><strong>Steps to Resolve the Ticket:</strong></p>
<ul>
  <li>In the ticket details, change the status to <strong>Resolved</strong>.</li>
  <li>Provide a closing note summarizing the resolution.</li>
  <li>Save the changes.</li>
</ul>

<p>
This completes the ticket lifecycle from creation to resolution!
</p>

<h2>Step 5: Handling a New Ticket as John</h2>

<h3>Creating the Ticket as an End-User</h3>

<p>
As an end-user, create a new ticket with the following details:
</p>

<ul>
  <li><strong>Name:</strong> Ken</li>
  <li><strong>Email:</strong> ken@email.com</li>
  <li><strong>Issue:</strong> Accounting department needs Adobe upgrade</li>
  <li><strong>Category:</strong> Broken</li>
</ul>

<p>
Submit the ticket under the “Report a Problem” category.
</p>

<h3>Observing Ticket Properties as John</h3>

<p>
Log in as John (Help Desk Agent) and review the ticket details. Observe the following properties:
</p>

<ul>
  <li><strong>Priority:</strong> Default</li>
  <li><strong>Department:</strong> Unassigned</li>
  <li><strong>SLA:</strong> Not yet set</li>
  <li><strong>Assigned To:</strong> Unassigned</li>
</ul>

<h3>Setting Ticket Properties</h3>

<p>
Update the ticket’s properties to reflect its urgency and assign it to the correct department.
</p>

<ul>
  <li><strong>SLA:</strong> Sev-B (4 hours, 24/7)</li>
  <li><strong>Department:</strong> Support</li>
</ul>

<h3>Working the Ticket to Completion</h3>

<p>
As John, take action on the ticket to resolve the issue:
</p>

<ul>
  <li>Check if the Adobe license is active for the accounting department.</li>
  <li>Download and install the necessary Adobe upgrade.</li>
  <li>Ensure the application is running correctly.</li>
  <li>Communicate the update to Ken in the ticket’s chat log.</li>
</ul>

<p><strong>Example message:</strong></p>

<blockquote>
"The Adobe upgrade has been successfully installed for the accounting department. Please verify that all users can access it."
</blockquote>

<p>
Once verified, change the ticket status to <strong>Resolved</strong> and close it.
</p>



<h2>Step 6: Escalating and Observing Ticket Access</h2>

<h3>Setting Properties for All Tickets</h3>

<p>
As a Help Desk Agent, update all ticket properties as follows:
</p>

<ul>
  <li>Set the <strong>Online Banking ticket</strong> to <strong>Sev-A (1 hour, 24/7)</strong>.</li>
  <li>Set the <strong>Adobe upgrade ticket</strong> to <strong>Sev-B (4 hours, 24/7)</strong>.</li>
  <li>Set the <strong>SysAdmins ticket</strong> to <strong>Sev-A (1 hour, 24/7)</strong> <em>(this should be the last one updated)</em>.</li>
</ul>

<h3>Observing Ticket Inaccessibility</h3>

<p>
After setting the SysAdmins ticket to Sev-A, you will notice that it is no longer accessible. This happens because of department-based visibility rules.
</p>

<h3>Regaining Access via the Admin Panel</h3>

<p>
To regain access to the escalated ticket:
</p>

<ul>
  <li>Switch to the <strong>Admin Panel</strong>.</li>
  <li>Navigate to <strong>Agents → Your Profile</strong>.</li>
  <li>Assign yourself <strong>View-access</strong> to the SysAdmins department.</li>
</ul>

<h3>Observing the Escalated Ticket</h3>

<p>
Switch back to the <strong>Agent Panel</strong> and locate the previously inaccessible ticket. You should now be able to view it but notice that:
</p>

<ul>
  <li>The ticket is still locked under the SysAdmins department.</li>
  <li>You <strong>cannot</strong> make changes to it unless given higher permissions.</li>
  <li>Tickets under critical Sev-A levels often require manual reassignment by a higher-level admin.</li>
</ul>

<p><strong>Conclusion:</strong> This step highlights how access permissions work in escalated ticket scenarios.</p>


<h2>Step 7: Resolving All Tickets</h2>

<h3>Working the Tickets to Completion</h3>

<p>Now, we will resolve all open tickets by following these steps:</p>

<ul>
  <li>Log in as the assigned agent for each ticket.</li>
  <li>Provide updates in the internal chat if necessary.</li>
  <li>Confirm that the issue has been addressed.</li>
  <li>Change the ticket status to <strong>Resolved</strong>.</li>
</ul>

<h3>Understanding Email Notifications in Ticketing Systems</h3>

<p>
Most modern ticketing systems, including osTicket, have built-in email capabilities. 
Whenever an agent updates a ticket, the end-user (customer) receives an email notification with the update details.
</p>

<p><strong>Key Points:</strong></p>

<ul>
  <li>End-users can reply to ticket emails, and their responses are automatically logged into the system.</li>
  <li>Agents can communicate directly with users without requiring them to log in to the portal.</li>
  <li>Email notifications help improve response time and efficiency.</li>
  <li>Critical tickets may trigger additional alerts for faster escalation.</li>
</ul>

<h3>Finalizing the Lab</h3>

<p>
With all tickets resolved, this lab demonstrates the full ticket lifecycle, from creation to resolution, while emphasizing how email notifications keep end-users informed.
</p>

<p><strong>Next up:</strong> Exploring advanced ticket automation and reporting tools!</p>







<h2>Step 8: Real-Life Ticket Intake</h2>

<h3>How Tickets Get Created in the Real World</h3>

<p>
In a real IT help desk or support environment, tickets can be created in multiple ways:
</p>

<ul>
  <li><strong>Phone Calls:</strong> A user calls in with an issue, and the support team logs a ticket.</li>
  <li><strong>Chat Apps:</strong> Users may reach out via Slack, Microsoft Teams, or other internal messaging platforms.</li>
  <li><strong>Email:</strong> Many ticketing systems automatically convert support emails into tickets.</li>
  <li><strong>Web Forms:</strong> End-users can submit requests via an official help desk portal.</li>
  <li><strong>In-Person:</strong> Sometimes, people stop by your desk or approach you in the hallway with a problem.</li>
</ul>

<h3>Why Every Issue Should Be Logged as a Ticket</h3>

<p>
While it might be tempting to fix small issues on the spot, it’s crucial to log everything as a ticket. 
Ticketing systems track issues, solutions, and workloads, which helps with:
</p>

<ul>
  <li><strong>Metrics and Reporting:</strong> Management can see trends and track problem areas.</li>
  <li><strong>Accountability:</strong> Ensures work is documented and recognized.</li>
  <li><strong>Follow-ups:</strong> If an issue recurs, there’s a record of past fixes.</li>
  <li><strong>Escalation:</strong> More complex problems can be properly assigned and prioritized.</li>
</ul>

<h3>Final Takeaway</h3>

<p>
It's okay to fix minor issues on the spot, but as a best practice, create a ticket for everything you do. 
Good documentation makes IT support more efficient and ensures no issue goes unnoticed.
</p>

<p><strong>With this, we wrap up our lab on ticket intake and management!</strong></p>





<h2>Finishing Up and Additional Practice</h2>

<p>
Obviously, there is much more to this product than what we covered here. The best way to get better is through hands-on experience. 
We encourage you to explore additional features, such as the email functionality, to see how ticket notifications and responses work in a real-world environment.
</p>

<h3>Repetition Builds Mastery</h3>

<p>
This lab helps go through everything in a simulated help-desk environment. here are some of the basic principals gone over in this lab.
</p>

<ul>
  <li>Create and manage tickets as an end-user and help desk agent.</li>
  <li>Assign tickets to the correct department, priority, and SLA.</li>
  <li>Work tickets to completion and communicate through internal notes.</li>
  <li>Observe ticket escalation and permission changes.</li>
  <li>Explore additional settings like email alerts and automation.</li>
</ul>

<h3>Technical Skill Pillar</h3>

<p>
Building strong technical skills requires both knowledge and practice. This lab helps develop essential IT support skills, including:
</p>

<ul>
  <li><strong>Ticket Management:</strong> Learning how to process, prioritize, and escalate support requests.</li>
  <li><strong>System Administration:</strong> Configuring permissions, departments, and teams within a help desk system.</li>
  <li><strong>Problem-Solving:</strong> Understanding how to troubleshoot and resolve user issues efficiently.</li>
  <li><strong>Documentation:</strong> Keeping track of work for accountability, metrics, and future reference.</li>
</ul>

<h3>Final Thoughts</h3>

<p>

By mastering these concepts, you'll be better prepared for real-world IT environments. Keep practicing, keep learning, and keep improving!
</p>
































<h2>Lifecycle Stages</h2>


<br />
