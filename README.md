<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Scholarship / Seminar Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 20px;
        }
        form {
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            max-width: 600px;
            margin: auto;
        }
        fieldset {
            margin-bottom: 15px;
            border: 2px solid #ccc;
            padding: 15px;
        }
        legend {
            font-weight: bold;
        }
        label {
            display: block;
            margin-top: 10px;
        }
        input, select, textarea {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
        }
        .inline {
            width: auto;
        }
        button {
            padding: 10px 15px;
            background-color: #007BFF;
            color: white;
            border: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>

<form>
    <h2>Scholarship / Seminar Registration Form</h2>

    <!-- Personal Information -->
    <fieldset>
        <legend>Personal Information</legend>

        <label>Full Name:
            <input type="text" name="fullname" required>
        </label>

        <label>Email:
            <input type="email" name="email" required>
        </label>

        <label>Phone Number:
            <input type="tel" name="phone">
        </label>

        <label>Date of Birth:
            <input type="date" name="dob">
        </label>
    </fieldset>

    <!-- Gender (Radio Buttons) -->
    <fieldset>
        <legend>Gender</legend>

        <label><input type="radio" name="gender" value="male" class="inline"> Male</label>
        <label><input type="radio" name="gender" value="female" class="inline"> Female</label>
        <label><input type="radio" name="gender" value="other" class="inline"> Other</label>
    </fieldset>

    <!-- Course Selection (Dropdown) -->
    <fieldset>
        <legend>Seminar / Scholarship Category</legend>

        <label>Select Category:
            <select name="category">
                <option value="">--Select--</option>
                <option value="science">Science Scholarship</option>
                <option value="engineering">Engineering Seminar</option>
                <option value="management">Management Seminar</option>
                <option value="arts">Arts Scholarship</option>
            </select>
        </label>
    </fieldset>

    <!-- Interests (Checkboxes) -->
    <fieldset>
        <legend>Areas of Interest</legend>

        <label><input type="checkbox" name="interest" value="ai" class="inline"> Artificial Intelligence</label>
        <label><input type="checkbox" name="interest" value="data" class="inline"> Data Science</label>
        <label><input type="checkbox" name="interest" value="web" class="inline"> Web Development</label>
        <label><input type="checkbox" name="interest" value="business" class="inline"> Business & Management</label>
    </fieldset>
    <!-- Address -->
    <fieldset>
        <legend>Address</legend>
        <label>City:
            <input type="text" name="city">
        </label>

        <label>State:
            <input type="text" name="state">
        </label>

        <label>Country:
            <input type="text" name="country">
        </label>
    </fieldset>

    <!-- Submit -->
    <button type="submit">Register</button>

</form>

</body>
</html>
