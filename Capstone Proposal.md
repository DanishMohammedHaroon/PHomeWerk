# Project Title
PHomeWerk (P for Physio, Home because it will be done at home or in a personal environment and Werk... because work is more fun and do-able when it does not sound like work!)... I will refer it to as PHW.

## Overview

Life is a loop—a routine that constantly takes feedback and adjusts, allowing us to maintain a balanced way of living. PHomeWerk (PHW) harnesses this concept to revolutionize physiotherapy by bridging the gap between in-person and remote care.

User Side (Physiotherapists):
PHW is all about providing physiotherapists with better feedback and enhanced patient care. With our platform, they can effortlessly assign exercises to clients, set specific repetitions and difficulty levels, and monitor progress in real time. This seamless integration means that even after an in-person visit, adjustments to a workout or treatment regime can be made remotely, ensuring that every patient receives tailored care.

Client Side (Patients):
For patients, PHW offers accountability, tracking, and remote access to exercises, ensuring they never feel disconnected from their treatment. The app allows patients to immediately notify their physiotherapists if an exercise isn’t working for them, creating an immediate feedback loop that optimizes recovery. Whether it's tracking progress or receiving timely reminders, PHW keeps patients engaged and supports a continuous cycle of improvement. It is also a method of holding the patients accountable to do the exercises and improve self discipline which is always necessary when it comes improving the quality of life.

### Problem Space

When covid hit we all lost access to life's necessities, access to healthcare was one of them, in our community of St. John's, NL we have the bulk of our population either in the working age (15 - 65) with heavier emphasis on the later years, and we have a higher than average elderly population (_see_ the _statistics link_). For them (15- 65 age demographic) to be working optimally access to physical health and wellbeing is necessary and, especially in health care, access to physiotherapy is a must. A lot of businesses went from brick and mortar to e-commerce and Doctors's went from seeing in-patients to booking calls over the phone and video calling. In all of this some fields were missed out and general workers, from fishermen to health care workers to athletes to physical labourers... all lost access to what supports them when their jobs have wear and tear on their bodies. This app is to start a process of healing that deficiency, its geared towards a simple interface, which is easy to use and allows remote interaction between the Phyhsiotherapist and the patient build that feedback loop into the circle of care.

_statistics link_:https://www12.statcan.gc.ca/census-recensement/2021/dp-pd/prof/details/page.cfm?Lang=E&SearchText=st%2E%20john%27s&GENDERlist=1,2,3&STATISTIClist=1&DGUIDlist=2021A00051001519&HEADERlist=0

### User Profile

Physiotherapists (User Side):

Licensed professionals who traditionally provide in-person physiotherapy and are now or more likey will be adapting to remote care with the implementation of PHW.
How will they utilize PHW: They use the app to assign personalized exercise routines, adjust treatment plans in real time based on patient feedback, and monitor patient progress remotely.
Special Considerations: The platform must integrate seamlessly into their workflow, offering easy-to-use tools that enhance, rather than complicate, their treatment processes.

Patients (Client Side):

Who They Are: Individuals ranging from working-age adults to seniors who rely on physiotherapy to manage pain, recover from injuries, or maintain overall physical health.
How They Use PHW: They use the app to access prescribed exercises, track their progress, receive timely reminders, and quickly communicate any issues with their exercises to their physiotherapist.
Special Considerations: The interface must be user-friendly and accessible, enabling seamless communication for the not so tech savvy. 

### Features
This might sound more like an advert. but here it is....

**Physiotherapists (User Side):**

1. Exercise Assignment:
Empower your practice with the ability to effortlessly assign personalized exercise routines. Tailor every session by setting the perfect number of repetitions and difficulty levels to match each client’s unique needs.
User Story: “As a physiotherapist, I want to assign custom exercises so that my patients receive the exact care they deserve.”

2. Progress Tracking & Feedback:
Stay in tune with your clients’ progress! Our app lets you see not only whether a routine was completed, but also gathers valuable insights on any parts that felt challenging. This means you can fine-tune every detail of your treatment plan.
User Story: “As a physiotherapist, I want to receive clear feedback on exercise completion so I can adjust and perfect my treatment plans.”

3. Remote Communication for Updates:
Communicate seamlessly without interrupting your patients' daily lives. With an easy-to-use system, send updates and improvements directly, ensuring your advice reaches them promptly and effectively.
User Story: “As a physiotherapist, I want to update my patients remotely so that I can help them improve their routines effortlessly.”

**Patients (Client Side):**

