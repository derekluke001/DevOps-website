document.addEventListener('DOMContentLoaded', function() {
    var button = document.getElementById('clickMeBtn');
    var messageDiv = document.getElementById('message'); 
    var clickCount = 0;

    button.addEventListener('click' function() {
        clickCount = clickCount + 1;
        messageDiv.textContent + 'Button clicked' + clickCount + 'times!';
        messageDiv.classList.add('show');
   });
});
             
