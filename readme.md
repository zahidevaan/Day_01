### Updated JavaScript for Toggle Functionality (scripts.js)
No changes are needed in the JavaScript, as the toggling functionality remains the same. The existing script handles the toggle logic between the login and sign-up forms perfectly:

### JavaScript
document.getElementById('loginBtn').addEventListener('click', function() {
    document.getElementById('loginForm').classList.add('active');
    document.getElementById('signupForm').classList.remove('active');
    this.classList.add('active');
    document.getElementById('signupBtn').classList.remove('active');
});

document.getElementById('signupBtn').addEventListener('click', function() {
    document.getElementById('signupForm').classList.add('active');
    document.getElementById('loginForm').classList.remove('active');
    this.classList.add('active');
    document.getElementById('loginBtn').classList.remove('active');
});
Explanation of the Updates:
