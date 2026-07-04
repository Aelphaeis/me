# Joseph Morain – Curriculum Vitae  

📧 joseph.morain@live.ca  

**Profiles:**  
- [GitHub: Aelphaeis](https://github.com/Aelphaeis)  
- [Stack Overflow](http://stackoverflow.com/users/2656813/aelphaeis)  
- [Codewars](https://www.codewars.com/users/Aelphaeis)  

---

## Education  

**Centennial College** – Bachelor of Applied Information Sciences  
*2009 – 2013*  
- Major: Software Systems – Design, Development and Management  

---

## Work Experience  

### Development Manager – *Clio*  
*Jan 2026 – Present* (interim Jan–Jun 2026; appointed Jul 2026)

Took over Clio's Calendar Rules team as interim manager, later appointed permanently. Manage a team of developers building court-rules products (deadline calculation, court-rules data management) across Clio Manage and a standalone Rails service.

- Led the team to #1 in true throughput and top-3 in PR throughput (both measured per developer) among the 89 engineering teams shipping more than 50 PRs this year
- Grew the Calendar Rules add-on from ~$35K to ~$43K monthly recurring revenue (+23%) in six months of team leadership
- Delivered the Update Notifications system through delegated DRI ownership — cross-service webhooks that have sent 64,000+ court-deadline notifications across five production regions since launch — growing two early-career developers into confident project leads
- Discovered and remediated a years-old billing defect, prioritizing ~$11K in proactive customer refunds over roadmap — "do honest work" as team policy
- Ran monthly written performance evaluations, deliberate DRI rotation, and deadline-negotiation practices that eliminated crunch while raising velocity

---

### Senior Software Developer – *Clio*  
*Aug 2021 – Jan 2026*  

- Led the design and delivery of revenue-critical features across Clio's e-filing and billing platforms, including the filing-fee architecture and e-service capabilities behind ClioFile's California market launch
- Designed the data model for e-service records: initiated and facilitated the design discussions, prototyped the approach, implemented the consensus version, and backfilled ~5,000 production filing records across four database shards with zero downtime
- Authored design documents and threat analyses for security-sensitive systems — including a DKIM privilege-escalation analysis for email forwarding and OTP-secured document access — partnering directly with Security
- Sustained one of the organization's highest delivery rates (peaking above 21 merged PRs per week) while owning architecture reviews, production support, and incident response
- Mentored developers through design patterns, threat modeling, and code review; mentee output roughly doubled and peers sought out the workflow
- Championed process improvements later adopted org-wide, including a single-reviewer PR pilot and AI-assisted development tooling and standards

---

### Senior Software Developer – *Echoworx*  
*Mar 2021 – Aug 2021*  
- Mentored and coached interns through code reviews, technical guidance, and evaluation  
- Led the Automated Testing Team, establishing practices that improved release confidence  
- Delivered features in Java from design through deployment, ensuring maintainability and scalability  
- Partnered with stakeholders to clarify requirements and took ownership of project outcomes  

---

### Software Developer – *Echoworx*  
*Oct 2017 – Mar 2021*  
- Developed and enhanced core Java systems, contributing to long-term product stability  
- Collaborated with stakeholders to refine requirements and align technical solutions with business needs  
- Took end-to-end ownership of project delivery, from implementation through production support  

---

### Programmer – *Astley Gilbert*  
*May 2015 – Sep 2017*  
- Designed and maintained software in Java to support business operations  
- Introduced automated unit testing, replacing manual-only validation and improving code reliability  
- Developed logging integrations by building an adapter between log4j and YouTrack, streamlining issue tracking and diagnostics  

---

### Programmer – *Plexxis Software*  
*May 2013 – Sep 2014*  
- Collaborated directly with executives to clarify goals and deliver solutions tailored to business needs  
- Implemented regression testing practices that accelerated debugging in an agile TDD environment  
- Promoted software quality by introducing design patterns and object-oriented best practices to peers  
- Worked with C#, Entity Framework, ODAC, Git, and Microsoft Team Foundation to build enterprise applications  

---

### Junior Programmer – *Fresh Intelligence*  
*May 2012 – May 2013*  
- Built mobile applications for Android and iOS using PHP with Confirmit Platform  
- Worked closely with stakeholders to design mobile solutions supporting client surveys and data collection  
- Assisted in survey implementation and deployment, ensuring functionality across multiple platforms  

---

## Projects  

### Court Rules Discoverability – *Clio*  
*March 2026 – April 2026*

Conceived and solely delivered a growth initiative to surface Clio's court-rules feature at the moments users need it, adding instrumented entry points across the product. Shipped end-to-end — from staged rollout through full ramp and cleanup — while serving as interim Development Manager.

**Impact Highlights:**
- **Grew net-new adoption to ~19× the pre-launch rate (+194 active firms in four weeks, ~5σ above baseline), delivering 128% of the launch's revenue plan for a ~$500K ARR add-on line**
- **Lifted sustained monthly active usage ~12% — from a flat ~1,600 firms/month to ~1,800, holding through the following quarter**
- Added "Add Court Rules" entry points across every e-filing surface, surfaced over 8 million times in the first four months
- Instrumented every entry point and built the analytics dashboards used to measure adoption and conversion

---

### California E-Service Launch – *Clio*  
*December 2025 – March 2026*

Core engineer on the two-person team that delivered Clio File's first e-service capability in California — enabling attorneys to serve court documents electronically alongside e-filings in a state whose filing managers offer no integrated e-service. Brought in for system design and email domain expertise, and shipped to pilot.

**Impact Highlights:**
- **Designed the provider architecture (decorator + strategy patterns) that layered e-service onto the existing e-filing pipeline without disrupting other jurisdictions**
- Built the email-based document service pipeline, including secure, expiring document links and two-factor (OTP) verification for recipient access
- Delivered a zero-downtime, three-stage schema change linking filing records to served contacts, with automated backfill across four database shards
- Implemented document open/view tracking with event notifications back to the filing provider
- Led the cutover of California's e-filing service provider behind a staged rollout

---

### Filing Fee Options System – *Clio*  
*October 2025 – November 2025*

Brought in to lead the delivery of a time-sensitive, mission-critical feature required for ClioFile’s expansion into California. Designed the technical approach and shipped the implementation in time for ClioCon, enabling a major market launch.

**Impact Highlights:**
- **Unblocked entry into California by designing and implementing a new filing fee architecture**
- **Designed and implemented the integration with a third-party e-filing service, defining how fee data is retrieved, transformed, and used across the product**
- Built a maintainable CRUD and workflow system for customer-facing fee management
- Redesigned the estimate experience to incorporate filing fees with improved usability and clearer workflows
- Reduced customer friction through automation and intelligent fee preselection logic
- Enhanced monitoring, error handling, and performance characteristics to support long-term stability

---

### 30-Day Free Trial Implementation – *Clio*  
*June 2025 – August 2025*  

Designed and launched a 30-day free trial system for Clio File as a solo project, leading it end-to-end from design through delivery and production support. Launched on schedule, with over 400 filings created through trial accounts in the months following release.  

**Key Technical Accomplishments:**  
- Defined and implemented new database models and business logic to manage the full trial lifecycle  
- Designed a dynamic pricing mechanism to handle fee waivers and transition logic during the trial period  
- Integrated trial functionality into existing user-facing flows and system components  
- Built internal administrative tooling to monitor and manage trial usage and outcomes  

---

### E-Filing Reconciliation Report – *Clio*  
*June 2024 – September 2024*  

Led the delivery of a reconciliation report system to streamline financial management for enterprise clients. Drove cross-functional alignment with Finance and Product teams to deliver a consolidated, exportable view of e-filing expenses, significantly reducing manual effort and improving accounting accuracy.  

**Key Technical Accomplishments:**  
- Defined the technical direction for an enhanced transaction history page with advanced filtering and sorting  
- Architected CSV export functionality for aggregated transaction views, adopted by Finance for reconciliation workflows  
- Established standards to ensure data integrity and completeness across all exported fields  
- Advocated for a lightweight, maintainable approach, balancing delivery speed with long-term scalability  

---

## Recognition  

- *Draw the Owl* Impact Award – Clio (2024)  
   Honored for demonstrating high agency, innovation, and ownership in delivering impactful solutions. Selected as a winner in one of Clio’s company-wide Impact Award categories, aligned to core cultural values.  

---

## Community Contributions  

- Active GitHub contributor: [github.com/Aelphaeis](https://github.com/Aelphaeis)  
- Stack Overflow: [Profile #2656813](http://stackoverflow.com/users/2656813/aelphaeis)  
- Codewars: [Aelphaeis](https://www.codewars.com/users/Aelphaeis)  

