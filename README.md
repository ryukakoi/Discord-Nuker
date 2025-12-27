
![standard](https://github.com/user-attachments/assets/0aa4a3fa-32ee-42ed-8ba7-21f200a36597)




# Educational Discord Server Nuker

**🚨 WARNING & DISCLAIMER - PLEASE READ THIS FIRST 🚨**

> This software is provided **STRICTLY FOR EDUCATIONAL AND RESEARCH PURPOSES ONLY**. It is designed to demonstrate security vulnerabilities in Discord's API and the potential damage of poor permission management.
>
> **❗ MISUSE OF THIS TOOL IS EXPRESSLY FORBIDDEN. ❗** 
>
> **Unauthorized use** of this tool to disrupt, damage, or destroy Discord servers is:
> - A direct **violation of Discord's Terms of Service**.
> - Likely **illegal** in your jurisdiction, constituting computer fraud, abuse, or vandalism. 
> - Punishable by a **permanent ban from Discord** and potential **legal action**. 
>
> **You are solely responsible for your actions.** The developer assumes **no liability** for any misuse or damage caused by this software. Use this only on a **private, self-owned server** that you have created for testing purposes.

---

## 📖 Overview

This is a proof-of-concept script that demonstrates how a malicious actor could abuse Discord's API and bot permissions to perform destructive actions on a server. The purpose of this project is to educate server administrators and developers on:
- The critical importance of **proper bot permission management**.
- The potential scale of damage from a single compromised account or bot.
- How to recognize and mitigate such attacks for **defensive security**.

## 🚀 Features (For Educational Analysis)

*   **Mass Channel Operations:** Create and delete channels.
*   **Mass Role Operations:** Create and delete roles.
*   **Ban/Kick All Members:** Shows the impact of compromised moderation powers.
*   **Role & Channel Spam:** Fills the server with junk data to disrupt operations.

## 🛠️ Installation & Setup

**Prerequisites:**
*   Python 3.8+
*   A Discord Bot token.

1.  **Create a Test Server:** Create a brand new, empty Discord server that you own and where you can safely test.

2.  **Create a Test Bot:**
    *   Go to the [Discord Developer Portal](https://discord.com/developers/applications).
    *   Create a New Application.
    *   Navigate to the "Bot" tab and create a bot user.
    *   **Copy the Bot Token.** This is your `BOT_TOKEN`.

3.  **Invite the Bot to Your TEST Server:**
    *   Generate an invite link in the "OAuth2" -> "URL Generator" tab.
    *   Select the `bot` scope.
    *   Select **Administrator** permissions.
    *   Use the generated URL to invite the bot to your test server.

4.  **Use the program**
    *  Run install.bat
    *  Run nuker.py
    
## ⚠️ How to Use for Learning (Ethically)

1.  **Study the Code:** The greatest value is in understanding the API calls and how permissions are abused. Read the code line-by-line.

2.  **Run in a Controlled Environment:**
    *   **ONLY** run this script on the **private, empty test server** you created.
    *   Observe the effects in real-time. See how quickly chaos can ensue.

3.  **Practice Defense:** Use this knowledge to secure your own servers.
    *   **Principle of Least Privilege:** Never give a bot the `Administrator` permission. Only grant the specific permissions it absolutely needs.
    *   **Audit Logs:** Regularly check your server's Audit Log to see what actions bots and users are performing.
    *   **2FA for Moderators:** Enforce 2FA on all staff accounts to prevent account compromise.
    *   **Webhook Management:** Be cautious about who can create webhooks. Review and delete unused ones.

## 📜 License

This project is licensed under the MIT License. By using this software, you agree to the terms stated in the disclaimer above. **Use responsibly.**
