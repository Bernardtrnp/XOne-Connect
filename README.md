# XOne Connect - WhatsApp Bot

Welcome to **XOne Connect**! 🚀  
This is the official WhatsApp bot developed by the **Student Council of SMPK Frater Xaverius 1 Palembang** | **Information Technology Division**. XOne Connect was created to enhance communication and provide an anonymous platform for students to interact freely.


## Features 🌟

- **Menfess (Confess) Feature**:  
  Share your thoughts, feelings, or secrets anonymously. Simply send a message, and Xone Connect will forward it without revealing your identity! 🤫💬

- **Privacy First**:  
  Your messages are forwarded securely and confidentially, ensuring your privacy is maintained. 🛡️🔒

- **Built with JavaScript**:  
  Powered by JavaScript, Xone Connect ensures a smooth, efficient, and responsive experience.


## Installation 🛠️

To get **XOne Connect** up and running on your local machine, follow these simple steps:

### Prerequisites 📋

Before you begin, make sure you have the following installed:

- **Node.js** (v12 or higher)
- **npm** (Node package manager)

### Steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/xone-connect.git
   cd xone-connect
   ```

2. **Install dependencies**:
   Install all necessary dependencies using npm:
   ```bash
   npm install
   ```

3. **Set up the WhatsApp Business API**:
   - You’ll need access to the WhatsApp Business API.
   - Follow the official [WhatsApp Business API documentation](https://developers.facebook.com/docs/whatsapp) to set up your WhatsApp number and obtain the API credentials.

4. **Configure the `config.json` file**:
   Create a file named `config.json` in the root directory and add the following content:

   ```json
   {
     "ownerNumber": "628xxxx@s.whatsapp.net",
     "botName": "XoneConnect",
     "ownerName": "OSIS SMPK Xaverius 1 Palembang",
     "sessionName": "session",
     "footer": "© Xone Connect 2024",
     "api_lolkey": "SadTeams",
     "group": {
       "judul": "group_name",
       "link": "group_link"
     }
   }
   ```

   Replace `"628xxxx@s.whatsapp.net"` with the actual owner number and update other details accordingly.

5. **Run the bot**:
   Once everything is set up, run the bot with the following command:
   ```bash
   npm start
   ```

6. **Start chatting**:
   - Add **XOne Connect** to your WhatsApp.
   - Start sending messages and use the **Menfess** feature.


## Features Explained 🧑‍💻

1. **Start Chatting**:  
   Add **XOne Connect** to your WhatsApp and start sending messages.
   
2. **Send a Confession**:  
   Type your message and let the bot forward it anonymously to your chosen recipients or group.

3. **Enjoy the Privacy**:  
   Share without fear, knowing your identity is kept private.


## Contribution 🤝

We welcome contributions to **XOne Connect**! If you want to help improve the bot, feel free to fork the project, submit pull requests, or open issues. Let’s build something amazing together! 🌍✨


## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


## Contact 📬

For any questions, issues, or feedback, reach out to us through our official channels.  
Let’s keep XOne Connect a safe, fun, and innovative space for everyone! 😄
