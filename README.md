# UGA SHRM HR Career Quiz

An interactive career-discovery experience created by the **University of Georgia Society for Human Resource Management (UGA SHRM) Student Chapter**. The quiz helps students, aspiring HR professionals, and individuals exploring the field understand which areas of human resources may best align with their personalities, strengths, interests, and preferred ways of working.

## Take the Quiz

**[Launch the UGA SHRM HR Career Quiz](https://saisadhu25-sketch.github.io/uga-shrm-hr-career-quiz/)**

The quiz includes 22 questions and typically takes about five minutes to complete.

## What the Quiz Does

Human resources is much broader than recruiting or handling employee concerns. It includes specialized career paths involving data, technology, law, learning, workplace culture, business strategy, compensation, operations, and more. Because many students and early-career professionals have not yet been exposed to all of these possibilities, deciding where to begin can feel overwhelming.

This quiz makes the field easier to understand. It combines personality and work-style questions with realistic HR scenarios to identify three career areas that may fit the participant. It then provides a detailed profile of the participant's strongest match, including:

- A description of what the HR field does
- Three ranked HR career matches
- A personality and work-style profile
- Strengths the participant may bring to the field
- Potential areas for professional growth
- Examples of common responsibilities
- Practical ways to begin exploring the career path
- A downloadable result graphic and suggested LinkedIn post

## Why This Quiz Is Important

Career exploration is most useful when people can connect their personal qualities to real professional opportunities. This quiz gives participants an approachable starting point for doing that within HR.

The results can help participants:

- Discover HR specialties they may not have previously considered
- Better understand how their interests and strengths can translate into a career
- Build vocabulary for discussing their professional goals in interviews, networking conversations, and mentoring meetings
- Identify skills, classes, certifications, internships, or experiences they may want to pursue next
- Ask more informed questions when speaking with HR professionals
- Feel more confident and intentional about their professional journeys

For current HR professionals, the quiz may also be a useful conversation starter for mentoring students, introducing others to the variety within HR, and encouraging early-career talent to explore different functions.

The quiz is designed for reflection and career exploration. It does not determine what someone must pursue, and it is not a formal psychological, educational, or employment assessment. Instead, it offers direction, language, and ideas that participants can use as they continue learning about themselves and the profession.

## From UGA SHRM Members to a Broader Community

The UGA SHRM HR Career Quiz was initially created to help members of the UGA SHRM Student Chapter better understand the many career opportunities available within human resources. It gave our members a personalized way to connect their strengths and interests with specific HR functions.

Although it began as a resource for our chapter, its purpose extends far beyond UGA. Students at other universities, individuals considering a transition into HR, early-career professionals, mentors, educators, and established HR practitioners can all use the quiz to begin meaningful conversations about career fit and professional development. What started as a tool for our members can now help many more people gain clarity and take a more informed next step in their HR journeys.

## HR Career Fields Included

1. HR Business Partner
2. Talent Acquisition
3. People Analytics
4. Learning & Development
5. Compensation & Benefits
6. Employee Relations
7. HR Compliance & Employment Law
8. HR Technology / HRIS
9. Organizational Development & Change
10. HR Operations
11. Culture & Engagement

## How It Works

The quiz combines:

- **11 personality and work-style questions**
- **11 realistic HR scenarios**

Responses are scored across several traits and preferences, then compared with profiles representing the 11 HR career fields. The three closest matches are presented in ranked order, with an expanded profile for the strongest match.

Participants should answer based on what naturally describes them, rather than what they believe an HR professional is expected to choose. Honest responses create a more useful reflection experience.

## About SHRM

The **Society for Human Resource Management (SHRM)** is a professional organization dedicated to advancing the field of human resources and supporting the people who shape workplaces. SHRM provides education, research, professional development, certifications, resources, and a professional community for HR students and practitioners.

Student SHRM chapters help connect classroom learning with the profession by giving students access to career education, leadership opportunities, networking, and exposure to HR professionals and employers.

## About UGA SHRM

The **UGA SHRM Student Chapter** is a Terry College of Business–affiliated student organization at the University of Georgia. The chapter helps students learn about human resources, connect with professionals, explore career opportunities, and prepare to become thoughtful leaders in the workplace.

UGA SHRM welcomes students who are interested in HR, people strategy, organizational leadership, workplace technology, analytics, employment law, and the many other ways people contribute to organizational success.

[Follow UGA SHRM on LinkedIn](https://www.linkedin.com/company/shrm-at-uga/)

## Running the Quiz Locally

No installation, framework, or build process is required.

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.

You can also use a simple local server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project Structure

- `index.html` — current quiz interface, scoring logic, and results experience
- `assets/` — downloadable career-result graphics and visual assets
- `card-data/` — supporting result-card data
- `.github/` — GitHub configuration and deployment files
- `quiz-final.html`, `quiz-v2.html`, and `quiz-working.html` — earlier development versions

## Updating the Quiz

Most quiz content and logic are contained in `index.html`:

- Edit the `personality` and `scenarios` arrays to update questions.
- Edit the `common` object to update career profiles, strengths, growth areas, responsibilities, and exploration steps.
- Edit `careerDescriptions` to update the short explanation shown for each field.
- Keep `careerSlugs`, `careerDescriptions`, and files in `assets/` aligned when adding or renaming a career field.

After making changes, test all 11 possible results on both desktop and mobile layouts.

## Deployment

The project is published through GitHub Pages from the `main` branch. Changes committed to the deployed source become available at the live quiz URL after GitHub Pages finishes publishing.