1. Accountability:
Stay on track and feel supported every step of the way. The app is designed to keep you engaged and committed to your exercise routine, ensuring you never miss a beat in your journey to better health.
User Story: “As a patient, I want consistent reminders and check-ins so that I remain dedicated to my recovery.”

2. Tracking Progress:
Celebrate your wins! Easily log your exercise routines and watch your progress unfold through clear, visual metrics that keep you motivated and inspired.
User Story: “As a patient, I want to track my progress so that I can see the improvements and feel proud of my hard work.”

3. Immediate Feedback:
Provide instant updates on how you’re feeling about your exercises. This quick and direct feedback ensures that no detail is missed, allowing your physiotherapist to make timely adjustments to your routine.
User Story: “As a patient, I want to give immediate feedback so that any issues are addressed right away, keeping my recovery on track.”

**All Users:**

1. Secure Communication:
Enjoy peace of mind with with a better way of communicating discreet problems than voicing them out verbally.

2. Anytime, Anywhere Exercising and Reporting:
Whether you’re at home, at work, or on the go, our app is there for you. It lets you exercise and report progress from any location, making your health journey as flexible as your lifestyle.

3. Extremely User-Friendly Interface:
Experience simplicity and elegance in design. Our platform is built to be accessible and intuitive for everyone, regardless of their comfort level with technology, ensuring a smooth and enjoyable user experience for all.


## Implementation

### Tech Stack

**Libraries I intend to use:**

1. React.js: 
Used to build a responsive, dynamic, and intuitive front-end interface.

2. Node.js with Express: 
Powers the backend APIs to handle requests and manage server-side logic seamlessly.

3. Sass:
Used for advanced CSS and SCSS styling, allowing you to write modular, reusable, and maintainable styles.

4. Axios:
Simplifies API calls by handling HTTP requests and responses between the front-end and back-end effortlessly.

5. Cors:
Ensures secure cross-origin resource sharing, allowing your API to communicate safely with the front-end.

6. React Router DOM:
Enables seamless navigation and dynamic routing in your React application for a smooth user experience.

6. dotenv:
Manages environment variables securely, keeping sensitive data like API keys and configuration settings out of your codebase.

7. React Query:
Handles asynchronous data fetching and caching, making server state management more efficient and responsive.

8. React Modal:
Provides accessible modal dialogs for pop-up interactions, enhancing the user interface without compromising on usability.

**Libraries that I might use but i am still researching:**

1. React Toastify:
For non-intrusive notifications and alerts that inform users about updates, successes, or errors in real time.

2. Formik and Yup:
For robust form handling and validation, ensuring data integrity and improving user input experiences.

3. Redux (or Zustand):
For managing global state, particularly useful if your application scales and state management becomes more complex.

4. Jest:
For unit testing, helping you ensure that your components and functions perform as expected.

5. Tailwind CSS:
A utility-first CSS framework that allows you to rapidly build custom designs directly in your markup. It can be easily integrated with React and Sass for more control over your styling.

### APIs

I intend on making my own server to host most of the data and validation. I havent found any physiotherapy API's but there are some interesting options that I might use and repurpose: 

1. API Ninjas Exercises API:
This API provides access to thousands of exercises, including details like muscle groups, equipment, and difficulty levels. It’s free up to a certain number of requests, this can be a good kickoff, but the limit is the drawback.

2. ExerciseDB API on RapidAPI:
With a collection of over 1,300 exercises, this API categorizes exercises by body part, equipment, and type. It’s available with a free tier, which gives me more information but is still limited by tier costs.

3. Free Exercise DB on GitHub:
Although not a traditional API, this open-source JSON dataset contains data on 800+ exercises. this is really interesting as it can serve as my dataset. 

4. Auto-generate exercises on CHAT-GPT and other AI respurces, leverage them to create data for my Database. This I would use if I do not have enough data needed for my specific purpose. When implemented in real life this database can be populated
by actual data from Physiotherapists using the app during beta-testing phase (and even after if it makes it tot  the market).

### Sitemap

List the pages of your app with brief descriptions. You can show this visually, or write it out.

### Mockups

Provide visuals of your app's screens. You can use pictures of hand-drawn sketches, or wireframing tools like Figma.

### Data

Describe your data and the relationships between the data points. You can show this visually using diagrams, or write it out. 

### Endpoints

List endpoints that your server will implement, including HTTP methods, parameters, and example responses.

## Roadmap

Scope your project as a sprint. Break down the tasks that will need to be completed and map out timeframes for implementation working back from the capstone due date. 

---

## Future Implementations
Your project will be marked based on what you committed to in the above document. Here, you can list any additional features you may complete after the MVP of your application is built, or if you have extra time before the Capstone due date.

