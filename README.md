# 🚀 GitHub Copilot Impact
Analytics to show how developers build habits with GitHub Copilot—what features they use, how engagement changes, and what drives adoption. Helps teams and leaders understand usage and show business value. Use organizational data to zoom in teams that are pulling ahead with agentic coding vs. the rest. Learn the patterns from these early leaders and drive adoption across the board.

<details open>
<summary><strong>✨ What You’ll Get</strong></summary>

- **Track Adoption and Engagment:**  
  See weekly active users, interactions, split by chat vs. agent mode - split by teams.
  Glean intensity and frequency of interaction with GitHub Copilot by teams

- **Measure Impact:**  
  View code activity, acceptance rates, lines of code suggested and added over time, segmented by teams.

- **Language Insights:**  
  Learn how acceptance rate, code gen activity, code accept activity varies by language.
  Split the views by teams to see if certain teams are finding greater success than others. 

- **Feature Insights:**  
 Learn how accceptance, code gen, code accept activity vary by features like code completion, agent mode, inline edits etc.
 Useful in answering questions like 'Do Principal Engineers have a higher acceptance rate? Do they have a greater adoption of agent mode?'

 - **Feature Insights:**  
 Learn how accceptance, code gen, code accept activity vary by features like code completion, agent mode, inline edits etc.
 Useful in answering questions like 'Do Principal Engineers have a higher acceptance rate? Do they have a greater adoption of agent mode?'

  - **Model Insights:**  
Glean which models are contributing to the code base, and which models are acquiring new users.

  - **Goal Tracking:**  
Set adoption targets by teams and identify hotspots and bright-spots.

</details>

<details open>
<summary><strong>🖼 Preview</strong></summary>

![Report Preview](./assets/ghcpgif.gif)

</details>

