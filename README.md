# Patient-detail-form.<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- 1. Meaningful title: "Patient Registration Form" -->
    <title>Patient Registration Form</title>
</head>
<body>

    <!-- 2. Heading and Instructions -->
    <h1>Patient Registration Form</h1>
    <p>Please take a moment to fill out all the required fields in the form below to complete your registration.</p>

    <hr>

    <!-- 3. Patient Details Form -->
    <form action="#" method="POST">
        
        <!-- Full Name -->
        <p>
            <label for="fullName">Full Name:</label><br>
            <input type="text" id="fullName" name="fullName" required>
        </p>

        <!-- Email Address -->
        <p>
            <label for="email">Email Address:</label><br>
            <input type="email" id="email" name="email" required>
        </p>

        <!-- Phone Number -->
        <p>
            <label for="phone">Phone Number:</label><br>
            <input type="tel" id="phone" name="phone" required>
        </p>

        <!-- Date of Birth -->
        <p>
            <label for="dob">Date of Birth:</label><br>
            <input type="date" id="dob" name="dob" required>
        </p>

        <!-- Gender (Radio buttons are best practice for selecting a single choice) -->
        <fieldset>
            <legend>Gender:</legend>
            <input type="radio" id="male" name="gender" value="Male" required>
            <label for="male">Male</label><br>
            
            <input type="radio" id="female" name="gender" value="Female">
            <label for="female">Female</label><br>
            
            <input type="radio" id="other" name="gender" value="Other">
            <label for="other">Other</label>
        </fieldset>

        <!-- Services Required (Checkboxes) -->
        <fieldset>
            <legend>Services Required:</legend>
            <input type="checkbox" id="consultation" name="services" value="Consultation">
            <label for="consultation">Consultation</label><br>
            
            <input type="checkbox" id="labTest" name="services" value="Laboratory Test">
            <label for="labTest">Laboratory Test</label>
        </fieldset>

        <br>
        <!-- Submit Button -->
        <button type="submit">Submit Registration</button>

    </form>

</body>
</html>
