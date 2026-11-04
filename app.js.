
const script = document.querySelector('#script');
const count = document.querySelector('#count');
const button = document.querySelector('#generate');
const status = document.querySelector('#status');

script.addEventListener('input', () => {
  count.textContent = script.value.length;
});

button.addEventListener('click', () => {
  if (!script.value.trim()) {
    status.textContent = 'Please type a message first.';
    return;
  }

  if (!document.querySelector('#permission').checked) {
    status.textContent = 'Please confirm you have permission to use this voice.';
    return;
  }

  status.textContent =
    'Your interface is ready. Connect a licensed text-to-speech service to generate audio.';
});