> 📧 **Before you begin, your GitHub Enterprise admin and Entra admin need to export usage data.**
> This pre-written email covers all required data sources, field names, admin roles, permissions, SSO prerequisites, and export steps — everything your admins need in one click.
>
> **[📨 Email Prerequisites to Your IT Admin](mailto:?subject=Action%20Required%3A%20GitHub%20Data%20Exports%20Needed%20for%20GitHub%20Copilot%20Impact%20Report%20%28Power%20BI%29&body=To%3A%20IT%20Admin%20%2F%20GitHub%20Enterprise%20Owner%20%2F%20Global%20Admin%0ARe%3A%20GitHub%20Copilot%20Impact%20%E2%80%93%20Power%20BI%20Report%20Setup%0A%0A%0AWHAT%20THIS%20REPORT%20DOES%0A%0AThe%20GitHub%20Copilot%20Impact%20Report%20is%20a%20Power%20BI%20report%20that%20tracks%20how%20developers%20in%20your%20organization%20are%20building%20habits%20with%20GitHub%20Copilot.%20It%20measures%20weekly%20active%20users%2C%20code%20acceptance%20rates%2C%20lines%20of%20code%20suggested%20and%20accepted%2C%20feature%20adoption%20%28code%20completion%2C%20agent%20mode%2C%20inline%20edits%29%2C%20model%20usage%2C%20and%20goal%20attainment%20by%20team.%20Designed%20for%20engineering%20leaders%20and%20DevOps%20teams%20to%20assess%20developer%20AI%20ROI.%0A%0A%0ADATA%20SOURCES%20REQUIRED%0A%0A1.%20GitHub%20Copilot%20Usage%20Insights%0A%20%20%20Export%3A%20GitHub%20Enterprise%20-%3E%20Insights%20-%3E%20Copilot%20Usage%20-%3E%20Last%2028%20days%20-%3E%20Download%0A%20%20%20Format%3A%20JSON%0A%0A2.%20GitHub%20Enterprise%20Members%0A%20%20%20Export%3A%20GitHub%20Enterprise%20-%3E%20People%20-%3E%20Members%20-%3E%20CSV%20Report%0A%20%20%20Format%3A%20CSV%0A%0A3.%20Microsoft%20Entra%20ID%20%E2%80%93%20User%2FOrg%20Data%0A%20%20%20Export%3A%20entra.microsoft.com%20-%3E%20Identity%20-%3E%20Users%20-%3E%20Download%20users%0A%20%20%20Format%3A%20CSV%0A%0A%0AREQUIRED%20FIELDS%20%E2%80%94%20DO%20NOT%20REMOVE%0A%0AIMPORTANT%3A%20Do%20not%20pre-process%2C%20filter%2C%20or%20re-save%20the%20GitHub%20JSON%20or%20CSV%20exports%20before%20loading%20them%20into%20Power%20BI.%20Removing%20fields%20from%20these%20files%20will%20break%20report%20calculations.%0A%0AGitHub%20Copilot%20Usage%20Insights%20JSON%3A%0Adate%2C%20total_active_users%2C%20total_engaged_users%2C%20copilot_ide_code_completions.total_engaged_users%2C%20copilot_ide_code_completions.total_code_suggestions%2C%20copilot_ide_code_completions.total_code_acceptances%2C%20copilot_ide_code_completions.total_code_lines_suggested%2C%20copilot_ide_code_completions.total_code_lines_accepted%2C%20copilot_dotcom_chat.total_engaged_users%2C%20copilot_ide_chat.total_engaged_users%2C%20breakdown%20%28language%2C%20editor%2C%20model%20arrays%29.%0A%0AGitHub%20Members%20CSV%3A%0Alogin%2C%20name%2C%20email%2C%20role%2C%20organization%2C%20teams%20%28used%20to%20link%20GitHub%20handles%20to%20Entra%20identity%20via%20SSO%29.%0A%0AMicrosoft%20Entra%20ID%20%E2%80%93%20User%20Export%3A%0AUserPrincipalName%2C%20Department%2C%20JobTitle.%0A%0A%0AINSIGHTS%20YOU%20WILL%20GAIN%0A%0A-%20Weekly%20active%20GitHub%20Copilot%20users%20and%20engagement%20rate%20by%20team%0A-%20Code%20acceptance%20rate%3A%20how%20often%20developers%20accept%20AI-generated%20code%20suggestions%0A-%20Lines%20of%20code%20suggested%20vs.%20accepted%20%E2%80%94%20quantifies%20AI%27s%20contribution%20to%20the%20codebase%0A-%20Feature%20adoption%20breakdown%3A%20code%20completion%2C%20agent%20mode%2C%20inline%20edits%0A-%20Language-specific%20acceptance%20rates%20and%20code%20generation%20volume%0A-%20Model%20distribution%3A%20which%20AI%20models%20are%20contributing%20to%20the%20codebase%0A-%20Goal%20tracking%3A%20adoption%20target%20progress%20by%20team%2C%20with%20hotspot%20and%20bright-spot%20identification%0A-%20Role-level%20insights%3A%20whether%20principal%20engineers%20use%20agent%20mode%20at%20higher%20rates%20than%20junior%20developers%0A%0A%0AROLES%20%26%20PERMISSIONS%20REQUIRED%0A%0AExport%20GitHub%20Copilot%20Usage%20Insights%3A%20GitHub%20Enterprise%20Owner%0AExport%20GitHub%20Enterprise%20Members%20CSV%3A%20GitHub%20Enterprise%20Owner%0AExport%20Entra%20user%20data%3A%20User%20Administrator%20or%20Global%20Reader%20%28Entra%29%0AEnable%20Copilot%20usage%20metrics%20policy%3A%20GitHub%20Enterprise%20Owner%20%28must%20opt%20in%20under%20AI%20Controls%20settings%29%0A%0A%0ASOFTWARE%20REQUIREMENTS%0A%0A-%20Power%20BI%20Desktop%20%E2%80%94%20required%20to%20open%20the%20.pbit%20template%20file%0A-%20GitHub%20Enterprise%20Cloud%20account%20with%20GitHub%20Copilot%20enabled%0A-%20Single%20Sign-On%20%28SSO%29%20enforcement%20between%20GitHub%20and%20Entra%20ID%20%E2%80%94%20required%20to%20join%20GitHub%20handle%20to%20M365%20identity%20for%20org-level%20segmentation%0A-%20Access%20to%3A%20github.com%2Fsettings%2Fenterprises%2C%20entra.microsoft.com%0A%0A%0APrerequisite%20%E2%80%94%20SSO%20Enforcement%3A%0AThe%20report%20joins%20GitHub%20user%20data%20to%20Entra%20organizational%20data%20using%20the%20SSO-linked%20identity.%20If%20SSO%20is%20not%20enforced%20in%20your%20GitHub%20Enterprise%2C%20department-level%20and%20team-level%20segmentation%20will%20not%20populate.%20Confirm%20with%20your%20GitHub%20Enterprise%20Owner%20that%20%22Enforce%20SAML%20SSO%22%20is%20active%20before%20exporting.%0A%0APrerequisite%20%E2%80%94%20Copilot%20Usage%20Metrics%20Policy%3A%0AGitHub%20Copilot%20usage%20data%20collection%20must%20be%20opted%20in%20under%20your%20enterprise%27s%20AI%20Controls%20settings.%20If%20not%20enabled%2C%20the%20usage%20metrics%20export%20will%20return%20empty%20data.)**

