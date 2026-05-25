# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: smoke.spec.ts >> Portfolio Smoke Test
- Location: tests/smoke.spec.ts:3:5

# Error details

```
Error: expect(locator).toBeVisible() failed

Locator: locator('text=Projects')
Expected: visible
Error: strict mode violation: locator('text=Projects') resolved to 2 elements:
    1) <strong>Projects</strong> aka getByRole('link', { name: 'Projects' })
    2) <p>…</p> aka getByText('Audit Platform, Payments ,')

Call log:
  - Expect "toBeVisible" with timeout 5000ms
  - waiting for locator('text=Projects')

```

# Page snapshot

```yaml
- generic [ref=e2]:
  - banner [ref=e3]:
    - heading "Hi. I'm Ishaan Iqbal" [level=1] [ref=e4]:
      - text: Hi. I'm
      - strong [ref=e5]: Ishaan Iqbal
    - paragraph [ref=e6]:
      - strong [ref=e7]: Senior Quality Analyst / QA Lead
      - text: with knowledge of automation testing using Playwright with JavaScript, Cucumber, and API testing using Postman
      - link "@linkedin" [ref=e8] [cursor=pointer]:
        - /url: https://www.linkedin.com/in/ishaan-iqbal/
      - text: .
  - navigation [ref=e9]:
    - list [ref=e10]:
      - listitem [ref=e11]:
        - link "Introduction" [ref=e12] [cursor=pointer]:
          - /url: "#intro"
          - strong [ref=e13]: Introduction
      - listitem [ref=e14]:
        - link "Specialization" [ref=e15] [cursor=pointer]:
          - /url: "#first"
          - strong [ref=e16]: Specialization
      - listitem [ref=e17]:
        - link "Technical Skills" [ref=e18] [cursor=pointer]:
          - /url: "#second"
          - strong [ref=e19]: Technical Skills
      - listitem [ref=e20]:
        - link "Projects" [ref=e21] [cursor=pointer]:
          - /url: "#cta"
          - strong [ref=e22]: Projects
  - generic [ref=e23]:
    - generic [ref=e26]:
      - heading "Professional Summary" [level=2] [ref=e28]:
        - strong [ref=e29]: Professional Summary
      - paragraph [ref=e30]:
        - text: QA Lead at Deloitte with 10+ years of experience delivering high-quality software through a blend of automation and hands-on testing. I specialize in uncovering complex bugs using exploratory testing, browser DevTools, and network throttling, while building robust automation with Playwright, Selenium, and API testing. I work closely with cross-functional teams in Agile environments to ensure reliable, production-ready releases.
        - strong [ref=e31]: ISTQB® and ICAgile
        - text: certified, with a strong focus on improving test coverage, optimizing QA processes, and driving quality across the development lifecycle.
    - generic [ref=e33]:
      - heading "My Expertise" [level=2] [ref=e35]:
        - strong [ref=e36]: My Expertise
      - list [ref=e37]:
        - listitem [ref=e38]:
          - generic [ref=e39]: 
          - heading "Functional Testing" [level=3] [ref=e40]:
            - strong [ref=e41]: Functional Testing
          - paragraph [ref=e42]: In software testing, the goal is to find as many bugs as possible before the customer does.
        - listitem [ref=e43]:
          - generic [ref=e44]: 
          - heading "Automation" [level=3] [ref=e45]:
            - strong [ref=e46]: Automation
          - paragraph [ref=e47]: Automation is not just about speeding up the process; it's about elevating the quality of our work.
        - listitem [ref=e48]:
          - generic [ref=e49]: 
          - heading "API Testing" [level=3] [ref=e50]:
            - strong [ref=e51]: API Testing
          - paragraph [ref=e52]: APIs are the backbone of modern software; testing them ensures our applications stand strong.
    - generic [ref=e53]:
      - generic [ref=e54]:
        - heading "Roles & Responsibilities" [level=2] [ref=e55]:
          - strong [ref=e56]: Roles & Responsibilities
        - paragraph [ref=e57]:
          - text: As part of the enablement project, I supported the integration of Levvia working papers into Omnia, ensuring data integrity, compatibility, and seamless workflows—enabling a unified and efficient audit experience across regions.
          - text: Led QA activities within Agile squads, driving sprint planning, estimation , and quality alignment across developers , product owners and stakeholders
      - list [ref=e58]:
        - listitem [ref=e59]:
          - generic [ref=e60]: 
          - strong [ref=e61]: CICD
          - text: Azure DevOps & Jenkins
        - listitem [ref=e62]:
          - generic [ref=e63]: 
          - strong [ref=e64]: API TESTING
          - text: POSTMAN & API Management
        - listitem [ref=e65]:
          - generic [ref=e66]: 
          - strong [ref=e67]: AUTOMATION
          - text: Playwright,Selenium
        - listitem [ref=e68]:
          - generic [ref=e69]: 
          - strong [ref=e70]: PM
          - text: Microsoft Azure,Jira & Confluence
      - paragraph [ref=e71]: Acted as primary QA point of contact for stakeholders , aligning quality expectations and providing release readiness report. Led end to end release validation , including deployment monitoring via Azure DevOps and testing of Websocket based real time feature, ensuring application stability , performance and reliable handling of concurrent user interactions. Engaged in backend and frontend discussions to validate technical feasibility, data flow impacts, and test coverage for integrated features Defect root cause analysis , find out requirement gaps by doing exploratory testing Validated newly developed APIs by verifying endpoints, request/response structures, http status codes, and JSON data using Microsoft Azure APIM tool. Modified request payloads as needed to ensure accurate data retrieval and alignment with business requirements. Conducted testing using browser DevTools by validating network requests, headers, payloads, and JSON response structures to ensure compliance with business requirements. Executed tests across multiple browsers (Chromium, Firefox, WebKit) using Playwright Used built-in waits and synchronization methods to handle dynamic web elements Utilized Playwright locators (e.g., getByRole, getByText) for stable and reliable element identification Performed end-to-end testing by automation script (Javascript/Typescript) for user workflows such as login, create engagement for audit, and navigation Verify newly created column in DB table using SQL query when user inserts data from back end or front end.
      - generic:
        - list
    - generic [ref=e72]:
      - generic [ref=e73]:
        - heading "Project Summary" [level=2] [ref=e74]
        - paragraph [ref=e75]: Audit Platform, Payments , Collections , Debicheck , Wealth Management , Cross Border Monetary Area Payments Projects & FedEx Logitics Services are some of my projects
      - list [ref=e77]:
        - listitem [ref=e78]:
          - link "Learn More" [ref=e79] [cursor=pointer]:
            - /url: generic.html
  - contentinfo [ref=e80]:
    - generic [ref=e81]:
      - heading "Achivements" [level=2] [ref=e82]
      - paragraph
      - list [ref=e83]:
        - listitem [ref=e84]: Kudos Award received for delivering critical project at SYNTEL for Quarter 4 in 2014.
        - listitem [ref=e85]: Received Client appreciation award for Compliance project at Nedbank in 20019.
        - listitem [ref=e86]: Client appreciation award for Compliance project at Nedbank in 2019.
      - paragraph
      - list [ref=e87]:
        - listitem [ref=e88]:
          - link "Agile Certified" [ref=e89] [cursor=pointer]:
            - /url: https://1drv.ms/b/c/f737a835f1a078c0/IQDPuq4Rw3OXTamtCOJy2QukAfFPYIWYmXWy8x4ITVJok8M?e=DyIN80
        - listitem [ref=e90]:
          - link "ISTQB Certified" [ref=e91] [cursor=pointer]:
            - /url: https://1drv.ms/b/c/f737a835f1a078c0/IQD1aKd0C7G0QJoVAzx3vViLAUJBMg9wKctaTZvZ0lP2yME?e=PRinRc
    - generic [ref=e92]:
      - heading "Contact Details" [level=2] [ref=e93]
      - generic [ref=e94]:
        - term [ref=e95]: Address
        - definition [ref=e96]: 103 Ashwood Manor • Holkam Road , Paulshof, Johannesburg 2191 • SA
        - heading "Contact Me" [level=2] [ref=e97]
        - generic [ref=e98]:
          - generic [ref=e99]:
            - generic [ref=e100]: Name
            - textbox "Name" [ref=e101]:
              - /placeholder: Enter your name
          - generic [ref=e102]:
            - generic [ref=e103]: Email
            - textbox "Email" [ref=e104]:
              - /placeholder: Enter your email
          - generic [ref=e105]:
            - generic [ref=e106]: Reason for Contact
            - combobox "Reason for Contact" [ref=e107]:
              - option "-- Select Reason --" [selected]
              - option "Job Opportunity"
              - option "QA Automation Project"
              - option "Playwright Consultation"
              - option "Freelance Testing Work"
              - option "Interview Discussion"
              - option "Collaboration Opportunity"
              - option "Technical Discussion"
              - option "Reference / Verification"
              - option "General Inquiry"
          - generic [ref=e108]:
            - generic [ref=e109]: Message
            - textbox "Message" [ref=e110]:
              - /placeholder: Enter your message
          - list [ref=e111]:
            - listitem [ref=e112]:
              - button "Send Message" [ref=e113] [cursor=pointer]
        - generic [ref=e114]:
          - term [ref=e115]: Phone
          - definition [ref=e116]: (+27)-618899512
          - term [ref=e117]: Email
          - definition [ref=e118]:
            - link "ishaan.iqbal@hotmail.com" [ref=e119] [cursor=pointer]:
              - /url: "#"
      - list [ref=e120]:
        - listitem [ref=e121]:
          - link "" [ref=e122] [cursor=pointer]:
            - /url: https://www.linkedin.com/in/ishaan-iqbal/
        - listitem [ref=e123]:
          - link "" [ref=e124] [cursor=pointer]:
            - /url: https://github.com/ishaaniqbal
```

# Test source

```ts
  1  | import { test, expect } from '@playwright/test';
  2  | 
  3  | test('Portfolio Smoke Test', async ({ page }) => {
  4  | 
  5  |   console.log('Opening portfolio website');
  6  | 
  7  |   await page.goto('https://ishaaniqbal.github.io/Portfolio/');
  8  | 
  9  |   await expect(page).toHaveTitle('Ishaan Automation Engineer Portfolio');
  10 | 
  11 |   console.log('Website loaded successfully');
  12 | 
  13 |   const sections = ['Introduction', 'Specialization', 'Technical Skills', 'Projects'];
  14 | 
  15 |   for (const section of sections) {
> 16 |     await expect(page.locator(`text=${section}`)).toBeVisible();
     |                                                   ^ Error: expect(locator).toBeVisible() failed
  17 |     console.log(`${section} section verified`);
  18 |   }
  19 | 
  20 |   await page.screenshot({
  21 |     path: 'smoke-test-homepage.png',
  22 |     fullPage: true
  23 |   });
  24 | 
  25 |   console.log('Smoke test completed successfully');
  26 | 
  27 | });
```