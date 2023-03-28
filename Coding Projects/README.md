# Resume-Coding-Examples
Examples of previous coding projects documenting problem identification skills as well as coding literacy

![Coding Collage](https://github.com/tkiyohar/Resume-Gallery-Assets/blob/main/Coding_Collage.png)

## ⭐⭐ Capstone: UCSDCoursesScraper ⭐⭐
- Most recent and most ambitious Python project to date
- Incorporates Python's “Selenium” package to log in to and web-scrape our school's course enrollment tool to retrieve a student's course info. Then uses the "googleapiclient" package to create a custom color-coordinated calendar with descriptive events for each of the student's courses.
- Utilizes several common packages like “re” (regular expression) and “pickle” (serialization package) for data manipulation as well as “sys” and “pprint” for ease of dianosing of errors.
- Written to avoid problems I'd encounter previously with my "LAB_HOURS" program maxing out Google's free API calls
- Automates a task that would generally takes students multiple hours of busywork down to a few minutes.
 
 
## LAB_HOURS
- Written to document the number of hours that robotics team members spent in the school robotics room. This was necessary for determining who “deserved” to go to regionals and world championships if our budget did not cover our entire team's tickets (which it most often did not).
- Built using the “gspread” Google sheets python package and the "oauth2client" package to read and edit Google sheets.
- Contains a built-in installer for the packages used within it making it easy to quick on multiple devices.
- Program saw usage and success for about half the robotics team’s season before hitting the free limit on Google’s API calls.
 
 
## Sorba 2.0
- First-ever attempt at writing a program to automate a repetitive web-based task. Basically, just a rudimentary macro.
- Built using the “pyautogui” python package
- Written to take any Spanish words I wasn't familiar with on my screen, plugging them into a translator, and creating flashcards of them on an online tool called Quizlet (required by my Spanish class at the time).
- Wherein the macro-less process took ~45 seconds per word to do manually, my finalized program made each word take as little as 3 seconds.
