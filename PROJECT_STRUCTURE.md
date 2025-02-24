## Project Structure ✨

<!-- START_STRUCTURE -->
```
├── LICENSE
├── PROJECT_STRUCTURE.md
├── README.md
├── code_of_conduct.md
├── components.json
├── contributing.md
├── data.json
├── jsconfig.json
├── next.config.mjs
├── package-lock.json
├── package.json
├── postcss.config.mjs
├── public/
│   ├── Logo.svg
│   ├── Mentor 1.jpeg
│   ├── Mentor 2.jpeg
│   ├── Mentor 3.png
│   ├── Newsletter.png
│   ├── avatar.png
│   ├── avatar1.png
│   ├── certi 1.svg
│   ├── certi 2.svg
│   ├── certi 3.svg
│   ├── certi 4.png
│   ├── certi 5.png
│   ├── dev1.jpeg
│   ├── dev2.jpeg
│   ├── dev3.jpeg
│   ├── dev4.jpeg
│   ├── dev5.jpeg
│   ├── dev6.jpeg
│   ├── dev7.jpeg
│   ├── devprod1.jpeg
│   ├── devprod2.png
│   ├── devprod3.jpeg
│   ├── devprod4.png
│   ├── devprod5.jpeg
│   ├── devprod6.jpeg
│   ├── exp1.png
│   ├── exp2.jpeg
│   ├── exp3.jpeg
│   ├── exp4.jpeg
│   ├── exp5.jpeg
│   ├── exp6.jpeg
│   ├── exp7.jpeg
│   ├── goal.webp
│   ├── gro1.png
│   ├── gro2.png
│   ├── gro3.svg
│   ├── gro4.svg
│   ├── hack1.jpg
│   ├── img1.jpg
│   ├── inovate1.png
│   ├── inovate2.png
│   ├── inovate3.png
│   ├── mission.webp
│   ├── ser1.png
│   ├── ser2.png
│   ├── ser3.svg
│   ├── ser4.svg
│   ├── sopt4.jpg
│   ├── spot1.jpg
│   ├── spot2.jpg
│   ├── spot3.jpg
│   ├── story1.jpeg
│   ├── story2.png
│   ├── story3.png
│   ├── story4.jpeg
│   ├── story5.png
│   ├── story6.png
│   ├── story7.png
│   ├── techeq1.webp
│   ├── techeq2.webp
│   └── vision.webp
├── repo_structure.txt
├── src/
│   ├── app/
│   │   ├── (pages)/
│   │   │   ├── About/
│   │   │   │   └── page.jsx
│   │   │   ├── AddEvent/
│   │   │   │   └── page.jsx
│   │   │   ├── AddHackathon/
│   │   │   │   └── page.jsx
│   │   │   ├── AddProjects/
│   │   │   │   └── page.jsx
│   │   │   ├── Certifications/
│   │   │   │   └── page.jsx
│   │   │   ├── Chapters/
│   │   │   │   └── page.jsx
│   │   │   ├── Contact/
│   │   │   │   ├── Contactus.svg
│   │   │   │   └── page.jsx
│   │   │   ├── Events/
│   │   │   │   ├── EventItem.js
│   │   │   │   ├── Events.css
│   │   │   │   └── page.jsx
│   │   │   ├── FAQsForum/
│   │   │   │   ├── FAQs.js
│   │   │   │   ├── Posts.css
│   │   │   │   ├── Posts.js
│   │   │   │   └── page.jsx
│   │   │   ├── GeminiAI/
│   │   │   │   └── page.jsx
│   │   │   ├── Hackathon/
│   │   │   │   ├── Card.jsx
│   │   │   │   ├── [id]/
│   │   │   │   │   └── page.jsx
│   │   │   │   └── page.jsx
│   │   │   ├── PrivacyPolicy/
│   │   │   │   └── page.jsx
│   │   │   ├── Projects/
│   │   │   │   ├── Card.jsx
│   │   │   │   ├── [id]/
│   │   │   │   │   └── page.jsx
│   │   │   │   └── page.jsx
│   │   │   ├── Resources/
│   │   │   │   ├── [id]/
│   │   │   │   │   └── page.jsx
│   │   │   │   ├── page.jsx
│   │   │   │   └── resources.js
│   │   │   ├── RulesAndRegulations/
│   │   │   │   └── page.jsx
│   │   │   ├── SignIn/
│   │   │   │   └── page.jsx
│   │   │   ├── SignUp/
│   │   │   │   └── page.jsx
│   │   │   ├── SingleEvent/
│   │   │   │   └── [id]/
│   │   │   │       └── page.jsx
│   │   │   ├── Stories-Achievements/
│   │   │   │   ├── achievements.js
│   │   │   │   ├── mentors.js
│   │   │   │   └── page.jsx
│   │   │   ├── Subscribe/
│   │   │   │   └── page.jsx
│   │   │   ├── TeamsGallery/
│   │   │   │   ├── Teams.js
│   │   │   │   └── page.jsx
│   │   │   ├── TechToolkits/
│   │   │   │   ├── page.jsx
│   │   │   │   └── techStacks.js
│   │   │   ├── TermsAndConditions/
│   │   │   │   └── page.jsx
│   │   │   ├── api/
│   │   │   │   ├── Certifications/
│   │   │   │   │   ├── data.js
│   │   │   │   │   └── route.js
│   │   │   │   ├── chapters/
│   │   │   │   │   ├── data.js
│   │   │   │   │   └── route.js
│   │   │   │   ├── generate-content/
│   │   │   │   │   └── route.js
│   │   │   │   └── subscribe/
│   │   │   │       └── route.js
│   │   │   ├── careers/
│   │   │   │   ├── [id]/
│   │   │   │   │   └── page.jsx
│   │   │   │   ├── opportunities.js
│   │   │   │   └── page.jsx
│   │   │   ├── devStudent/
│   │   │   │   └── page.jsx
│   │   │   ├── devfest/
│   │   │   │   └── page.jsx
│   │   │   ├── devprod/
│   │   │   │   └── page.jsx
│   │   │   ├── expertdev/
│   │   │   │   └── page.jsx
│   │   │   ├── explore/
│   │   │   │   └── page.jsx
│   │   │   ├── gitContributors/
│   │   │   │   └── page.jsx
│   │   │   ├── growth/
│   │   │   │   └── page.jsx
│   │   │   ├── helpCenter/
│   │   │   │   └── page.jsx
│   │   │   ├── how-apply/
│   │   │   │   └── page.jsx
│   │   │   ├── inovate/
│   │   │   │   └── page.jsx
│   │   │   ├── ioext/
│   │   │   │   └── page.jsx
│   │   │   ├── localdev/
│   │   │   │   └── page.jsx
│   │   │   ├── orginizer/
│   │   │   │   └── page.jsx
│   │   │   ├── participationterms/
│   │   │   │   └── page.jsx
│   │   │   ├── services/
│   │   │   │   └── page.jsx
│   │   │   ├── stories/
│   │   │   │   └── page.jsx
│   │   │   ├── student-challenge/
│   │   │   │   └── page.jsx
│   │   │   ├── sustainable/
│   │   │   │   └── page.jsx
│   │   │   ├── techequity/
│   │   │   │   └── page.jsx
│   │   │   ├── timeline/
│   │   │   │   └── page.jsx
│   │   │   ├── who-apply/
│   │   │   │   └── page.jsx
│   │   │   └── womentechmakers/
│   │   │       └── page.jsx
│   │   ├── api/
│   │   │   └── subscribe/
│   │   │       └── route.js
│   │   ├── favicon.ico
│   │   ├── fonts/
│   │   │   ├── GeistMonoVF.woff
│   │   │   └── GeistVF.woff
│   │   ├── globals.css
│   │   ├── images/
│   │   │   ├── ai_img.jpg
│   │   │   ├── gdsc-logo.png
│   │   │   └── teamMember.jpg
│   │   ├── layout.js
│   │   ├── not-found.jsx
│   │   └── page.js
│   ├── components/
│   │   ├── Chatbot.jsx
│   │   ├── GTranslateLoader.js
│   │   ├── Global/
│   │   │   ├── AddEventForm.jsx
│   │   │   ├── AddHackathonForm.jsx
│   │   │   ├── AddProjectsForm.jsx
│   │   │   ├── Footer.jsx
│   │   │   ├── Header.jsx
│   │   │   ├── Hero.jsx
│   │   │   ├── Navbar.jsx
│   │   │   └── ProductsNavbar.jsx
│   │   └── ui/
│   │       ├── aspect-ratio.jsx
│   │       ├── back2top.jsx
│   │       ├── badge.jsx
│   │       ├── breadcrumb.jsx
│   │       ├── button.jsx
│   │       ├── card.jsx
│   │       ├── carousel.jsx
│   │       ├── collapsible.jsx
│   │       ├── command.jsx
│   │       ├── dialog.jsx
│   │       ├── drawer.jsx
│   │       ├── dropdown-menu.jsx
│   │       ├── form.jsx
│   │       ├── homepage.jsx
│   │       ├── hover-card.jsx
│   │       ├── input.jsx
│   │       ├── label.jsx
│   │       ├── menubar.jsx
│   │       ├── navigation-menu.jsx
│   │       ├── notification.jsx
│   │       ├── progress-bar.jsx
│   │       ├── progress.jsx
│   │       ├── resizable.jsx
│   │       ├── select.jsx
│   │       ├── separator.jsx
│   │       ├── sheet.jsx
│   │       ├── skeleton.jsx
│   │       ├── sonner.jsx
│   │       ├── switch.jsx
│   │       ├── tabs.jsx
│   │       ├── textarea.jsx
│   │       ├── toast.jsx
│   │       ├── toaster.jsx
│   │       └── tooltip.jsx
│   ├── hooks/
│   │   └── use-toast.js
│   ├── lib/
│   │   ├── Hackathon.js
│   │   ├── Projects.js
│   │   ├── cpp-content.js
│   │   ├── dsa-content.js
│   │   ├── dsa-track-content.js
│   │   └── utils.js
│   └── public/
│       └── GDSC-RCIIT Logo.png
└── tailwind.config.js
```
<!-- END_STRUCTURE -->