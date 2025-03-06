/* Reset default browser styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body and general layout */
body {
    font-family: Arial, sans-serif;
    background-color: #f1f3f4;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    padding: 10px;
}

/* Container for the signup box */
.container {
    width: 100%;
    max-width: 450px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    padding: 20px;
}

/* Title */
h2 {
    text-align: center;
    color: #3c4043;
    margin-bottom: 20px;
}

/* Form input box */
.input-box {
    margin-bottom: 20px;
}

.input-box label {
    display: block;
    font-size: 14px;
    color: #5f6368;
    margin-bottom: 5px;
}

.input-box input {
    width: 100%;
    padding: 10px;
    font-size: 14px;
    border: 1px solid #dadce0;
    border-radius: 4px;
    outline: none;
}

.input-box input:focus {
    border-color: #4285f4;
}

/* Terms checkbox */
.terms {
    font-size: 14px;
    color: #5f6368;
}

.terms label {
    font-size: 13px;
}

.terms a {
    color: #1a73e8;
    text-decoration: none;
}

.terms a:hover {
    text-decoration: underline;
}

/* Submit button */
.submit-btn {
    width: 100%;
    padding: 12px;
    background-color: #4285f4;
    color: white;
    border: none;
    border-radius: 4px;
    font-size: 16px;
    cursor: pointer;
}

.submit-btn:hover {
    background-color: #357ae8;
}

.button-container {
    margin-top: 10px;
}


