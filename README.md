
# **PresentPup: Simplifying Temporary File Sharing and Presentation Competitions**

### **Overview**

Have you ever found yourself needing to quickly share a presentation or class notes without using your personal storage accounts on an unfamiliar device? **PresentPup** is here to solve that problem. Whether you’re a teacher, student, or speaker, PresentPup allows you to temporarily upload your presentations or documents and access them securely from anywhere, without the hassle of logging into personal accounts.

In addition to its core file-sharing functionality, PresentPup helps organizers manage **presentation competitions** by allowing participants to submit their documents via a form. The platform generates a random order for presentations, maintains a list of participating teams, and syncs data to Google Sheets for easy tracking.

---

### **Services**

- **Temporary File Sharing**:
   - Secure, temporary storage for sharing documents with passcode-protected URLs.
   
- **Presentation Competition Management**:
   - Streamlined submission and organization of presentations for competitions.
   - Integration with Google Sheets for live data tracking.

---

### **Getting Started**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/presentpup.git
   ```
   
2. **Install dependencies**:
   ```bash
   npm install
   ```
   
3. **Set up environment variables**:
   - Configure the `.env` file for database, file storage (e.g., AWS S3), and Google Sheets API credentials.

4. **Run the application**:
   ```bash
   npm start
   ```

---

### **Contributing**

We welcome contributions to **PresentPup**! Here's how you can help:

- **Report bugs**: Open an issue for any bugs or problems you encounter.
- **Suggest features**: We’d love to hear your ideas to make PresentPup better.
- **Submit pull requests**: Fork the repo, make your changes, and submit a pull request for review.
