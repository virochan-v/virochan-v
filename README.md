<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,30:2d1f00,70:FFB000,100:0D1117&height=240&section=header&text=VIROCHAN%20V&fontSize=64&fontColor=FFB000&fontAlignY=38&desc=Software%20Engineer%20%7C%20Java%20Developer%20%7C%20DSA%20Specialist&descAlignY=57&descSize=18&animation=fadeIn&fontAlign=50" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=2800&pause=1000&color=FFB000&center=true&vCenter=true&width=800&height=50&lines=root%40virochan%3A~%24+whoami;%E2%86%92+Logic-First+Problem+Solver;%E2%86%92+HackWithInfy+2026+%E2%80%94+L2+Competency+Qualifier+%E2%9C%93;%E2%86%92+371%C3%97+faster+%7C+one+algorithm+at+a+time;%E2%86%92+Open+to+SWE+%7C+Backend+%7C+Java+Full-Stack" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/virochan-v)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:virochan.tech@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/virochan-v)
[![HackerRank](https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/profile/virochan_v)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/virochan_v/)

</div>

---

## `$ ./boot --profile virochan-v`

<div align="center">
<img src="terminal.svg" width="100%" alt="Virochan V — Animated Terminal Boot Sequence"/>
</div>

---

## `$ cat my_story.log`

I didn't start with frameworks — I started with **why.** A question about the real cost of linear search at scale led to a **371× speedup**, which became LogShield, which cleared **HackWithInfy 2026 at the L2 Competency level**, placing me among the top tier nationally. The same first-principles thinking won startup stages at **IIFT Kakinada (1st Prize)** and **NIT Tiruchirappalli (2nd Runner-Up)**, earned 4 Oracle cloud certifications, and got a paper presented at the **13th International Biltek Congress.** I'm now evolving LogShield into a **Spring Boot REST API** — not to collect frameworks, but because the backend world I want to build in lives there.

> [!TIP]
> 💡 **Philosophy:** Every business problem is an algorithm problem in disguise. I engineer solutions from data structures up — not frameworks down.

---

## `$ cat about_me.log`

```yaml
name        : Virochan V
college     : R.M.D. Engineering College — B.Tech CSBS | CGPA: 7.94 / 10.0
graduation  : May 2027  |  location: Tamil Nadu, India
identity    : Logic-First Problem Solver
target      : Software Engineer · Java Backend · Full-Stack
superpower  : Turning O(n) into O(log n) — and knowing exactly why it matters
```

---

## `$ cat system.status`

<table>
<tr>
<td width="50%" valign="top">

### 🔨 Currently Building
- [ ] **LogShield v2** — CLI → Spring Boot REST API *(active)*
- [ ] **Microsoft Azure** — Cloud architecture fundamentals *(learning)*

</td>
<td width="50%" valign="top">

### ✅ Certifications

<details>
<summary><b>🏅 View All 8 — with verification links</b></summary>
<br/>

