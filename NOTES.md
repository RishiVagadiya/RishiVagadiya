// Utility functions - Updated: 2026-03-08T18:30:59.441Z

function processData(input) {
  if (!input) return null;
  return input.toString().trim();
}

function formatDate(date) {
  return new Date(date).toLocaleDateString();
}

module.exports = { processData, formatDate };