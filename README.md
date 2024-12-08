function clearScreen() {
    document.getElementById('screen').value = '';
}

function deleteLast() {
    let screen = document.getElementById('screen');
    screen.value = screen.value.slice(0, -1);
}

function appendToScreen(value) {
    let screen = document.getElementById('screen');
    screen.value += value;
}

function calculateResult() {
    let screen = document.getElementById('screen');
    try {
        screen.value = eval(screen.value);
    } catch {
        screen.value = 'Error';
    }
}
- 👋 Hi, I’m @parwez85
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
parwez85/parwez85 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
