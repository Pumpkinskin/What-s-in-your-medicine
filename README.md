function searchMedication() {
  const medication = document.getElementById('medicationInput').value;
  
  if (medication === '') {
    document.getElementById('results').innerHTML = 'Please enter a medication name.';
    return;
  }
  
  // In the future, we'll call an API here to get the side effects.
  // For now, just display a dummy message.
  document.getElementById('results').innerHTML = `Showing side effects for: <strong>${medication}</strong>`;
}
