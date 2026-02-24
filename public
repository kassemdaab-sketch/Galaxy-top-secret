// Firebase Configuration
const firebaseConfig = {
    databaseURL: "https://galaxy-82629706-default-rtdb.firebaseio.com",
    projectId: "galaxy-82629706",
};

// Initialize Firebase
firebase.initializeApp(firebaseConfig);
const database = firebase.database();

// Galaxy Tab Cloaking Logic
window.onblur = function () {
    document.title = "Google Docs";
    const favicon = document.getElementById("favicon");
    if (favicon) favicon.href = "https://ssl.gstatic.com/docs/documents/images/kix-favicon7.ico";
};

window.onfocus = function () {
    document.title = "Galaxy AI";
};

// Simple Chat/AI Function
function sendMessage() {
    const input = document.getElementById("user-input");
    if (input && input.value.trim() !== "") {
        console.log("Galaxy AI processing: " + input.value);
        // Add your custom AI responses here!
        input.value = "";
    }
}
