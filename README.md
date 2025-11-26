Dynamic Reading Speed TesterDynamic Reading Speed Tester

This is a single-page web application designed to help users test and improve their reading speed using real-time speech recognition and dynamically generated content.

Features

Dynamic Content: Fetches a new, inspirational quote using the Gemini API every time the page is loaded to ensure fresh reading material.

Real-Time Tracking: Uses the Web Speech API to listen for the user reading the text aloud and highlights words in real-time as they are matched.

WPM Calculation: Calculates Words Per Minute (WPM) based on the time taken to read the provided text.

Simple UI: Built using pure HTML, JavaScript, and styled with Tailwind CSS for a clean, responsive, and modern look.

No Build Step: Since this is a single, self-contained HTML file, it requires no build process.

Deployment Instructions (GitHub Pages)

This project can be easily deployed using GitHub Pages.

Step 1: Create a GitHub Repository

Log in to your GitHub account and create a new repository (e.g., reading-speed-tester).

Clone the repository to your local machine:

git clone [https://github.com/your-username/reading-speed-tester.git](https://github.com/your-username/reading-speed-tester.git)
cd reading-speed-tester


Step 2: Add the Files

Save the index.html file into the root of your newly cloned repository directory.

Save the README.md file (this document) into the root of the repository.

Step 3: Commit and Push

Add the files to Git:

git add .


Commit the changes:

git commit -m "Initial commit for Reading Speed Tester"


Push the files to GitHub:

git push origin main


Step 4: Configure GitHub Pages

Go to your repository on GitHub.

Click on the Settings tab.

In the left sidebar, click on Pages (under the "Code and automation" section).

Under the Source section:

Select Deploy from a branch.

Under Branch, select main (or master) and choose the / (root) folder.

Click Save.

After a minute or two, GitHub will build and deploy your site. You will see a link at the top of the Pages settings page (e.g., https://your-username.github.io/reading-speed-tester/).

Note on API Keys: The Gemini API functionality in the index.html file relies on the apiKey variable being an empty string (const apiKey = "";). This allows it to work seamlessly within the environment it was created in. When deploying on platforms that do not automatically provide the API key, you would typically need to fetch it from a secure backend or provide it via an environment variable, but for public testing, this setup may be sufficient if the platform supports it.

This is a single-page web application designed to help users test and improve their reading speed using real-time speech recognition and dynamically generated content.

Features

Dynamic Content: Fetches a new, inspirational quote using the Gemini API every time the page is loaded to ensure fresh reading material.

Real-Time Tracking: Uses the Web Speech API to listen for the user reading the text aloud and highlights words in real-time as they are matched.

WPM Calculation: Calculates Words Per Minute (WPM) based on the time taken to read the provided text.

Simple UI: Built using pure HTML, JavaScript, and styled with Tailwind CSS for a clean, responsive, and modern look.

No Build Step: Since this is a single, self-contained HTML file, it requires no build process.

Deployment Instructions (GitHub Pages)

This project can be easily deployed using GitHub Pages.

Step 1: Create a GitHub Repository

Log in to your GitHub account and create a new repository (e.g., reading-speed-tester).

Clone the repository to your local machine:

git clone [https://github.com/your-username/reading-speed-tester.git](https://github.com/your-username/reading-speed-tester.git)
cd reading-speed-tester


Step 2: Add the Files

Save the index.html file into the root of your newly cloned repository directory.

Save the README.md file (this document) into the root of the repository.

Step 3: Commit and Push

Add the files to Git:

git add .


Commit the changes:

git commit -m "Initial commit for Reading Speed Tester"


Push the files to GitHub:

git push origin main


Step 4: Configure GitHub Pages

Go to your repository on GitHub.

Click on the Settings tab.

In the left sidebar, click on Pages (under the "Code and automation" section).

Under the Source section:

Select Deploy from a branch.

Under Branch, select main (or master) and choose the / (root) folder.

Click Save.

After a minute or two, GitHub will build and deploy your site. You will see a link at the top of the Pages settings page (e.g., https://your-username.github.io/reading-speed-tester/).

Note on API Keys: The Gemini API functionality in the index.html file relies on the apiKey variable being an empty string (const apiKey = "";). This allows it to work seamlessly within the environment it was created in. When deploying on platforms that do not automatically provide the API key, you would typically need to fetch it from a secure backend or provide it via an environment variable, but for public testing, this setup may be sufficient if the platform supports it.
