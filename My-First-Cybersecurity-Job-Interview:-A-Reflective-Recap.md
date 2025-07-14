# My First Cybersecurity Job Interview: A Reflective Recap

About a month ago, I had my very first cybersecurity job interview. It was for an **IT DevOps Analyst** role with a well-established **S&P 500 real estate investment trust (REIT)**—a rare opportunity, and certainly not something I was expecting. Truthfully, I couldn’t even remember applying for the position, but once I got the email, I figured I’d take it as a sign to get some formal interview experience outside of law enforcement. I already had a feeling that the job might not align with my current focus, but I wanted to push myself to try something unfamiliar and see what I could learn from the process.

Leading up to the interview, I was surprisingly calm. I felt prepared—not overly confident, but definitely focused. The nerves didn’t take over like I thought they might. Instead, I welcomed the challenge. One thing that stood out to me: the interviewer joined the call about eight minutes late. While I understand delays happen, punctuality is something I really value, especially when it comes to professional opportunities. I showed up early, prepared, and focused, which I believe reflects how I’d approach any role I step into.

---

## Interview Breakdown

The interview itself moved quickly and covered a solid mix of technical and scenario-based questions. While I anticipated some talk around scripting and cloud, I was impressed by how layered the questions were — clearly aimed at gauging both foundational knowledge and how I approach real-world problem solving.

### 🔧 PowerShell Scripting & Automation
I walked through how I’ve used PowerShell during my internship to automate remediation efforts related to DISA STIGs. In one project, I built and ran scripts to apply secure configuration baselines across multiple Windows systems. These scripts addressed critical vulnerabilities and significantly reduced the manual workload. I made a point to emphasize how automation can speed things up, but I always validate outcomes with follow-up scans and log reviews to make sure nothing slips through the cracks.

### ☁️ Cloud Exposure & Vulnerability Management

Another question touched on cloud provisioning, and while I haven’t spun up an enterprise-level cloud environment on my own yet, I drew from my experience using Microsoft Defender XDR and Tenable.io during my internship. One specific project involved identifying and tracking exposed cloud-hosted assets that were missing endpoint protection or proper configuration. I performed credentialed vulnerability scans through Tenable, which helped pinpoint unmanaged devices or systems with outdated security baselines. Once discovered, I documented the risks and cross-referenced with Defender alerts to validate exposure and escalate accordingly.

While I’m still building hands-on infrastructure skills in Azure, I used this opportunity to highlight how I’m learning cloud security concepts in a practical setting, including interpreting risk scores, investigating attack paths, and following remediation recommendations aligned with security baselines like CIS and NIST 800-53.


### 🛠️ Troubleshooting App Behavior vs Documentation
We also discussed troubleshooting scenarios—especially around applications that don’t behave the way the documentation says they should. I brought up a moment from my internship where I ran a PowerShell-based hardening script, but a credentialed scan with Tenable showed several STIG vulnerabilities still present. I could’ve just assumed it worked, but instead, I retraced the steps, reviewed the logs, and found the issue: there were conflicting Group Policy Objects (GPOs) that blocked certain changes. I adjusted the script, applied the changes in segments, and verified resolution through another scan. It was a reminder that even good automation requires active oversight and critical thinking.

### 🚀 Understanding DevOps Tools
As for DevOps tools, I was transparent that I haven’t worked in a dedicated DevOps environment yet. But I highlighted what I do know — how CI/CD pipelines support secure code deployment, how tools like Infrastructure-as-Code streamline configuration management, and how these principles connect to secure build practices. I also mentioned that I’m actively learning more in this space, especially through my hands-on labs and ongoing prep for the SC-200 certification.

There were other questions as well — some that I honestly don’t remember word-for-word — but they all reinforced the same thing: this field values not only technical knowledge, but how you think, how you solve problems, and how well you can adapt under pressure.

---

## Final Thoughts

After the interview, I found myself reflecting not just on the questions, but on how much I’ve grown. Coming from law enforcement, these kinds of technical conversations used to feel intimidating. But this one showed me I can hold my own. I understood the questions, answered honestly, and stayed calm under pressure. Even if I don’t get a callback (and at this point, I’m assuming I didn’t), I left with something far more valuable: **confidence**.

Would I have accepted the offer? Maybe. With the commute, the role would’ve had to feel right for me—not just financially, but in terms of growth and contribution. I’m not afraid of starting small, but I want to be somewhere that values long-term learning and building something meaningful.

Right now, I’m continuing my internship with **Log(N) Pacific**, gaining real-world experience in vulnerability management, EDR/XDR detection, and threat hunting. I’m working toward my **Microsoft SC-200 certification** and building out projects that I document in my [GitHub portfolio](https://github.com/GScalzo21).

---

Thanks for reading. If you’re just getting started in cybersecurity, take that first interview—even if it’s not a perfect fit. You’ll learn, grow, and come out stronger on the other side.
