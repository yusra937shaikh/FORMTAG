# FORM TAG
FORM TAG &amp; ITS ATTRIBUTE
<html>
<head>
</head>
<body>
    <h1>Simple Form Example</h1>
    <form action="/submit_form" method="POST" enctype="multipart/form-data" target="_self" autocomplete="on" validate>
        <!-- Input for Name -->
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required placeholder="Enter your name"><br><br>
        <!-- Input for Email -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required placeholder="Enter your email"><br><br>
        <!-- Input for password -->
        <label for="password">Create Password:</label>
        <input type="password" id="password" name="password" required placeholder="create a strong password"><br><br>
        <!-- Input for birthdate -->
        <label for="bdate">Birthdate:</label>
        <input type="date" id="date" name="date" required placeholder="Enter your birthdate"><br><br>
        <!-- Input for age -->
        <label for="bdate">Age:</label>
        <input type="number" id="age" name="age" required placeholder="Enter your age"><br><br>
        <!-- File Upload -->
        <label for="file">Upload File:</label>
        <input type="file" id="file" name="file"><br><br>
        <!-- Radio Buttons -->
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label><br><br>
        <!-- Dropdown Menu -->
        <label for="country">COURSE</label>
        <select id="COURSE" name="COURSE">
            <option value="india">BCA</option>
            <option value="usa">BBA</option>
            <option value="uk">B.TECH</option>
        </select><br><br>
        <!-- Submit Button -->
        <button type="submit">Submit</button> 
        <!-- Reset Button -->
        <button type="reset">Reset</button>
    </form>
</body>
</html>
