<div align="center">
  <h1>Hi there, I'm Wallace Zhao </h1>
</div>

<div align="center">
  I'm driven by a curiosity to understand how AI models work and how they can be leveraged to build innovative yet user friendly solutions.
</div>

---

## What I'm Currently Up To

*   Exploring the intricacies of LLMs, from foundational concepts like RAG architectures to practical applications in conversational AI.
*   Continuously refining my Python skills, focusing on libraries and techniques crucial for AI/ML development.
*   Seeking opportunities to apply my AI development and full-stack skills to new and challenging projects.
*   Brainstorming ideas for projects that further merge my mobile/web development background with my growing expertise in LLMs.

---

## Featured Projects

<details>
  <summary><strong>Stars Orthodontics AI Assistant - Award-Winning RAG AI Implementation</strong></summary>
  <br>
  <p>
    <strong>Overview:</strong> To address high patient call volumes and language barriers at Stars Orthodontics, our team developed an award-winning Progressive Web App (PWA) integrating a custom AI assistant. Recognized with a <strong>2nd Place award by Algonquin College (Applied Research Day)</strong>, the Next.js PWA empowers patients with 24/7 self-service for clinic information and appointment requests. The AI assistant, built on a Retrieval-Augmented Generation (RAG) architecture using OpenAI and Pinecone, provides reliable multilingual support (text and voice) based strictly on clinic-approved data.
  </p>
  <p>
    <strong>My Role & Contribution (AI Developer | Team of 6 | 4 Months):</strong>
    <ul>
      <li>Led the AI development, architecting the end-to-end solution including frontend, backend conversational flow (Flowise), and RAG infrastructure (OpenAI, Pinecone).</li>
      <li>Implemented real-time, multilingual speech-to-speech functionality and engineered prompts for a multi-path agent router (Greeting, FAQ, Booking).</li>
      <li>Developed the interactive Next.js chat interface with session-based context, suggestion chips, and integrated privacy information.</li>
      <li>Deployed and managed the application infrastructure using Docker on Digital Ocean, ensuring concurrency for multiple users.</li>
    </ul>
  </p>
  <p>
    <strong>Key Challenges & Solutions:</strong>
    <ul>
      <li><strong>Concurrent Users:</strong> Scaled Flowise worker services horizontally (Docker) and planned for vertical scaling on Digital Ocean.</li>
      <li><strong>Slow RAG Retrieval:</strong> Optimized FAQ document structure and conciseness for faster, more relevant information retrieval.</li>
    </ul>
  </p>
  <p>
    <strong>Outcomes & Impact:</strong> Delivered a production-ready, multi-agentic AI assistant, achieving scalable architecture (99.9% uptime) and demonstrating significant AI potential for patient engagement to the client.
  </p>
  <p>
    <strong>Tech Stack:</strong> Next.js, PWA, OpenAI API, Pinecone, Flowise, RAG, Session Storage, Bearer Token Authentication, PIPEDA Compliance, Docker, Digital Ocean, XSS Protection, Markdown.
  </p>
  <p>
<!--     <em><a href="/" target="_blank">View Code (Specify if Private)</a> | <a href="" target="_blank">View Demo</a></em> -->
  </p>
</details>

<details>
  <summary><strong>Tranquil Telehealth - Designing an Intuitive Virtual Care Experience</strong></summary>
  <br>
  <p>
    <strong>Overview:</strong> A conceptual platform designed to simplify virtual healthcare access. This project focused on creating a user-centered telehealth solution with easy appointment booking, centralized medical records, and clear communication, prioritizing security, privacy, and user trust through an intuitive interface.
  </p>
  <p>
    <strong>My Role & Contribution (UX/UI Designer | Solo Project | 3 Months):</strong>
    <ul>
      <li>Conducted product and user research (including sentiment analysis with BigQuery) to define patient personas, needs, and pain points.</li>
      <li>Designed the Information Architecture (IA) and developed user scenarios for the primary patient persona.</li>
      <li>Created low-fidelity sketches, mid-fidelity wireframes, and high-fidelity interactive prototypes in Figma.</li>
      <li>Conducted usability testing sessions and iterated on designs based on qualitative feedback, establishing a foundational design system.</li>
    </ul>
  </p>
  <p>
    <strong>Key Challenges & Solutions:</strong>
    <ul>
      <li><strong>Accessibility (WCAG):</strong> Ensured compliance through WCAG guidelines, contrast checkers, and readable typography.</li>
      <li><strong>Visual Trust Building:</strong> Adopted a clean, calm aesthetic with professional typography and transparent feedback to convey security and empathy.</li>
    </ul>
  </p>
  <p>
    <strong>Outcomes & Impact:</strong> Delivered a high-fidelity, interactive Figma prototype demonstrating core patient user flows, validated by usability testing. Successfully incorporated user feedback, improving task flows and interface clarity, and addressed key accessibility considerations.
  </p>
  <p>
    <strong>Tech Stack:</strong> Figma, BigQuery, WCAG Guidelines.
  </p>
  <p>
    <a href="" target="_blank">View Figma Prototype</a>
  </p>
</details>

<details>
  <summary><strong>FreeUp - Full-Stack Local Item Exchange Platform</strong></summary>
  <br>
  <p>
    <strong>Overview:</strong> FreeUp is a full-stack web application enabling users to list items for free and discover items nearby. It features an interactive Google Maps interface, Google OAuth authentication, secure image uploads to Google Cloud Storage, and a RESTful API managing item exchange states.
  </p>
  <p>
    <strong>My Role & Contribution (Full-Stack Developer | Solo Project | 1 Months):</strong>
    <ul>
      <li>Designed and developed the full-stack architecture: Next.js frontend (Tailwind CSS) and Node.js/Express backend.</li>
      <li>Implemented Google Maps API for location display/directions, and Google OAuth (Passport.js) with JWTs for authentication.</li>
      <li>Developed MongoDB (Mongoose) schemas with GeoJSON for location queries and integrated Google Cloud Storage (Multer) for image uploads.</li>
      <li>Built the RESTful API with a defined state machine for item exchange, ensuring data validation and security (XSS protection).</li>
    </ul>
  </p>
  <p>
    <strong>Key Challenges & Solutions:</strong>
    <ul>
      <li><strong>Full-Stack Integration & Auth:</strong> Seamlessly connected Next.js and Node.js/Express, managing JWTs in HttpOnly cookies via Next.js middleware.</li>
      <li><strong>Item Exchange State Management:</strong> Designed a robust state machine with dedicated backend services and API endpoints for transitions.</li>
    </ul>
  </p>
  <p>
    <strong>Outcomes & Impact:</strong> Developed a functional platform for local item exchange with location-aware search, interactive maps, secure authentication, and a clear state-managed workflow.
  </p>
  <p>
    <strong>Tech Stack:</strong> Next.js, Tailwind CSS, Node.js, Express.js, MongoDB, Mongoose, GeoJSON, Google Maps API, Google OAuth 2.0, Passport.js, JWT, Multer, Google Cloud Storage, RESTful API, XSS Protection.
  </p>
  <p>
<!--     <a href="" target="_blank">View Code</a> | 
    <a href="" target="_blank">Live Demo</a> -->
  </p>
</details>


---

## My Learning Roadmap & Goals

I'm committed to lifelong learning. Here's what's currently on my learning agenda:

*   [x] **Python:** Strengthening core concepts and advanced features for AI/ML.
*   [x] **RAG Architectures:** Hands-on experience with OpenAI, Pinecone, Flowise.
*   [ ] **Advanced Machine Learning:**
    *   [ ] Scikit-learn
    *   [ ] PyTorch
*   [ ] **LLM Platforms & Tools:**
    *   [ ] Amazon Bedrock
    *   [ ] Google Agent Development

---

## My Tech Stack

<div align="center">
  <i>A collection of tools and technologies I've worked with and am growing with:</i>
</div>
<br>

