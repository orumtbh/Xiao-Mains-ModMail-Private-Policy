# 1. Data We Collect

When you send a direct message to the Bot to initiate a support thread or interact with an active thread, we collect and store the following information:

 -  User Data: Your Discord User ID, username, and avatar.

 -  Message Content: The text content, links to attachments, and timestamps of any messages sent to the Bot.

 -  Server Data: Relevant Guild (Server) IDs and Channel IDs required to route your messages to the correct moderation team.

 -  Action Logs: Metadata related to the thread, such as when it was opened, closed, or transferred by moderators.

# 2. How We Store Your Data

The modmail-dev/modmail application does not store data on Discord's infrastructure once a thread is archived ("closed"). Instead, all collected data (including message logs and user identifiers) is exported and stored off-platform in a Railway database.

This database is managed independently by the individual hosting the bot. We implement reasonable security measures to protect your data from unauthorized access.

# 3. How We Use Your Data

The data we collect is strictly used to provide and maintain the functionality of the Bot. Specifically, we use it for:

 - Facilitating Communication: Relaying messages between you and the server's moderation or support staff.

 - Record Keeping: Maintaining an accurate history of support requests, appeals, or reports for server staff to reference.

 - Service Improvement: Allowing server administrators to review past interactions to improve community guidelines and support responses.

# 4. Data Sharing and Disclosure

Your data is highly restricted. We do not sell, monetize, or trade your personal information. Your data is only accessible to:

 - Authorized Server Staff: Moderators and administrators of the Discord server who have the necessary permissions to view Modmail threads and logs.

 - The Database Administrator: The technical individual responsible for hosting the Railway instance and keeping the Bot online.

 - Railway Employees: Select employees of the MongoDB Atlas team may have the ability to access the data. Their usage is restricted and governed by their [privacy policy](https://railway.com/legal/privacy).

We will not share your data with any third parties unless explicitly required to do so by law or to comply with Discord's Trust and Safety requests.

# 5. Data Retention

Chat logs and associated user identifiers are retained indefinitely within our MongoDB database to ensure server staff have a consistent historical record of all moderation and support interactions.

# 6. Your Rights and Data Deletion

Under the Discord Developer Policies, you have the right to request the deletion of your personal data. If you wish to have your Modmail logs and associated identifying information permanently removed from our off-platform MongoDB database, you may exercise this right by:

  - Sending a message directly to the Bot requesting data deletion.

  - Contacting the server administrators or the contact person listed below.

Upon receiving a valid request, we will purge your identifying information and message content from our database within 21 days.

7. Contact Information

If you have any questions, concerns, or data deletion requests regarding this Privacy Policy or the Bot's operation, please contact:

  - The Bot directly; or

  - The host of the bot: Orum on Discord.
