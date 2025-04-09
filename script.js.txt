document.getElementById('registrationForm').addEventListener('submit', function(e) {
  e.preventDefault();
  alert("Thank you for registering with Prodigy InfoTech! We'll contact you soon.");
  this.reset();
});