<table>
  <tr>
    <td valign="top" width="33%">
      <h3 align="center">Frontend & Mobile</h3>
      <div align="center">
        <a href="https://reactjs.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/react-original-wordmark.svg" alt="React" height="40" /></a>
        <a href="https://nextjs.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/nextjs.png" alt="NextJS" height="40" /></a>
        <a href="https://flutter.dev/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/flutterio-icon.svg" alt="Flutter" height="40" /></a>
        <a href="https://www.javascript.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/javascript-original.svg" alt="JavaScript" height="40" /></a>
        <a href="https://www.typescriptlang.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/typescript-original.svg" alt="TypeScript" height="40" /></a>
        <a href="https://www.w3schools.com/css/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/css3-original-wordmark.svg" alt="CSS3" height="40" /></a>
        <a href="https://en.wikipedia.org/wiki/HTML5" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/html5-original-wordmark.svg" alt="HTML5" height="40" /></a>
        <a href="https://www.tailwindcss.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/tailwindcss.svg" alt="Tailwind CSS" height="40" /></a>
        <a href="https://mui.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/mui.png" alt="Material UI" height="40" /></a>
      </div>
    </td>
    <td valign="top" width="33%">
      <h3 align="center">Backend & Databases</h3>
      <div align="center">
        <a href="https://www.python.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/python-original.svg" alt="Python" height="40" /></a>
        <a href="https://nodejs.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/nodejs-original-wordmark.svg" alt="Node.js" height="40" /></a>
        <a href="https://expressjs.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/express-original-wordmark.svg" alt="Express.js" height="40" /></a>
        <a href="https://www.mongodb.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/mongodb-original-wordmark.svg" alt="MongoDB" height="40" /></a>
        <a href="https://www.postgresql.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/postgresql-original-wordmark.svg" alt="PostgreSQL" height="40" /></a>
        <a href="https://redis.io/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/redis-original-wordmark.svg" alt="Redis" height="40" /></a>
        <a href="https://www.prisma.io/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/prisma.png" alt="Prisma" height="40" /></a>
        <a href="https://www.cplusplus.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/cplusplus-original.svg" alt="C++" height="40" /></a>
      </div>
    </td>
    <td valign="top" width="33%">
      <h3 align="center">AI/ML & DevOps</h3> <!-- Merged AI/ML here -->
      <div align="center">
        <a href="https://git-scm.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/git-scm-icon.svg" alt="Git" height="40" /></a>
        <a href="https://www.docker.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/docker-original-wordmark.svg" alt="Docker" height="40" /></a>
        <a href="https://kubernetes.io/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/kubernetes-icon.svg" alt="Kubernetes" height="40" /></a>
        <a href="https://cloud.google.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/google_cloud-icon.svg" alt="GCP" height="40" /></a>
        <a href="https://firebase.google.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/firebase.png" alt="Firebase" height="40" /></a>
        <a href="https://www.nginx.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/nginx-original.svg" alt="Nginx" height="40" /></a>
      </div>
    </td>
  </tr>
  <tr>
    <td colspan="3" valign="top"> <!-- Adjusted colspan -->
      <h3 align="center">Design & Other Tools</h3>
      <div align="center">
        <a href="https://www.figma.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/figma-icon.svg" alt="Figma" height="40" /></a>
        <a href="https://www.adobe.com/in/products/photoshop.html" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/photoshop-plain.svg" alt="Photoshop" height="40" /></a>
        <a href="https://www.adobe.com/in/products/illustrator.html" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/adobe_illustrator-icon.svg" alt="Illustrator" height="40" /></a>
        <!-- Removed Lightroom & Tableau as they weren't in project tech, add back if needed -->
      </div>
    </td>
  </tr>
</table>

---


## My GitHub Stats

      
<div align="center">
  <table>
    <tr>
      <td>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Zhao0148&layout=compact&theme=radical&hide_border=true&langs_count=10&exclude_repo=forked_repo1,forked_repo2" alt="Top Languages" />
      </td>
      <td>
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=Zhao0148&theme=radical&hide_border=true" alt="GitHub Streak" />
      </td>
    </tr>
  </table>
</div>

    

<br>
