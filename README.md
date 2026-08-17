# 12-Week Meal & Workout Plan

A modern, responsive 12-week meal and workout planning website.

## Features

- Black and gold editorial-style design
- 12 weekly plans
- Breakfast, lunch, snack, and dinner ideas
- Calories, protein, carbohydrates, and fat for each meal
- Daily estimated calorie and protein totals
- Daily workout routine without prescribing specific exercises
- Ability to enter your own exercises for each workout day
- Exercises and daily check-ins saved in the browser with localStorage
- Mobile-friendly layout
- No backend required
- No external libraries or dependencies

## Run locally

Open `index.html` in a web browser.

For a local development server, you can also use:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy with GitHub Pages

1. Create a new GitHub repository, for example `12-week-fitness-plan`.
2. Upload all files and folders from this project.
3. Open the repository's **Settings**.
4. Select **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)`.
7. Click **Save**.
8. GitHub will provide your public Pages URL after deployment.

The site is static, so no server or database is required.

## Notes

Exercise entries and daily check-ins use browser localStorage. They are saved on the device/browser being used and are not synchronized between devices.

Meal macros are estimates and can vary by brand, portion size, and preparation method.

This is a general fitness and meal-planning resource, not medical advice.
