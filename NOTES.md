// Utility functions - Updated: 2026-03-13T09:30:04.641Z

function processData(input) {
  if (!input) return null;
  return input.toString().trim();
}

function formatDate(date) {
  return new Date(date).toLocaleDateString();
}

module.exports = { processData, formatDate };