| | Certification | Verify |
|:---:|---|:---:|
| 🏅 | OCI Multicloud Architect Professional | [Credly](https://www.credly.com) |
| 🏅 | Oracle AI Foundations Associate | [Credly](https://www.credly.com) |
| 🏅 | OCI Generative AI Professional | [Credly](https://www.credly.com) |
| 🏅 | OCI Foundations Associate | [Credly](https://www.credly.com) |
| 📚 | NPTEL — Human Computer Interaction · **Elite 96%** | [NPTEL](https://nptel.ac.in) |
| 📚 | NPTEL — Introduction to Machine Learning | [NPTEL](https://nptel.ac.in) |
| 📚 | NPTEL — Google Cloud Computing Foundations | [NPTEL](https://nptel.ac.in) |
| 📝 | TOEFL ITP 603/677 — C1 Listening & Reading | — |

</details>

![OCI](https://img.shields.io/badge/Oracle_Multicloud_Architect-F80000?style=flat-square&logo=oracle&logoColor=white)
![GenAI](https://img.shields.io/badge/Oracle_Gen_AI_Professional-F80000?style=flat-square&logo=oracle&logoColor=white)
![NPTEL](https://img.shields.io/badge/NPTEL_Elite_96%25-0056D2?style=flat-square)

</td>
</tr>
</table>

---

## `$ ls tech_stack/`

<div align="center">
<img src="https://skillicons.dev/icons?i=java,mysql,git,github,linux,azure,postman,idea&theme=dark&perline=4" />
</div>

---

## `$ cat projects/LogShield.md`

<div align="center">

### 🛡️ LogShield — Real-Time Log Anomaly Detector
*A CLI-based log analysis engine in Core Java. Every design decision justified by algorithmic complexity — not convenience.*

</div>

| Layer | Structure | Purpose | Complexity |
|---|---|---|---|
| 🔍 Pattern Indexing | `Trie` | Prefix-based anomaly lookup | $O(m)$ per query |
| 📊 Severity Ranking | `Cyclic Sort` | Minimal memory writes | $O(n)$ · $O(1)$ space |
| 📂 Log Retrieval | `Binary Search` | Sub-linear lookup at scale | $O(\log n)$ |
| 🏆 Top-K Alerts | `MinHeap` | Efficient anomaly ranking | $O(n \log k)$ |
| 🏗️ Architecture | `Singleton · Factory · Observer` | Resource mgmt & extensibility | — |

> [!NOTE]
> ⚡ **Benchmark:** Binary Search vs Linear Scan · 10,000 entries · `Linear: 2,847ms` → `Binary: 7ms` → **371× faster**

<details>
<summary><b>☕ The code behind 371× — click to expand</b></summary>
<br/>

```java
// LogShield — BinarySearchRetriever.java
// O(log n) vs O(n): same data, better algorithm — 371× the result

public int retrieve(List<LogEntry> sortedLogs, String targetPattern) {
    int lo = 0, hi = sortedLogs.size() - 1;

    while (lo <= hi) {
        int mid = lo + (hi - lo) / 2;           // avoids integer overflow
        int cmp = sortedLogs.get(mid)
                            .getPattern()
                            .compareTo(targetPattern);

        if (cmp == 0) return mid;                // O(log n) exit
        if (cmp < 0)  lo = mid + 1;
        else          hi = mid - 1;
    }
    return -1;
}
```

</details>

<details>
<summary><b>🔍 System Architecture Diagram</b></summary>
<br/>

```mermaid
flowchart LR
    A([📄 Log File\n10K+ entries]) --> B[⚡ LogShield Engine]
    B --> C[🔍 Trie\nO m per query]
    B --> D[🔃 Cyclic Sort\nO n · O 1 space]
    B --> E[🔎 Binary Search\nO log n]
    B --> F[📊 MinHeap\nO n log k]
    C & D & E & F --> G{🔔 Observer\nAlert Dispatcher}
    G --> H([🚨 Anomaly Report])
    G --> I([📈 Benchmark Output])
    subgraph GoF Patterns
        J[Singleton · Factory]
    end
```

</details>

<div align="center">

[![View LogShield](https://img.shields.io/badge/View_Repository-FFB000?style=for-the-badge&logo=github&logoColor=black)](https://github.com/virochan-v/LogShield)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![v2 in progress](https://img.shields.io/badge/v2-Spring_Boot_In_Progress-FFB000?style=for-the-badge)

</div>

---

## `$ cat achievements.log`

<div align="center">

| | Achievement | Event | Year |
|:---:|---|---|:---:|
| 🥇 | **1st Prize** + ₹10,000 | Fuse: Start-up Hackathon — IIFT Kakinada | 2025 |
| 🥉 | **2nd Runner-Up** | PitchStorm — NIT Tiruchirappalli (National) | 2025 |
| ⚡ | **L2 Competency Qualifier** — Top-tier nationally | HackWithInfy 2026 | 2026 |
| 📄 | **International Paper Presenter** | 13th Biltek Congress — Quantum Computation | 2025 |
| 🧑‍💼 | **Organizing Committee** — "One Pitch" Lead | DEXTERO '26 National Tech Symposium | 2026 |
| 💼 | **Software Developer Intern** | CODTECH IT SOLUTIONS PVT LTD | 2025 |

</div>

---

## `$ cat work.history`

**Software Developer Intern** · CODTECH IT SOLUTIONS PVT LTD · *Jul – Aug 2025*
- Developed and tested application modules using **Java** and web technologies
- Contributed to **API development** and backend business logic implementation

---

## `$ run github_stats --render`

<div align="center">
<img src="https://streak-stats.demolab.com/?user=virochan-v&hide_border=true&background=0D1117&ring=FFB000&fire=FFB000&currStreakLabel=FFB000&sideLabels=FFB000&dates=C9D1D9&currStreakNum=FFFFFF&sideNums=FFFFFF&card_width=700" />
</div>

---

## `$ run leetcode_stats --user virochan_v`

<div align="center">
<img src="https://leetcard.jacoblin.cool/virochan_v?theme=dark&font=source_code_pro&ext=heatmap&border=0&radius=10" />
</div>

---

## `$ tail -f activity.log`

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=virochan-v&bg_color=0D1117&color=FFB000&line=FFB000&point=FFFFFF&area=true&area_color=FFB000&hide_border=true&custom_title=Contribution%20Activity" width="100%"/>
</div>

---

## `$ git log --recent --author=virochan-v`

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

---

## `$ connect.init() --open-to-work`

> [!IMPORTANT]
> 🟢 **Open to Software Engineering · Backend · Java Full-Stack**
> Internships & Full-Time · Response within 24hrs · Full-time available May 2027

<div align="center">

<br/>

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/virochan-v)
[![Gmail](https://img.shields.io/badge/Say_Hello-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:virochan.tech@gmail.com)
[![HackerRank](https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/profile/virochan_v)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/virochan_v/)

<br/>

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark&quote=First%2C%20solve%20the%20problem.%20Then%2C%20write%20the%20code.&author=John%20Johnson" />

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,30:2d1f00,70:FFB000,100:0D1117&height=120&section=footer&animation=fadeIn" width="100%"/>

</div>
