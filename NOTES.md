// Utility functions - Updated: 2026-03-12T12:30:04.639Z

function processData(input) {
  if (!input) return null;
  return input.toString().trim();
}

function formatDate(date) {
  return new Date(date).toLocaleDateString();
}

module.exports = { processData, formatDate };