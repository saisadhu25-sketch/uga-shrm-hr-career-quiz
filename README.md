# UGA SHRM HR Career Quiz

An interactive career-discovery quiz created by the **UGA Society for Human Resource Management (SHRM) Student Chapter**. The quiz helps students explore which areas of human resources best match their personality, strengths, work preferences, and responses to realistic workplace scenarios.

## Take the Quiz

**[Launch the UGA SHRM HR Career Quiz](https://saisadhu25-sketch.github.io/uga-shrm-hr-career-quiz/)**

The quiz contains 22 questions and usually takes about five minutes to complete.

## What Participants Receive

After completing the quiz, each participant receives:

- Three ranked HR career matches
- A detailed explanation of their strongest match
- A personality and work-style profile
- Strengths they may bring to the field
- Potential growth areas
- Examples of typical responsibilities
- Suggestions for exploring the career path
- A downloadable result graphic and suggested LinkedIn post

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

Responses are scored across several traits and preferences, then compared with profiles for the 11 HR career fields. The three closest matches are presented in ranked order. Results are intended for career exploration and are not a formal psychological or employment assessment.

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

## About UGA SHRM

UGA SHRM is a Terry College of Business–affiliated student organization that helps students learn about human resources, connect with professionals, and prepare for careers focused on people and the workplace.

[Follow UGA SHRM on LinkedIn](https://www.linkedin.com/company/shrm-at-uga/)
