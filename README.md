<!-- hide -->
# Build a Personal Expense Tracker with Python and Flask
<!-- endhide -->

<onlyfor saas="false" withBanner="false">
## 🌱 How to start this project?

Do not clone this repository because we are going to use a different template.

We recommend opening the project using [Codespaces](https://4geeks.com/lesson/what-is-github-codespaces) (recommended) or [Gitpod](https://4geeks.com/lesson/how-to-use-gitpod). Alternatively, you can clone the repository to your local computer using `git clone`.

This is the base repository you need to use:

```
https://github.com/4GeeksAcademy/flask-rest-hello
```

> ⚠ You will need to have Python installed if you are working locally, but everything is preconfigured in Codespaces or Gitpod.
</onlyfor>

## 📝 Instructions

### Step 1: Set Up Your Environment

- [ ] Clone the base repository and follow the README instructions to install the dependencies.

- [ ] Make sure to install Flask and any other required libraries. Use this command:

```bash
pip install flask flask-sqlalchemy
```

### Step 2: Create the Data Model

- [ ] Define an `Expense` model in your `models.py` file. Include fields such as:

  - `id`: Primary key.
  - `description`: Description of the expense.
  - `amount`: Amount of the expense.
  - `date`: Date of the expense.

### Step 3: Set Up the API Routes

- [ ] Create a `routes.py` file with the following routes:

  - **Get All Expenses**: Returns a list of all expenses.
  - **Add an Expense**: Allows adding a new expense via POST.
  - **Delete an Expense**: Allows deleting an expense via DELETE.

### Step 4: Create the User Interface

- [ ] Use HTML, CSS, and JavaScript to create a basic interface that consumes your API.

- [ ] Include:

  - A form to add new expenses.
  - A table to display the list of expenses.
  - Buttons to delete expenses.

### Step 5: Add Advanced Features (Optional)

- [ ] **Date Filtering**: Allow filtering expenses by date range.

- [ ] **Categorization**: Add categories to expenses, such as "Food," "Transportation," etc.

- [ ] **Charts**: Use a library like Chart.js to show a graphical summary of expenses.

## Bonus Section

### Additional Features to Practice

1. **Authentication**: Implement a basic user registration and login system.
2. **Data Export**: Add the option to export data to a CSV file.
3. **Notifications**: Send alerts when the user exceeds a monthly budget.
4. **Deploy**: Publish your application on Heroku or Render.

Explore different enhancements to make your application more complete and useful!