---

<details>
<summary><strong>✅ Requirements</strong></summary>

- Power BI Desktop installed  
- GitHub admin access
- Enforced single sign on to enable connection between enterprise id and github handles
- Opt-in to the Copilot usage metrics policy under "AI Controls"

</details>

<details>
<summary><strong>📥 Get Started</strong></summary>

## ✅ What You’ll Do

<details open>
<summary>📤 Step 1: Export 3 Files</summary>

- **GitHub Copilot Usage Insights** from GitHub 
- **GitHub Members** from GitHub
- **Org data** from Microsoft Entra Admin Center  

</details>

<details open>
<summary>🔐 Step 2: Light up the PBI template by providing file paths</summary>

- Download the .pbit file  
- Paste full file paths for each CSV into the Power BI (PBI) template:
  
</details>



## 📁 Detailed Steps

<details>
<summary>🔍 GitHub Copilot Usage Insights from GitHub</summary>

- Sign in to GitHub with an account that has Enterprise Owner permissions
- Navigate to https://github.com/settings/enterprises and select your Enterprise
  - On the top ribbon, navigate far right to breadcrumbs (...) and access **Insights**    
- Select Copilot Usage  
  - Select Last 28 days option and click download  
- Save it as a .json file  


📖 Learn more: [View Usage and Adoption of Copilot](https://docs.github.com/en/enterprise-cloud@latest/copilot/how-tos/administer-copilot/manage-for-enterprise/view-usage-and-adoption)

</details>

<details>
<summary>👤 GitHub Members from GitHub</summary>

- Sign in to GitHub with an account that has Enterprise Owner permissions.
- In the top-right corner, click your profile picture.
- From the menu: Click Enterprise, or if you manage multiple, click Enterprises and select the enterprise you want.
  - At the top of the enterprise page, click People.
- On the **Members** section:
  - Look to the right side of the page and click CSV Report.
- Download the file:
  - If your enterprise has fewer than 1,000 members, the CSV downloads immediately.
  - If your enterprise has 1,000 or more members, GitHub will email you a link to download the report.

📖 Learn more: [GitHub Members Download](https://docs.github.com/en/enterprise-cloud@latest/admin/managing-accounts-and-repositories/managing-users-in-your-enterprise/exporting-membership-information-for-your-enterprise)

</details>

<details>
<summary>📥 User and Org Data from Entra</summary>

1. Sign in to the [Microsoft Entra admin center](https://entra.microsoft.com)  
2. In the left-hand navigation, go to: `Identity ➝ Users`  
3. Select **All users**  
4. Click the **“Download users”** button (in the toolbar or under the `...` menu)  
5. In the download dialog:  
   - Select the attributes to include in the CSV  
   - **Required fields**:  
     - `UserPrincipalName`  
     - `Department`  
   - **Optional fields**:  
     - Choose as appropriate  
6. Choose **CSV format** and click **Download**

📖 Learn more: [Download a list of users – Microsoft Learn](https://learn.microsoft.com/en-us/entra/identity/users/users-bulk-download)  
💡 _Note: Avoid downloading non-essential attributes as it can degrade performance._

</details>

<details>
<summary>📊 Open Power BI Template & Set File Paths</summary>

- Download the provided Power BI report template (`.PBIT`)
- Open the `.pbit` file in **Power BI Desktop**  
- When prompted, paste in the full file paths for the three CSVs you downloaded:  
  - `GitHub Copilot Usage Insights.csv`  
  - `GitHub Members.csv`  
  - `Org_Data.csv`  
- This will connect the template to your data and begin processing

</details>


</details>

---

## 🤓 Nerd Corner
If you want a window into how GitHub Copilot helped you personally, the value it added, the skills it augmented, how it helped speed up your work

👉 https://github.com/microsoft/What-I-Did-Copilot


