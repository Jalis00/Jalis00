# Set path and content
$readmePath = "README.md"

$readmeContent = @"
# Hi there 👋

## 👨‍💻 Whoami

Hey! I'm Jacob Hakimi from **Stockholm, Sweden** 🇸🇪  
I'm passionate about software development, traveling the world 🌍, and hitting the gym 💪.  
I have an entrepreneurial mindset and I'm the **founder of JalisAI** – a company that helps businesses grow using AI.  
Currently studying **Systemutvecklare (SUVx24)** and constantly striving to learn and build more.

🟧 `SOFTWARE DEVELOPER`   🟧 `FITNESS COACH`   🟧 `TRAVELER`

---

## 🧠 An Easy Way to Connect/Remember Me

📎 [LinkedIn – Elis Jacob Hakimi](https://www.linkedin.com/in/elis-jacob-hakimi-04b85b201/)

---

## 📚 Courses I’ve Completed (SUVx24)

- 🧠 **Course 1** – Bootcamp for Programmers  
- 📂 **Course 2** – C/C++  
- 🖥️ **Course 3** – Operating Systems  
- ⚙️ **Course 4** – Embedded Systems  
- 🚀 **Course 5** – Advanced System Development  
- 🎓 **Thesis** – From my education as a Systemutvecklare  

---

## 🛠️ Tools of Trade (Optional – Add what you use)

\`C#\` \`C++\` \`PowerShell\` \`Arduino\` \`Git\` \`VS Code\` \`TinkerCAD\`

---

📌 Creator of **JalisAI** | Passionate about growth, freedom, and impact.
"@

# Create the file
Set-Content -Path $readmePath -Value $readmeContent

Write-Host "Your README.md has been created successfully!" -ForegroundColor Green
